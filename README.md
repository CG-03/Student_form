# Student_form
Student Enrollment Form using JsonPowerDB

Description

The Student Enrollment Form is a web application that allows users to add, update, and manage student records using JsonPowerDB (JPDB). This lightweight, high-performance, and easy-to-use NoSQL database helps efficiently store and retrieve student details.

Benefits of using JsonPowerDB

Simple & Fast: No complex setup, lightweight, and high-speed performance.

Schema-free: No need for predefined tables and schemas.

Built-in API: Direct JSON-based API for effortless integration.

Real-time updates: Quick response and minimal latency.

Minimalistic CRUD Operations: Direct use of PUT, GET, and UPDATE API endpoints.

Release History

v1.0.0 (March 2025)

Initial release with basic form functionality.

Added student record storage and retrieval.

v1.1.0 (April 2025)

Enhanced UI with Bootstrap styling.

Improved error handling for API calls.

v1.2.0 (May 2025)

Implemented form validation and roll number verification.

Table of Contents

Description

Benefits of using JsonPowerDB

Release History

Illustrations

Scope of Functionalities

Examples of Use

Project Status

Sources

Other Information

Illustrations



Scope of Functionalities

Student Registration using Roll Number.

Storing student details in JsonPowerDB.

Fetching existing student details from the database.

Updating student records.

Resetting the form for new entries.

Examples of Use

Saving a Student Record (API Request)
{
  "token": "YOUR_API_KEY",
  "dbName": "SCHOOL-DB",
  "cmd": "PUT",
  "rel": "STUDENT-TABLE",
  "jsonStr": {
    "Roll-No": "101",
    "Full-Name": "John Doe",
    "Class": "10A",
    "Birth-Date": "2008-05-12",
    "Address": "123 Main St",
    "Enrollment-Date": "2025-03-28"
  }
Project Status

🚀 Active Development: The project is actively maintained and new features are being added.

🛠 Planned Enhancements:

Add authentication system.

Integrate student image upload feature.

Export data as CSV.

Sources

JsonPowerDB Official Documentation



Other Information

For support and contributions, please submit a pull request on GitHub.
