# Kitchen Shelf Organizer
Kitchen Shelf Organizer is an IOS app helping users to organise kitchen shelf efficiently at the home.It helpes user to add and search items in shelf and notifies user periodically about items that are expiring. Proper management and proactive notification will result in efficient Kitchen management and reducing waste.

## Requirements
Kitchen Shelf Organiser is expected to provide below features.
* User should be able to create shelves.
* User should be able to Add/Delete/Update items with expiry date in selected shelf.
* User should be able to search the location of given item in the Kitchen.
* App should show the list of items that are expiring in near future.

## High Level Design 
<img src="./highLevelDiagram.png" width="800" height="600">

## Impementation Details
### Screen Details
#### Screen 1:  Main Screen
* "Screen 1" contains search bar for searching Item in Kitchen. While searching it will fetch the data from database and display the location of item in the label
* "Screen 1" has button "Check Shelves". On click of "Check Shelves" button "Screen 2" opens displaying the all the shelves.
* Table view in screen 1 fetch data from database and display the items which are expiring in near furture.

#### Screen 2
* Screen 2 displays the list of shelves user has created in table view.
* By clicking "+" button we can ADD new shelf.
* Clicking on any of the shelf will open "Screen 3" to show the items stored in the selected shelf

#### Screen 3
* Screen 3 displays the list of items in table view in the selected shelf.
* By clicking "+" button user can add items with expiration date in shelf. This items get update in database.
* Once data is added into table, "table view" in "Screen 3" refreshes to show updated data.

### Database
Database for this application will be on server.
                    





