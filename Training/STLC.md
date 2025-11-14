Fits within SDLC
A process through which the software is tested 
## STEPS

1) Requirement Analysis
	Understand the user requirements and prepare documents 
2) Test Planning 
	Once the requirements is understood the testers will write the test plans 
	for each sprints write a small test plan
3) Test case design and development 
	Design and develop the test cases to test the software
4) Environment Setup
	Maybe done by another team to setup test environment 
5) Test Execution and monitoring 
	Perform the actual tests

6) Test Reporting
	Defects will be reported to developers 
* Defect Management 
* Process audit and reviews
6) Test closure
	Closure documentation, details about development document, artefacts

## Test Case Design Technique

## 1) Error Guessing 
- No rules, analytical thinking of testers 
- guess the error
- decimal in number fields
## 2) Equivalence Partitioning 
- Divide the class test into sections so that we are sure it works for that section
- for example for a field of 1-500 number possible 
- break down test for 1-100, 101-200, 201 - 300 ...
- this way we can choose any random number from each section to ensure that section works
## 3) Boundary Value analysis
- chose the values adjacent to the min and max values
- for 50 - 100 choose 49,50,51,99,100,101
## 4) Decision Table Technique
- When the application works on if else or decision tree 
- number of test cases = 2^n 
- n = number of decision rules

## 5) State Transition Technique
- States and transitions are defined 
- Testers need to test at each state for each transition 


# Functional Testing 
- Functional testing is a method of software testing that focuses on the functionality of an application or system
- Can be performed at various stages
- Based on functionalities of the requirements
- Defects error and other issues
- Look and feel

## Non Functional Testing 
- How good the application is 
- how well the system works 
- reliability, efficiency, maintainability, usability etc.
Types 
- performance (Validate response time)
- load testing (how much load it can handle at a time)
- Stress (High insertion and noting down when the system breaks)
- Usability  (look feel, navigation)
- Maintainability 
- Portability 
- Volume (Huge amount of data)
- Configuration (deployment to  different systems and dependencies )
- Compatibility testing (Different browsers, OS, Screen sizes)
- Security (check for vulnerability and protection of data)

