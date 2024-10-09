# classes-and-objects
Experiment 11
## Contents
- [Aim](#aim)
- [Software Used](#software-used)
- [Theory](#theory)
  * [Definition](#definition)
  * [Class](#what-is-a-class)
  * [Object](#what-is-an-object)
  * [OOP Principles](principles-of-oop-in-c++)
- [Algorithms](#algorithms)
- [Conclusion](#conclusion)
## Aim 
To study Class and Objects

## Software Used 
VS Code

## Theory
### Definition
Object-Oriented Programming (OOP) is a programming principle centered around the concept of "objects."
#### What is a Class?
Class is basically a framework or blueprint which we use to create objects. It encapsulates data and functions that operate on the data. Objects share similarities to its class. For eg children and thier parents where children could be considered objects of the parent class.
> For example:
```cpp
#include <iostream>
using namespace std;

class Dog {
public:
    string name;
    int age;
