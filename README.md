
# E02a-Control-Structures

Let's start experimenting with some Python code! This is a set of exercises for MSCH-C220; they should give you the tools to help build your first game.
 
This exercise assumes that you have already installed Python, GitHub Desktop, and VS Code, and that you have already created a GitHub account. If that is not the case, please refer to previous exercises.

This repository contains several files that you will need to alter to complete the assignment. Fork this repository (instructions below) and edit the files. Commit and push the changes back to GitHub and turn in the URL to your repository on Canvas.

Comments in Python are marked by a # sign (for single-line comments) or three matching quotation marks (''' or """) if a comment requires more than one line. They should also appear in a different color in VS Code. The Python Interpreter ignores comments, so you can safely include any information you want there.

*If you wish your exercise to be graded, please edit the LICENSE file (add the current year and your name).*

Edit README.md to answer the following questions:

- Open main01.py. Before running it, what do you expect this program to do?
I expect for the program to ask me what its favorite color is. 
  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened.
  The program greeted me and asked me what its favorite color is. When I put an input in, the game ended because the program did not have nay instructions to follow once I had answered its initial question.
  - What do you think the program did with what you typed in answer to the question?
  The program did nothing with my answer because it was not instructed on what to do with any type of input. 
- Open main02.py. Before running it, describe how this is different than main01.py.
main01.py. is different from the first version because after the asking what its favorite color is and after I have answerd its question, the program has been instructed on printing the answer that I have provided it.
  - What do you think the color = input() will do?
  It will acknoledge that the color I have types in as an input to the question.
  - Run the program in the terminal and answer the question. Did the program do what you expected?
  Yes it did
- Open main03.py. Before running it, describe how this is different than main02.py.
This version of the program has an answer inscribed in it. When the answer of the user matches the answer of the program, it will say correct. If not the it will say " Sorry try again".
  - What is happening on lines 9–12?
  In lines 9-12 the program is proccessing the input the user has provided it with. If the answers match it will follow the protocol in its code where the answers are the same and vise versa
  - Why are lines 10 and 12 indented?
  Lines 10 and 12 are indented because they are the specific instructions for the program to follow if the scenarios of whether the answer is right or wrong. 
  - Run the program and answer the question. What happens if you don’t capitalize Red?
  If Red is not capitalize it will read it as the wrong answer.
  - What does this tell you about "color"?
  "color" is case sensitive.
- Open main04.py. Before running it, describe how this is different than main03.py.
Version 4 gives more leway in its answer choices as here the answer is accepted whether it is spelled as "Red" or "red".
  - What problem is this trying to solve?
  This is trying to tsolve the problem that some people might not capitalize the colors names while other do.
  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)?
  It does not accept them as correct answers.
- Open main05.py. What do you expect line 9 to do?
  - What problem is it trying to solve?
  Line 9 will process the answer and covert it to lowecase if not already. It is also trying to solve the problem that some people capitalize colors while other do not. This way all answers processed by the progam wil be in lowecase.
  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)?
  It does not accept it as an answer.
 - Open main06.py. How is line 9 different than in main05.py?
   - What would you guess .strip() is doing?
   It is different because this line 9 has stript built into it which removes any leading or trailing spaces.
   - Run the program and answer the question. Is there another way of writing “red” that will break this logic?
   Yes if you put any sort of punctuation.
 - Open main07.py. Before running this program, how do you expect this to be different than main06.py?
 In this program if you guess a color close to the answer it will give you feedback if it is close. Here if you answer Pink instead of red you will get a feedback saying close. 
   - What is happening on line 12?
   In line 12 the program acknoledges that the color Pink is close to the color Red. Therefor instead of saying wrong, it will say that you are close to the correct answer. 
   - Run the program and answer the question.
   Done.
 - Open main08.py. What is the purpose of line 9?
   Line 9 creates a loop in the program.
   - Why are lines 10–17 indented?
   They are all different outcomes that have an effect of the loop. Loop is broken if line 12 happens. Loop continues if line16 happens.
   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)?
   I got an infinite loop of sorry try again.
   - Make that change and run the program again. (To end any Python program, you can type ctrl-c)
   Done.
 - Open main09.py. What is happening on line 13?
 Line 13 will add one guess to your total number of guesses.
   - What is the purpose of “count”?
   Count is the count of how mny times a given object has occured in the program
   - What is happening on line 22?
   I did not see a line 22 in main09.py.
   - Run the program.
 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).
 - *Extra credit:* open main11.py. What is happening on lines 6-11?
  
Commit your changes and push them back to the repository.
 

---

Instructions for forking this repository:
 
Log into your account on [github.com](https://github.com)

Go to the [exercise template page](https://github.com/BL-MSCH-C220-S20/E02a-Control-Structures) on GitHub

There is a button in the top right corner of the page labeled "Fork". Press that now

This will create an independent copy of this repository in your account that you can control and edit

Go to your GitHub home page, and select the new E02a-Control-Structures repository

On that page, you will see a green button labeled "Clone or download". Press that now. You will see a drop down box. Press the "Open in Desktop" button.

This should launch GitHub Desktop. It will ask you for a location (on your computer) where the repository may be cloned (downloaded). Choose a location that will be easy for you to find, and press the blue "Clone" button.

Once GitHub Desktop has cloned (downloaded) the code, it will be responsible for keeping the code on your local computer synchronized with the repository in your GitHub account. Now, open Visual Studio Code, and choose File->Open. Find the folder of the cloned repository and select Open.

In the left (File Explorer) panel, you should see a list of files that comprise this repository

First, edit the file called LICENSE. Replace year and name with the current year and your name. Save this file

Then open README.md. Feel free to remove any extraneous information, and then answer the questions posed in the file. You can add your answers after each question

When the time comes for you to run any of the python files, you can do so by clicking the green arrow in the top right corner of the window or by right-clicking on the code and selecting "Run Python File in Terminal". The results will appear at the bottom. If you don't see "Run Python File in Terminal" in the contextual menu, that is because VS Code doesn't have the Python extension installed. You can do that here: [https://marketplace.visualstudio.com/items?itemName=ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

When you are done editing the files, return to GitHub Desktop. In the left panel, you should see a list of the files that have changed

At the bottom of the leftmost area, you should see a text box labeled "Summary (required)". Add a message that describes what you have done; these messages are typically stated in the active-present tense. For example, "Updates the LICENSE, README.md, and completes the assignment." Push the blue "Commit to master" button

In the top bar of the window, you should see a button that is labeled "Push origin", push that now

Check out your page on GitHub. You should see the changes you made reflected there, Repeat steps 10 through 16 as necessary

When you are satisfied with your efforts, turn in a URL to your repository on Canvas

---
If you try to push your changes, and you receive a permission error, it is likely that you are trying to edit the BL-MSCH-C220-S20 copy of the repository rather than your own. Make sure you don't skip the step of forking your own copy and cloning that.

---

The grading criteria will be as follows:
 
[1 point] Repository contains a description of the project in README.md

1 point will be awarded for answering the questions associated with each of the files

10 points total (+2 points extra credit)
