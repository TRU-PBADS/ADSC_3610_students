# ADSC 3610 - Database Systems in Applied Data Science II - Syllabus
This course will introduce students to the fundamentals of non-relational databases, with a focus on MongoDB as the main platform. We will cover data modeling, CRUD operations, and advanced querying techniques using MongoDB and its integration in Python via Pymongo. The course then transitions to PySpark, covering distributed data processing, DataFrames, Spark SQL, and machine learning applications. In the final section, the focus shifts to data governance, ethics, and security, addressing key topics such as data quality management, privacy, legal compliance, and the ethical implications of AI.

## Learning objectives

- Understand the fundamental concepts of non-relational databases and their differences from relational databases.
- Gain proficiency in using MongoDB for data storage, retrieval, and manipulation.
- Learn to design and implement efficient data models in MongoDB.
- Master the basics of PySpark for big data processing and analytics.
- Perform data wrangling and transformation tasks using PySpark.
- Understand the principles of distributed computing and how they apply to PySpark.
- Grasp the key principles of data governance, compliance, and privacy, ensuring responsible and secure data management.
- Explore and address the ethical implications of AI and machine learning

## Schedule & office hours

Lectures every Tue, Thu, Fri from 9:30 - 10:20 AM in the computer lab OM 1241 at Old Main building.

Office hour: Thu 11:30 AM-12:30 PM at OM 1232. Please book your timeslot [here](https://calendly.com/quan3010/office-hour-with-quan)

## Communication
- For any **course-related questions**, such as lectures, assignments, exames, course logistics, please ask them under the discussion forum in Moodle.
- For any **individual-related questions**, such as academic concession, deadline extension, personal circumstances, etc., please email me at lnguyen[at]tru[dot]ca
- **Response time**: I will try our best to reply to your inquiries as soon as possible during the normal working hours (9AM-5PM Mon-Fri). If you send me a message outside of regular working hours, please expect a response on the next working day.

## Lectures

Please find the list of lecture, and the required readings below. This list will be updated frequently so please revisit to get the latest version. 

| Week no. | Week day | Date   | Topic                                                       |
|----------|----------|--------|-------------------------------------------------------------|
|        1 | Tue      |  Sep 3 | Introduction to noSQL database, [READINGS](https://www.mongodb.com/resources/basics/databases/nosql-explained)                              |
|        1 | Thu      |  Sep 5 | Introduction to MongoDB and the document model, [READINGS](https://www.mongodb.com/docs/manual/introduction/)              |
|        1 | Fri      |  Sep 6 | Setup MongoDB Atlas & connecting to a MongoDB database, [READINGS](https://www.mongodb.com/docs/atlas/getting-started/)      |
|        2 | Tue      | Sep 10 | Data modelling 1: types of data relationships, MongoDB rule |
|        2 | Thu      | Sep 12 | Data modelling 2: embedding, referencing, anti-schema       |
|        2 | Fri      | Sep 13 | MongoDB CRUD operations: Insert and Find                    |
|        3 | Tue      | Sep 17 | MongoDB CRUD operations: Replace and Delete                 |
|        3 | Thu      | Sep 19 | MogoDB CRUD operations: Modifying query results             |
|        3 | Fri      | Sep 20 | MongoDB Aggregation in Python                               |
|        4 | Tue      | Sep 24 | MongoDB Indexes                                             |
|        4 | Thu      | Sep 26 | MongoDB Atlas search                                        |
|        4 | Fri      | Sep 27 | Atlas Vector Search for LLMs                                |
|        5 | Tue      |  Oct 1 | Part 1: MongoDB review                                      |
|        5 | Thu      |  Oct 3 | Backup lecture                                              |
|        5 | Fri      |  Oct 4 | MIDTERM 1: Cover materials from week 1 - 4                  |
|        6 | Tue      |  Oct 8 | Introductino to PySpark                                     |
|        6 | Thu      | Oct 10 | Working with RDDs                                           |
|        6 | Fri      | Oct 11 | Introductin to DataFrames in Pyspark                        |
|        7 | Tue      | Oct 15 | Basic dataframe operations                                  |
|        7 | Thu      | Oct 17 | Spark SQL                                                   |
|        7 | Fri      | Oct 18 | Dataframe optimization techniques                           |
|        8 | Tue      | Oct 22 | Working with structured streaming                           |
|        8 | Thu      | Oct 24 | Machine learning with PySpark (MLlib)                       |
|        8 | Fri      | Oct 25 | Clustering and recommendation                               |
|        9 | Tue      | Oct 29 | PySpark best practices and case study                       |
|        9 | Thu      | Oct 31 | Backup lecture                                              |
|        9 | Fri      |  Nov 1 | MIDTERM 2: Cover materials from week 5 - 9                  |
|       10 | Tue      |  Nov 5 | Introduction to data governance                             |
|       10 | Thu      |  Nov 7 | MID-TERM BREAK                                              |
|       10 | Fri      |  Nov 8 | MID-TERM BREAK                                              |
|       11 | Tue      | Nov 12 | Data quality management                                     |
|       11 | Thu      | Nov 14 | Data privacy                                                |
|       11 | Fri      | Nov 15 | Data security fundamentals                                  |
|       12 | Tue      | Nov 19 | Data ethics                                                 |
|       12 | Thu      | Nov 21 | Legal and regulatory compliance                             |
|       12 | Fri      | Nov 22 | AI and ethics                                               |
|       13 | Tue      | Nov 26 | Data breaches and responses                                 |
|       13 | Thu      | Nov 28 | Future trends in data governance, privacy, and security     |
|       13 | Fri      | Nov 29 | Course conclusion                                           |

## Assessment overview

You are responsible for the following deliverables, which will determine your course grade:

| Assignment            | Note                                       | Weight | Date            |
|-----------------------|--------------------------------------------|--------|-----------------|
| Weekly worksheet x 10 | Open-book. Release on Mondays              | 20%    | Sundays 11:59PM |
| Midterm 1             | Closed-book, Moodle timed-quiz, 45 minutes | 25%    | Fri, Oct 4th, 9:30AM    |
| Midterm 2             | Closed-book, Moodle timed-quiz, 45 minutes | 25%    | Fri, Nov 1st, 9:30AM    |
| Exam                  | Closed-book, Moodle timed-quiz, 90 minutes | 30%    | TBD             |


## Weekly assignments

Every week, you will have a worksheet that is worth 2%. These low-stakes assignments consist of multiple choice questions and small exercises that help you consolidate your understanding of the materials and serve as a formative assessment. 

The worksheet will be distributed via Github classroom every Monday (except for midterms' weeks) and the deadline for each worksheet is the same Sunday of that week at 11:59 PM. 

## Mid-terms & exam

There will be two midterms and one final exam in this course.

The midterms are closed-book format, and they will take place on Moodle for the duration of 45 minutes. It will consist of a mix of multiple choice, fill in the blank, and open-ended questions. 

Midterm 1 will cover the materials from week 1-4
Midterm 2 will cover the materials from week 5-9

The final exam is closed-book format, taking place on Moodle for the duration of 90 minutes. It will consist of a mix of multiple choice, fill in the blank, and open-ended questions. 

The final exam will cover all the materials in the course. 

## Attendance, late assignments, academic concessions, academic accomodation

### Attendance

A registered student who does not attend the first two events (e.g., lectures/labs/ etc.) of their course(s) and who has not made prior arrangements acceptable to the instructor(s) may, at the discretion of the instructor(s), be considered to have withdrawn from the course(s) and have their course registration(s) deleted.

Please refer to [TRU's attendance policy](https://www.tru.ca/__shared/assets/Policy_ED_03-135351.pdf). In addition, we will take attendance during class via Moodle's QR code.

In the CS department, you need to get **at least 75% attendance** for passing any course. 

### Academic concessions
If you encounter situations that may impede your ability to meet course requirements—such as illness, family emergencies, or other significant life events—please notify the instructor **at least 24 hours before deadline**. Academic concessions, including extensions or alternative assessments, will be considered on a case-by-case basis. You may be required to provide documentation to support your request. Concession requests after the deadline has passed will likely be refused. 

### Late Assignments
Assignments are expected to be submitted on time. Late submissions will incur a penalty of 25% per day, up to a maximum of 75%. After 3 days, late assignments will no longer be accepted and will receive a grade of zero. Extensions may be granted in exceptional circumstances, provided that you contact the instructor before the deadline.

### Accessbility
Students registered with the Accessibility Services who require accommodations must provide their Letter of Accommodation to the instructor as soon as possible. This letter will outline the necessary accommodations to ensure an equitable learning environment. Please ensure that this is done early in the term to facilitate timely arrangements.

## Policy on the use of generative AI

Please refer to TRU's guideline on the use of generative AI tools such as chatGPT or Copilot in this course. 

https://libguides.tru.ca/artificialintelligence
