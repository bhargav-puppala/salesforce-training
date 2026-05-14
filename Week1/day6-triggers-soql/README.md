# Week 1 - Day 6 Triggers and SOQL

## Topics Covered
- SOQL Basics
- Database Queries
- Apex Triggers
- Before and After Triggers
- Event Driven Automation
- Flow vs Trigger

---

# What is SOQL?

SOQL stands for Salesforce Object Query Language. It is used to retrieve data from Salesforce objects. It is similar to SQL but designed specifically for Salesforce data and objects.

Example:
Finding students enrolled in a specific course.

---

# What is an Apex Trigger?

An Apex Trigger is a piece of code that runs automatically when data changes happen in Salesforce, such as insert, update or delete operations.

Triggers help automate actions based on events.

---

# Flow vs Trigger

## Flow
Flow is a no-code automation tool used for simple and standard business processes.

Examples:
- sending notifications
- updating records
- approval processes

### Best For
Simple automation with less complexity.

---

## Apex Trigger
Triggers are code-based automation used for advanced business logic and event-driven actions.

Examples:
- complex validations
- integrations
- advanced calculations

### Best For
Complex and scalable automation logic.

---

# Before vs After Trigger

## Before Trigger
Runs before data is saved into the database.

Used for:
- validations
- modifying values before save

---

## After Trigger
Runs after data is saved into the database.

Used for:
- sending notifications
- updating related records
- integrations

---

# Trigger Use Cases in College Management System

## 1. After Student Registration → Send Welcome Email

### Trigger Event
After Insert on Student object.

---

## 2. After Course Becomes Full → Notify Faculty

### Trigger Event
After Update on Course object.

---

## 3. After Attendance Drops Below 75% → Send Warning

### Trigger Event
After Update on Attendance field.

---

## 4. After Fee Payment → Generate Receipt

### Trigger Event
After Update on Fee object.

---

## 5. After Student Record Deletion → Archive Student Data

### Trigger Event
After Delete on Student object.

---

# Flow vs Trigger Thinking

## Simple Email Notification
Use Flow

Why?
Easy automation without coding.

---

## Complex Fee Eligibility Check
Use Apex Trigger

Why?
Requires advanced business logic.

---

## Updating Related Records
Use Flow

Why?
Simple record automation is easier in Flow.

---

## External API Integration
Use Apex Trigger

Why?
Needs backend programming and API handling.

---

# Query Examples

## Query 1
Find all students enrolled in Course A.

---

## Query 2
Find all courses handled by Faculty X.

---

## Query 3
Find students with attendance below 75%.

---

## Query 4
Find all students from Computer Science department.

---

## Query 5
Find courses with no available seats.

---

# Reflection

Enterprise systems need event-driven behavior because actions should happen automatically when data changes occur. This improves efficiency, reduces manual work and helps systems respond quickly to important business events.

---

# Screenshots



---

# My Learnings

Today I understood how Salesforce retrieves data using SOQL and how Apex Triggers help systems react automatically to data changes and business events.
