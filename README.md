The Console.

DESCRIPTION

HBNB is a command-line interface (CLI) tool designed for managing various aspects of the Holberton BnB (HBNB) application. It provides a command interpreter that allows users to create, update, delete, and retrieve objects related to the HBNB application, including users, places, states, cities, and amenities.

Features

1.Object Management: Create, update, delete, and retrieve objects such as Users, Places, States, Cities, and Amenities.

2.Storage: Persist objects to a file using JSON serialization.

3.Interactive Shell: An interactive command interpreter for executing commands efficiently.

4.Non-Interactive Mode: Execute commands from a file or a script.

Command Interpreter;

How to Start It

-To start the command interpreter, execute the console.py script from your terminal. Ensure that you have Python installed on your system.

Clone the repository:

sh

enter code;

git clone https://github.com/username/AirBnB_clone.git
cd AirBnB_clone

Make the script executable (if not already):

sh

enter code;

**chmod +x console.py**

Start the command interpreter:

sh

enter code;

**./console.py**

Alternatively, you can start it using Python:

sh

enter code;

**python3 console.py**

How to Use It

Once the command interpreter is running, you can use various commands to manage your HBNB objects. The basic syntax for commands is as follows:

sh

enter code;

**command [arguments...]**

Examples

Creating an Object

To create a new object, use the create command followed by the class name:

sh

enter code;

**create User**

Showing an Object

To display the details of a specific object, use the show command followed by the class name and object ID:

sh

enter code;

**show User 1234-5678-9012**

Updating an Object

To update an attribute of a specific object, use the update command followed by the class name, object ID, attribute name, and new value:

sh

enter code;

**update User 1234-5678-9012 email "newemail@example.com"
**
Deleting an Object

To delete a specific object, use the destroy command followed by the class name and object ID:

sh

enter code;

**destroy User 1234-5678-9012**

Listing All Objects

To list all objects of a specific class, use the all command followed by the class name:

sh

enter code;

**all User**

To list all objects regardless of the class, simply use the all command:

sh

enter code;

**all**

Exiting the Interpreter

To exit the command interpreter, you can use the quit or EOF command:

sh

enter code;

**quit**


or


sh

enter code;

**EOF**


