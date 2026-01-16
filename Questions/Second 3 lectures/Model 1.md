# Software Engineering Review Questions

## Lecture 4: Use-Case & Activity Diagrams (20 Questions)

### 1. What is a Business Process?
a) A static rule that defines business structure.  
b) A collection of linked activities to achieve a specific goal.  
c) A single decision point in a workflow.  
d) A visual model of system architecture.

### 2. A Business Rule is best described as:
a) A sequence of tasks.  
b) A testable directive that influences business behavior.  
c) A diagram showing system functionality.  
d) A role played by an external user.

### 3. In a Use-Case Diagram, the box that defines the scope of the system is called the:
a) Actor  
b) Use Case  
c) System Boundary  
d) Relationship

### 4. An "Actor" in a Use-Case Diagram can be:
a) Only a human user.  
b) Only another software system.  
c) A role played by an external entity (human or system).  
d) An internal module of the system.

### 5. A Use Case represents:
a) A system constraint.  
b) A specific goal of an actor.  
c) A business rule.  
d) A sequence of activities.

### 6. A solid line connecting an Actor to a Use Case represents:
a) An <<include>> relationship.  
b) An <<extend>> relationship.  
c) An Association.  
d) A System Boundary.

### 7. The <<include>> relationship indicates that:
a) A Use Case is optional.  
b) A Use Case extends another under specific conditions.  
c) A Use Case must include the functionality of another Use Case.  
d) An Actor is optional.

### 8. The <<extend>> relationship is:
a) Mandatory.  
b) Conditional and optional.  
c) Represented by a solid line.  
d) Used to show system boundaries.

### 9. In an Activity Diagram, the start of the workflow is represented by a:
a) Rounded Rectangle.  
b) Diamond.  
c) Filled Circle.  
d) Bull's Eye Circle.

### 10. Which element in an Activity Diagram represents a branch in the flow with conditions?
a) Initial Node  
b) Decision Node  
c) Merge Node  
d) Fork Node

### 11. A "Fork Node" in an Activity Diagram is used to:
a) End the process.  
b) Represent alternative paths.  
c) Start concurrent (parallel) activities.  
d) Merge flows back together.

### 12. "Swimlanes" in an Activity Diagram are used to:
a) Show the sequence of activities.  
b) Group activities by the responsible actor or department.  
c) Represent decision points.  
d) Indicate the start and end of the process.

### 13. Which diagram is best for showing "How" a specific task is accomplished step-by-step?
a) Use-Case Diagram  
b) Class Diagram  
c) Activity Diagram  
d) Deployment Diagram

### 14. In the tea-making example, the rule "The water must be at 100°C" is a:
a) Business Process.  
b) Business Rule.  
c) Use Case.  
d) Activity.

### 15. The primary purpose of a Use-Case Diagram is to:
a) Model the dynamic flow of activities.  
b) Show the static structure of classes.  
c) Capture the system's functionalities and actor interactions.  
d) Document business rules.

### 16. In an Activity Diagram, an arrow represents:
a) An Actor.  
b) A Control Flow.  
c) A Decision.  
d) A Swimlane.

### 17. Which relationship would you use to model that "Withdraw Cash" MUST include "Validate PIN"?
a) Association  
b) <<extend>>  
c) <<include>>  
d) Generalization

### 18. In the online shopping example, "Apply Discount" extending "Make Purchase" is an example of:
a) A mandatory relationship.  
b) An optional, conditional relationship.  
c) A business process.  
d) An association.

### 19. A "Merge Node" in an Activity Diagram:
a) Splits the flow into multiple paths.  
b) Brings together alternative flows into one.  
c) Starts parallel activities.  
d) Represents an activity.

### 20. Which of the following is a key difference between a Business Process and a Business Rule?
a) A Process is a sequence; a Rule is a constraint on that sequence.  
b) A Process is static; a Rule is dynamic.  
c) A Process defines "What"; a Rule defines "How".  
d) A Process is always automated; a Rule is always manual.

## Lecture 5: UML & Class Diagrams (20 Questions)

### 21. What is the primary purpose of modeling in software engineering?
a) To write code faster.  
b) To reduce complexity by abstracting away unessential details.  
c) To eliminate the need for testing.  
d) To create user manuals.

### 22. UML stands for:
a) Unified Modeling Language.  
b) Universal Module Linkage.  
c) User Management Layer.  
d) Unified Module Language.

### 23. Which type of UML diagram shows the static structure of a system?
a) Activity Diagram  
b) Use-Case Diagram  
c) Class Diagram  
d) Sequence Diagram

### 24. A standard Class box in UML has how many compartments?
a) 1  
b) 2  
c) 3  
d) 4

### 25. In a Class Diagram, the attribute `- name: String` has what visibility?
a) Public  
b) Private  
c) Protected  
d) Package

### 26. The `#` visibility modifier means:
a) Public  
b) Private  
c) Protected  
d) Package

### 27. A static attribute in a class is indicated by:
a) A minus sign (-).  
b) Being italicized.  
c) Being underlined.  
d) A plus sign (+).

### 28. An abstract method in a class is indicated by:
a) Being underlined.  
b) Being italicized.  
c) A hash symbol (#).  
d) A tilde (~).

### 29. Which relationship represents a "has-a" relationship with weak ownership?
a) Association  
b) Aggregation  
c) Composition  
d) Inheritance

### 30. Which symbol represents an Aggregation relationship?
a) Solid line  
b) Hollow diamond  
c) Filled diamond  
d) Hollow triangle

### 31. In a Composition relationship, when the whole is destroyed:
a) The parts continue to exist.  
b) The parts are also destroyed.  
c) The relationship becomes an aggregation.  
d) The parts become public.

### 32. Inheritance is represented by:
a) A solid line.  
b) A hollow diamond.  
c) A filled diamond.  
d) A hollow triangle arrow.

### 33. In the University example, the hollow diamond between University and Department represents:
a) Composition.  
b) Aggregation.  
c) Inheritance.  
d) Association.

### 34. In the Library example, the relationship between Library and Book (filled diamond) is:
a) Aggregation.  
b) Composition.  
c) Inheritance.  
d) Association.

### 35. Multiplicity `1..*` means:
a) Zero or one.  
b) Exactly one.  
c) One or more.  
d) Zero or more.

### 36. A derived attribute is indicated by:
a) A leading slash (/).  
b) Being underlined.  
c) Being italicized.  
d) A minus sign (-).

### 37. Which of the following is a Behavioral UML diagram?
a) Class Diagram  
b) Object Diagram  
c) Use-Case Diagram  
d) Deployment Diagram

### 38. The method `+ calculateTotal(): double` is:
a) Private, returns a double.  
b) Public, returns a double.  
c) Protected, takes no parameters.  
d) Static, returns a double.

### 39. In the relationship "Student -- enrolls in -- Course", what does the solid line represent?
a) Inheritance  
b) Association  
c) Aggregation  
d) Composition

### 40. Which of the following is TRUE about an Association relationship?
a) It represents a strong ownership.  
b) It can be unidirectional or bidirectional.  
c) It is always represented by a diamond.  
d) It implies a parent-child hierarchy.

## Lecture 6: Introduction to Testing (20 Questions)

### 41. The main goal of software testing is to:
a) Prove the software has no bugs.  
b) Find bugs and ensure the software works as expected.  
c) Write documentation.  
d) Replace the need for requirements.

### 42. In Plan-Driven (Waterfall) development, testing is typically:
a) Continuous throughout the project.  
b) A separate phase at the end.  
c) Done only by the developers.  
d) Not required.

### 43. In Agile development, testing is:
a) Only done at the end of the project.  
b) A separate team's responsibility.  
c) Continuous and integrated throughout development.  
d) Less important than documentation.

### 44. Test-Driven Development (TDD) follows which cycle?
a) Blue-White-Refactor  
b) Red-Green-Refactor  
c) Plan-Code-Test  
d) Analyze-Design-Test

### 45. In the Red-Green-Refactor cycle, the "Red" phase means:
a) The code is complete.  
b) The test passes.  
c) The test is written and fails.  
d) The code is refactored.

### 46. Which quality factor refers to the software performing the exact tasks in the requirements?
a) Reliability  
b) Correctness  
c) Efficiency  
d) Usability

### 47. "How well the software uses computing resources" refers to:
a) Integrity  
b) Efficiency  
c) Reliability  
d) Portability

### 48. The ease with which you can find and fix a bug is called:
a) Testability  
b) Flexibility  
c) Maintainability  
d) Reusability

### 49. The ability of software to run on different platforms is:
a) Portability  
b) Interoperability  
c) Reusability  
d) Flexibility

### 50. A common trade-off exists between:
a) Correctness and Reliability  
b) Security (Integrity) and Performance (Efficiency)  
c) Usability and Maintainability  
d) Portability and Testability

### 51. The base of the Testing Pyramid is:
a) System Testing  
b) Integration Testing  
c) Unit Testing  
d) Acceptance Testing

### 52. Testing the complete, integrated system against requirements is:
a) Unit Testing  
b) Integration Testing  
c) System Testing  
d) Acceptance Testing

### 53. Black-Box Testing is performed from the perspective of:
a) The developer who sees the code.  
b) The user, based on requirements.  
c) The database administrator.  
d) The project manager.

### 54. Equivalence Partitioning is a technique used in:
a) White-Box Testing  
b) Black-Box Testing  
c) Unit Testing only  
d) Acceptance Testing only

### 55. Boundary Value Analysis focuses on testing:
a) The middle of input ranges.  
b) The edges of input partitions.  
c) Only invalid inputs.  
d) The internal code paths.

### 56. White-Box Testing is also known as:
a) Behavioral Testing  
b) Structural Testing  
c) Functional Testing  
d) User Acceptance Testing

### 57. Path Testing is a White-Box technique that aims to:
a) Test every possible input combination.  
b) Test every possible path through the code.  
c) Test only the main functionality.  
d) Test the user interface.

### 58. Cyclomatic Complexity is a measure of:
a) Code size in lines.  
b) Number of bugs in the code.  
c) Code complexity based on decision points.  
d) Execution speed of the program.

### 59. A higher Cyclomatic Complexity indicates:
a) Simpler, easier to test code.  
b) More complex, harder to test code.  
c) Better performance.  
d) Fewer decision points.

### 60. In the given code example, if there are 7 independent paths, the Cyclomatic Complexity is:
a) 6  
b) 7  
c) 8  
d) Depends on the number of lines.

---

## Answer Key

1) b | 2) b | 3) c | 4) c | 5) b | 6) c | 7) c | 8) b | 9) c | 10) b

11) c | 12) b | 13) c | 14) b | 15) c | 16) b | 17) c | 18) b | 19) b | 20) a

21) b | 22) a | 23) c | 24) c | 25) b | 26) c | 27) c | 28) b | 29) b | 30) b

31) b | 32) d | 33) b | 34) b | 35) c | 36) a | 37) c | 38) b | 39) b | 40) b

41) b | 42) b | 43) c | 44) b | 45) c | 46) b | 47) b | 48) c | 49) a | 50) b

51) c | 52) c | 53) b | 54) b | 55) b | 56) b | 57) b | 58) c | 59) b | 60) b

