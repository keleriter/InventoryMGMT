# Usability Summary #
Nielsen’s ten heuristics are a set of rules to keep in mind when designing an user interface. They provide a framework as to how to create an interface that is user friendly and efficient, ultimately enabling UI/UX designers to give users the best experience possible. The 10 Heuristics are listed below (Nielsen, 2020).
1. Visibility of system status
2. Match between system and real world
3. User control and freedom
4. Consistency and standards
5. Error prevention
6. Recognition rather than recall 
7. Flexibility and efficiency of use
8. Aesthetics and minimalism
9. Error recognition
10. Help and documentation

Hello world utilises majority of these Heuristics to create the Inventory Management User Interface. 

## General ##
Element | Description
------- | -----------
Tooltips | When users hover on various elements, tooltips may appear to help users understand the various functionalities. This is a form of **help and documentation**.
Toolbar | Users can navigate to different screens of the application easily, giving them **user control and freedom**
Application Thumbnail | The application's thumbnail is **aesthetic and minimal** and provides a **consistentcy** throughout different windows

## Login Page ##
Element | Description
------- | -----------
Prompts in username and password fields | This is an example of **help and documentation**. The prompt enables users to easily navigate the application as they are made aware of what information needs to be inputted where.
Incorrect credentials results in red text “Incorrect credentials, please try again” | This is **error recognition**, as the user is informed of whether their credentials(inputted to login to their account) were correct or not. It also prompts the user to try again, which also fulfills another of Nielsen’s ten heuristics: **recognition not recall**.
Whitespace around edges of the window | The interface shows **aesthetics and minimalism**. The simple grey and white colour scheme is clear and clean, avoiding cluttering and unnecessary objects.
Hello World Logo | The Hello World logo is clearly recognisable and remains **consistent and standard** through all other interfaces.The green and white colour theme is also minimalistic and easy to recognise. 

## Dashboard ##
Element | Description
------- | -----------
Logout icon | **Match with Real World** (Skeuomorphism):The logout button is the symbol of the door with an arrow. This is a universally recognised symbol for exiting the current location. 
Logout button | **User control and freedom**: Users can easily exit the application through the click of this button. 
Use of whitespace | The use of whitespace results in a clean interface that is simple and uncluttered (**minimalistic design**). The JavaFX application uses default themes depending on the device, and a sense of familiarity and **consistency** is present whether it is ran on Windows, MacOS, or other operating systems.
Product filter | The placement is **consistent** to most web applications, the filters are places on the leftmost side.
Refresh button | **User control and freedom**: The refresh button allows users to update all the records displayed in the database at their choice.<br>**Consistent and Standard**: the refresh symbol is placed at the top right hand side of the screen consistently throughout the application.<br>**Match with Real World** (Skeuomorphism): The replay button logo for the refresh button is a universally recognised symbol. 
Resizable columns | The dashboard allows the user to adjust the width and size of each of the columns on the dashboard and these changes can be reset by clicking the refresh button at the top right corner of the window. This is an example of **user control and freedom**, as they can customise their dashboard. This also increases the **flexibility** of the application to suit individual user needs.
Remove filter through refresh | **User control and freedom**: users can choose to filter their orders and clear all filters by clicking the refresh button situated at the top right of the screen.
Disabling functionalities for suppliers | **Error prevention**: This prevents suppliers from accidentally or intentionally using that function. If not controlled, this could compromise the integrity of the database.
Piechart label shows counts of each status | **Recognition not Recall** : The pie chart is a visual representation of all the orders listed in the database, sorted according to order status. Instead of sorting each order individually and having to remember, the user can recall the proportion of orders according to status by referring to the pie chart. 


## Create Order ##
Element | Description
------- | -----------
Deletion of order item | If a user is ordering multiple products in one order, they have the ability to cancel specific products within that order. This is an example of user **control and freedom**. 
Warning screen when field(s) are unfilled | **Error recognition**: pop up window telling the user they’ve either not filled all the fields, or the quantity is invalid. From this information, users can rectify errors made. 
Multiple order items on table | **Visibility of System Status**: This table provides information to the user on whether the system has processed the specific product order or not, hence informing the system status,  before the user confirms their order and committing it to the orders database. 

## Edit Order ##
Element | Description
------- | -----------
Delete button | **User freedom and control**: users can discard the orders whenever they want
Trashcan icon | **Match with Real World** (Skeuomorphism): The trashcan icon is a commonly recognised symbol for discarding unwanted items. In this application, the trashcan symbol can be recognised by users as a function to delete an order.
Delete order confirmation window | **Error prevention**: This warning message make the user aware that they are clicking the option to permanently delete an order. This prevents errors where the user may have not known how to navigate the function and accidentally clicked the delete order function.
Alert message when you try to edit without selecting an order | **Error recognition**: The pop up window telling the user they have not selected an order to edit allows the user to understand the error that they have made to then go onto rectify it (i.e. Click an order).
Cancel button | Users can cancel editing the order at anytime giving them **user control and freedom**.

## Suppliers Page ##
Element | Description
------- | -----------
Ability to adjust the width of table columns | **Inclusivity**: The user can adjust the width of the columns on the dashboard and these changes can be reset by clicking the refresh button at the top right corner of the window. This is also an example of **user control and freedom**, as they can customise their dashboard, and undo those changes if they are not desirable.This also increases the **flexibility** of the application to suit individual user needs.
Home button | **Match with Real World** (Skeuomorphism): The home icon is a commonly recognised symbol for returning to original location. In this application, the home symbol is recognised by users as a function to return to the original dashboard one views when first logging in. 

## About Page ##
Element | Description
------- | -----------
Textbox | **Help and documentation**: source of documentation which provides additional information to the user regarding copyrights and references to other libraries used in the development of the application. 
About button | **Match with Real World** (Skeuomorphism): The exclamation mark symbol is easily recognisable as something that needs to be read urgently. This allows the users to understand the purpose of that button without having to read a written description of the function. 

## References ##
> Nielsen, J. 2020, *10 Heuristics for User Interface Design: Article by Jakob Nielsen*, Nielsen Norman Group, Accessed 15 November 2020, <https://www.nngroup.com/articles/ten-usability-heuristics/.> 
