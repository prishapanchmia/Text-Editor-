# Text-Editor-
Project description: This is a simple text editor application developed in Java. It is created in java for front-end interface. It is used to simply write anything for our day to day use. Its main objective is to reduce the manual work and mistakes that occur in it. This application completely provides a user-friendly interface. Its main objective is to easily provide any support where users can write their notes and save it for further use. It has the variety of features like:

•	New- This feature allows the user to create a completely blank new screen which will contain all the default features.
•	Open-This feature allows users to open files saved at the desired location.
•	Save-This allows users to save a file with the desired name at any particular location.
•	Save As- This function is similar to the save, which allows you to specify the name and location of the file you are saving. This option is chosen when you want to change the name of the file or make a duplicate.
•	Exit- This function allows the user to exit the application.
•	Undo- This allows users to undo any edited text.
•	Redo- This allows the user to redo any reverse the last undo.
•	Word Wrap: ON/OFF - Word wrap is a text editor or word processor feature that breaks lines between words to adjust them within specified margins.
•	Font- This function allows the user to change the font of the text.
•	Font Size- This function allows the user to change the size of the text.
This is text editor program in java using swing and uses simple core java concepts to come up with basic text editor functionalities. It uses the BufferedReader to read the text line by line. We implement the FileReader and FileWriter methods to read files and directories.

Features of java implemented in the project:

-> Packages:
A package in Java is used to group related classes. Think of it as a folder in a file directory. We use packages to avoid name conflicts, and to write a better maintainable code. The Java API is a library of prewritten classes that are free to use, included in the Java Development Environment. The library contains components for managing input, database programming, and much more. The library is divided into packages and classes. Meaning you can either import a single class (along with its methods and attributes), or a whole package that contain all the classes that belong to the specified package.
To use a class or a package from the library, you need to use the import keyword.
Packages used in the project are:
•	java.awt.event.ActionEvent;
•	java.awt.event.ActionListener;
•	javax.swing.JFrame;
•	javax.swing.JMenu;
•	javax.swing.JMenuBar;
•	javax.swing.JMenuItem;
•	javax.swing.JScrollPane;
•	javax.swing.JTextArea;
•	javax.swing.event.UndoableEditEvent;
•	javax.swing.event.UndoableEditListener;
•	javax.swing.undo.UndoManager;


-> Classes
A class can be defined as a template/blueprint that describes the behaviour/state that the object of its type support. A class can contain any of the following variable types.
•	Local variables − Variables defined inside methods, constructors or blocks are called local variables. The variable will be declared and initialized within the method and the variable will be destroyed when the method has completed.
•	Instance variables − Instance variables are variables within a class but outside any method. These variables are initialized when the class is instantiated. Instance variables can be accessed from inside any method, constructor or blocks of that particular class.
•	Class variables − Class variables are variables declared within a class, outside any method, with the static keyword.
A class can have any number of methods to access the value of various kinds of methods.
Classes used in the project are:
•	Class GUI
•	Class FunctionFile
•	Class FunctionEdit
•	Class FunctionFormat

-> Methods
A method is a block of code or collection of statements or a set of code grouped together to perform a certain task or operation. It is used to achieve the reusability of code. We write a method once and use it many times. We do not require to write code again and again. It also provides the easy modification and readability of code, just by adding or removing a chunk of code. The method is executed only when we call or invoke it. The most important method in Java is the main() method. In this project, the main() method is called in the public class GUI.

Methods used in the project are:
In GUI.java
•	createWindow()
•	createTextArea()
•	createMenuBar()
•	createFileMenu()
•	createEditMenu()
•	createFormatMenu()
•	actionPerformed(ActionEvent)

In FunctionFile.java

•	newFile():void
•	open():void
•	save():void
•	saveAs():void
•	exit():void
•	fileDialog()

In FunctionEdit.java

•	undo()
•	redo()

In FunctionFormat.java
•	wordWrap()
•	createFont(int)
•	setFont(String)

-> Constructors
Every class has a constructor. If we do not explicitly write a constructor for a class, the Java compiler builds a default constructor for that class. Each time a new object is created, at least one constructor will be invoked. The main rule of constructors is that they should have the same name as the class. A class can have more than one constructor. It is used to initialize objects.
Constructors used in the project are:
In class GUI – public GUI()
In class FunctionFile – public FunctionFile()
In class FunctionEdit - public FunctionEdit()
In class FunctionFormat – public FunctionFormat()

-> Interface
Class GUI implements ActionListener() which is an interface that contains a method called actionPerformed(ActionEvent e).  The ActionEvent parameter is an Event object that represents an event like a button click. It contains information about the event. 


