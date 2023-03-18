# COLUMNFAMILY
HBase is most effectively used to store non-relational data, accessed via the HBase API. Apache Phoenix is commonly used as a SQL layer on top of HBase allowing you to use familiar SQL syntax to insert, delete, and query data stored in HBase.

HBase is a column-oriented non-relational database management system that runs on top of Hadoop Distributed File System (HDFS). HBase provides a fault-tolerant way of storing sparse data sets, which are common in many big data use cases.

In this stu_details table there are three columns named bio, marks and details of the students in three rows
![WhatsApp Image 2023-03-18 at 10 04 33 PM](https://user-images.githubusercontent.com/114007429/226120503-08c043f4-b2a7-4945-8554-b5904d8d5753.jpeg)


In the first row I updated the values of row no 01 by changing their mobileno of bio, Then In the second row I inserted the CGPA of marks column using put keyword. finally I deleted the last row's MQ/GQ of details using delete keyword.
![WhatsApp Image 2023-03-18 at 10 09 47 PM](https://user-images.githubusercontent.com/114007429/226120693-7d01720d-c09b-45e7-822b-487a06f720ee.jpeg)

To make the above operation I used the following keywords:
     put- put keyword is used to insert and update the values of the student in the table 
     scan- scan keyword is used to display the entities of the table we have created
     get-  get keyword is used to read the values of the table
     delete- delete keyword is used to delete the value as well as the table
     
     Pictorial representation of CRUD operation in student details are attached in the issues file(3 files).

In conclusion, column-family databases are a powerful tool in the world of data management, and their popularity is only expected to grow as organizations continue to generate and collect more and more data.

