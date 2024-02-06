# SA_Assignment04

Goal of this is to practive making libraries, splitting apart existing librries, making a unit test, setting up a fixture, and finally making a mock using GMock.

0) Read this assignment all the way through and make your estimate on amount of work for your over-arching assignment.

1) Refactor the repo https://github.com/olekaspt/LibraryRefactor to go from one mega library, called BlobLibrary into at least three libraries.

Notes:
* Somethings worth pointing out, I didn't put library exports on all classes, as the blob library doesn't need it.  But if we break this up, we may need to add them (you have been warned).
* At the end of the assignment BlobLibrary shoudl be deleted as it won't be needed.
* All library exports should go into their own seperate header file (see BlobExports.h) and should be named appropiately.
* I'd highly suggest starting by splitting one library out one at a time, starting at the top UI, or bottom (core\system)
* MyApplication1 and MyApplication2 do entirely different things with different classes and functionality.
* Business Intelligence is a utilty home grown, and uses some classes needed in Core.

The library structure starts off as :
![Before](https://github.com/olekaspt/SA_Assignment04/blob/main/Before.png)

The library structure ends off as :
![After](https://github.com/olekaspt/SA_Assignment04/blob/main/After.png)

Delivarble 
* You should make at least three libraries at a minimum. (core\system, application, and User Interface).  But that said feel free to make more.
* In addition, I want you to make a UnitTest library as well.  I want you to test the combineString method I made.  I want three tests that will test all three code blocks.  I also want you to use a test fixture for the two strings to pass in (this is not the greatest use).  But in the Setup assign the values to these static values.  And in the TearDown set the values to the empty.  (see https://learn.microsoft.com/en-us/visualstudio/test/microsoft-visualstudio-testtools-cppunittestframework-api-reference?view=vs-2022#Initialize_and_cleanup)


(REPORT) Describe your new library structure and graph it.  (hint you can make a graph using VS as I showed during class).  Defend your opinion on breakup.


2) Make a copy of repo https://github.com/olekaspt/GmockExamples

Add in your "real" world System Under Test (SUT) class, as well Collaborator class.  Implement a method on the SUT class that will utlize the collbaborator class.

Now using the GMOCK, properly mock out the collbaborator.  And then write two UnitTests to test the SUT method.

(REPORT) Describe your SUT class, collaborator class, and SUT test method.   What is the value of using mock for unit testing?

3) Evaluate how much time you spent vs your estimate.

(REPORT) Perform  Evaluation of team members
Participation rubric of teammates.  List out for your all team members how much they participated.  This will go into your Lab report.
```
	             Member1	Member2	
Member1 (opinion)	55	     45
Member2 (opinion)	50	     50
```

  Discuss how much time spent vs the estimate.  And if the estimate was missed, reasons why it was missed.

## Rubric
* 20% readability and format, and you estimate and analysis of your how you did on your work.
* 60% GMOCK example and LIbrary break up code.
* 20% Report.  Items prefaced with (REPORT) are items that should be in PDF report as well as peer review.

# Submission
* PDF of Report
* Zip of your code submissions of the library breakup, as well as the GMOCk example.  You can do one or two zips.

