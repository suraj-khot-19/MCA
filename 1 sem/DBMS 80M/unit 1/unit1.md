<h1 align="center">Unit 1</h1>
<h3>Syllabus</h3>
<p>Basics of DBMS: Database Concept, Characteristics and architecture of DBMS, Database
users, 3-tier architecture of DBMS-its advantages over 2-tier, Introduction of Parallel,
Distributed Databases, Mobile databases and Cloud databases. Data independence. Physical
data organization, Indexing-introduction and types of indexing</p>
<hr>
<ul>
<li>Database Concept</li>
<hr>
<li>Characteristics and architecture of DBMS</li>
        <p>
 key characteristics of a Database Management System (DBMS):

1.  **Real-World Entity**: DBMS represents real-world entities and their relationships. For example, a student database might include entities like students, courses, and instructors.

2.  **Self-Describing Nature**: A DBMS contains not only the database itself but also metadata, which is data about data. This metadata describes the structure of the database, making it self-explanatory.

3.  **Atomicity of Operations (ACID Properties)**: DBMS ensures that all operations (transactions) are atomic, consistent, isolated, and durable. This means that transactions are completed fully or not at all, maintaining data integrity.

4.  **Concurrent Access**: Multiple users can access and modify the database simultaneously without affecting each other's work. This is crucial for systems like banking or airline reservations.

5.  **Data Integrity**: DBMS enforces data integrity constraints to ensure the accuracy and consistency of data. For example, it can enforce rules like unique IDs for each student.

6.  **Security**: DBMS provides security features to protect data from unauthorized access. This includes user authentication, access controls, and encryption.

7.  **Data Abstraction and Independence**: DBMS provides a level of abstraction between the physical storage of data and the logical view of the data. This means changes in the database structure do not affect the application programs.

8.  **Support for Multiple Views**: DBMS allows different users to have different views of the database according to their needs. For example, a student might see their grades, while an instructor sees the grades of all students.

 </p>
 <hr>
    <li>Database users</li>
    <p>
In a Database Management System (DBMS), there are several types of users, each with distinct roles and responsibilities. Here are the main categories:

1. **Database Administrators (DBA)**:
   - **Role**: DBAs are responsible for managing the overall database system. They define the schema, control access, ensure data integrity, and handle backup and recovery¹.
   - **Responsibilities**: Creating user accounts, setting permissions, monitoring performance, and maintaining security.

2. **Database Designers**:
   - **Role**: They design the structure of the database, including tables, indexes, views, and constraints².
   - **Responsibilities**: Ensuring the database meets the needs of all user groups and is optimized for performance.

3. **System Analysts**:
   - **Role**: They analyze the requirements of end users and ensure that the database system meets these needs¹.
   - **Responsibilities**: Bridging the gap between users and developers, and ensuring the system's functionality aligns with user requirements.

4. **Application Programmers**:
   - **Role**: Also known as back-end developers, they write the code for applications that interact with the database².
   - **Responsibilities**: Developing and maintaining application programs, ensuring efficient data retrieval and manipulation.

5. **Naive/Parametric Users**:
   - **Role**: These are end users who interact with the database through predefined applications without needing to understand the underlying database structure¹.
   - **Responsibilities**: Performing routine tasks like data entry and retrieval using user-friendly interfaces.

6. **Sophisticated Users**:
   - **Role**: These users are familiar with the database and can write their own queries to retrieve data².
   - **Responsibilities**: Conducting complex data analysis and generating reports.

7. **Casual Users**:
   - **Role**: These users occasionally interact with the database, often for specific queries or reports².
   - **Responsibilities**: Accessing data as needed, typically through query languages like SQL.

Each type of user plays a crucial role in the efficient operation and management of a DBMS, ensuring that data is accurately stored, retrieved, and maintained.          
</p>
<hr>
    <li> 3-tier architecture of DBMS-its advantages over 2-tier</li>
<hr>
    <li>Introduction of Parallel,Distributed Databases</li>
<hr>
    <li> Mobile databases and Cloud databases</li>
<hr>
    <li>Data independence</li>
<hr>
    <li>Physicaldata organization</li>
<hr>
    <li>Indexing-introduction and types of indexing</li>
    </ul>
