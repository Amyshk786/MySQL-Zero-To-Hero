- For Single Line Comment we can give below

(# or --)


- For Multi Line Comment we can give below

/*
And between  this we can write the data which we want to comment
*/





===================

## In Postgresql, Oracle has Something Called as "SCHEMA" which is Also Called as Namespace 



-> For Example 

We have retail_db as our Database

DEV, TEST & PROD Will be the Schema or Namespace [These are different Environments within an Org]

Then we will have Tables Under Each Environment



🏢 Real-World Example

Database:
retail_db


Schemas (Environments):
DEV 🧪
TEST 🔍
PROD 🚀

Each schema contains its own tables.




📊 Visual Structure

retail_db
│
├── DEV
│   ├── customers
│   ├── orders
│
├── TEST
│   ├── customers
│   ├── orders
│
└── PROD
    ├── customers
    ├── orders









In a Nutshell

DB -> SCHEMA -> TABLES  [This is the Hirerachy]




📂 Database Hierarchy

Database
   ↓
Schema
   ↓
Tables








