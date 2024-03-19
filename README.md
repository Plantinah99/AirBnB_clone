This project is a Python implementation of a command interpreter for an Airbnb clone. The command interpreter allows users to perform various actions such as creating, updating, and deleting instances of different classes like BaseModel, User, State, City, Amenity, Place, and Review. The instances are stored in a JSON file for persistence.

Command Interpreter Description
To start the command interpreter, run the console.py script. The prompt will be (hbnb) .

How to Start
To start the command interpreter, run ./console.py .

How to Use
Once the prompt (hbnb) appears, you can enter various commands to interact with the different classes. Use create , show , destroy , all , and update commands followed by the class name and relevant arguments to perform actions on instances of that class.

Examples
create BaseModel
show BaseModel 1234-1234-1234
destroy BaseModel 1234-1234-1234
all BaseModel
update BaseModel 1234-1234-1234 email "aibnb@mail.com"
