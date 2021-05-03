
# Mendix : Low-code Application Development Course
  
## Introduction
  
  * **How to install Mendix** \
      Install Mendix Pro from Mexdix Website
  * **Fast Orientation** \
    How Mendix will be used to create a web application
  * **Sales Management System and Bussiness Problem** \
    Explined the usercase for developing web application to manage Sales and Sales Representative
  * **Creating home page** \ 
    How to create home page
  * **Improving UI** \
    Adding link to Customer Page, Product Page, Sales Person Page and Sales Tracking Page
  * **Creating Customer Page** \ 
    Explains how to create new Page in Mendix
  * **Handling Error**
  
  ## Create Sales Mangement System Pages
  
  * **Creating Product Page** \
    Create Product Page and mention it as link in the Home Page
  * **Creating Location Page** \
    Create Location Page and mention it as link in the Home Page
  * **Creating Sales Person Page** \
    Create Sales Person Page and mention it as link in the Home Page
  * **Creating Sales Tracking Page** \
    Create Sales Tracking Page and mention it as link in the Home Page
    
  ## Domain Model
  
  * **What is Domain Model** \
    Explains what is domain Model and how to create it
  * **Creating Customer Entity** \
    Create Entity and Attributes for Customer and Mention it in the customer page grid and Also explains how to create Enumeration
  * **Creating Product Entity** \
    Create Entity and Attributes for Product
  * **Creating Location Entity** \
    Create Entity and Attributes for Location
  * **Creating Sales Person Entity** \
    Create Entity and Attributes for Sales Persons
  * **What is Relation Database?** \
    Explains what is relational database and how tables are mapped using Primary and Foreign Key, explains what is One to One, One to Many and Many to Many relations
  * **Creating Relation Between Entities** \
    Create relation between Entities created eallier
  * **Defining Datagrid Sources** \
    Define the entities to datagrid created for Customer, Product, Sales Person and Sales Tracking Page
    
  ## Creating Edit Pages and generating Data
  
  * **Creating Edit Page** \
    How to create Edit/New page on New Button 
  * **Creating Page Navigation** \
    Create Page Navigation and add links in Navigation
  * **Adding Data to Customer Entity** \
    Create, edit and Delete Customers
  * **Adding Data to Product Entity** \
    Create, edit and Delete Product
  * **Adding Data to Location Entity** \
    Create, edit and Delete Location
  * **Adding Data to Sales Person Entity** \
    Create, edit and Delete Sales Person
  * **Adding Data to Sales Tracking Entity** \
    Create, edit and Delete Saled Tacking
    
  ## Mobile Application
  
  * **Creating HomePage** \
    Create Home Page for Mobile Usage
  * **Creating Customer and Product Pages** \
    Create Customer and Product list Pages
  * **Applying CSS and HTML** \
    Explines how to add html and css to attributes
  * **Adjusting Listview cells with CSS** \
    Add Containers(DIV) and Text fields in the List view of Customer Page
  * **Adjusting Listview cells with CSS 2** \
     Add Containers(DIV) and Text fields in the List view of Product Page
  * **Understanding Data View** \
    How to open new page by clicking on a item in data grid list - Data View will be used to display one row, Data Grid will be ised to display all the rows in term of list
  * **Understanding Data View 2** \
    Create Save button to commit the object and Back Button to Close the page
  * **Creating Sales Order Draft Entity** \
    Create Temprory Table for Sales Tracking and Added DataGrid to list the Temprory Sales Tracking Records. 
  * **Create Sales Order Draft Page** \
    Using microflow for Button to open DataView page to create Temprory Sales Tracking Page
  * **Adjusting Sales Order Draft Page UI** \
    Add container(DIV) and Text Field to Sales Order Tracking Temprory DataGrid view to improve the UI
    
  ## Microflows
  
  * **Create Variable** \
    Create and Use Variable
  * **Change Variable** \ 
    Change content of variable
  * **If Statement** \
    Use flows to create if statement
  * **How to Debug Microflows** \
    How to Use Beakpoints and Debugger to debug Microflow
  * **How to observer Database** \
    How to use open Database Application in Mendix and view data
  * **Retrive** \
    How to retrive object in Microflow
  * **Loop** \
    How to create ForEach loop
  * **Create Object** \
    How to create object in microflow, Commit Object, Refresh on Clint feature
  * **Change Object** \
    How to change attribute values of an object
  * **Delete Object** \
    Delete object in Microflow
  * **Nested Microflow** \
    How to call one microflow from another, How to return value from microflow 
  * **Merge Action** \
    How to merge flows in Microflow
  * **Break - Continue** \
    How to Break and Continue in Loops
  * **Change List - Microflow as DataSourse** \
    Create List, Replace values in list, Delete value in the list
  * **Aggregate List** \
    Use of Min, Max, Count, Sum function for list of object
  * **Usage of List operation** \
    Usage of Union, Intersection, Subtact, Contains, Sort, Filter, Find, Tail operations on the List
  * **Send Draft Sales to Real System** \
    Added functionality to send the Temprory Sales Tracking Objects to Real Sales Tracking Object
    
  ## XPATH
  
  * **XPath String Function** \
    Explains XPath and XPath String Function to Filter Data
  * **XPath Data Function** \
    XPath Date Function to Filter Data
  * **XPath as Datasourse** \
    Usage of XPath to filter Data to View on Grid
  * **XPATH and System Variables** \
    Usage of System Variables in XPath Constaint
    
  ## Security
  
  * **Mendix Security System and User Roles** \
  Creating User Roles and Users
  * **Data Level Security** \
  Adding User Roles at Data Level
  * **Page Level Security** \
  Adding User Role at Page Level
  * **Microflow Level Security** \
  Adding User Roles at Microflow Level to access the Microflows
  * **Entity Level Security ** \
  List Data Based On the User Roles by Defining the XPath Constaint at Entity Level
  * **Role Based Visibility** \
  Defining the visibility based on userRole to view Data in Data Grid
  * **Attribute Based Visibility** \
  Showing up the One Attribute Based on Defining values on Other Attribute(Enumeration)
  * **Expression Based Visibility** \
  Displaying one Attribute on the Page Based on Expression Condition met on other attribute value
  
  ## Advance Domine Model
  
  * **Deep dive into Domain Model** \
  Create association between 2 entities present in different Model, Define Validation at Attribute level, Event hadlers to call Microflow after specific actions line commiting the object, deleting object etc, Defining Indixes on attributes for fast search, defining the access rules based on user roles.
  * **Validation Rules** \
  Added some validation rules on Sales Order Tracking entity
  * **Calculated Columns - Listen to Widget** \
  Calculate number of records in Sales Order Temprory Tracking table by looking into datagrid
  * **Calculated Column With Entity Parameter** \
  For an attribute call a microflow to get the calculated value by default
  * **Delete List View Item - Adjust UI of Listview Cell** \
  Add Delete button for each row in Sales Order Temprory Tracking datagrid to delete a row
  
  
  ## Java Actions
  
  * **How to Install Community Common Package** \
  How to install and use predefined Java Actions in Mendix
  * **Java Action - DateTimeToLong** \
  How to calculate float number for date
  * **Java Action - Months Between** \
  How to calculate Months between Two Date
  * **Generating Random Hash for Sales Order** \
  Generate Hash value for transfer of Sales Order Tracking Temprory objects to Real Sales Order Tracking object
  * **Java Action - Split String Function** \
  Split string Java Action function
  
  ## Consuming REST Services
  
  * **Getting Current IP Addess using REST** \
  Get Current IP address by calling ipify.org API
  * **Get Current Location using REST** \
  Get current location using ip-api.com api
  * **Sending user Location to System** \
  Use above apis to get the current location and ip address and store in Sales Ordere Tracking Page
  
  ## App Store - Custom Widgets
  
  * **What is Mendix App Store **\
  How to use Mendix App Store to use custom widgets
  * **Custom Widget - OnChange Input** \
  Add on change field to application
  
  ## Adjusting User Interface and Final
  
  * **Adding buttons to Bottom NavBar** \n 
  Adding links to Mobile navigation bar
  
  
  
  ### Course Completed Certificate
  ![Certificate](/images/UdemyCerificate.jpg) Format: ![Alt Text](url)
  
  
  Source: [Udemy Course By Tarik Subaşı](https://www.udemy.com/course/mendix-low-code-application-development-course/)
  
  
  
  
  
    
    
  
  

 
  
