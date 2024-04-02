# SIMPLE_CALCULATOR_WITH_ADVANCE_FEATURES_COD6000
TITLE: CodTech IT Solutions Internship-Task Documentation:Building Simple Calcualtor.

INTRODUCTION:

This documentation provides a detailed explanation of the task assigned during the CodTech IT Solutions internship program.The task involves writing a Java Program to Build Simple calculator .This documentation will cover the implementation details,rationale behind the code structure,and insights into the programming techniques utilized.Additioinally ,it will include information about the intern,B.Chandra,and her assigned ID,COD6000.

INTERN INFORMATION: Name:B.Chandra Intern ID: COD6000

TASK DESCRIPTION: The task assigned to B.Chandra during the CodTech IT Solutions internship program is to Build a Simple Calculator.

IMPLEMENTATION: The implememtation of the task involves utilizing Java programming language to Build a simple calculator .

CODE EXPLANATION:

The given code is an implementation of a simple calculator using Java's AWT (Abstract Window Toolkit) and Swing libraries. Let's go through the code and explain its different parts.

Import Statements

The code begins with import statements that import the necessary classes from the java.awt and javax.swing packages.

Calculator Class

The Calculator class is the main class that implements the ActionListener interface. It contains the main method and other methods required for creating the calculator window and handling user actions.

main Method

The main method is the entry point of the program. It calls the createWindow method to create the calculator window.

createWindow Method

The createWindow method is responsible for creating the calculator window. It creates a JFrame object, sets its title, size, and default close operation. Then, it calls the createUI method to create the user interface components and adds them to the frame. Finally, it sets the frame's visibility to true.

createUI Method

The createUI method is responsible for creating the user interface components of the calculator. It creates a JPanel object and sets its layout to GridBagLayout. It also creates an instance of the Calculator class.

Next, it creates a JTextField object named inputBox and sets its editable property to false. This text field will display the input and output of the calculator.

After that, it creates JButton objects for digits (0-9), operators (+, -, /, *), and other buttons (Clear, Dot, Equals). It adds action listeners to these buttons, which will be handled by the Calculator class.

Then, it sets the constraints for each button using GridBagConstraints and adds them to the panel in a grid-like layout.

Finally, it adds the inputBox and the Equals button to the panel, and adds the panel to the frame's content pane using the BorderLayout.CENTER constraint.

actionPerformed Method

The actionPerformed method is called when a button is clicked. It handles different button actions based on the command associated with the button.

If the Clear button is clicked, it clears the inputBox text.
If the Equals button is clicked, it evaluates the expression in the inputBox using the evaluate method and sets the result in the inputBox.
For other buttons, it appends the button's command to the inputBox text.

evaluate Method

The evaluate method takes an expression as input and evaluates it. It uses a loop to iterate over each character in the expression. It separates the operands and operator based on the presence of digits or specific operators (+, -, /, *). It then performs the corresponding arithmetic operation and returns the result.

RATIONALE:

1.The Calculator class implements the ActionListener interface to handle button clicks.

2.The main method creates the calculator window by calling the createWindow method.

3.The createWindow method sets up the JFrame and calls the createUI method to create the calculator's user interface.

4.The createUI method sets up the JPanel, adds buttons and the input text field, and sets the layout using GridBagLayout.

5.The actionPerformed method is called when a button is clicked. It handles different button actions, such as clearing the input, evaluating the expression, or appending numbers and operators to the input text field.

6.The evaluate method takes an expression as input, parses it, performs the arithmetic operation, and returns the result.

CONCLUSION: In conclusion the task assigned to B.Chandra during CodTech IT solutions internship programming building a simple calculator .The implemented solution successfully accomplishes this task using a 'switch case'.This documentation provides insights ,into the implementation details ,code explanation and rationale behind the chosen approach .B.Chandra with the intern ID:COD6000 has effectively completed this task as part of internship programme.
