# UML Diagram
An UML (Unified Modeling Language) class diagram is a visual representation of the structure of a system. It shows the system's classes, their attributes, methods (operations), and the relationships among the classes. Here's a simple explanation of the main components:
1. Classes
Represented as rectangles divided into three parts:
Top part: Class name (e.g., Person)
Middle part: Attributes (e.g., name: String)
Bottom part: Methods/Operations (e.g., getName(): String)
2. Attributes
Properties or data members of a class.
Syntax: attributeName: DataType
Example: age: int
3. Methods (Operations)
Functions or behaviors of the class.
Syntax: methodName(parameters): ReturnType
Example: calculateSalary(): float
4. Relationships
Associations: A general connection between classes (e.g., a Person uses a Car).
Multiplicity: Indicates how many instances of a class relate to instances of another class (e.g., 1..*, 0..1).
Inheritance (Generalization): One class inherits from another (e.g., Student inherits from Person), shown with a solid line and a hollow arrow pointing to the parent.
Aggregation: A "whole-part" relationship where parts can exist independently of the whole, shown with a line ending in a hollow diamond.
Composition: Stronger "whole-part" relationship where parts cannot exist without the whole, shown with a filled diamond.
