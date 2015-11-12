# LineDB

This is a repository for LINE programming project with 

enwiki-20150901-page.sql
enwiki-20150901-pagelinks.sql

Need to make a PageRank. 

### Original Requirements:

Test1. Wikipediaの各エントリのPageRankスコアを計算するプログラムを作成してください。
　　PageRankを計算するためのデータは下記のファイルを利用すること。

Test2, Test1.で計算したスコアの上位10名を出力するプログラムを作成し、
　 10名の氏名を答えてください。10名の氏名は、課題4の資料に記載してください。

Test3. Test1, で作成したデータをつかった，おもしろいサービスを作成してください。

Test4, Test1～3 のプログラムおよびサービスの特徴や工夫した内容をまとめて，
PowerPoint、またはPDFの資料として提出してください。
　 Test2の「10名の氏名」は、この資料に記載してください。
　 
　 
### Translation for me:

Test 1 
Create a program that calculates each entry of Wikipedia PageRank Score.

Test 2
Create a program that outputs 10 people with highest scores from test 1, and give their names. 
Include their names in data youre submitting in test 4.

Test 3
Create an interesting service using data from Test 1.

Test 4
Create a summary of programs and services (where you put into work and creativity, interesting points) and submit them as PDF or powerpoint. 
Put the names of 10 ppl here


## What I'm doing

Using JDBC to write SQL queries. Requires Java 1.8 and Connector/J. I will eventually upload the sql files onto a Digital Ocean droplet and run mysql from a remote server so that the database files aren't required and the script can be run locally by connecting to the droplet sql server.
The service will then hook into this server and tables to parse the data. Maybe I'll even have the java code run on the server and just return the useful into to the application.
The application will be written in Meteor.

## Steps

1. Get JDBC -- DONE
2. Get JDBC to hook to local mysql -- DONE
3. Create table -- DONE
4. Try loading table from MySQL command line to check the table structure
5. Figure out what the hell is contained in this data in the first place</br>
...</br>
X. Create Meteor Application</br>
Y. Set up remote server</br>
Z. PDF with relevant info</br>
