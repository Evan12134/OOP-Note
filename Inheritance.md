Inheritance: 
When an object or class is based on another class; where its features are from a parent class

Three types of inheritance: 
Single Inheritance: A subclass inheriting the features of a single superclass / parent class
Multiple Inheritance: A subclass inheriting the features of a multiple parent classes
Multilevel Inheritance: A subclass is inheriting from another subclass… A → B → C

Multi-Generational
Grandparent → Parent → Child
2. Multi-Parent (Not limited to two)
Parent A \
			> Child
Parent B /

3. Mixture of 1 and 2


Important: 
If a child class inherits the parent class:
The child does not need a new __init__() method UNLESS it requires new attributes
The child does not need to reinstate the parent’s methods UNLESS you override them
