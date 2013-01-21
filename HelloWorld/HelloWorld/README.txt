Andrew Wirth

This project is called Hello World App.  This app allows the user to enter a name in the textbox, then by either hitting 'done' on the keyboard or hitting the 'hello' button it will say "Hello, {textbox text}!" or "Hello, World!" if the textbox is empty.  

What does 'resignFirstResponder' mean?  
- In this instance it allows the user to use the textbox, instead of the keyboard.  When the textbox is selected, the keyboard becomes the First Responder.  When the user does not want to use the keyboard, you want the app to set the First Responder to the textbox (or main storyboard).  The 'resignFirstResponder' just resets the First Response to the storyboard instead of the keyboard.
