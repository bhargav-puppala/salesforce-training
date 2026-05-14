# Week 1 - Day 5 Apex Introduction

## Topics Covered
- Introduction to Apex
- Variables and Logic
- Classes and Conditions
- SOQL and DML Basics
- Flow vs Apex
- Configuration vs Coding

---

# What is Apex?

Apex is Salesforce’s programming language used to implement custom business logic and advanced automation. It is similar to Java and helps developers build features that cannot be achieved using only clicks and flows.

---

# Flow vs Apex

## Flow
Flow is a no-code or low-code automation tool used to automate business processes visually.

Examples:
- sending emails
- updating records
- approval automation

### Advantages
- easy to build
- faster development
- no coding required

---

## Apex
Apex is used when business logic becomes complex and requires programming.

Examples:
- external integrations
- complex calculations
- advanced validations

### Advantages
- more flexibility
- advanced logic handling
- better control over processes

---

# Configuration vs Coding

## Configuration
Uses Salesforce tools without writing code.

Examples:
- Flows
- Validation Rules
- Formula Fields

### Best for
Simple and standard business automation.

---

## Coding
Uses Apex and programming logic.

Examples:
- integrations
- complex workflows
- advanced business rules

### Best for
Complex enterprise requirements.

---

# Real Examples Where Apex Is Needed

## 1. Complex Fee Calculation

A college may calculate fees based on:
- scholarship
- attendance
- category
- semester performance

Why Apex?
Flow becomes difficult for highly complex calculations.

---

## 2. External Payment Integration

Connecting Salesforce with payment gateways like Razorpay or Stripe.

Why Apex?
Requires API calls and custom backend logic.

---

## 3. Advanced Student Eligibility Logic

Check multiple conditions before course registration:
- attendance
- fee status
- prerequisites
- internal marks

Why Apex?
Complex conditions are easier and more scalable in code.

---

# Integrated College Management System

## CRM
Manages complete student admission and academic workflow.

---

## Objects
- Student
- Faculty
- Course
- Department
- Fees

---

## Relationships
- Department → Faculty
- Department → Course
- Student ↔ Course

---

## Validation Rules
- Email cannot be empty
- Student age cannot be negative
- Seats cannot exceed limit

---

## Formula Fields
- Full Name
- Remaining Seats
- Percentage

---

## Flow Automation
- Auto email after registration
- Auto update remaining seats
- Fee payment reminders

---

## Apex Usage
- Complex fee calculation
- Payment gateway integration
- Advanced eligibility checks

---

# Pseudocode Examples

## Example 1

IF seats are full  
THEN block student registration

---

## Example 2

IF attendance < 75%  
THEN notify student and faculty

---

## Example 3

IF fee payment is pending  
THEN send reminder email

---

# Reflection

Enterprise systems cannot depend only on clicks and configuration because some business requirements become too complex. Advanced calculations, integrations and custom workflows require programming for better flexibility and control.

---

# Screenshots


---

# My Learnings

Today I understood why Apex is important in Salesforce and how programming helps developers build advanced enterprise solutions beyond no-code automation.
