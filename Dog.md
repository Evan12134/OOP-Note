class Dog:
    ''' Dog conceptualizes possible attributes and methods that a Dog can have to represent an idea of a Dog through programming

    Attributes:
        name: the name for the Dog
        breed: the breed for the Dog
        age: positive integer age for the Dog
        
    '''

    def __init__(self, given_name, breed, age):
        ''' Initializes the dog by providing its name, breed and age

        Arg:
            name: the name for the Dog
            breed: the breed for the Dog
            age: positive integer age for the Dog
        '''
        self.name = given_name
        self.breed = breed
        self.age = age

    def bark(self):
        ''' This gives Dogs an ability to bark: will output Woof! '''
        print('Woof!')

    def eat(self, food):
        print(f'{self.name} is eating {food}')

    def __str__(self):
        ''' This is a __str__() base override to give our Dog Objects a string equivalent value. This allows our Dogs to type casted to strings. WHENEVER WE PRINT AN OBJECT, 
        THE OBJECT WOULD AUTOMATICALLY LOOK FOR STR'''
        return f'A {self.breed} named {self.name} with an age of: {self.age}.' 

    def __repr__(self):
        ''' Making our Dog Objects being representable in other objects. This is done by overriding __repr__()'''
        return self.__str__()
        
      EXTRA SOURCE:
      https://www.youtube.com/watch?v=39m3rstTN8w
