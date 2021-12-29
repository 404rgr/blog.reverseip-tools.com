---
title: "Database management system and its Scope"
date: 2021-12-28T17:20:38-05:00
author: "Pausi"
draft: false
description: "DBMS (Database Management System) is a system or software specifically designed to manage a database and perform operations on data requested by many users."
images: ["/database.jpg"]
tags: ["DBMS", "MySQL"]
categories: ["database"]
featuredImage: "/database.jpg"
featuredImagePreview: "/database.jpg"
---

<!-- {{< figure src="/database.jpg" height="500px" alt="database">}} -->

DBMS (Database Management System) is a system or software specifically designed to manage a database and perform operations on data requested by many users.
DBMS is an intermediary for users with the database, to be able to interact with the DBMS can use the database language that has been determined by the DBMS company. Database languages generally consist of various kinds of instructions that are formulated so that these instructions can be processed by the DBMS.

This DBMS can also assist in maintaining and processing large amounts of data, using a DBMS so that it does not cause chaos and can be used by users as needed.
WHAT IS A DBMS?


## DEFINITION OF DBMS ACCORDING TO EXPERTS
1. According to **C.J. Date** DBMS is software that handles all access to the database to serve user needs.
2. According to **S. Attre** DBMS is the software, hardware, firmware and procedures that manage the database. _Firmware_ is software that has become a module embedded in hardware (ROM).
3. According to **Gordon C. Everest** DBMS is an effective management for organizing data resources.

## DATABASE STRUCTURE
Database structure is a series of knowledge about data modeling, including:
1. Table 
{{< line_break >}}A table is referred to as a complete collection of records and fields in the database system.

2. Basis Data
{{< line_break >}}The database is a collection of data that has been neatly and well organized by the system. All of this data can be stored, manipulated, and can be recalled at any time by the user

3. File
{{< line_break >}}Files consist of records that describe a single unit of similar data. For example, a course file contains data about all existing courses.

4. Data
{{< line_break >}}Data is a collection of events and facts that can be used to solve problems in the form of special information in the database.

5. Field
{{< line_break >}}Represents an attribute of a record that represents a data item, such as name, address, and so on.

6. Record
{{< line_break >}}A collection of fields forms a record. Record describes a particular individual data unit.


## COMPONENTS OF THE DBMS
1. Database Manager
{{< line_break >}}In this component, it can provide an interface between the low-level data that exists in each database with an application program and also on queries that will be given to a system.

2. File Manager
{{< line_break >}}File Manager is a component that can manage the available space on disk and also on a data structure that can be used to represent information that has been stored on a disk.

3. Dictionary Manager
{{< line_break >}}The dictionary manager is a component of the DBMS that can manage access to and maintain dictionary data.

4. DDL Interpreter
{{< line_break >}}DDL Interpreter serves to translate DDL commands and record definitions in the data dictionary. Examples of DDL commands such as CREATE, ALTER, RENAME, DROP, TRUNCATE, COMMENT.

5. DML Compiler
{{< line_break >}}DML Compiler is a component that can convert a command from DML, which will later be added in an application program to a normal procedure player in the parent language. Examples of DML commands such as UPDATE, DELETE, INSERT, SELECT.

6. Mesin Evaluasi Query
{{< line_break >}}In this DBMS component, it can function as translating a command into a query language into a low-level instruction and can be understood by the database manager.


## Database Scope
A database system has a scope in its operation, this scope supports the database system to work according to our needs. Differences in the scope of a database system can be seen clearly through the database architecture:

1. Standalone
{{< line_break >}}In this architecture, the DBMS, database and database applications are placed on the same machine (computer). Thus, only one user can use it at any time (single user).

2. Sistem Terpusat
{{< line_break >}}Is a database system that places the database and all its scope into a particular server computer.

3. Sistem Client Server
{{< line_break >}}Client Server system (Distributed Database system) is a database system where the database is stored on several server computers.

## DBMS Purpose
* Can be used or used together
* Speed and convenience when accessing data
* Save data storage space
* For data security
* Eliminate duplication and data inconsistency
* Handling large or large amounts of data

## DBMS functions
* Defines data
* Changing data or manipulating data
* Data security and integrity
* Recovery / Repair and data accuracy
* Data dictionaries
* For work performance

## Benefits of DATABASE
* Ease and speed in data retrieval (speed).
* Redundancy Control.
* Access Restrictions.
* Persistent Storage for program objects & data structures.
* Database Inference using deduction rules.
* Availability of Multiple User Interfaces.
* Can present complex relationships between the data involved.
* Availability of Backup & Recovery Facilities.

## Some examples of DBMS applications
* MySQL
* PostgreSQL
* MS SQL Server
* MongoDB
* SQLite
* Oracle
* Firebird
* MS Access
