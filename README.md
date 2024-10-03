Deep-dive into the pillars of object-oriented programming and their application, then learn how to profile and optimize code.

In this tutorial, you’ll learn about the first pillar of object-oriented programming: Abstraction. 
By the end of this tutorial, you will be able to:
1. Explain how abstraction is used to expose only necessary script components
2. Expose only the important details of an object by correctly recognizing opportunities to implement abstraction

In this tutorial, you’ll learn about inheritance and polymorphism, two closely related pillars of OOP;
1. Explain how inheritance is used to share functionality between a parent and child class
2. Define the relationship between a parent and child class, including what a child class can and cannot do with respect to its parent class.
3. Recognize opportunities where inheritance could be used to simplify code.
4. Describe how polymorphism is used to modify parent class functionality in a child class
5. Describe how polymorphism can be applied at compile time (method overloads) and run time (method overrides).
6. Recommend a high-level system architecture for a given project

In this tutorial, you’ll learn about the second pillar in object-oriented programming: encapsulation.
1. Explain how encapsulation is used to write code that can only be used as intended by the programmer
2. Control access to data within a class by applying encapsulation with getters and setters
3. Obj-Prog-WIC-3.3: Differentiate between public variables (properties), private variables (fields), and local variables.
4. Enable easier readability and debugging by correctly organizing classes to include only singular purpose code

In this tutorial, you’ll learn how to use the Profiler to analyze a scene and identify where optimization bottlenecks are occurring.
By the end of this tutorial, you will be able to:
1. Deduce the script method that uses the most CPU time (vs. a script method that does not) by using the CPU profiler in the Profiler window
2. Differentiate a loop that efficiently goes through a collection once in an Update() call from many loops that go through the same collection in an Update() call
3. Recognize possible issues that might cause performance problems (e.g., too many RigidBody components, too many Colliders, too many shadows, etc.), given a scenario
4. Investigate performance issues caused by poly count, texture sizes, or too many objects on the screen by using Unity's Stats window
5. Identify unnecessary nested if statements
