Download Link: https://assignmentchef.com/product/solved-cpe212-project02-class-inheritance
<br>
<h1>PROJECT GOALS</h1>

The goal of this project is to test your knowledge of class inheritance. It also deals with an introduction into unsorted lists and basic pointers. At the end of this project you should feel confident in implementing class inheritance and incorporating code you write into a larger product.

<h1>PROJECT DESCRIPTION</h1>

In this project you will be implementing a very basic command line RPG game with two or more characters that will battle and support each other. You will be writing 7 classes to complete this assignment. These classes will be called Character, Warrior, Mage, Rogue, Cleric, Goblin and Inventory. You will be given the header files for each of the mentioned classes and they contain detailed descriptions of what is needed as well as the makefile and test files. Below are some key details for each class.

<h2>Character Class</h2>

The Character class is the parent class for all of the other classes except for the Inventory class. All of the other classes will inherit from this class. Note that there are several virtual classes that must be implemented in the inherited classes.










<h2>Inventory Class</h2>

The Inventory class is inherited from all of the other classes as each of the characters contain an inventory. The inventory is very simple at the moment with only two methods.




<h2>Warrior Class</h2>

The Warrior class inherits from both the Character and Inventory classes and represents a warrior in the game. The warrior has the unique characteristic of strength. This class also has the unique skill of PowerAttack which takes in a pointer to the character to be attacked.




<h2>Mage Class</h2>

The Mage class inherits from both the Character and Inventory classes and represents a warrior in the game. The warrior has the unique characteristic of intelligence. This class also has the unique skill of Fireball which takes in a pointer to the character to be attacked.




<h2>Rogue Class</h2>

The Rogue class inherits from both the Character and Inventory classes and represents a warrior in the game. The warrior has the unique characteristic of dexterity. This class also has the unique skill of BackStab which takes in a pointer to the character to be attacked.







<h2>Cleric Class</h2>

The Cleric class inherits from both the Character and Inventory classes and represents a warrior in the game. The warrior has the unique characteristic of willpower. This class also has the unique skill of Heal which takes in a pointer to the character to be healed.




<h2>Goblin Class</h2>

The Goblin class inherits from both the Character and Inventory classes and represents a warrior in the game. The warrior has the unique characteristic of attack. This class also has the unique skill of SneakAttack which takes in a pointer to the character to be attacked.




<h1>PROJECT TESTING</h1>

To run the sample solution you must first login to the blackhawk.ece.uah.edu system and issue the following command:




-bash-4.2$  cd /your/project02/location

-bash-4.2$  /home/work/cpe212-01-20s/project02/Game inputfilename

where the inputfilename is the name of one of the provided input files (for example, test_inventory.txt). Your current working directory must contain the input files for this to work.




A test script can also be found with the following:

-bash-4.2$  cd /your/project02/location

-bash-4.2$  /home/facstaff/taf0004/CPE212SP20/Project02/preview02.bash

<h1>PROJECT INSTRUCTIONS</h1>

<h2>Compilation</h2>

This project consists of eight C++ files so you do not want to compile and link these files manually.  The makefile contains the sequence of commands required to compile and assemble (link) your executable program.  The provided file works on blackhawk.  So, for this assignment, all you must do to compile the program is to use the following command at the Linux command line

-bash-4.2$ make

which will create an executable named  project02 from the provided files main.cpp and the files you have written.

If your program compiled successfully, you may then type

-bash-4.2$ ./Game   NameOfInputFile

to execute your program assuming that the input file is located in the same directory with the executable.   (For example,   ./Game  test_inventory.txt  )

To force all files to be recompiled and relinked, type the following sequence of commands at the Linux prompt.

-bash-4.2$ make clean

-bash-4.2$ make

<h2>File Constraints</h2>

On Project02, all allowable include files are already specified in the provided source code materials.

Card header files such as “character.h”, “inventory.h”, or the classes header file are allowed

No additional include files are allowed!!!

Failure to follow these directions will result in zero (0) credit on this assignment.

<strong>          </strong>

<h2>Debugging</h2>

Your program must be fully commented (including variable and parameter declarations, function descriptions, descriptions of logical blocks of code, etc.)  in order to receive debugging assistance from the instructor and teaching assistants.  See Canvas for an example of an acceptable commenting style.

<h2>Submission</h2>

THERE ARE TWO SUBMISSIONS FOR THIS PROJECT:

1) Documentation.  This is due on Friday January 24 at 23:59. 2) Code.  This is due Friday, January 31 at 23:59.

Make sure to follow the checklist below to verify you get full credit on your submission. You MUST implement all of these classes and each of these files will need to be submitted through Canvas.




IMPORTANT

Your last submission must contain all of these files. All other submissions will be considered incomplete. Do NOT compress these files. Submit them individually.




▢ character.cpp

▢ inventory.cpp

▢ warrior.cpp

▢ cleric.cpp

▢ mage.cpp

▢ rogue.cpp

▢ goblin.cpp

<strong>          </strong>

<h2>Final Notes</h2>




IMPORTANT

Do NOT modify game.cpp as it is the main test driver that the automated grader uses.




IMPORTANT

Incomplete submissions will receive zero credit (0 points) on this assignment




IMPORTANT

Follow the instructions in the header of each class for very specific print instructions











