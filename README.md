# Examine input output in the Linux shell

<h2>Activity overview</h2>

Previously, you discussed how the Bash shell helps you communicate with a computer’s operating system.

When you communicate with the shell, the commands in the shell can take input and return output or error messages.

In this lab activity, you’ll use the echo command to examine how input is received and how output is returned in the shell. Next, you’ll use the expr command to further explore input and output while performing some basic calculations in the shell.

This activity will build foundations in understanding how you communicate with the Linux operating system through the shell. As a security analyst, you'll need to input commands into the shell and recognize when the shell returns either output or an error message.

<h2>Scenario</h2>

As a security professional, it’s important to understand the concept of communicating with your computer via the shell.

In this scenario, you have to input a specified string of text that you want the shell to return as output. You'll also need to input a few mathematical calculations so the OS (operating system) can return the result.

Here’s how you’ll do this: First, you’ll use the echo command to generate some output in the shell. Second, you’ll use the expr command to perform basic mathematical calculations. Next, you’ll use the clear command to clear the Bash shell window. Finally, you’ll have an opportunity to explore the echo and expr commands further.

<h2>Task 1. Generate output with the echo command</h2>

The echo command in the Bash shell outputs a specified string of text. In this task, you’ll use the echo command to generate output in the Bash shell.

1. Type echo hello into the shell and press ENTER.

![image](https://github.com/user-attachments/assets/c4fe93d8-8248-4cb5-87e1-0f32e753bca0)

The hello string should be returned:
The command echo hello is the input to the shell, and hello is the output from the shell.

2. Rerun the command, but include quotation marks around the string data. Type echo "hello" into the shell and press ENTER.

![image](https://github.com/user-attachments/assets/30b85a18-d7f9-4627-a74e-168e4175700e)

The hello string should be returned again:

3. Use the echo command to output your name to the shell.
Type echo "name" into the shell, replacing "name" with your own name, and press ENTER.

![image](https://github.com/user-attachments/assets/f7148495-fb61-4324-967b-b945748b7aad)

The name you’ve entered as the string should return as the output.

<h2>Task 2. Generate output with the expr command</h2>
In this task, you’ll use the expr command to generate some additional output in the Bash shell. The expr command performs basic mathematical calculations and can be useful when you need to quickly perform a calculation.

Imagine that the system has shown you that you have 32 alerts, but only 8 required action. You want to calculate how many alerts are false positives so that you can provide feedback to the team that configures the alerts.

To do this, you need to subtract the number of alerts that required action from the total number of alerts.

1. Calculate the number of false positives using the expr command.

![image](https://github.com/user-attachments/assets/2f3c6527-b700-4051-af10-b0320ab690d3)

2. Now, you need to calculate the average number of login attempts that are expected over the course of a year. From the information you have, you know that an average of 3500 login attempts have been made each month so far this year.

So, you should be able to calculate the total number of logins expected in a year by multiplying 3500 by 12.

![image](https://github.com/user-attachments/assets/7afcd73b-7421-4913-b7dd-9d20f0681886)

<h2>Task 3. Clear the Bash shell</h2>

In this task, you’ll use the clear command to clear the Bash shell of all existing output. This allows you to start with the cursor at the top of the Bash shell window.

When you work in a shell environment, the screen can fill with previous input and output data. This can make it difficult to process what you’re working on. Clearing the screen allows you to create a clutter-free text environment to allow you to focus on what is important at that point in time.

 - Type clear into the shell and press ENTER

![image](https://github.com/user-attachments/assets/0f552188-3086-4115-a961-1057e9cb9c66)
