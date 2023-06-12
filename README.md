# Head First Android Knowledge
This repository contains the knowledge I have gained while studying the "head first android development 3rd edition" book in chapter 3. 
The following sections provide a summary of the key concepts and techniques covered.

# Android has different types of layout

- Android has different types of layout, and each one has its own policy about
how its views are arranged
- A linear layout, for example, will always layviews out in a linear row or column, while a frame layout stacks its views,
one on top of another

# linear layout

- Events in Android include actions such as button clicks, screen swipes, or hardware key presses.

# String Resources

- Linear layout arranges views one after
another in a vertical column or a horizontal row.

- Orientation can be vertical or horizontal

- dp: density-independent pixels
- sp: scalable pixels

# MainFest.xml

- Every Android app must include a file called AndroidManifest.xml

- file contains essential information about your app that the Android operating system, the Android build tools, and the
Google Play Store need to know about.

-  This includes the app’s package name, details of any activities, and any permissions the app requires.

# Use padding to add space to the layout’s

# layout-gravity controls the position of a view within a layout

# The layout’s views are inflated into objects
-  setContentView() method converts the views in the layout’s XML
into objects. This process is called layout inflation because it inflates each
view into an object

- When run  app, Android instantiates the layout XML by
converting each of the layout’s items into an object. This is known as
layout inflation

# A frame layout stacks its views

- a layout whose views can overlap, a simple option is to use a
frame layout

-  Instead of displaying its views in a single row or column, it
stacks them, one on top of another. It’s often used to hold just a single view

-  When  define a frame layout, you list views in the order you want them
to be stacked. 

- The first view is displayed first, the second is stacked on top
of it, and so on.

# All layouts are a type of ViewGroup…All layouts are a type of ViewGroup…

- The ViewGroup class is a subclass of View that can hold other views.
Behind the scenes, every layout is a subclass of ViewGroup, which means
that every layout is also a type of View.

- Every UI component you add to a layout is a type of View: an object
that takes up space on the screen.
- Every layout is a type of ViewGroup: a type of View that can contain
other Views





Please note that this is a brief summary of the concepts covered. Refer to the "Head First Android" book for detailed explanations and examples.

