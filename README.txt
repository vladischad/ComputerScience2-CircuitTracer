****************
* Project CircuitTracer
* Class CS 221: Computer Science II
* Date 4/24/2023
* Your name Vlad Maliutin
**************** 

OVERVIEW:

CircuitTracerTester.java class is meant to check correctness of CircuitBoard.java and CircuitTracer.java.
Those classes contain code necessary for creating board and path from 1st component to 2nd on it.
CircuitTracerTester is supposed to compare results from manual results for different tests (in it) and returns from functions in given classes.
Then it gives result with total tests run plus passed and failed tests.


INCLUDED FILES:

 * Storage.java - a completed class that can be implemented using either a stack or a queue.
 * CircuitBoard.java - a partially-completed class that represents a circuit board.
 * TraceState.java - a completed class that represents a search state with the trace path.
 * InvalidFileFormatException.java, and OccupiedPositionException.java - exceptions used by other classes in this project
 * CircuitTracer.java - a partially-completed driver class.
 * CircuitTracerTester.java - tester.



COMPILING AND RUNNING:

 From the directory containing all source files, compile t
 $ javac *.java

 Run the compiled class file with the command:
 $ java CircuitTracerTester

 Console output will give the results (description of each test seperately, total tests run plus passed and failed tests) after the program finishes.


PROGRAM DESIGN AND IMPORTANT CONCEPTS:

 Process of creating this program was prety straigh forward.
 It was just mostly following instruction and doing some logic.
 I used some parts of code from my previous project from last semester.
 Of course I had to adapt them for my specific purposes and details of new code.
 I also used techinqe when I devide my code in parts so it looks organized and it is easy to navigate it.
 It is important since it helps to find mistakes in code really fast if there are any.
 Plus I used comments in my code for easier navigation.
 The most important part of code is probably logical part where I had to pay a lot of attention to details so I accidentaly don't make any mistake.
 Code had a lot of different methods which made it easy to organize and seperate pars of code.
 I had to think about every possible situation for methods in program so it doesn't throw any unpredicted exeption (I tried to avoid it as much as possible).
 Honestly I wish I had more time to work on this project to maximise its efficiency.

TESTING:

 CircuitTracerTester.java was the primary mechanism for testing. 

 CircuitTracerTester.java was also helpful for debugging.
 I used it to develope a logic for my code and find mistakes in it.

 Righ now my code passes most of the tests (but far from all).


DISCUSSION:
 
 I spent a lot of time trying to predict all exeptions to avoid them.
 It took a lot of time not because it was very complicated but because there are a lot of parts in this project (code) and it was not easy to move between them 
 and make sure the work right.
 And it was also important not to rush there because it would be realy hard to find even the smallest mistake in all of those conditions.
 
 
EXTRA CREDIT:

 I didn't have enough time to work on extra credit part of this project creating GUI, but I will try to attempt it this summer.


----------------------------------------------------------------------------