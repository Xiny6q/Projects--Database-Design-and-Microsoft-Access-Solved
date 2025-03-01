Download link :https://programming.engineering/product/projects-database-design-and-microsoft-access-solved/

# Projects--Database-Design-and-Microsoft-Access-Solved
Projects- Database Design and Microsoft Access Solved
Project 1: Create a Microsoft Access database

Using Microsoft Access, create a database based on your E-R diagram from Assignment 2.

The Entity-Relationship Diagram (ERD) is the model or ‘blueprint’ that is used to create a database. For Assignment Three, you will take the requirements of the E-R diagram from Assignment Two and use that to create a database using MS Access.

You are required to use the attributes and the relationships of the E-R Diagram from Assignment Two. This includes the correct use of the Primary and Foreign keys and their correct properties in the MS Access database.

You MUST submit a copy of your CORRECTED Assignment Two E-R Diagram as part of Assignment Three. This means you must re-do your Project One (E-R Diagram) from Assignment Two.

“Should I wait until I get my Assignment Two grade back before I can start Assignment Three?”

NO!!!!! DO NOT WAIT. Even if you did not even submit Assignment Two there is more than enough information provided in this written description of Assignment Three for you to start right now (immediately – i.e. you do NOT wait!)

EVEN IF you received an 86 out 86 marks on Project One of Assignment Two, you still MUST submit your E-R Diagram based on the marking sheet BEFORE you continue with the rest of Assignment Three. (Yes, even if you earned an 86/86 you MUST still submit the ER Diagram.)

YOU MUST USE YOUR CORRECTED E-R DIAGRAM BASED ON WHAT YOU SUBMITTED IN ASSIGNMENT TWO.

Only a correct ER Diagram will produce the database below. The database MUST match the specifications below.

YOUR DATABASE IN ASSIGNMENT THREE WILL BE COMPARED TO YOUR CORRECTED E-R DIAGRAM BASED ON YOUR ASSIGNMENT TWO.

This will provide the student with the experience of using their design to create a functional database.

BUT! You MUST correct your E-R Diagram to the specifications in the Assignment Two marking.

Your database MUST meet the requirements and the tables and fields below. So, if you E-R Diagram was wrong or incomplete, you MUST re-do and re-submit the diagram for this assignment.

You MUST submit a corrected ERD to show these changes.

HINT: You can use the specifications below to ‘reverse engineer’ the E-R Diagram.

Obviously, DO NOT wait to have the corrected ERD before you start this assignment.

Start with what you did submit and correct/adjust after you get Assignment Two back.

The database must have all the tables that were in your Assignment Two design.

hint, there should be six (6) tables in your database because you were told there were six entities in your ERD.

The fields will match the E-R Diagram attributes as provided in the Assignment Two (2).

The database properties for those supplied attributes from Assignment Two are given below.

if the field was a primary key, then it must be set as a primary key in the table.

if a field was nullable in the ERD then the data in the corresponding field in the database must be nullable.

if a field was unique in your E-R Diagram, then the field must be set to be unique in the database.

Follow the examples covered in class. Everything required to complete this assignment has been covered extensively (and very well) in class. Just follow those same simple steps.

If you do NOT submit the corrected E-R Diagram (with your name in the diagram as required in Assignment Two) in this assignment you will receive a zero (0) for Project One of Assignment Three.

(Project 1) PART 1:

a) Create a new table called “CUSTOMER” information using the following specifications:

Unique Customer ID that automatically created when a new item is entered note: this ID must start with YOUR initials:

so – if your name is Dolly Madision – every customer ID would start with DM example: DM0001, where “DM” are YOUR initials

DM0002, where “DM” are YOUR initials DM0004, where “DM” are YOUR initials DM0007, where “DM” are YOUR initials

hint: MUST be 2 initials and four digits (see examples above) must use Autonumber (Long Integer)

must use the Format Field Property to accomplish this

hint: if you do not know how to do this, a simple internet search will provide the answer …

NOTE: – very important:

if the Employee ID is used as a Foreign Key in another table:

that key must be of type Long Integer

the value entered will just be the number:

example: the foreign key is 1 where the Customer ID is DM0001 the foreign key is 2 where the Customer ID is DM0002 the foreign key is 4 where the Customer ID is DM0004 the foreign key is 7 where the Customer ID is DM0007

Customer’s Last Name – maximum 40 characters

Customer’s First Name – maximum 30 characters

Customer’s Street Address – maximum 30 characters

Customer’s City – maximum 30 characters

Customer’s Province – 2 characters exactly

display in all capital letters (i.e. ON or AB etc.)

hint: use the Input Mask Field Property

Customer’s Postal Code – 7 characters exactly format: A1B 2C3 (L9L N9N – L: letter 9: number) hint: use the Input Mask Field Property

Customer’s Phone Number – maximum 10 characters

stored as: 5195552323 (no brackets or dashes)

Customer’s Payment Method (Credit Card)

Credit Card (Yes/True) -or- Cheque [i.e not Credit Card] (No/False) indicates CREDIT CARD (yes or true) or CHEQUE (no or false). (hint: is there a data type that allows ONLY a yes –or- no value?)

Create a new table called “PRODUCT” information using the following specifications:

Unique Product ID that is NOT automatically created when a new item is entered note: this ID must start with ANY alphabetic character followed by 4 digits:

the letter MUST be a capital letter example: K-9345

F-0302 X-3000 F-0022

example: L-9999 – where L means a capital letter and 9 means a number

dash is required as part of the input mask

use the input mask Field Property

NOTE: – very important:

if the Product ID is used as a Foreign Key in another table:

that key must be of type Text (String)

the value entered will just be the letter and the number (no dash):

example: Foreign key will be K3433 where the Product ID is K-3433 L0090 where the Product ID is L-0090

P0300 where the Product ID is P-0300

2) Product Name – maximum 150 Characters

Product Classification – maximum 70 characters

(i.e. shirt, novelty, edible, pillow, pant, shoes, etc.)

Product Retail Cost – stored as currency

Product Size – stored as one of three values: ‘Small’, ‘Medium’ or ‘Large’ (“but my product does not come in small, medium or large???”

That’s fine, don’t worry about it. Use this anyway.

This field MUST be filled with only Small, Medium or Large)

Product Shipping Weight – stored as a number with one decimal place only.

remember – the Field Name will have the measurement type as part of the name (i.e. ProdWeight-in-Kilograms)

Create a new table called “INVOICE” information using the following specifications:

Unique INVOICE ID that is NOT automatically created when a new item is entered note: this ID is made up of numbers only, but can start with zero (0):

example: 6567

0037

100200

note: make this a reasonable maximum length (less than 20).

Invoice Date:

Date (short format) when this invoice was created.

Invoice Total – NOT stored as currency

stored as a number with two (2) decimal places

Invoice Status – stored as one of three values: ‘New’, ‘Shipped’ or ‘Paid’

Create a new table called “EMPLOYEE” with the following specifications:

Unique EMPLOYEE ID – Integer Value (DO NOT use AutoNumber)

Employee’s Last Name – maximum 40 characters

Employee’s First Name – maximum 30 characters

ALSO: You MUST include any other tables and fields in your ERD

hint: foreign keys and connector tables.

(Project 1) PART 2: REFERENTIAL INTEGRITY

You must build all the relationships described in your diagram. You must use the Relationships Database Tool in MS Access to enforce the relationships as demonstrated in class.

You must fill in the tables with example data of at least four (4) records for each and every table.

Your name must be the name of the first Employee.

You are allowed to make up the names of the other EMPLOYEEs, as well as the PRODUCTs and the CUSTOMERs.

The PRODUCTS should be created to appear valid and should make sense in the context of your other data.

Complete the above as required saving the database in your “Business” database. i.e youraccountname_Business.accdb (or .mdb for earlier versions)

(Project 1) PART 3: NORMALIZATION

Normalization is the process of structuring a relational database in order to reduce data redundancy and improve data integrity.

The database created to the specifications above in part 1 contains three (3) fields in two (2) separate tables that need to be normalized.

Create an MS Word document and complete the following question pertaining to the database you created in Part 1 above.

1.) Identify the two tables and the field(s) in each table that needs to be normalized.

(for example:

table: CUSTOMER – field: Province ) – note – this is NOT the correct answer!

hint: it is NOT in the CUSTOMER table or the EMPLOYEE table.

That is it. You do NOT have to actually change or Normalize the actual database.

Just identify (write in your MS Word document) the tables and fields that need to be Normalized.

Yes, that means you will submit the MS Access database exactly as specified and exactly as you designed in your E-R design.

Yes, this means you do NOT change, add tables or edit in any way, the database you created for Project 1 – Part 1.

Yes, you are only being asked to identify (name) the fields and the tables that would require change.

You do NOT actually make these changes.

You will put this written answer into the same document that you will use to complete Project Two (2) below.

This means you only need to submit one (1) and only one (1) MS word document.

This document will contain your answers to Project 1 – Part Three AND your answers to Project Two.

Yes, this means you add the two parts together into one document (Project 1 – Part 3 AND Project 2).

You put both into one and only one document.

Yes, this means you do NOT submit two MS Word documents, only one.

Project 2: Information Systems Questions about Your Company

In the MS Word document you created for Project 1 – Part Three above, complete the following questions pertaining to the business you described in Assignment One (1).

Each answer must be comprehensive (more than one sentence). Each answer requires at least a couple of sentences. (i.e. what is being graded is the quality of your answer, not the quantity. ‘Brevity is the soul of wit’. It is expected that some thought and explanation is included in this section. BUT, an intelligent answer is required. If you just type in something just to complete the assignment, then your grade will reflect the amount of effort and thought you put into each answer.)

1.) Identify which of Porter’s Five Forces might influence your company the most and why.

2.) Which competitive strategy (Cost + Differentiation) does your company position itself any why.

The format of this document should be identical to format you used in Assignment One (1).

Place your name, followed by the company name at the top.

Fill in the required information after.

At the end of the document, include your name, Student number and Western ID (the first part of your Western email (i.e. if your email is – ibrai2328@uwo.ca your ID will be – ibrai2328)

Formatting is not important as long as the document is easy to follow:

This document must be a Word file saved and submitted as a .doc (or .docx) file

The name must be a combination of your Western Account Name and the name of your company. The file name must be youraccountname_companyname_A3.doc (or .docx)

example (from above) ibrai2328_MaggicSoftware_A3.docx

Submission Instructions:

You must upload and submit, via the Assignment Section in the CS1032 Web Site, ALL of the following three (3) files:

youraccountname_CORRECTED_ER_Diagram.dia youraccountname_Business.accdb (or .mdb for earlier versions) youraccountname_yourcompanyname_A3.docx (or .doc for earlier versions)

The corrected Entity-Relationship Diagram must follow the standard of Assignment Two.

it MUST be a .dia file

it MUST have your name, Western UserName and Western Student Number in the diagram.

It is your responsibility to ensure the files have been submitted in OWL.

Please check and make sure you have received the confirming email and then check that the three

(3) files (you must submit three (3) Files for this assignment) have been uploaded correctly.

You must do both Projects in this assignment. This is Assignment Three, comprised of two (2) projects, Project 1 and Project 2.

Both projects are to be completed and submitted. There was confusion on Assignment One and Assignment Two regarding what was required.

NOTE: ‘I did achieve a perfect 86 out of 86 on my Assignment Two E-R Diagram. Should I submit an E-R Diagram anyway, even though it was perfect and did not need corrections?’

ANSWER: YES!! To make sure you do not get deducted for not submitting three files, you must submit the ERD.

Remember: Do your own work. You will need to know how to perform these tasks on the exam.

Remember: youraccountname is the part of your UWO email that is before (to the left of) the @ sign.

example:

IF email is: ibrai2328@uwo.ca

THEN youraccountname is: ibrai2328

START NOW ! – Although this is very doable, it is not a trivial task.

GIVE YOURSELF ENOUGH TIME !

… and finally – REMEMBER to use the correct email specifications

(review the Course Outline and/or the three reminders in the Announcements)

Good luck and have fun with this…
