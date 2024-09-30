The Chemical Inventory application is a web-based tool for managing and maintaining a list of chemical supplies. Users can perform various operations such as adding, editing, deleting, and sorting chemical entries, making it a useful resource for inventory management in laboratories and industries.

#Features
Responsive Design: The application utilizes Bootstrap for a responsive layout that works well on different devices.
CRUD Operations: Users can create (add), read (view), update (edit), and delete chemical entries.
Sorting: Users can sort the table based on different chemical attributes by clicking on the column headers.
Dynamic Toolbar: The toolbar allows users to perform actions like add, edit, delete, move up/down, reset, and save.
Input Validation: Ensures that all fields are filled out before saving any changes.
Installation
To run the application locally, follow these steps:

Clone the Repository (if applicable):

bash
Copy code
git clone <repository-url>
cd chemical-inventory
Open the HTML File:

Open index.html (or the main HTML file) in a web browser.
Usage
Interface Overview
Toolbar: Located at the top, it contains buttons for performing various actions:

Add: Add a new chemical entry.
Edit: Edit the selected entry.
Move Up/Down: Change the order of the selected entry.
Delete: Remove the selected entry.
Reset: Restore the initial list of chemicals.
Save: Save changes made to the selected entry.
Table: Displays a list of chemicals with their attributes:

ID
Chemical Name
Vendor
Density
Viscosity
Packaging
Pack Size
Unit
Quantity
Interacting with the Application
Adding a Chemical:

Click the ➕ button in the toolbar.
A new row will be added to the table where you can enter chemical details.
Editing a Chemical:

Click on a row in the table to select it.
Click the ✏️ button to edit the selected entry. Input fields will appear for modification.
Fill in the details and click the 💾 button to save changes.
Deleting a Chemical:

Select a row and click the 🗑️ button. A confirmation prompt will appear to confirm deletion.
Moving Entries:

Select a row and use the ⬆️ or ⬇️ buttons to change its position in the list.
Resetting the List:

Click the 🔄 button to restore the original set of chemicals.
Sorting:

Click on any column header to sort the entries by that attribute (ascending/descending).
Code Structure
HTML
The HTML structure consists of a head section containing meta tags and Bootstrap CSS, followed by a body that houses the container for the chemical inventory table and toolbar.
CSS
Custom styling for selected rows and cursor appearance over table headers is defined in a <style> block.
JavaScript
Data Handling: Sample data is stored in the initialChemicals array, which is manipulated through various functions.
Event Listeners: Attached to buttons for handling user interactions and to table headers for sorting.
Functions:
renderTable(): Renders the table rows based on the chemicals array.
sortTable(key): Sorts the chemicals based on the clicked column.
selectRow(row, index): Handles row selection for editing and deletion.
toggleToolbarButtons(): Enables or disables toolbar buttons based on selection.
editRow(index): Prepares the selected row for editing.
validateInputs(inputs): Checks if all input fields are filled.
Conclusion
The Chemical Inventory application provides a user-friendly interface for managing chemical supplies effectively. With its responsive design, CRUD functionality, and sorting capabilities, it is an essential tool for any laboratory or industrial setting.

This documentation should give users a comprehensive understanding of how to use the Chemical Inventory application and the underlying code structure. Feel free to modify or expand upon this as necessary!






