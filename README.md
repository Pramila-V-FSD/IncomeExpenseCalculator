Income Expense Calculator

Project Overview:

This web-based Income Expense Calculator allows users to track their income and expenses. It enables users to add, edit, delete, and filter entries. The application calculates and displays total income, total expenses, and the net balance, allowing users to easily monitor their finances.

Features:

Track Income and Expenses: Add, edit, or delete income or expense entries.
Filter Entries: Filter the list of entries by type (Income, Expense, or All).
Summary: Displays the total income, total expenses, and net balance dynamically.
Responsive Design: The layout is mobile-friendly and adapts to different screen sizes.

Features Breakdown:

Add Entry:

The user can add a new entry by providing a description, amount, and selecting whether it is an income or expense.
A unique ID is automatically generated for each entry and saved to the browser's local storage.

Edit Entry:

Existing entries can be edited by clicking the Edit button next to the entry.
When editing, the existing details populate the form, allowing the user to modify them.

Delete Entry:

Each entry has a Delete button that removes the entry from the list and updates the total income and expenses.

Filter Entries:

Entries can be filtered by type (all, income, or expense) using radio buttons.

Total Calculations:

The application calculates the Total Income, Total Expenses, and Net Balance dynamically and displays them at the top of the page.

Technology Stack:

HTML5: For the structure of the web page.
CSS3: For styling the layout, including responsive design.
JavaScript: For the logic to manage user interactions (adding, editing, deleting entries), updating the UI, and storing data in local storage.
LocalStorage: To store the user's data (income and expense entries) persistently across page reloads.

Installation and Usage:

Clone the Repository: You can copy or download the HTML, CSS, and JavaScript files to your local machine.

Open the Application: Open the index.html file in your web browser.

Using the Calculator:

Add Entries: Enter a description and amount, then select whether it’s an income or expense. Click Add Entry.
Edit Entries: Click the Edit button next to an entry to modify its details.
Delete Entries: Click the Delete button to remove an entry from the list.
Filter Entries: Use the filter options (All, Income, or Expense) to display specific types of entries.
Local Storage: All the entries are stored in your browser’s local storage, so they will persist even after you refresh the page.
