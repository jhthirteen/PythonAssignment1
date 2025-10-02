# 🐾 Interactive Lesson 1 - Pet Class

## Topics Covered

- Using **variables** to store information  
- Creating simple **classes and objects** for the Object-Oriented Programming (OOP) Paradigm  
- Using **third-party libraries** to practice integrating reusable features 

## Assignment Instructions
You are tasked with creating a Pet Class in the file **Pet.py**. This object should allow users to dynamically instantiate Pet objects in their code and perform actions with the objects.
1) Create the Pet Class
1a) Create a constructur
- Remember, a constructor for every class in Python has the following syntax: def __init__(self).
- The constructor should have the variables _name_, _species_, _age_, _birthday_ as arguments, so these basic facts can be stored for our Pet
1b) Create a method called __speak__ for the animal to output something
1c) Create a method called __describe__ that outputs the name of the pet, its species, and how old it is!
1d) Create a method called __happy_birthday__ that increases the age of the pet by one year.

2) Practice creating objects
2a) In **main.py**, import your Pet class, create a Pet, and call all its functions.

3) Use a third-party library to enhance outputs
3a) Use pip to install the emoji library with the command _pip install emoji_
3b) Import the emoji library at the top of the file **Pets.py** with the statement _import emoji_
3c) In your __describe()__ function, include an emoji of your choice in the output!
- ex) print(emoji.emojize(f'{self.name} says hi! :smile_cat:'))
- You can find the names of all the emojis to use in code here https://www.webfx.com/tools/emoji-cheat-sheet/
