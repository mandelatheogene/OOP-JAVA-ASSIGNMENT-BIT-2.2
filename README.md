# Java (OOP) Assignment

## Student Information
**Names:** Mandera Theogene  
**Reg No:** SCT221-0897/2021

## Table of Contents
1. [Object Modeling Techniques (OMT)](#i-what-is-the-object-modeling-techniques-omt)
2. [Comparison: OOAD vs OOP](#ii-compare-object-oriented-analysis-and-design-ooad-and-object-analysis-and-designoop)
3. [Main Goals of UML](#iii-discuss-main-goals-of-uml)
4. [Advantages of Using OOP](#iv-describe-three-advantages-of-using-object-oriented-to-develop-an-information-system)
5. [Types of Associations in OOP](#v-explain-the-three-types-of-associations-relationships-between-objects-in-object-oriented)
6. [Class Diagram](#vii-what-do-you-mean-by-class-diagram-where-it-is-used-and-also-discuss-the-steps-to-draw-the-class-diagram-with-any-one-example)

## i. What is the Object Modeling Techniques (OMT)
- The object-modeling technique is an object modeling approach for software modeling and designing.

## ii. Compare Object-Oriented Analysis and Design (OOAD) and Object Analysis and Design (OOP)
- Object-Oriented Analysis and Design (OOAD) encompasses the entire process of analyzing and designing a system using object-oriented principles.
- Object-Oriented Programming (OOP) is a specific programming paradigm based on encapsulation, inheritance, and polymorphism.

## iii. Discuss Main Goals of UML
- Define a standard way to visualize the way a system has been designed.
- Help engineers understand the system and identify potential issues.

## iv. Describe Three Advantages of Using Object Oriented to Develop an Information System
1. **Inheritance and Code Reusability:** Allows a new class to inherit attributes and behaviors from an existing class.
2. **Encapsulation and Information Hiding:** Supports the concept of encapsulation, where an object hides its internal state.
3. **Modularity and Reusability:** Promotes the modular design of software systems, breaking them down into smaller, manageable units.

## v. Explain the Three Types of Associations (Relationships) Between Objects in Object Oriented
- **Association:** Bi-directional relationship between two or more classes.
- **Aggregation:** One class represents a whole, and another class represents its part.
- **Composition:** Stronger form of aggregation, where parts are strongly tied to the whole.

## vii. What do you mean by Class Diagram? Where it is Used and Steps to Draw the Class Diagram
- **Class Diagram:** UML diagram illustrating the structure and relationships of classes within a system.
- **Used for:**
  - Modeling system structure.
  - Communication and documentation.
  - Code generation in Model-Driven Architecture (MDA) environments.
- **Steps to Draw a Class Diagram:**
  1. Identify Classes.
  2. Define Class Attributes and Methods.
  3. Define Associations.
  4. Specify Multiplicity.
  5. Add Class Relationships.
  6. Refine and Review.
  7. Document the Diagram.
  8. Finalize and Share.

### Example: Hospital Management System
1. **Identify Classes:**
   - Patient
   - Doctor
   - Appointment
   - Department
2. **Define Class Attributes and Methods:**
   - Patient: patientId, name, birthDate, contactNumber.
   - Doctor: doctorId, name, specialization, contactNumber.
   - Appointment: appointmentId, patient (reference to Patient), doctor (reference to Doctor), appointmentDate.
   - Department: departmentId, name, description.
3. **Define Associations:**
   - Patient has an association with Appointment (one-to-many).
   - Doctor has an association with Appointment (one-to-many).
   - Department has an association with Doctor (one-to-many).
4. **Specify Multiplicity:**
   - Patient has many appointments (0..*).
   - Doctor has many appointments (0..*).
   - Department has many doctors (0..*).
5. **Add Class Relationships:**
   - Draw lines between classes to represent associations.
   - Add arrows to indicate the direction of associations.
   - Label the associations with multiplicity.
   - Add a relationship between Doctor and Department to represent the department each doctor belongs to.
6. **Refine and Review:**
   - Add additional details such as visibility modifiers (public, private) and methods if needed.
7. **Document the Diagram:**
   - Add a title, summary, and any additional notes that clarify the purpose and elements of the diagram.
8. **Finalize and Share:**
   - Finalize the diagram, ensuring it is clear and easy to understand.
