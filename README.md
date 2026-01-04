# MMU Library Database Management System

**Database Fundamentals Assignment**  
Course: CIT6114 | Multimedia University

## Overview

Comprehensive relational database system for MMU Library featuring 9 interconnected tables with advanced SQL operations including triggers, stored procedures, views, and complex queries with window functions.

## Database Architecture

**Tables:** Users, Books, Genres, Branches, Loans, Loan Details, Reservations, Fines, Damage Reports

**Key Features:**
- Relational integrity with foreign key constraints
- Advanced triggers for validation and automation
- Stored procedures for complex operations
- Views for simplified data access
- Aggregate functions and nested queries

## Core Functionality

### Business Rules Implementation
- User borrowing limits by type
- Book availability tracking
- Automated fine calculation
- Reservation management
- Damage report integration

### Advanced SQL Features

**Triggers:**
- BEFORE INSERT validation for loan conditions
- AFTER INSERT automation for book availability

**Stored Procedures:**
- checkout_book() - Complete checkout workflow with validation

**Views:**
- user_loan_fine_view - Comprehensive user fine tracking

**Complex Queries:**
- Window functions for ranking and analytics
- Nested subqueries for advanced filtering
- Aggregate functions with GROUP BY and HAVING
- CTEs for readable complex logic

## Technical Highlights

- 9-table normalized database design
- Comprehensive ERD with clear relationships
- Data dictionary for all entities
- Test data covering all scenarios
- Advanced query optimization

## Query Examples

- Genre popularity analysis with window functions
- User overdue loan tracking with CTEs
- Pivot table simulation for branch statistics
- Correlated subqueries for complex filtering

## Technologies Used

- **Database:** PostgreSQL / OpenGauss
- **Language:** SQL, PL/pgSQL
- **Concepts:** Database Design, Normalization, Triggers, Stored Procedures
- **Features:** Transactions, Referential Integrity, Views

## Team Members

- **Siti Zulaikha Binti Abdul Razif** (Leader) - 242UC243TL
- Eba Mohamed Abbas Ahmed - 242UC243BE
- Lama M. R. Siam - 242UC243B4
- Eshika Prasaad - 243UC246VX

## Course Information

**Course:** CIT6114 - Database Fundamentals  
**Tutorial Section:** T10L  
**Group:** 2
