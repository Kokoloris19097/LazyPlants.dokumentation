# Test plan

## 1.	Introduction
### 1.1	Purpose
The purpose of the Iteration Test Plan is to gather all of the information necessary to plan and control the test effort for a given iteration. 
It describes the approach to testing the software.
This Test Plan for vnv supports the following objectives:
-	Identifies the items that should be targeted by the tests.
-	Identifies the motivation for and ideas behind the test areas to be covered.
-	Outlines the testing approach that will be used.
-	Identifies the required resources and provides an estimate of the test efforts.

### 1.2	Scope
This document describes the used tests.

### 1.3	Intended Audience
This document is meant for internal use primarily.

### 1.4	Document Terminology and Acronyms
- **SRS**	Software Requirements Specification
- **n/a**	not applicable
- **tbd**	to be determined

### 1.5	 References
| Reference        | 
| ------------- |
| [Blog](https://lazysmartplants.wordpress.com/) | 
| [SRS](https://github.com/Kokoloris19097/LazyPlants.dokumentation/blob/master/SRS.md) |
| [SAD](https://github.com/Kokoloris19097/LazyPlants.dokumentation/blob/master/SAD.md) |
| [UC1 Add Plant](https://github.com/Kokoloris19097/LazyPlants.dokumentation/blob/master/UC/uc-add-plant.md) |
| [UC2 Water Plant](https://github.com/Kokoloris19097/LazyPlants.dokumentation/blob/master/UC/uc-water-plants.md) |
| [UC3 Sync Settings and Data](https://github.com/Kokoloris19097/LazyPlants.dokumentation/blob/master/UC/uc-sync-settings.md) |

## 2.	Evaluation Mission and Test Motivation
### 2.1	Background
By testing our project, we make sure that all changes to the sourcecode do not break the functionality. Also by integrating the test process in our deployment process, we make sure that only working versions of our project getting deployed.
### 2.2	Evaluation Mission
n/a
### 2.3	Test Motivators
Our testing is motivated by 
- quality risks 
- technical risks 
- use cases 
- functional requirements

## 3.	Target Test Items
n/a

## 4.	Outline of Planned Tests
n/a
### 4.1	Outline of Test Inclusions
n/a
### 4.2	Outline of Other Candidates for Potential Inclusion
n/a
### 4.3 Outline of Test Exclusions
n/a

## 5.	Test Approach
### 5.1 Initital Test-Idea Catalogs and Other Reference Sources
**n/a**
#### 5.1.2	Unit Testing

|||
|Technique Objective|Every service request shall be done correctly. Possible exceptions are caught correctly.|
|Technique|Unit testing the widgets|
|Oracles|user enter valid data, for example a valid username and a valid password|
|Required Tools|Flutter test|
|Success Criteria|successful scenarios, all tests will pass, no strange behaviour will occur|
|Special Consideration|-|

### 5.2	Testing Techniques and Types
#### 5.2.1	Database Integrity Testing
n/a
#### 5.2.2 Function Testing

#### 5.2.3 Business Cycle Testing
**n/a**

#### 5.2.4 User Interface Testing
**n/a**

#### 5.2.5 Performance Profiling 
**n/a**

#### 5.2.6 Load Testing
**n/a**

#### 5.2.7 Stress Testing
**n/a**

#### 5.2.8	Volume Testing
**n/a**

#### 5.2.9	Security and Access Control Testing
**n/a**

#### 5.2.10	Failover and Recovery Testing
**n/a**

#### 5.2.11	Configuration Testing
**n/a**

#### 5.2.12	Installation Testing
**n/a**

#### 5.2.13	Field Testing


## 6.	Entry and Exit Criteria
### 6.1	Test Plan
#### 6.1.1	Test Plan Entry Criteria
Building a new version of the software with Gitlab-CI will execute the testprocess.
#### 6.1.2	Test Plan Exit Criteria
When all tests pass without throwing an exception.
#### 6.1.3 Suspension and Resumption Criteria
It will be possible to skip the tests for faster deployment during development.
Apart from that the tests will always run till the end.

## 7.	Deliverables
### 7.1	Test Evaluation Summaries

### 7.2	Reporting on Test Coverage
 
### 7.3	Perceived Quality Reports

### 7.4	Incident Logs and Change Requests

### 7.5	Smoke Test Suite and Supporting Test Scripts

### 7.6	Additional Work Products
#### 7.6.1	Detailed Test Results

#### 7.6.2	Additional Automated Functional Test Scripts
**n/a**
#### 7.6.3	Test Guidelines
In general all testable code should be tested. Due to time constraint this is of course not always possible. Therefore we set a bound of 20% for coverage
#### 7.6.4	Traceability Matrices
**n/a**

## 8.	Testing Workflow

## 9.	Environmental Needs
This section presents the non-human resources required for the Test Plan.
### 9.1	Base System Hardware

### 9.2	Base Software Elements in the Test Environment

### 9.3	Productivity and Support Tools

### 9.4	Test Environment Configurations

## 10.	Responsibilities, Staffing, and Training Needs
### 10.1	People and Roles
This table shows the staffing assumptions for the test effort.

Human Resources


| Role | Minimum Resources Recommended (number of full-time roles allocated) |	Specific Responsibilities or Comments |
|---|---|---|
| Test Manager | 1 | Provides management oversight. <br> Responsibilities include: <br> planning and logistics <br> agree mission <br> identify motivators<br> acquire appropriate resources<br> present management reporting<br> advocate the interests of test<br>evaluate effectiveness of test effort |
| Test Designer | 1 | Defines the technical approach to the implementation of the test effort. <br> Responsibilities include:<br> define test approach<br> define test automation architecture<br> verify test techniques<br> define testability elements<br> structure test implementation|
| Tester | 1 |	Implements and executes the tests.<br> Responsibilities include:<br> implement tests and test suites<br> execute test suites<br> log results<br> analyze and recover from test failures<br> document incidents|
| Test System Administrator | 1 | Ensures test environment and assets are managed and maintained.<br> Responsibilities include:<br> 	administer test management system<br> install and support access to, and recovery of, test environment configurations and test labs | 
| Database Administrator, Database Manager | 1 | Ensures test data (database) environment and assets are managed and maintained.<br> Responsibilities include:<br> support the administration of test data and test beds (database). |
| Implementer | 3 | Implements and unit tests the test classes and test packages.<br> Responsibilities include:<br> creates the test components required to support testability requirements as defined by the designer |

### 10.2	Staffing and Training Needs
**n/a**
## 11.	Iteration Milestones

| Milestone | Planned Start Date | Actual Start Date | Planned End Date | Actual End Date |
|---|---|---|---|---|
| Have Unit Tests |  |    |    |    |
| 20% coverage |  |    |    |    |
| Tests integrated in CI |  |  |  |  |


## 12.	Risks, Dependencies, Assumptions, and Constraints
| Risk | Mitigation Strategy	| Contingency (Risk is realized) |
|---|---|---|
| Untestable features in <br/>the framework | Cannot be avoided | Try to test it with integration tests |
| Testing scenario is not <br/>covered | Carefully design tests | Add scenario | 
| Technical Difficulties for Testers | Try to help remote | Try it out on different browsers before and check the availability on multiple systems | 
## 13. Management Process and Procedures
**n/a**
