# Head First Android Knowledge
This repository contains the knowledge I have gained while studying the "Head First Android Chapter 2" book. 
The following sections provide a summary of the key concepts and techniques covered.

# Overview

- The onCreate() method is called when the activity is first created.
- The setContentView() method is used to specify the layout that the activity should use.

# Events

- Events in Android include actions such as button clicks, screen swipes, or hardware key presses.

# String Resources

- The strings.xml file is a string resource file used to separate text values from layouts and activities, supporting localization.

- Add a string to strings.xml using: 
   <string name="name">Value</string>.
- Reference a string in a layout using:
   @string/name.

- Add an array of string values to strings.xml using:
  <string-array name="array_name"><item>string1</item>...</string-array>.

- Reference a string array in a layout using: 
   @array/array_name.

# Views and Interactions

- Use the findViewById() method to get a reference to a view by its ID.

- Make a button respond to clicks by calling its setOnClickListener() method.

- Change the text displayed in a view by updating its text property.

- Get the selected item in a spinner using its selectedItem property.

Please note that this is a brief summary of the concepts covered. Refer to the "Head First Android" book for detailed explanations and examples.
