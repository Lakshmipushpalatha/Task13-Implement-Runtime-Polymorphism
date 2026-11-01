# Task13-Implement-Runtime-Polymorphism
java calculation

# Task 13: Implement Runtime Polymorphism

## 1. Introduction
Runtime Polymorphism is an important concept in Java Object-Oriented Programming (OOP).

It allows a parent class reference to hold different child class objects. The method that gets executed depends on the actual object at runtime.

## 2. Objective
The main objective of this task is to understand:
- Runtime Polymorphism.
- Dynamic Method Dispatch.
- Method Overriding.
- Parent class references holding child class objects.

## 3. Description
In this task, we create one parent class called `Animal` and two child classes called `Dog` and `Cat`.

The parent class contains a common method called `sound()`.

Both child classes override the `sound()` method and provide their own implementations.

A single parent class reference is used to call the overridden methods of different child objects.

## 4. Classes Used

### Animal (Parent Class)
- Contains the `sound()` method.
- Acts as the common parent class.

### Dog (Child Class)
- Inherits the Animal class.
- Overrides the `sound()` method.
- Displays "Dog barks".

### Cat (Child Class)
- Inherits the Animal class.
- Overrides the `sound()` method.
- Displays "Cat meows".

## 5. Program Execution
1. Create an object reference of the parent class `Animal`.
2. Assign a `Dog` object to the parent reference.
3. Call the `sound()` method.
4. Assign a `Cat` object to the same parent reference.
5. Call the `sound()` method again.
6. Java selects the appropriate overridden method at runtime.

## 6. Source Code
The program uses:
- `extends` keyword for inheritance.
- `@Override` annotation for method overriding.
- Parent class reference to hold child class objects.
- Dynamic Method Dispatch to achieve runtime polymorphism.

## 7. Expected Output

```text
Dog barks
Cat meows
```

## 8. Concepts Learned

- **Polymorphism:** One thing having many forms.
- **Runtime Polymorphism:** Method execution is decided at runtime.
- **Method Overriding:** A child class provides its own implementation of a parent class method.
- **Dynamic Method Dispatch:** Java determines which overridden method to execute based on the actual object.
- **Inheritance:** Child classes acquire properties and methods from a parent class.

## 9. Conclusion
Through this task, I learned how to implement Runtime Polymorphism in Java using inheritance and method overriding.

I also understood how a single parent class reference can hold different child class objects and execute their overridden methods dynamically.

This task helped me improve my understanding of Object-Oriented Programming concepts in Java.
