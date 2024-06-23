# Java Class Hierarchy - 'Share Surprises' Application

## Description
The 'Share Surprises' application is a project aimed at deepening the understanding of class hierarchy design concepts in Java. The main goal of the project is to implement various object-oriented programming concepts, such as inheritance, composition and aggregation, encapsulation, interface utilization, and generics, in a practical and efficient manner.

## Objectives
- Reuse functionality through various means, including inheritance, composition, and aggregation.
- Implement a moderately complex class architecture with appropriate code organization.
- Work with objects of different types from a common perspective using upcasting.
- Design and use interfaces for communication between components.
- Implement the concept of generics in software development.

## Implementation
The project is structured into several sections, each detailed below:

### 1. Types of Surprises
Each surprise is represented by a class that implements the ISurprise interface. There are three types of surprises:
- FortuneCookie
- Candies
- MinionToy

### 2. Storing Surprises
Surprises are stored in various types of containers, which dictate the storage method and the order in which they are distributed. For this purpose, the IBag interface is used, and each container implements this interface.

### 3. Creating Surprises
The GatherSurprises class is responsible for the random generation of surprises, either in a specified number or just a single surprise.

### 4. Creating Containers
To create containers, a Factory Pattern mechanism is used, implemented through the IBagFactory interface.

### 5. Sharing Surprises
The abstract class AbstractGiveSurprises defines the mechanism for sharing surprises. This class is extended by three concrete classes: GiveSurpriseAndApplause, GiveSurpriseAndSing, GiveSurpriseAndHug, each distributing surprises in different ways.


--- 

This is a general description of the project. For specific details and the source code, it is recommended to access the relevant files.