# ohreport
- Developer Test for Orderhood

Orderhood developer test project
Overview
Orderhood delivers food orders from restaurants to customers.  The purpose of this project is to develop a simple, web-based report to view the list of orders for any arbitrary time period. 

The report will be viewable in a web interface, and can be downloaded as a CSV file.  You are allowed to use the language(s) and tools of your choice, though Orderhood’s preferred toolkit is javascript, angular, bootstrap, and node for any necessary server-side code.
Database
The data is stored in an online database called Firebase, which exposes a simple javascript API.  Our firebase login info is below for this project.  This login info permits read-only access to our development database.  While this is not our live database, please do not share any of the info from this database outside the scope of this project:

Login / password: Jake emailed you directly

The orders are stored under the “orders” key.
Major functionality
For this project, we only specify the major functionality.  The design, architecture, and actual layout of the user interface is completely up to the developer.  Since this is an interview for a development position (not a graphical designer), strive for a user interface that is plain, but simple to use and that exposes all necessary functionality.

We are not trying to judge your graphic design ability, so feel free to use default styles or styles from any major toolkit, like bootstrap.
Report format
The report should contain the following columns, formatted appropriately:
Order ID
Restaurant Name
Runner Name
Status
Order Amount
Tip Amount
Orderer name
Order date and time

Functionality
On opening the report, the user should see a simple tabular view with the columns above, for the last 1 week.  By default, the report is sorted on order datetime from newest to oldest.

The user can sort the report on any column by clicking on it.

There should be date fields allowing the user to specify a start and end date for the report and constrain or expand the date range.

There should be a button to export the current data to a CSV file.
