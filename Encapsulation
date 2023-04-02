Encapsulation: 

1. Defination: 
(Information Hiding)Restricting access to the classes/objects' certain attributes and methods.

2. Purpose: 
Data protection and restricing certain methods to be callable.

3. Technique:
This is not possible in python, so we use double underscore(__) as a prefix to hide attributes and objects 

How we would have access to the encapsulated variables is by: 
Defining a "GETTER":
ex.
class Student:
    def __init__(self,nameF, nameL, num):
        self.__firstName = nameF
        self.lastName = nameL
        self.studentNumber = num

    def getfirstName(self):
        return self.__firstName

#end of Student

s1 = Student("Mr.", "Park", 10)
s1.__firstName = "Ms."
print(s1.getfirstName()) # Returns/Outputs “Ms.”


4. Application: 
ex.1
class Student:
  def __init__(self,nameF, nameL, num):
    self.firstName = nameF
    self.lastName = nameL
    self.__studentNumber = num
  
  def __getStudentNumber(self):
    return self.__studentNumber
    
s1 = Student("Mr.", "Park", 10)
print(s1.__getStudentNumber()) # Will cause an error
print(s1.__studentNumber) # Will also cause an error
#If double underscores were removed from all the encapsulated variables, the first print would give 10 and the second print would also give 10. e


ex.2
class Student:
  def __init__(self,nameF, nameL, num):
    self.firstName = nameF
    self.lastName = nameL
    self.__studentNumber = num

#end of Student

s1 = Student("Mr.", "Park", 10)
print(s1.firstName) # Returns/Outputs “Mr.”

s1.firstName = "Ms."
print(s1.firstName) # Returns/Outputs “Ms.”
#If we do not encapsulate firstName, this is what would happen. 

5. Extra Helping Sources: 
https://www.youtube.com/watch?v=GN1LR0UoFI4
