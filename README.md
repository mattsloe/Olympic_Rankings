# Olympic_Rankings
# Overview
* Look at the stats for the top 5 olympic contenders and learn more about these athletes
  - How long they have been compeeting
  - If they have background in world circuit
  - Is this their first olympics?
* Pick different competitions you are interested in

# Specification
## Class Heirarchy
* Create a heirarchy of 3 types of competitions derived from a common base class
  - Push up the common elements and derive the differences
* Pick 2 or 3 stats that you would like to keep track of

## A Collection of Athletes
* Build a collection of athletes participating in a particular type of competition
* Keep 3 different types of competitions in three different data structures
  - no need for dynamic binding
* One data structure should be homemade and the other two can be from the STL (Array,vector,list)

## Implementing Data Structure Choices
* Need to implement a BST or a balanced tree
* Balanced trees do not need a remove function
  - Insert, Search, and Display functions

1. Implement a binary search tree. It should have a full complement of insert, search, display, and remove functions
1. Implement a balanced tree of your choice (except an AVL tree)

**REQUIRED for this assignment:**
* exception handling
* using string class
* use one char*
* use at least one STL data structure at least once
  - Array, Vector, List, Forward List
* Implement a full complement of Operators Overloaded

## Operator Overloading Requirements
* Support operators with your classes (=,+,+=,==,!=,relational operators, stream insertion/extraction)
  - Can we use relational operators to determine where an athelete is placed in the tree
  - Consider operators as wrapper functions for named functions
