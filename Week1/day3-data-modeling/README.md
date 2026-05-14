# Week 1 - Day 3 Data Modeling

## Topics Covered
- Objects, Fields and Records
- Standard vs Custom Objects
- Relationships in Salesforce
- Formula Fields
- Validation Rules
- Structured Data in Enterprise Systems

---

# Difference Between App, Object, Record and Field

## App
An App in Salesforce is a collection of objects, tabs and features designed for a specific business purpose.

Example:
College Management App

---

## Object
An Object stores data in Salesforce.

It is similar to a table in a database.

Examples:
- Student
- Faculty
- Course

---

## Record
A Record is a single entry inside an object.

Example:
A student named Rahul stored inside the Student object.

---

## Field
A Field stores specific information about a record.

Examples:
- Student Name
- Email
- Age

---

# Standard vs Custom Objects

## Standard Objects
These are objects already provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity

## Custom Objects
These are objects created based on business requirements.

Examples:
- Student
- Faculty
- Department

---

# College Management System Data Model

## Objects
- Student
- Faculty
- Course
- Department

---

## Relationships

### Department → Faculty
One department can have many faculty members.

### Department → Course
One department can have many courses.

### Course → Student
Many students can enroll in courses.

### Faculty → Course
One faculty can teach multiple courses.

---

## Relationship Type

Lookup relationships can be used between:
- Student and Course
- Faculty and Department
- Course and Department

---

# Formula Fields

## 1. Full Name
Formula combines first name and last name automatically.

Why?
It reduces manual work and keeps naming consistent.

---

## 2. Remaining Seats
Available Seats - Enrolled Students

Why?
It updates automatically whenever admissions increase.

---

## 3. Percentage
(Obtained Marks / Total Marks) * 100

Why?
Manual calculation can cause mistakes.

---

# Validation Rules

## 1. Student Age Cannot Be Negative

Why?
Prevents invalid student data.

---

## 2. Email Cannot Be Empty

Why?
Ensures communication details are available.

---

## 3. Course Seats Cannot Exceed Limit

Why?
Prevents over-allocation of seats.

---

# Reflection

Companies need structured data because managing large amounts of business information using random spreadsheets can create duplicate data, mistakes and confusion. Structured systems help companies maintain consistency, relationships and proper data management.

---

# Screenshots



---

# My Learnings

Today I understood how Salesforce stores data using objects, records and relationships. I also learned how formula fields and validation rules help automate business logic without coding.
