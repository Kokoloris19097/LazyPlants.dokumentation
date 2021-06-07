# Software Architecture Document


## 1. Introduction 
### 1.1 Purpose
This document provides a comprehensive architectural overview of the system, 
using a number of different architectural views to depict different aspects of the system. 
It is intended to capture and convey the significant architectural decisions which have been made on the system.

### 1.2 Scope
The scope of this SAD is to show the architecture of the project. Affected are the class structure, the use cases and the data representation.

### 1.3 References
- [GitHub](https://github.com/jdk-21/lazyplants)
- [Blog](https://lazysmartplants.wordpress.com/)
- [WIKI](https://github.com/Kokoloris19097/LazyPlants.dokumentation)
- [Software Requirements Specification](SRS.md)


## 2. Architectural Representation
![MVC](./UC/MVC-Diagram.png)

## 3.Architectural Goals and Constraints 


## 4. Use-Case View 
### Overview
![ucd](https://raw.githubusercontent.com/Kokoloris19097/LazyPlants.dokumentation/master/UC/Use-Case-Diagram.png)

### UC: Add Plant
![Use Case Diagram ADD Plant](./UC/uc-add-plant.png)

### UC: Water Plant
![Use Case Diagram Water Plant](./UC/uc-water-plants.png)

### UC: Measure
![UC Measure](./UC/uc3-measure.png)

### UC: Sync Settings and Data
![UC Sync Settings](./UC/uc-sync-settings.png)
![UC Sync Settings alternative flow](./UC/uc-sync-settings-alternative.png)

### UC: Monitoring
![UC monitoring](./UC/uc-monitoring.png)

### UC: Live Dashboard
![UC live dashboard](./UC/uc-live-dashboard.png)

## 5. Logical View
![MVC-UML](https://raw.githubusercontent.com/Kokoloris19097/LazyPlants.dokumentation/master/UML/out/class_diagram_20201208.png)


## 6. Process View


## 7. Deployment View



## 8. Implementation View
![UML](./UC/classdiagramm.png)

## 9. Data View
![Database Design](./UC/databasediagramm.png)

## 10. Size and Performance


## 11. Quality
For this project we are using the MVC pattern. It helps us to maintain a stable codebase. Additionaly we are using Continous Integration for testing. Every pull request gets peer reviewed to ensure the best code quality possible. 
We also use metrics (dart_metrics) to get a better understanding of our code complexity etc.
