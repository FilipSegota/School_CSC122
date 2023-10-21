# School_CSC122
## Info
**Author:**
Filip Segota  
**Class:**
CSC 122 (Programming 2), Fall 2020  
**Assignment:**
Programming Improvement Lab  

## Overview
This lab consists of 3 phases. One of the most valuable skills when it comes to programming is to learn to work in phases. One should not attack the problem as one big problem. This lab will help put that into practice. It is not uncommon to not have the full requirements at the start of a project. That is true in this case. The project owner is going to want to develop a system for an education environment that will have students, instructors, and courses.

## Phase 1
This phase will be to deal with the people in the system. Design and create classes (in specified steps) for the people. We know that names, emails, IDs, and GPAs will be important to this system.
  - Step 1  
In step one, design the class (NOT code them) and design the testing of them.  
    - To design the people:
      1. Identify at least two or three items that students and faculty     share. Determine the data type and name for each.
      2. Identify at least two items unique to students. Determine the data type and name for each.
      3. Identify at least two items unique to professors. Determine the data type and name for each.
      4. For students, their GPA can change by adding a course (that is X hours) and a grade. We do not need to store the course itself (that would be a transcript and would be a separate class).
      5. Professors have a group of students that they advise.
      6. Might need more field variables to support the tasks.
      7. Create class UML diagrams for students, professors, and people. Add in all typical methods and any additional methods needed to maintain the data
      8. Design testing plans (with input and expected output) to test classes.
  - Step 2  
Implement the code
    - Code the three classes (using inheritance)
    - Code a driver to test (i.e. implement a testing plan)

## Phase 2
For this Phase, the advisee list should be a queue. Also, add classes (which have students and an instructor). The students will be a list. The class will also have a seating chart (a 2D array) for the students (with some seats able to be empty).
  - Design the work first
  - Implement the code

## Phase 3
For this phase, implement a number of different sorts and searches of the class lists and compare them.
  - **Step 1:** Comparing: code, implement, and test at least two different compareTo's for the student. (You will be able to only have one active at a time -> comment out the other one).
  - **Step 2:** Write up a report on this work.
  - **Step 3:** Add a method to your class Class to search for a given student. Use binary and unordered sequential search. Include a field variable that will count the number of compares and a method to report that result back.
  - **Step 4:** Test this method on small, medium, and large data with the student being in different places in the list and plot the results on a graph.
  - **Step 5:** Add a sort (of your choice), to sort the students by name. Include field variables to count the number of times a student in the class is moved to a different position and the number of times two students are compared to each other. Add methods to report these results.
  - **Step 6:** Test this method on small, medium, and large data (in order, in reverse order, in random order). and plot the results on a graph.
  - **Step 7:** Implement a binary search method and a sequential search on order data methods.
  - **Step 8:** Analyze the work done between just searching ordered data, sorting and sequential search, and sorting and binary search. Have a different number of lookups for one sort (a couple, maybe 1/2n, maybe n, maybe 10n). Report the results.
