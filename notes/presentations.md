# Presentation Links

### Presentation Signup Form & Q/A
https://docs.google.com/spreadsheets/d/1H0HO2xX_xkNHPZv7Ealy1FPWbQwKsvN2sidp6juUjJI/edit?usp=sharing

### Presentation Rubric
https://github.com/gilland-astate/mobileappdev-winter2021/blob/main/resources/presentation_rubric.pdf


# Presentation Expectations
Each student will present their topic with a slide deck that will go over the basics of the topic. Each presentation should be practiced and timed to last 20 minutes. Going over or under the time limit will result in a hit on the credit for the course. Each presentation should also be as informative and comprehensive as possible. The presenter will be evaluated by each student based on the rubric posted above and the totals from the students will factor into the final grade received for the presentation. The graders participation will also factor into their final grade on the presentation. Comment period for each presentation will be no longer than five minutes and discussions for each presentation will be available through the Signup Form google document above with a Q&A style. Presenters will be expected to answer questions posted to the document for 1 week following their presentation. Comments posted on the Evaluation will be shared privately with the presenter as well.

# Presentation Description

### Selecting your Programming Language: Java vs Kotlin
* Slides 
    * https://github.com/gilland-astate/mobileappdev-winter2021/blob/main/resources/KotlinVsJava.pptx
* Pros & Cons of Each Language
* Short overview of how Kotlin changes Java for the better. (Tell me what each of these mean and how they help me as a developer)
    * "auto" style inference
    * Exception Handling (This is a pro & con)
    * Null Safe
    * Functional Programming
    * "data"
    * Extendability
    * Smart Casting
    * Co-Routines
* Demonstrate how Android Studio can convert Java to Kotlin, but there are caveats (You won't be able to recognize these, but see if you can find some information on the pitfalls of doing automatic conversion)

### Android Studio IDE Overview
* A quick install guide would be helpful, as well as where to find all of the relevant items you will need.
* Show how to use the IDE to place view components.
* The next presentation will talk about the structure of the program however knowing how to navigate the IDE in those areas may be helpful.
* Knowing some keyboard shortcuts for various needed functions or cheatsheets would be helpful. (Do your research don't give me the first cheatsheet on google unless its good!)
* Show us around the VCS (version control)
* Show how gradle works in the IDE (again remember the next presentation will go into some of these things)
* Explore pitfalls when working on projects as a team with the IDE (Not sure if there are any but maybe do a bit of digging to see if there are any complaints)
* Compile a "hello,world" style app and walk us through how to do so and what that looks like? (This one isn't necessary, but could be a nice quick glance at the process)


### Android Project Structure: Code, XML, Build Instruction Files
* This one is going to be either really easy or really hard to stay below 20 minutes.
* I want detailed info about all of the different aspects of how an Android Project should be structured.
* Best practices on where to store things in the IDE properly, how to manage your file structure and how to best name and categorize files.
* Best practices on storing configuration data when needed to pass for runtime to runtime.
* Using gradle and what build instruction files are for.
* Dependancy management and what needs to happen when you add additional dependancies (#includes in C terms)

### Activity Lifecycle
* What Are Activities - Quick rundown on what they are and what we need them for.
* Explain this image in detail and why this matters:
![Activity Lifecycle](https://developer.android.com/guide/components/images/activity_lifecycle.png)
* Explain in short how multi-window affects the activity lifecycle.

### Activity: Tasks, Notifications, & Back Stack
* Explain what the Back Stack is using a relevant example and how it relates to app traversal.
* Explain how the Back Stack is used to swap from activity to activity and how this relates to the Activity Lifecycle explained previously.
* What are tasks, and how do they relate to the Back Stack?
* How are tasks and thus the stack managed? Give examples and code as well as a quick walkthrough if time permits.
* Explain how the manifest file affects the activity/task.
* Quick overview on how tasks are launched.

### Services
* Different types of services with detailed explanations and examples of each.
* Service vs thread
* Service Lifecycle
* How services are declared
* Code examples + Walthrough of code explanation
* Explain AIDL and how it can be used to help you communicate with services.

### Broadcast Receivers
* Explain the publish-subscribe pattern using psuedocode & examples
* Overview of what broadcast receivers accomplish
* Explain how broadcast receivers are declared
* Code examples + Walthrough of code explanation
* How broadcasts are sent with code example

### Content Providers
* What Content Providers are.
* Advantages of using content providers versus hard coding
* Overview of the API
* Code Overview of creating/using content providers

### Intents
* Overview of Intents
    * How they are used
    * What they are for
* Difference between Implicit and Explicit
* Intent Filters and what they do
* Mainly this should be a basic high-level view of intents

### Intent v2
* Intent Implementation
* Overview of Intent Actions
    * Activity Actions
    * Broadcast Actions
* This should primarily be a deep dive into intents. We have already received and overview, give me more in-depth look at using intents in code and examples.

### Views
* Overview of View
* Element properties overviews
    * Position
    * Padding
    * Margins
    * Etc.
* Properly laying out elements
* Simple Views
    * TextView
    * ImageView
    * Button
    * EditText

### View Groups
* Overview of ViewGroups
* Built-in ViewGroups and how to use them
    * LinearLayout
    * RelativeLayout
    * FrameLayout
    * ConstrainLayout

### Custom View Types: Canvas, Bitmap, ect. (Built-ins)
* Using advanced view types
    * Canvas
    * Bitmap
    * Paint
    * Other built-in that are noteworthy
* Creating custom View

### Specific ViewGroup Types: RecyclerView, ViewPager
* Using advanced ViewGroups
    * RecyclerView
    * ViewPager
    * ScrollView
    * CoordinatorLayout
    * Spinner
* Creating custom ViewGroup

### Working with UI Resources
* Overview of the Android Resource Structure
* How to use UI Resources in your App
* Creating icons and drawables xmls
* Layouts
* Strings

### Working with UI Resources v2
* Advanced UI Resource overview
* Localization
* Different layouts for different devices
* Color
* Drawables
* Anims
* Menus

### Fragments
* Overview
* Benefits of Fragments
* Fragment vs Activity
* more...

### Working with Sharing Resources & File System I/O
### Build Options (Debug/Release) and Tips & Tricks
### Unit Testing
### Threading: Threads & Co-Routines
### Debugging & Profiling
### Android Jetpack Overview
### Jetpack Topic (I will choose this later)