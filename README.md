# To-Do List App

## Description:
The To-Do List App is a simple command-line application that helps users manage their tasks efficiently. Users can perform various actions to interact with their to-do list, such as viewing tasks, creating new tasks, updating existing tasks, deleting tasks, and prioritizing tasks.

## Features
### 1. View Tasks (Option: V)
   - Displays a tabulated list of all existing tasks.
   - If no tasks are present, a message indicating the absence of tasks is shown.

### 2. Create a Task (Option: C)
   - Allows users to add a new task to their to-do list.
   - Users are prompted to enter the task details, and the new task is added to the list.

### 3. Update a Task (Option: U)
   - Displays the current list of tasks with their corresponding IDs.
   - Users can choose a task to update by entering its ID and then provide the updated task details.
   - The selected task is then modified with the new information.

### 4. Delete a Task (Option: D)
   - Shows the current list of tasks with their corresponding IDs.
   - Users can choose a task to delete by entering its ID, and the selected task is removed from the list.

### 5. Prioritize a Task (Option: P)
   - Displays the existing tasks with their corresponding IDs.
   - Users can select a task to prioritize by entering its ID.
   - The chosen task is moved to the top of the list, giving it higher priority.

### 6. Exit (Option: E)
   - Allows users to exit the application with a friendly farewell message.

## Usage
1. Run the script in a Python environment.
2. Follow the on-screen prompts to interact with the to-do list.

## Notes
- Task IDs are displayed in the app to assist users in performing actions like updating and deleting tasks.
- The app utilizes the `tabulate` library for visually appealing tabular displays.
- Make sure to input valid options when prompted to ensure smooth operation.
