# Campus Course Records Manager

## Made by

Name : Chhavi Mangalwaniya
Course : Programming in Java  
Course Code: CSE2006  
Institution: VIT Bhopal University  
Submission Platform: Vityarthi  

## About This Project

This Java project manages campus courses and student records. It demonstrates concepts of object-oriented programming, exception handling, and file operations. The project is part of the Programming in Java course at VIT Bhopal, submitted through the Vityarthi platform.

## How to Setup and Run

### Requirements
- Java JDK 21 or later
- Terminal or Command Prompt

### Steps to Run:
1. Download/extract the project files.
2. Open Terminal.
3. Navigate to the project source folder:
```cd ~/Desktop/CampusCourseRecordsManager/src```
4. Compile the main application:
```javac -d ../out edu/ccrm/cli/CCRMApplication.java```
5. Run the program:
```cd ../out```
```java edu.ccrm.cli.CCRMApplication```

## Features Implemented

### Student Management
- Add, update, list, deactivate, and view student profiles

### Course Management
- Add, update, list, deactivate, and search courses

### Enrollment & Grading
- Enroll and unenroll students from courses
- Record grades

### Reports
- Top students by GPA
- GPA distribution
- Course and Student statistics

### Backup and File Operations
- Create backups and view backup directory size
- Export data and list backup files

### Search Operations
- Search students by status or GPA range
- Search courses by credits

## Evolution of java

•⁠  ⁠1995: Java 1.0 released by Sun Microsystems

•⁠  ⁠2004: J2SE 5.0 introduced generics, autoboxing, enums

•⁠  ⁠2014: Java SE 8 introduced Lambdas and Stream API

•⁠  ⁠2018: Java SE 11 (LTS) with modularization

•⁠  ⁠2021: Java SE 17 (LTS) with sealed classes

•⁠  ⁠2023: Java SE 21 (LTS) with virtual threads

•⁠  ⁠Java Platforms Comparison


## Java Platforms Comparison

| Aspect | Java ME | Java SE | Java EE |
|--------|---------|---------|---------|
| Purpose | Mobile & Embedded | Desktop & Server | Enterprise |
| Scope | Limited API | Full Core API | Enterprise Extensions |
| Target | IoT devices | Applications | Web Services |
| This Project | ❌ | ✅  | ❌ |

## JDK/JRE/JVM Explanation

### JDK (Java Development Kit)
It is a complete development package for Java programmers.
It contains compiler (javac) to convert Java code to bytecode.
It contains Tools (java, jar, javadoc) for development.
It contains Libraries and development files.
It is used for development Java applications.


### JRE (Java Runtime Environment)
It is an environment to run Java applications.
It contains JVM (Java Virtual Machine).
It contains Core libraries and classes.
It contains Support files.
It is used to execute Java programs (end-users need this).

### JVM (Java Virtual Machine)
It is a Virtual machine that executes Java bytecode.
It loads bytecode.
It verifies code safety.
It executes code line by line.
It provides memory management (garbage collection).
It makes Java platform-independent (Write Once, Run Anywhere).

## Windows Installation Steps
1.⁠ ⁠Download JDK 21 from Oracle website
2.⁠ ⁠Run installer and follow setup instructions
3.⁠ ⁠Set JAVA_HOME environment variable to JDK installation path
4.⁠ ⁠Add %JAVA_HOME%\bin to system PATH
5.⁠ ⁠Verify installation with ⁠ java -version ⁠ and ⁠ javac -version ⁠

(See screenshots/java-install-verification.png)


## Eclipse Setup on Mac
	1.	Download Eclipse IDE for Java Developers (macOS version).
	2.	Open the downloaded `.dmg` and drag Eclipse to your Applications folder.
	3.	Run Eclipse from Applications.
	4.	Configure Installed JREs to point to JDK 21 via Preferences → Java → Installed JREs.
	5.	Import your project as Existing Projects into Workspace.
	6.	Set run configuration for `CCRMApplication` main class.

## Syllabus Topic Mapping

### 1. Java Introduction & Basics
| Topic | File/Class | Method/Example |
|-------|------------|----------------|
| Java Variables & Data Types | All domain classes | Field declarations |
| Java Operators | ⁠ CCRMApplication.java ⁠ | ⁠ demonstrateOperators() ⁠ |
| Java Input and Output | ⁠ CCRMApplication.java ⁠ | ⁠ Scanner ⁠ usage throughout |
| Java Comments | All files | Code comments |
| Java Expressions & Blocks | All files | Method implementations |

### 2. Java Flow Control
| Topic | File/Class | Method/Example |
|-------|------------|----------------|
| if-else statements | ⁠ Student.java ⁠ | ⁠ enrollInCourse() ⁠ |
| switch Statement | ⁠ CCRMApplication.java ⁠ | Menu system |
| for Loop | ⁠ CCRMApplication.java ⁠ | ⁠ displayStudentProfile() ⁠ |
| for-each Loop | ⁠ StudentService.java ⁠ | ⁠ findAll() ⁠ method |
| while Loop | ⁠ CCRMApplication.java ⁠ | Main menu loop |
| break Statement | ⁠ CCRMApplication.java ⁠ | Labeled break |
| continue Statement | ⁠ CCRMApplication.java ⁠ | ⁠ displayStudentProfile() ⁠ |

### 3. Java OOP (Basics)
| Topic | File/Class | Method/Example |
|-------|------------|----------------|
| Class and Objects | All domain classes | Class definitions |
| Methods | All classes | Method implementations |
| Constructor | All domain classes | Constructors |
| Strings | All files | String manipulations |
| Access Modifiers | All classes | ⁠ private ⁠, ⁠ protected ⁠, ⁠ public ⁠ |
| this keyword | All domain classes | Constructor usage |
| final keyword | ⁠ Name.java ⁠ | Immutable class |
| Recursion | ⁠ BackupService.java ⁠ | ⁠ calculateDirectorySize() ⁠ |
| instanceof Operator | ⁠ CCRMApplication.java ⁠ | ⁠ demonstratePolymorphism() ⁠ |

### 4. Java OOP (Inheritance & Polymorphism)
| Topic | File/Class | Method/Example |
|-------|------------|----------------|
| Inheritance | ⁠ Person.java ⁠ → ⁠ Student.java ⁠ | ⁠ extends ⁠ keyword |
| Method Overriding | ⁠ Student.java ⁠ | ⁠ displayProfile() ⁠ override |
| super Keyword | ⁠ Student.java ⁠ | Constructor ⁠ super() ⁠ |
| Abstract Class & Method | ⁠ Person.java ⁠ | ⁠ abstract ⁠ class/methods |
| Interfaces | ⁠ Persistable.java ⁠ | Interface implementation |
| Polymorphism | ⁠ CCRMApplication.java ⁠ | ⁠ displayProfile() ⁠ calls |
| Encapsulation | All domain classes | Getters/setters |

### 5. Java OOP (Other types of classes)
| Topic | File/Class | Method/Example |
|-------|------------|----------------|
| Nested & Inner Class | ⁠ Student.Statistics ⁠ | Static nested class |
| Static Class | ⁠ Comparators.java ⁠ | Static utility class |
| Anonymous Class | ⁠ Comparators.java ⁠ | ⁠ BY_REGISTRATION_DATE ⁠ |
| Singleton Pattern | ⁠ AppConfig.java ⁠ | ⁠ getInstance() ⁠ method |
| enum Class | ⁠ Grade.java ⁠, ⁠ Semester.java ⁠ | Enums with fields |
| enum Constructor | ⁠ Grade.java ⁠ | Enum constructors |
| enum String | All enums | ⁠ toString() ⁠ overrides |

### 6. Java Exception Handling
| Topic | File/Class | Method/Example |
|-------|------------|----------------|
| Exceptions | Custom exception classes | Exception hierarchy |
| Exception Handling | ⁠ CCRMApplication.java ⁠ | ⁠ try-catch ⁠ blocks |
| try-catch | ⁠ CCRMApplication.java ⁠ | ⁠ manageBackup() ⁠ method |
| throw and throws | ⁠ Student.java ⁠ | ⁠ enrollInCourse() ⁠ |
| Custom Exceptions | ⁠ DuplicateEnrollmentException.java ⁠ | Custom exception classes |

### 7. Java Collections & I/O Streams
| Topic | File/Class | Method/Example |
|-------|------------|----------------|
| Collections Framework | All services | ⁠ ArrayList ⁠, ⁠ HashMap ⁠ |
| List Interface | All services | ⁠ List ⁠ usage |
| ArrayList | ⁠ StudentService.java ⁠ | ⁠ students ⁠ collection |
| I/O Streams | ⁠ BackupService.java ⁠ | ⁠ Files ⁠ operations |
| Byte-oriented streams | ⁠ BackupService.java ⁠ | ⁠ Files.write() ⁠ |
| String operations | All files | String manipulations |
| Arrays | All services | Array operations |


## Enabling Assertions

To enable Java assertions (used for validations), run with `-ea` flag:
```java -ea edu.ccrm.cli.CCRMApplication```
