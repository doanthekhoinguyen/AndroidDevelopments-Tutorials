OnCreate() method called when the activity is first created

setContentView() tell Android which layout the activity uses

Each time the user does something in your app it’s called an event. There
are many different event types in Androidville, such as clicking a button,
swiping the screen, or pressing a hardware key on the device.

strings.xml is a String resource file. It’s used to separate out
text values from the layouts and activities, and supports
localization.
Add a String to strings.xml using:
<string name="name">
Value
</string>
Reference a String in the layout using:
"@string/name"
Add an array of String values to strings.xml using:
<string-array name="array_name">
<item>string1</item>
...
</string-array>
Reference a string-array in the layout using:
"@array/array_name"
Use the findViewById method to get a reference to a view
by its ID.
Make a button respond to clicks by calling its
setOnClickListener method.
The setOnClickListener method takes one parameter—
a lambda—which describes what should happen when the
button is clicked.
Change the text that’s displayed in a view by updating its
text property.
Get the selected item in a spinner using its selectedItem
property.
The selectedItem property can hold any type of value, so
you need to convert its value before you can use i
