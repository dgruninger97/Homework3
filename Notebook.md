# Homework 3

## Date 5/8/2020

## Entry 1: Balance Abstraction with the Best Factory Pattern

### Option 1: Factory Method Approach

I think that using the Factory Method pattern in order to generate a common Graph abstraction that hides the differences between the two implementations of the
graphs is a very good approach. Both of these Graph implementations can be constructed in the same factory since there is no real different between the two
graphs aside from the data structures used.Therefore, it makes perfect sense, in my opinion, to approach this problem via the Factory Method Pattern. Again, the reasoning
behind this being the fact that this approach will **hide the differences** between the two separate representations of the Graphs.

I created a **very preliminary** sketch of what this might look like below:
![FactoryMethod](images/FactoryMethodDiagram.png)

Again, the idea behind this approach is the reasoning that we can hide the differences between the two graphs implementations and construct them in the same factory.

### Option 2: Abstract Factory Approach

The second option of using an abstract factory approach also could apply to our problem. Since there are substantial differences regarding the **data structures**
used by the graph implementations, it makes sense to group them up as **families of related objects**. This approach would mean that we have two separate factories
which both differently handle the construction of the graphs.

Again, I have made a **preliminary sketch** of what this might loook like regarding an implemetation below.
![AbstractFactory](images/AbstractFactoryDiagram.png)
