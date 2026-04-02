Smart Fridge Temperature Controller (Python)
Overview

This project is a Smart Fridge Temperature Controller built using Python. It simulates a real refrigerator system where users can monitor and control temperature through a menu-driven interface. The project demonstrates core Object-Oriented Programming (OOP) concepts.

Features
View current temperature
Increase / decrease temperature
Quick Freeze mode (-2°C)
Normal mode (2°C)
Input validation for safe temperature limits
Continuous menu-driven interaction


Concepts Used
Object-Oriented Programming (OOP)
Classes & Objects
Inheritance
Conditional Statements
Loops (while loop)


Project Structure
Fridge (Parent Class)
   ├── Attributes: temperature, min_temp, max_temp
   ├── Methods: display(), increase(), decrease()

SmartFridge (Child Class)
   ├── Inherits Fridge
   ├── Methods: quick_freeze(), normal_mode(), menu()


How It Works
The program displays a menu with options
User selects an action
System performs the operation
Loop continues until user exits


sample Menu
1. Display Temperature
2. Increase Temperature
3. Decrease Temperature
4. Quick Freeze Mode
5. Normal Mode
6. Exit


How to Run
python fridge.py
📷 Output Example
--- FRIDGE DISPLAY PANEL ---
Temperature: 2°C
---------------------------


Objective
Simulate a real-world fridge system
Apply OOP concepts in Python
Build an interactive console application

 

Conclusion

This project successfully demonstrates how Python and OOP can be used to create a structured, reusable, and real-world simulation of a smart appliance.
