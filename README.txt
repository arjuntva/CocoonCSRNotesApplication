==========================================================
Cocoon Customer Service Application : Release: Version 1.0
==========================================================

Author: Arjun Anand

The Cocoon Customer Service Notes Application consists of the following features:

Minimum UAT criteria Satisfied

1. The CSR should be required to login to access the feature
2. Each note should be tagged with the login of the CSR who made the note
3. The CSR should see notes in reverse chronological order
4. The customers name should include a title, first name and last name
5. The customers name should be capable of containing accented characters
6. Retrieval of the customers record should happen based on a Cocoon ID

Additional Features:

1. Facility to create relevant Tables automatically
2. Admin based CSR user and password addition
3. Facility to view all notes from all the CSRs
4. SQL Server URL is configurable along with username and Password.

Software Requirements:

1. Java 1.7
2. MySQL JDBC Driver
3. MySQL

=============================
KNOWN ISSUES IN THIS RELEASE:
=============================

1. MySQL DB needs basic database named "cocooncsr" created manually
2. URL and password details for MySQL server is hardcoded in code related to Admin based CSR user addition
3. Passwords are not encrypted or hidden

======================
IDEAS FOR IMPROVEMENTS
======================

1. Encrypted passwords
2. Alternate way to register user so that admin password need not be set or made visible
3. Make the application web-based for lightweight access

==================
INSTALLATION NOTES
==================

1. MySQL DB needs basic database named "cocooncsr" created manually
2. Update the properties file under CocoonCSRNotesApplication\src\com\application\cocooncsr\properties
3. The Runnable JAR is under CocoonCSRNotesApplication\dist

=========
JAVA DOCS
=========

CocoonCSRNotesApplication\dist\javadoc

