# Instructions on the LSM-LSDA course assignments 

For the course assignments, we will try (!) to use GitHub classroom and Google Colab. 
As this assignment flow is experimental, please be patient with us and expect some things to be still suboptimal!
Your constant feedback during the course will be very important for us to understand how our strategy can be improved.

### Requirements:
You will need:
1. A GitHub profile linked to the [classroom](https://classroom.github.com/classrooms/82461945-mscne-lsmlsda-test-classroom)
2. A Google account
3. (only for future assignments): access to the shared data folder on Google Drive


## 1. Accepting an assignment
The assignment will be created through GitHub classroom. When you accept the assignment, a new private repository under your name will be created. 
Only you and the TAs will have access to the repository! You will see the complete link to the repository refreshing the page after it gets created.
It is easy to obtain the link again, but just copy it now - you'll need it soon!

---
**NOTE:** If you are not familiar with the basic ideas behind creating GitHub repositories and commit code to it, we recommend some tutorials at the end of this page.

---
**NOTE:** You won't need git operations for completing the assignments; it is just better if you know a bit what is happening behind the scenes. 

## 2. Open the assignment in Google Colab
The assignments will be in the form of python notebooks with some preliminary info and instructions.
You recommend working on them using Google Colab. Google Colab is a very convenient tool to run IPython notebooks using a remote python kernel, 
executing remotely the code that you write in your browser. Using Google Colab we can be sure that everyone has a standard working Python environment,
without package version issues and operative system related idiosyncrasies. 
Moreover, Google Colab can be integrated with GitHub, making the submission of solutions very easy without any knowledge of git syntax. 

To open the assignment in Google Colab:
1. Go to the [Google Colab](https://colab.research.google.com) website
2. Sign in with your Google account
3. In the opening panel, go to the GitHub tab
4. Enable the "Include private repos" option; you will be redirected to a GitHub authentication page
5. Login with your GitHub credentials (this could happen automatically if they were saved in the browser)
6. Copypaste the link to the assignment repo (t might take a second or two for the interface to load the repos)
7. You will now see all the notebooks of the assignment folder listed below; just click one to open it and run it in Google Colab! (you might be asked for an additional authentication step at this point). If you get a warning about the code not coming from a Google source, just ignore it.

---
**NOTE:** using Google Colab is not mandatory! If you have a working Python on your machine,
and you know your git syntax, you can just clone the assignment, work on it locally and commit your solutions. If decide to you go for this option
make sure you know how to fix potential python installation/packages conflicts!

## 3. Submit assignment solutions
Exercises can be open questions about data or code interpretations, or code to be written.
The coding assignments will ask you to implement functions that calculate some quantities given some inputs.
Answers to the questions and code of the functions that is part of your answer submission will have to be copy-pasted into a `submission.ipynb` file
that you will find in all the assignments.
We (teacher and TAs) will manually evaluate all your final submitted solutions. However, we will also try to write tests for your code submission;
in this way, every time you submit a solution you can already know if the code of your submission is functional, and you get immediate feedback even 
without intervention from the instructors! Obviously, this does not mean that you can't come back to us with questions if you are running into errors you don't understand, we are always here to help.

To submit your solution:
1. Tinker with code as much as you like in the assignment notebook, until you find a solution that convinces you. 
2. To save your changes to the notebook, you can go to _File/Save a copy in GitHub_. A window will open that allow you to create a new commit on GitHub with the current version of the notebook. If you want, you can add a commit message (`draft first solution`, `testing new strategy`, etc.); otherwise, just leave the default and say OK. Next time you open the notebook, you will see the latest version you saved, but don't worry - you can always go back to past commits if you need to.
3. Copypaste your solution code in the `submission.ipynb` file. 
4. To save your solution, just  follow instructions of point 2 for the `submission.ipynb` notebook. 
5. To check if tests were running correctly, you can go to your assignment repository, and check the "Actions" tab. There, you will find the results of testing of all of your commits, with a green ticks for tests that were passed and a red cross for failing tests. If you want to know what happened during a failed test, you can click on it, and open the "Run education/autograding@v1" step. You will see error messages pointing you to errors in your function execution.
6. Once you have a final submission, save it a last time writing in the commit message `final submission`.

---
**NOTE:** Some tests will always be failing until you submit all the solutions

---
**NOTE:** For making sure that the tests run, always check the following:
- Make sure you name your functions following the assignment instructions
- Import all the modules that your function needs also in the `submission.ipynb` file
- Make sure that all your function variables are defined in the `submission.ipynb` notebook
- don't leave in the `submission.ipynb` file any code that is not part of the solution functions

---
**NOTE:** The code that will run the tests is accessible in the submission_test.py file, that you can open in GitHub or in your local version. Please, don't edit this file - we'll see it! :)
