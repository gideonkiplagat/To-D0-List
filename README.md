## GUI Elements
The application has a Tkinter window with several frames for organizing the layout.

Labels, entry fields, and buttons are used for user interaction.

## Database Connection
It connects to an SQLite database file named 'listOfTasks.db'.

A table named 'tasks' is created if it doesn't exist, with a single column 'title'.

## Functions
add_task: Adds a task to the list and inserts it into the 'tasks' table.

list_update: Updates the Tkinter listbox with tasks from the 'tasks' table.

delete_task: Deletes a selected task from both the list and the 'tasks' table.

delete_all_tasks: Deletes all tasks from both the list and the 'tasks' table.

clear_list: Clears the Tkinter listbox.

close: Closes the application.

## Tkinter Components:
Labels, entry fields, buttons, and a listbox are placed on the GUI using the place() method.

## Main Loop
The mainloop() method is called to run the Tkinter application.

## Database Retrieval:
The retrieve_database() function is called to populate the tasks list from the 'tasks' table in the database.

## Commit and close Database
After the main loop, the connection with the database is committed, and the cursor is closed.
