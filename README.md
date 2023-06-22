# Rotating the screen changes the device configuration

- The device configuration includes options specified by the user (such
as the locale), and options relating to the physical device (such as the
orientation and screen size). A change to any of these options results in
the activity being destroyed and then recreated

# An activity’s states

- When Android creates and destroys an activity, the activity moves from
being launched to running to being destroyed.

- The main state of an activity is when it’s running or active.

- When an activity moves from being launched to being destroyed, it triggers
key activity lifecycle methods: the onCreate() and onDestroy()

- An activity is running when it’s in the foreground of the screen

- The onCreate() method gets called immediately after your activity is
launched. 
- The onDestroy() method is the final call you get before the activity is
destroyed




- Your activity inherits the lifecycle methods

- The activity lifecycle methods are defined in the
android.app.Activity class. Each activity you create is a subtype of
this class, so it inherits these methods.

# Save the current state in a Bundle

- A Bundle is a type of object that’s used to hold key/value pairs. Before the
activity is destroyed, Android lets you put key/value pairs into a Bundle.

- This Bundle is then picked up by the new instance of the activity when
it’s recreated. Using a Bundle therefore gives you a way of reinstating an
activity’s state when you rotate the device screen


- Save the state using onSaveInstanceState()
- Bundles are passed from one instance of an activity to another using two
methods: onSaveInstanceState() and onCreate().
- onSaveInstanceState() lets you add values to a Bundle before the
activity is destroyed, and onCreate() picks the Bundle up again when
the activity has been recreated


1. The activity gets launched, and the onCreate() method runs.
Any activity initialization code in the onCreate() method runs.
At this point, the activity isn’t yet visible, as no call to
onStart() has been made.
2. The onStart() method runs. It gets called when the activity is
about to become visible.
After the onStart() method has run, the user can see the
activity on the screen.
3. The onStop() method runs when the activity stops being visible
to the user.
After the onStop() method has run, the activity is no longer
visible.
4. If the activity becomes visible to the user again, the onRestart()
method gets called followed by onStart().
The activity may go through this cycle many times if the activity
repeatedly loses visibility and then becomes visible again.
5. Finally, the activity is destroyed.
The onStop() method will get called before onDestroy()




Please note that this is a brief summary of the concepts covered. Refer to the "Head First Android" book for detailed explanations and examples.

