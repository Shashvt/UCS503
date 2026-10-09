# Post-MST Week 1 Journal
## Collaborative Study Platform — Class Diagram

**Week:** First Week After MST Examinations  
**Project:** Collaborative Study Platform  
**Primary Focus:** Understanding and Creating the UML Class Diagram

---

## 1. Introduction

After completing my MST examinations, I resumed working on my Software Engineering project, the Collaborative Study Platform. During the first week after the examinations, I focused on understanding the structure of the project and creating its UML Class Diagram.

The purpose of this activity was to represent the major classes of the system, their attributes, operations, and relationships. I also reviewed UML notation to ensure that the diagram would be suitable for my project prototype report.

## 2. Work Undertaken During the Week

### 2.1 Understanding the Class Diagram

I started by studying the basic concepts of a UML Class Diagram. I learned that a Class Diagram represents the static structure of a software system, including its classes, attributes, methods, and relationships.

I reviewed the standard three-compartment structure of a UML class, which consists of the class name, attributes, and operations. I also studied associations, multiplicities, inheritance, aggregation, composition, and dependency relationships.

### 2.2 Identifying the Main Classes

After understanding the UML concepts, I identified the main entities relevant to the Collaborative Study Platform. These included:

- **User:** Represents a registered user who accesses the platform.
- **Classroom:** Represents the academic or classroom structure used for organizing resources.
- **Note:** Represents study notes available on the platform.
- **Book:** Represents academic books accessible to students.
- **Previous-Year Question:** Represents previous-year question papers available through the platform.
- **File Storage Service:** Represents the storage-related service responsible for handling uploaded files, if modelled separately.

These classes were considered based on the platform's functionality. Their final attributes and relationships need to be consistent with the actual backend implementation and database schema.

### 2.3 Defining Attributes and Operations

I then considered the attributes and operations that describe each class.

For example, the User class may contain attributes such as user ID, name, email, and password hash, with operations related to registration, login, and logout.

Similarly, resource classes such as Note, Book, and Previous-Year Question may contain identifiers, titles, subject information, file references, and creation timestamps.

This step helped me understand how classes represent the data and responsibilities associated with different parts of the system.

### 2.4 Establishing Relationships

I studied how classes interact with and relate to one another. I considered associations between users and uploaded resources, as well as relationships between academic contexts and resources.

I also reviewed UML multiplicities to represent how many instances of one class may be associated with another. I understood that relationships, multiplicities, and inheritance should only be included when supported by the system design or implementation.

### 2.5 Referring to the UML Template

I referred to a traditional UML Class Diagram example to understand the correct visual representation of classes and relationships. I used it as a guide for arranging class boxes, separating attributes and operations, and drawing association and dependency lines.

My objective was to produce a clear and readable diagram that followed standard UML conventions and matched the academic style expected in the prototype report.

## 3. Technology and Architecture Considerations

While preparing the Class Diagram, I also considered the technology stack used in the project:

- **React and TypeScript:** Used for the frontend interface.
- **Go/Gin:** Used for backend application logic and API handling.
- **PostgreSQL:** Used for structured information and resource metadata.
- **AWS S3:** Used for storing uploaded files.

I learned that a Class Diagram should not simply list all technologies as domain classes. Instead, it should focus on the classes and relationships relevant to the system's structure.

I also distinguished between PostgreSQL and AWS S3. PostgreSQL stores structured records and metadata, whereas AWS S3 stores the actual uploaded files. The backend coordinates the interactions with these two storage systems.

## 4. Challenges Faced

During this activity, I focused on resolving the following design questions:

1. Identifying which concepts should be represented as classes.
2. Distinguishing domain classes from technical components and services.
3. Deciding which attributes and operations were relevant to each class.
4. Understanding when to use association, aggregation, composition, inheritance, and dependency.
5. Avoiding unsupported attributes, relationships, and multiplicities.
6. Arranging the diagram so that the classes and their connections remained readable.

These considerations helped me approach the diagram as a representation of the actual project rather than simply a visual illustration.

## 5. Learning Outcomes

By the end of the week, I developed a better understanding of:

- The purpose and structure of UML Class Diagrams.
- The relationship between classes, attributes, and operations.
- UML association and multiplicity notation.
- The difference between domain classes and implementation components.
- The separation of structured database information and cloud-based file storage.
- The importance of keeping software documentation consistent with the actual implementation.

## 6. Work Status

During this week, I studied the UML Class Diagram notation, identified candidate classes, considered their attributes and operations, and planned the relationships needed to represent the Collaborative Study Platform.

The next step is to verify the proposed class structure against the actual Go structs and PostgreSQL table definitions. This will help ensure that the final diagram accurately represents the implemented prototype.

## 7. Plan for the Next Week

My planned activities for the following week are:

1. Review the backend source code and database schema.
2. Confirm the attributes and relationships of the identified classes.
3. Finalize the UML Class Diagram.
4. Check the diagram for incorrect or unnecessary relationships.
5. Include the completed diagram in the Software Engineering prototype report.
6. Continue preparing the remaining UML diagrams and project documentation.

## 8. Reflection

The first week after my MST examinations was an opportunity to resume project work and focus on the design documentation of the Collaborative Study Platform. Creating the Class Diagram helped me understand the structure of the system more clearly and reinforced the importance of accurate UML modelling.

I also learned that a good Class Diagram should be based on the actual requirements and implementation rather than assumptions. This activity provided a foundation for refining the project's design and completing the remaining documentation in the upcoming weeks.

---

**Conclusion:** The first week was primarily dedicated to understanding UML Class Diagrams, identifying the main classes of the Collaborative Study Platform, and planning their attributes, operations, and relationships. The next stage is to verify and finalize the diagram using the actual project implementation.
