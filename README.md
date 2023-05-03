Download Link: https://assignmentchef.com/product/solved-cs1301-lab-01-creating-compiling-and-executing-java-programs
<br>
The purpose of this lab is to introduce you to creating and executing Java programs. The Integrated Development Environment (IDE) <strong><em>Eclipse</em></strong> will be used to create, compile, and execute Java programs. Eclipse offers a graphical interface, syntax checking, and several other useful features that make creating and maintaining large Java applications easier than it otherwise would be.

The lab will also walk you through the process of submitting your completed lab assignment to <strong><em>eLC</em></strong>.

<h1>Lab Objectives</h1>

By the end of the lab, you should:

<ul>

 <li>understand the general steps required to create, compile, and execute Java programs; be able to use an IDE (specifically Eclipse) to create and execute Java programs;</li>

 <li>be able to submit project files to the course <strong><em>eLC</em></strong> website using a Web browser.</li>

</ul>

<h1>Prerequisites</h1>

At this point, you need only understand that a Java program begins life as one or more source code files which are then compiled into class files containing bytecode. The bytecode is then executed by the JVM. Basic computer literacy and familiarity with Microsoft Windows is also needed for the lab. You need to know how to create folders and files in Windows, use a text editor, and upload files using a Web browser.

<strong>Note</strong>: The words “folder” and “directory” will be used interchangeably in this document. Directories (folders) are used to organize information on a computer. Directories may contain files or other directories. They are arranged into tree-like hierarchies, with each drive on the computer (for instance, the <strong>C:</strong> drive) having a root directory that branches into multiple subdirectories.

In the lab, you will create one small Java program. The source file (ending in <strong>.java</strong>) should be submitted to the course eLC site. Detailed instructions on how to do this are included as the second part of this document.

Part I – Using Eclipse to create your first Java program

<ol>

 <li>Before you start becoming familiar with <strong><em>Eclipse</em></strong>, create a folder on the desktop called <strong>CSCI1301</strong>.</li>

 <li>Afterwards, click on the <strong><em>Eclipse</em></strong> icon on the desktop. <strong><em>Eclipse</em></strong> will prompt for the folder (workspace) in which the new project will be saved. Click on the Browse button to locate the folder <strong>CSCI1301</strong> that you just created in step 1. <strong><em>Note:</em></strong> if you use a lab machine, your workspace is at <strong>I:DesktopCSCI1301</strong>, but on another Windows machine outside the lab you may need to use another location like <strong>C:DesktopCSCI1301</strong>.</li>

 <li>After you click <strong><em>OK</em></strong>, you will see the following window or something similar (otherwise click on the <strong><em>Welcome</em></strong> in the <strong><em>Help</em></strong> menu):</li>

</ol>

Click on the Workbench icon to start the <strong><em>Eclipse</em></strong> IDE.

After few seconds, you will see a window like this:

<ol start="4">

 <li>In <strong><em>Eclipse</em></strong>, a project is a collection of one or more Java source code files (.java) saved in the folder <strong><em>src</em></strong> under the project’s folder located in the workspace you specified in step 2.</li>

</ol>

Click on <strong><em>New/Java Project</em></strong> in the <strong><em>File</em></strong> menu or <strong><em>New Java Project</em></strong> button in the main toolbar to create your first project in Eclipse

<ol start="5">

 <li>In the <strong><em>New Java Project</em></strong> window, type <strong>HelloWorld</strong> in the <strong><em>Project name</em></strong> textbox</li>

 <li>Click on the <strong><em>Finish</em></strong> button, and after few seconds <strong><em>Eclipse</em></strong> should have created a new empty Java project. When you instruct Eclipse to create a new project, it creates a folder with the name of your project in the workspace that you specify in step 2.  In this example, <strong><em>Eclipse</em></strong> creates the folder <strong><em>HelloWorld</em></strong> in the folder <strong>CSCI 1301</strong>.  In this folder, <strong><em>Eclipse</em></strong> also creates a folder called <strong><em>src</em></strong> where the Java source files of the project will be saved and another folder <strong><em>bin</em></strong> that will stored the Java byte code (.class files) of your project. Afterwards, you will see a window like this</li>

</ol>




<ol start="7">

 <li>The next step is to create the class <strong><em>HelloWorld</em></strong> within your project. To do so, click on <strong><em>New/Java Class</em></strong> in the <strong><em>File</em></strong> menu or on the <strong><em>New Java Class</em></strong> button in the main toolbar to create the class file.</li>

</ol>

This will open up the <strong><em>New Java Class</em></strong> window. Select HelloWorld/src as the source folder if it is not already specified.  Type HelloWorld in the <strong><em>Name</em></strong> textbox, check the checkbox <strong><em>public static main …</em></strong>

to create the main() method of the class and click <strong><em>Finish</em></strong>:

<strong><em>Eclipse</em></strong> then creates a template of the class HelloWorld and saves its Java source file in the <strong><em>src</em></strong> folder.  Afterwards, <strong><em>Eclipse</em></strong> displays the code of the new class in the editor window under the Helloworld.java tab.  As you can observe, <strong><em>Eclipse</em></strong> had automatically included a template of the main method within the class …

<strong><em>Eclipse’s</em></strong> source editor offers some nice features that help you to enter and read Java source code in an easy manner.  For example, <strong><em>Eclipse</em></strong> displays the source code of the class in the source editor window.

<ul>

 <li>Tabs are used to indent several parts of the program. This makes your code more readable and easier to debug.</li>

 <li>Words in purple are keywords in Java: words that belong to the Java’s vocabulary. We will learn the specific function of these words throughout the course.</li>

 <li>Lines in light blue are comments that provide documentation to your program but are not part of the Java code meaning that comments will not be executed by the Java VM.</li>

 <li>Braces and parentheses come in pairs. If you place the cursor after a brace (and parentheses), Eclipse will enclosed its corresponding partner.  This feature is useful when you need to find unmatched braces or parentheses in your code, which are common source of syntax errors.</li>

</ul>

<ol start="8">

 <li>Within the main method, replace the line:</li>

</ol>

<strong>//// TODO Auto-generated method stub </strong>

by

<strong>System.out.println(“Hello World!”); </strong>

Afterwards, the <strong><em>HelloWorld.java</em></strong> window should look like this:

Notice that the phrase “Hello World!” is in blue, which means it is a String literal.  A String literal in Java is a sequence of characters enclosed between double quotes.  In this example, the String literal is used to display a greeting message to the user.

<ol start="9">

 <li>In the <strong><em>Project</em></strong> menu, check the option <strong><em>Build Automatically</em></strong> if it is not already checked. When this option is checked, <strong><em>Eclipse</em></strong> will run the <strong>javac</strong> compiler against all of the source code you have associated with this project every time you save a source Java file.  If you prefer to compile your project manually, uncheck the <strong><em>Build Automatically</em></strong> option and click on the option <strong><em>Build All</em></strong> in the <strong><em>Project</em></strong> menu to have <strong><em>Eclipse</em></strong> run the <strong><em>javac</em></strong> compiler on all the source files in your project.</li>

</ol>

After the source code has been compiled, <strong><em>Eclipse</em></strong> will report all syntax errors found (if any) by the Java compiler under the item named <strong><em>Errors</em></strong> in the <strong><em>Problems</em></strong> tab in the lower window.  If no syntax errors are reported in the <strong><em>Items </em></strong>tab then your source code has been successfully compiled and the

.class file generated and saved in the folder <strong><em>bin</em></strong>.  Otherwise, click on the <strong>+</strong> button of the item <strong><em>Errors</em></strong> to see the list of syntax errors founds in your Java source file.

<strong><em>Eclipse</em></strong> displays the description, the name of the file and line in the source file where a syntax error was found.  Click on the line in the <strong><em>Errors</em></strong> item that displays the error, and this will take you to the line that contains the error in the editor window.  After you locate the error, you must fix and compile the project again until your project is successfully compiled.  If your source code has no syntax errors, the Java bytecode file HelloWorld.class is generated in the folder <strong><em>bin</em></strong> in the HelloWorld folder.

<ol start="10">

 <li>To run your first Java program, right-click on the default package in the Package Explorer and select <strong><em>Run As &gt; Java Application</em></strong> or on the <strong><em>Run as/Java Application</em></strong> option of the <strong><em>Run</em></strong> The <strong><em>Console</em></strong> view should appear at the bottom and display the message “Hello World!”</li>

 <li>Before you exit <strong><em>Eclipse</em></strong>, click on <strong><em>Close</em></strong> in the file menu to close the project. If <strong><em>Eclipse</em></strong> prompts you to save the modifications, click on <strong><em>Yes</em></strong> if you want to save the last modifications you made.  Finally, click on <strong><em>Exit</em></strong> in the <strong><em>File</em></strong> menu to exit.</li>

</ol>