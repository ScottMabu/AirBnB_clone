The Console.

DESCRIPTION
HBNB is a command-line interface (CLI) tool designed for managing various aspects of the Holberton BnB (HBNB) application. It provides a command interpreter that allows users to create, update, delete, and retrieve objects related to the HBNB application, including users, places, states, cities, and amenities.

Features

Object Management: Create, update, delete, and retrieve objects such as Users, Places, States, Cities, and Amenities.
Storage: Persist objects to a file using JSON serialization.
Interactive Shell: An interactive command interpreter for executing commands efficiently.
Non-Interactive Mode: Execute commands from a file or a script.

Command Interpreter

How to Start It

To start the command interpreter, execute the console.py script from your terminal. Ensure that you have Python installed on your system.
Clone the repository:

sh
Copy code
git clone https://github.com/username/AirBnB_clone.git
cd AirBnB_clone
Make the script executable (if not already):

sh
Copy code
chmod +x console.py
Start the command interpreter:

sh
Copy code
./console.py
Alternatively, you can start it using Python:

sh
Copy code
python3 console.py
How to Use It
Once the command interpreter is running, you can use various commands to manage your HBNB objects. The basic syntax for commands is as follows:

sh
Copy code
command [arguments...]
Examples
Creating an Object
To create a new object, use the create command followed by the class name:

sh
Copy code
create User
Showing an Object
To display the details of a specific object, use the show command followed by the class name and object ID:

sh
Copy code
show User 1234-5678-9012
Updating an Object
To update an attribute of a specific object, use the update command followed by the class name, object ID, attribute name, and new value:

sh
Copy code
update User 1234-5678-9012 email "newemail@example.com"
Deleting an Object
To delete a specific object, use the destroy command followed by the class name and object ID:

sh
Copy code
destroy User 1234-5678-9012
Listing All Objects
To list all objects of a specific class, use the all command followed by the class name:

sh
Copy code
all User
To list all objects regardless of the class, simply use the all command:

sh
Copy code
all
Exiting the Interpreter
To exit the command interpreter, you can use the quit or EOF command:

sh
Copy code
quit
or

sh
Copy code
EOF


