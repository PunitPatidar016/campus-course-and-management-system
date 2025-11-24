Campus Course \& Records Manager (CCRM) - Project Statement

1\. Problem Statement

Educational institutions frequently struggle with managing the vast and interconnected data regarding students, course offerings, and academic performance. Manual record-keeping or disparate legacy systems often lead to data redundancy, errors in grade calculation, and significant delays in generating student transcripts. There is a critical need for a centralized, automated, and efficient system to manage these academic entities, ensuring data integrity and quick retrieval of academic records via a streamlined interface.



2\. Scope of the Project

The Campus Course \& Records Manager (CCRM) is a robust CLI-based software solution designed to digitize the core academic operations of a university.



The scope includes:



Entity Management: Full lifecycle management (creation, updating, deactivation) for Student and Course records.



Academic Logic: Enforcing rules for course enrollment (e.g., preventing duplicate enrollments) and automating the calculation of Letter Grades and GPA based on raw marks.



Data Persistence: Utilizing Java NIO.2 file I/O to store, retrieve, and backup data in CSV format, ensuring records are preserved between sessions.



Reporting: Generating specific outputs such as student transcripts, filtered course lists, and profile views.



The scope excludes:



Graphical User Interface (GUI).



Real-time networked database connectivity (SQL).



Financial/Fee payment processing.



3\. Target Users

University Administrators: To manage the central database of students and the course catalog for each semester.



Faculty Members: To look up course details and record marks for students enrolled in their subjects.



Academic Registrars: To handle student enrollments, generate academic transcripts, and perform system data backups.



4\. High-Level Features

Student Lifecycle Management: Add, update, deactivate, and view comprehensive student profiles with unique registration IDs.



Smart Course Catalog: Manage courses with advanced filtering capabilities (search by Instructor, Department, or Semester).



Enrollment System: Map students to courses with validation checks to ensure data integrity.



Automated Grading Engine: Input raw marks to automatically compute Letter Grades (S, A, B, etc.) and calculate GPA/CGPA.



Data Import/Export: Seamlessly import data from external CSV files and export current records for reporting.



Backup Utility: A specialized command to create timestamped backups of all system data for disaster recovery.

