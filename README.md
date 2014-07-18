#Monsoon Android

Your assignment is to build a to-do-list Activity that looks like the main_screen.png / show_edit_screen.png.
All assets you need are included in assets folder.

###High level Features
- Show a list of user inputed tasks
- Add a task to the list
- Remove a task from the list
- Store tasks

###Task
User can create tasks with any number of characters and select color from pre-set color palette.

Color palette will define card color and text color. 1 card color is tied with 1 text color.

Color palette should have the ability to add / remove the color set easily.

###Add task
When tapping the edit icon on the bottom right corner of the main_screen.png, show the task input UI.

UI should include 
- Text input field
- Color palette picker
- Submit button

On the selection of color picker, show what color is selected and the state should be persistent.  You are going to decide what representation it should be.

Submit button should close the input UI and update the list on the main screen.

Tapping outside of the input UI should close it and not update the list.

###Remove task
When tapping the 'x' button on the card, the task should be deleted.  After deletion, the list should not have the task.

###Store tasks
The Tasks should be stored so that when the app is relaunched again, it should show what user added the last time.
The task list should look exactly the same as what the user entered last time.  (Color, order)

###Bonus Points
1. Add animations: (The type of animation is not specified.  You can show off your skills)
   - Show input UI
   - Hide input UI
   - New task card added to list

2. Swipe horizontally to remove task card.
3. Share the task to the native Google calendar app as an event  (Consider how the user enters the event time)


If you have any qustions, please feel free to contact emma@monsoonco.com.
