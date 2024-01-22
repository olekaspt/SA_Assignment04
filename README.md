# SA_Assignment04


0) Read this assignment all the way through and make your estimate on amount of work for your over-arching assignment.

1) Refactor the repo https://github.com/olekaspt/LibraryRefactor to go from one mega library, called BlobLibrary into several libraries.

* Somethings worth pointing out, I didn't put library exports on all classes, as the blob library doesn't need it.  But if we break this up, we may need to add them (you have been warned).

*  All library exports shoudl go into their own seperate header file (see BlobExports.h) and shoudl be named appropiately.

*  MyApplication1 and MyApplication2 do entirely different things with different classes and functionality.

* Business Intelligence is a utilty home grown, and uses some classes needed in Core.


(REPORT) Describe your new library structure?  (hint you can make a graph using VS as I showed during class).  Defend your opinion on breakup.


2) Make a copy of repo https://github.com/olekaspt/GmockExamples

Add in your "real" world System Under Test (SUT) class, as well Collaborator class.  Implement a method on the SUT class that will utlize the collbaborator class.

Now using the GMOCK, properly mock out the collbaborator.  And then write two UnitTests to test the SUT method.

(REPORT) Describe your SUT class, collaborator class, and SUT class method.   What is the value of using mock for unit testing?



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

