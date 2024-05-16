# Implementing Distributed Database with MarkLogic Server
Source code, project report and report slide for **Distributed Database Subject - HCMUIT**

## Contributors
Tran Kim Thanh - 21522605
Tran Minh Hoang - 21522101
Vo Thanh Tu - 20520839

## What is MarkLogic Server?
![MarkLogic Server](https://th.bing.com/th/id/OIP.k2fIaiRY5kWCVn9Nt2Fp6gHaDt?rs=1&pid=ImgDetMain)
MarkLogic Server is a leading distributed database management system that is gaining significant attention in the field of distributed databases. In the modern environment, the exponential growth of data has presented new challenges for storing, retrieving, and processing complex data. MarkLogic Server has emerged as a powerful and flexible solution to address these challenges.

  

With its document-oriented architecture, MarkLogic Server allows for storing and retrieving data in a natural and flexible manner. Data is stored as documents such as XML, JSON, or text, rather than in the traditional table and row model. This enables users to store and retrieve complex data easily and efficiently.
# About our work

## Problem statement

A library needs to manage thousands of books, information about authors, book categories, and the borrowing and returning records of readers. The system must be designed to ensure efficient data management, quick search capabilities, and high performance when hundreds of users access it simultaneously.

## Requirements

- **Book and Author Information Management**
> The system needs to store information about books, including titles, authors, genres, descriptions, and detailed information about authors (name, country, year of birth, etc.). 
> 
- **Book Categories and Borrowing/Returning Management**
> The system must track information about book categories, the number of available books, and details about borrowing and returning books, including the borrowed books, borrowing date, due date, etc. 

- **Quick Search and Data Querying**
> Fast search and data querying capabilities are crucial for users to easily find books by title, author, or genre.
> 
- **Data Consistency and Synchronization**
> Data about books and borrowing/returning information needs to be synchronized and consistently updated across all nodes in the distributed system.
