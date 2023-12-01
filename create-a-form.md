# Create a Form

The Create Form wizard is used to quickly create forms for adding or editing data.

***

_Create a Form_

***

### Properties

1.  **Query**

    The insert or update query to use with the form.
2.  **Query type**

    Insert or Update.
3.  **Select Query**

    If applicable, the select query to populate your update form.
4.  **Datagrid**

    If applicable, indicate a datagrid to display your data.
5.  **Label**

    The label for the form field.
6.  **Control**

    The type of control (field), e.g. textbox.
7.  **Validations**

    The validations that must be performed on the data, e.g. required field, number validation or email validation.
8.  **Read-Only**

    To make the field read-only (non-editable).
9.  **Label placement**

    Indicate where the label must appear in relation to the field.
10. **Save button text**

    The text on the form button.

***

### How to create an update form

Assume that you have a database and that you want to provide your users with a form to update data in the database.

1. Add a [Database connector](.gitbook/assets/DatabaseConnector) to your application.
2. Add the following 3 SQL queries to the connector:
   * a query to load the DataGrid (let's name it _SelectAll_)
   * a query to load the edit form with a specific record (name it _SelectRecord_)
   * a query to update the specific record (name it _UpdateRecord_)
3. Add a DataGrid to your page.
   * Select your _SelectAll_ query to load your DataGrid columns.
4. Click Create Form on the toolbar.
   * Select your _UpdateRecord_ query.
   * For Query Type, select the _Update Query_ radio button.
   * To provide a select query, select your _SelectRecord_ query.
   * Attach your DataGrid to the form.
     * Select the _staffID_ DataGrid column for the _Source_ property of the staffID key field.
   * Click Next, then click Generate.
