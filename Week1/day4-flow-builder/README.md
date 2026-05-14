# Week 1 - Day 4 Flow Builder and Automation

## Topics Covered
- Flow Builder Basics
- Business Process Automation
- Types of Flows
- Record Automation
- Manual vs Automated Systems
- Workflow Improvement

---

# What is Flow Builder?

Flow Builder is a Salesforce tool used to automate business processes without writing code. It helps companies reduce manual work, save time and improve productivity by automating tasks and workflows.

---

# Why Automation Matters

Automation helps businesses:
- reduce repetitive work
- improve accuracy
- save time
- increase productivity
- maintain consistency

---

# Types of Flows

## Screen Flow
Screen Flow interacts with users by showing screens and collecting input.

Example:
Student registration form.

---

## Record Triggered Flow
Record Triggered Flow runs automatically when a record is created, updated or deleted.

Example:
Automatically update remaining seats when a student enrolls in a course.

---

# Automation Ideas for College Management System

## 1. Auto Email After Registration
Send a confirmation email after student registration.

Why?
Reduces manual communication work.

---

## 2. Generate Student ID Automatically
Automatically create unique student IDs.

Why?
Prevents duplicate IDs and saves time.

---

## 3. Auto Update Remaining Seats
Reduce available seats when a student enrolls.

Why?
Keeps course data updated automatically.

---

## 4. Fee Payment Reminder
Send reminders before fee due date.

Why?
Improves payment tracking and reduces delays.

---

## 5. Notify Faculty When Course is Full
Send notification when maximum student limit is reached.

Why?
Helps faculty manage admissions efficiently.

---

# Flow Design Thinking

## Automation Selected
Auto Update Remaining Seats

---

## Flow Steps

### Trigger
Student enrolls in a course.

↓

### Step 1
Get course details.

↓

### Step 2
Check available seats.

↓

### Decision
Seats available or not?

↓

### If Yes
Reduce remaining seats count.

↓

### Final Action
Update course record automatically.

---

# Manual vs Automated Process

## Process Chosen
Student Registration

### Manual Process
Staff manually enters student details, checks seat availability and sends confirmation messages.

### Problems in Manual Process
- takes more time
- chances of mistakes
- duplicate entries
- delayed communication

### Automated Process Using Salesforce
Salesforce automatically stores student data, updates course seats and sends confirmation emails.

Benefits:
- faster process
- fewer errors
- improved productivity
- better consistency

---

# Reflection

Companies automate repetitive business processes to save time, reduce manual errors and improve efficiency. Automation also helps businesses maintain consistency and allows employees to focus on more important tasks instead of repetitive work.

---

# Screenshots

(Add Trailhead screenshots here)

---

# My Learnings

Today I understood how Flow Builder helps automate business workflows in Salesforce and why automation is important in enterprise systems.
