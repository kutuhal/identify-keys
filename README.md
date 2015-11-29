# identify-keys

#### What it does?

HTML code is minimal here. A simple input field is there. Everytime a key is pressed, all the events fired are shown on the screen.
Also, it will show the exact keypressed **_e.g._** *T* or *t*.
#### Why?

This was done to crystalize the learning of keyevents and how to identify the key that was pressed using JavaScript.


####Points to remember

- **event.which** holds the *charCode*
- __*keydown/keyup*__ and __*keypress*__ can give different *charCode*
- Use __*keyup*__ and __*keydown*__ for identifying physical keys and __*keypress*__ for identifying typed characters. 
- **keypress** event is not fired for all keys (_e.g. ALT, CTRL, SHIFT, ESC_)
