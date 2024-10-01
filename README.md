# Quicksell_Assignment_Uddeshya

# Kanban Board Application

This project is a React-based Kanban board that fetches data from the API and allows users to group and sort tickets dynamically. The board is responsive and saves the user's view state after a page reload.

## API Used

The application uses the following API to fetch the ticket data:

https://api.quicksell.co/v1/internal/frontend-assignment


## Features

- **Dynamic Grouping Options**:
  - By Status: Group tickets based on their current status.
  - By User: Arrange tickets according to the assigned user.
  - By Priority: Group tickets based on their priority level.

- **Sorting Options**:
  - **Priority**: Sort tickets in descending order based on priority level.
  - **Title**: Sort tickets in ascending order based on their title.

- **Priority Levels**: 
  - Urgent (Priority level 4)
  - High (Priority level 3)
  - Medium (Priority level 2)
  - Low (Priority level 1)
  - No priority (Priority level 0)

The priority values received from the API are:

| Priority Level | Description |
| -------------- | ----------- |
| 4              | Urgent      |
| 3              | High        |
| 2              | Medium      |
| 1              | Low         |
| 0              | No Priority |

# Setup

## Installation

To install the necessary dependencies, run the following command:

```bash
npm install
```

**Run the Application:**

```bash
npm start
  ```

Access the Application: Open your browser and go to `http://localhost:3000`.
