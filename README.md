# QUICKSELL_FRONTEND_ASSIGNMENT-01

# **Kanban Board - Frontend Assignment**

This is a simple **Kanban Board** application built using **React JS**. The application fetches data from the provided API and allows users to group and sort the tickets based on different criteria like **status**, **user**, and **priority**.

## **Features**

1. **Dynamic Grouping**:
    - Group tickets by **status**, **user**, or **priority**.
    
2. **Sorting**:
    - Sort tickets by **priority** (descending order).
    - Sort tickets by **title** (ascending order).

3. **Persistent State**:
    - The application saves the user's view state in `localStorage`, ensuring the state remains even after a page reload.

4. **Responsive Design**:
    - The UI is fully responsive, ensuring a good user experience across different screen sizes.

5. **Pure CSS**:
    - No CSS libraries like Bootstrap or Tailwind were used. Only pure CSS and Styled JSX were used for styling.

## **Prerequisites**

Before running this project, make sure you have the following installed:

- **Node.js**: https://nodejs.org/
- **npm** (or **yarn**): npm comes with Node.js, but you can also install it separately.


## **API**

The app fetches ticket data from the following API endpoint:

```
https://api.quicksell.co/v1/internal/frontend-assignment
```

## **Application Structure**

The app is divided into the following components:

1. **KanbanBoard**: The main component responsible for rendering the board.
2. **TicketCard**: This represents individual tickets on the board.
3. **FilterControls**: Allows users to select grouping and sorting options.
4. **APIService**: Contains the logic for fetching data from the provided API.

## **How It Works**

- The app fetches ticket data from the API and stores it in the state.
- Users can choose how to group the tickets:
    - By **Status**: Tickets are grouped according to their current status.
    - By **User**: Tickets are grouped by the user assigned to them.
    - By **Priority**: Tickets are grouped based on their priority level.
- Users can also sort tickets by **priority** or **title** using the provided controls.
- The current grouping and sorting state are saved in `localStorage` to ensure persistence across page reloads.

## **Styling**

- The application is styled using **pure CSS**.
- The design is based on the provided mockups and ensures a clean, modern UI.
