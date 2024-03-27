### Scenario
In this scenario, you have recently been hired as a data engineer by a New York-based coffee shop chain looking to expand nationally by opening several franchise locations. They want to streamline operations and revamp their data infrastructure as part of their expansion process.

Your job is to design their relational database systems for improved operational efficiencies and to make it easier for their executives to make data-driven decisions.

Currently, their data resides in several different systems: Accounting software, suppliers' databases, point of sales (POS) systems, and even spreadsheets. You will review the data in these systems and design a central database to house all of their data. You will then create the database objects and load them with source data. Finally, you will create subsets of data your business partners require, export them, and load them into staging databases using different RDBMS.


### Data used in this project
In this project, I worked with a subset of data from the Coffee shop sample data.

I used a modified version of the data for the project, so to succeed in the project, I downloaded the linked files when prompted in the instructions.

Throughout the scenario, I worked with data from the following sources:
- Staff information held in a spreadsheet at headquarters (HQ)
- Sales outlet information held in a spreadsheet at HQ
- Sales data output as a CSV file from the POS system in the sales outlets
- Customer data output as a CSV file from a bespoke customer relationship management system
- Product information maintained in a spreadsheet exported from the  suppliers' databases


### Objectives
- Identify entities
- Identity attributes
- Create an entity relationship diagram (ERD) using the pgAdmin ERD Tool
- Normalize tables
- Define keys and relationships
- Create database objects by generating and running the SQL script from the ERD Tool
- Create a view and export the data
- Create a materialized view and export the data
- Import data into a Db2 database
- Import data into a MySQL database
