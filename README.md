# QuickBase Cheatsheet

What is Quickbase?

**Quickbase is a low-code platform that allows users to create custom business applications without the need for coding. It provides a web-based interface for building and managing applications, as well as integrations with other tools and services.**

## Creating a new application

### To create a new application in Quickbase, follow these steps:

- Log in to your Quickbase account.
- Click the "Create an App" button on the dashboard.
- Select the "Create a blank app" option.
- Give your app a name and description, and select a table style.
- Click the "Create" button.
Adding fields

### To add fields to an application in Quickbase, follow these steps:

- Navigate to the "Fields" tab in the app builder.
- Click the "Add a field" button.
- Select the field type (e.g., text, number, date).
- Give the field a name and any other relevant options (e.g., field size, default value).
- Click the "Save" button.
Creating a form

### To create a form in Quickbase, follow these steps:

- Navigate to the "Forms" tab in the app builder.
- Click the "Add a form" button.
- Select the fields you want to include on the form.
- Use the drag and drop interface to rearrange the fields and customize their layout.
- Click the "Save" button.
Creating a report

### To create a report in Quickbase, follow these steps:

- Navigate to the "Reports" tab in the app builder.
- Click the "Add a report" button.
- Select the fields you want to include in the report.
- Use the drag and drop interface to rearrange the fields and customize the layout.
- Click the "Save" button.
Integrating with other tools

**Quickbase can be integrated with a wide range of other tools and services, such as:**

- Google Sheets
- Salesforce
- Slack
- Zendesk
To integrate Quickbase with another tool, follow these steps:

- Navigate to the "Integrations" tab in the app builder.
- Click the "Add an integration" button.
- Select the tool you want to integrate with.
- Follow the prompts to authenticate and set up the integration.
- I hope this cheatsheet helps you get started with Quickbase! Let me know if you have any questions.

## Commands

`[table].`: This command allows you to access the fields in a specific table. For example, if you have a table called "Contacts" and you want to access the "Email" field, you would use the command Contacts.Email.

`[field]=[value]`: This command allows you to set the value of a field to a specific value. For example, if you have a field called "Status" and you want to set it to "Completed", you would use the command Status="Completed".

`[field].[function]`: This command allows you to perform a function on a field. For example, if you have a field called "Total Sales" and you want to sum all of the values in that field, you would use the command Total Sales.SUM().

`SORT([field],[asc/desc])`: This command allows you to sort a table by a specific field. The second parameter (asc/desc) specifies whether the sort should be in ascending or descending order.

`FILTER([field],[operator],[value]`): This command allows you to filter a table based on specific criteria. For example, if you have a field called "Status" and you want to only see records where the status is "Completed", you would use the command FILTER(Status="Completed").

`GROUPBY([field])`: This command allows you to group a table by a specific field.
