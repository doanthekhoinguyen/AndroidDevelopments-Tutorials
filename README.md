
Fragments represents a reusable portion of your app's UI.
A fragment defines and manages its own layout, has its own lifecycle, and can handle its own input events. 
Fragments can't live on their own. They must be hosted by an activity or another fragment. The fragment’s
view hierarchy becomes part of,  or attaches to, the host’s view hierarchy.

A fragment defines and manages its own layout, has its own lifecycle, and can handle its own input events. 
Fragments can't live on their own.They must be hosted by an activity or another fragment. 
The fragment’s view hierarchy becomes part of, or attaches to, the host’s view hierarchy.


Modularity

Fragments introduce modularity and reusability into your activity’s UI by letting you divide the UI into discrete chunks.


A fragment has Kotlin code and a layout.
Every fragment extends the Fragment class or one of its
subclasses.
Add a fragment to an activity’s layout using a
FragmentContainerView.
onCreateView() gets called each time Android needs the
fragment’s layout.
The Fragment class doesn’t extend Activity.
Fragments don’t have a findViewById() method.
The Navigation component is a suite of libraries, plug-ins, and
tools which you add to your project using Gradle.
A navigation graph describes possible destinations and
navigation paths. It uses actions to describe these paths.
A navigation host is an empty container used to display the
fragment you navigate to. The Navigation component comes
with a default navigation host named NavHostFragment,
which extends the Fragment class and implements the
NavHost interface.
A navigation controller uses actions to control which fragment
is displayed in the navigation host.
