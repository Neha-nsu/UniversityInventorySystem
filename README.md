# UniversityInventorySystem
Comprehensive Java application demonstrating OOP principles through university asset management system. Manages equipment, furniture, and lab equipment assignment with full CRUD operations, exception handling, and reporting.

# Table of content 
Objective: 
 Master Object-Oriented Programming principles (encapsulation, inheritance, polymorphism, abstraction)
 Implement professional exception handling patterns
 Apply all Java control structures meaningfully
 Design modular, maintainable software architecture
 Demonstrate production-ready code quality
 Create portfolio-worthy GitHub repository with README
 
# Project Structure
UniversityInventorySystem/
│
├── src/
│ ├── models/
│ │ ├── InventoryItem.java
│ │ ├── Equipment.java
│ │ ├── Furniture.java
│ │ ├── LabEquipment.java
│ │ └── StaffMember.java
│ │
│ ├── exceptions/
│ │ └── InventoryException.java
│ │
│ ├── managers/
│ │ ├── InventoryManager.java
│ │ └── InventoryReports.java
│ │
  └── UniversityInventorySystem.java

#Features
Inheritance Hierarchy: InventoryItem → Equipment/Furniture/LabEquipment
Array Management: Max 5 equipment per staff member with add/remove logic
Custom Exceptions: EquipmentNotAvailableException, AssignmentLimitExceededException
Method Overloading: 3 searchEquipment() variants
Polymorphism: toString() and getItemType() overrides
Complete Loop Coverage: for, while, do-while, enhanced for
Menu-driven Interface: Exception-safe console application

# Conclusion
The University Inventory Management System successfully demonstrates mastery of core Java programming concepts through a comprehensive, production-ready application. This project fulfills all specified requirements across six assessment tasks, showcasing advanced object-oriented programming principles, robust exception handling, sophisticated control structures, and professional software architecture.
