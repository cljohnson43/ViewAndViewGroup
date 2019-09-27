# View and ViewGroup Homework Assignment (Week 1 Day 3)
## Research Questions

1. **What are Listeners?**

Listeners are objects that have registered with an event source so that when the event source fires an event the registered event listener object will be notified. The notification usually takes place via a registered callback function that is called by the the event source and has all relevant information about the event passed to the callback in the form of a function argument.

2. **Define the difference in Runtime and Compile Time.**

Runtime and compile time refer to different stages of a program. Runtime refers to the time when the program is executing and compile time refers to when the program is built. There is also runtime binding versus compile time binding.

In runtime binding a reference isn't bound until the program is executing. For compile time binding a reference is bound at the time the program is built. Compile time binding has better performance and type checking, but is less flexible than runtime binding.

3. **What is reflection in JAVA?**

Reflection in Java is an API defined in the java.lang.reflect package. The API provides a way to access, modify, and use methods and properties for classes, methods, and interfaces at runtime. This allows an application to extend third-party classes, bypass access modifiers on properties, enumerate a class's API, etc.

References: [Reflection in Java](https://www.geeksforgeeks.org/reflection-in-java/) and [Trail: The Reflection API](https://docs.oracle.com/javase/tutorial/reflect/index.html)

4. **How does gradle work behind the scene.**

Gradle executes a build in three phases:

    * Initialization - the build environment is set up and the build script is evaluated to determine what projects are needed to perform the user's task.
    * Configuration - The tasks needed for to perform the user's task are identified, then the task graph is built, finally the order that the tasks need to be performed is determined.
    * Execution - The tasks are executed and the project is built.

5. **Explain each of the following view dimension measurement types :
sp, dp, px, pt, in, mm?**

sp - Scale independent pixel - A unit that is based on the pixel density of the screen and the user's font size preference.
dp - Density independent pixel - A unit that is based on the pixel density of the screen. The dp is relative to a 160 dpi screen.
px - Corresponds to a screen pixel
pt - Stands for points and corresponds to 1/72 of an inch based on screen size
in - Corresponds to actual screen size in inches
mm - Corresponds to actual screen size in millimeters

## Coding Problems

Write an application that will take a user input, reverse the string entered, and display it to a textview. Play with different attributes for the views.

### Screen Capture
![Screen Capture](/app/src/main/res/img/ViewAndViewGroup.png)
