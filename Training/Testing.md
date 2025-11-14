unit testing
integration testing
System testing
Regression Testing
User Acceptance Testing


## Unit Testing 
- Unit testing is the process of check units of a program individually at low level
- Performed by the developers themselves
- Early testing 
- Ensures correctness for inputs, edge cases and error corrections 
- Living documentation for how a unit should behave
- Ensures the existing functionalities are not broken 
- Indecisive: does not guarantee future integration flow 

## Integration Testing 
- Each modules or unit is integrated into or combined and tested as a group to ensure, they work together as expected. 
- Interface defects and data flow issues
- after unit testing before system testing 
- Approaches
	- Big Bang: All units integrated as a whole
	- Top-Down: Start from high level modules to low modules
	- Bottom-up: Testing begins from the lowest-level modules and integrates upwards 
	- Sandwich Approach: Combines both topdown and bottomup
	- Incremental approach: Modules are integrated one by one and tested in a chunk
## System Testing (Black box testing)
- Performed after Integration testing
- System testing is a level of software testing where the complete and fully integrated software is tested
- Both Functional and Non-Functional requirements are tested
- Before UAT
- The purpose is to test the end to end system specification

Alpha: Developers
Beta: Peer
Acceptance: Client or users

## User Acceptance Testing
- Final phase of testing software where the end users test the software for thier business requirement
- To ensure the software is ready for real-use and delivers expected values
- Verify the software serves the business values
- confidence for go-live
- catch the gaps between requirements and delivery before release
- Ensure usability 
- Alpha testing:  
- Beta testing: 



# Test Case
-  A set of steps to verify the functionality of the application, written by test engineers
- A detailed set of actions to perform for the confirmation of a function in the software.
- input and outcomes 
- Content 
	- Title
	- Description 
	- Prerequisites 
	- Test data
	- Test steps 
	- Expected outcome
Importance 
- traceability 
- re-usability of test
- Gap in tests (coverage)
- 

# Test Scenarios 
Test scenarios are high level documentation of functionality or situation of a software that needs to be tested.
Test scenarios focus on each functionalities and aim to validate that every part of software meets the business requirements
used in both manual and automated testing 

How to write Test Scenarios ?
1. understand requirements and priority
2. Identify key features, negative, positive and edge cases 
3. User centric scenarios 
4. define pre and post conditions and test data
5. Concise Steps for each scenarios 
6. review and validate scenarios with stakeholders 
7. coverage, clarity, traceability, completeness

Test scenarios vs Test Case
Test scenarios > Test case
Test scenarios is a broader and describes a situation or function to validate 

**Scenarios are  what to test**
**Case are how to test**

#### Test Conditions 
Perspectives or states a software must go through. Base for test conditions.

# Act - > Arrange -> Assert

