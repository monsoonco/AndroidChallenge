#Monsoon Android

Your assignment is to build to-do-list Activity that looks like main_screen.png / show_edit_screen.png.
All assets you need is included in assets folder.

###High level Features
- Show a list of user inputed tasks
- Add a task to the list
- Remove a task from the list
- Store tasks

###Task
User can create task with any number of characters and select color from pre-set color palette.

Color palette will define card color and text color. 1 card color is tied with 1 text color.

Color palette should have ability to add / remove color set easily.

###Add task
On tap of edit icon on the bottom right corner on main_screen.png, show task input UI.

UI should include 
- Text input field
- Color palette picker
- Submit button

On selection of color picker, show what color is selected and state should be stayed.  You are going to decide what represetation should it be.

Submit button should close input UI and update the list on main screen.

Tap outside of input UI should close input UI and do not update the list.

###Remove task
On tap of x button on card, delete a task.  After the delete, the list should not have the task.

###Store tasks
Tasks should be stored so that when app is relaunched again, it should show what user added last time.
Task list should look exactly same as what user input last time.  (Color, order)

###Bonus Points
1. Add animation on (A kind of animation is not specified.  You can show off your skills)
   - Show input UI
   - Hide input UI
   - New task added to list

2. Swipe to remove task card.
3. Share the task to Native Google calendar as event  (Consider how user input event time)
