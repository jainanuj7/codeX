# codeX
An interactive web app for competitive programming (tricky MCQ questions with a timer) with a live leader board functionality.
It contains three level of problems viz easy, intermediate and hard.
Total time duration is 30 minutes.
The question bank is large enough to make it impossible to answer them all before time ends.
Starting off with easy level, if you answer correctly, questions will be upgraded to next level otherwise if you answer incorrectly, level will be downgraded. Higher the level, more points you get for a correct answer.
This app was developed by TEAM CODE-E-SALSA as a part of Sinhgad Karandak - Techtonic 2017. 

# How to use?
1. Start an Apache and MYSQL server(through XAMPP or similar software)
2. Create a database with name 'code_e_salsa' and import data from code_e_salsa.sql
3. Browse localhost:port_no to start
4. Sign up a new account & log into start the test
5. Browse the live leader board from http://localhost:port/codex/admin_panel and select leaderboard
5. Main database config can be tweeked from /includes/misc.inc
