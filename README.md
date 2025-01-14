# CricBoss
**Version 1.0.0**

It's a web based platform. The goal is to make a list of best players for any cricket academy.

# About
**CricBoss** is a web based system. Aiming for various cricket academies, the goal of this project is to make a web platform which will sort out the best list of players of a certain organisation. **CricBoss** is made for the cricket academies so that they can have the best possible team for their upcoming matches.
It can sort out the best players of the three cricket fields - **Batsman, Bowlers**. The list results in a sorted list of players depending on their performance.

So, one only needs to give the data of their corresponding players and they can easily find out their best playing team.

# Features
- Sorted list of top batsman
- Sorted list of top bowlers
- Database to store the records of players
- User friendly interface
- Simple and easy to use

# Instructions
**CricBoss** is very to use as it's a user friendly application. For any academy that wants to use its features, the instructions are
- Register your academy
  - Input all the information wanted
- Register your players
  - Input all the information of the players
- Update the status and records of the players regularly
- Click the top batsman or top bowlers to find the best list
---

# How it works
**Cricboss** registers the academies and registers the players of that academy under its name. All of those data are stored in a database. The database is regularly updated when the player data is updated for regular match. CricBoss uses statistical analysis to find the following parameters - `Batting Average` and `Strike Rate` for batsman, and `Bowling Average`and `Economy`For bowlers. Based on these parameters using statistical analysis a sorted list of the top batsman and bowlers are given.

# Codes
## Front End
For front end `Javascript`, `HTML` and `CSS` are used. `HandleBars` were used as rendering engine.
## Back End
`MySQL` is used for making the database and tables. All the records are stored in this database.
All the backends API were build using NodeJs and ExpressJs.




![Preview](https://github.com/PulockDas/Player-Selection/blob/main/Screenshot%20(139).png)
![Relational Database](https://github.com/PulockDas/Player-Selection/blob/main/Screenshot%20(9).png)


# How to run it(for educational purposes)
1) Install NodeJS and npm 
2) Install XAMPP
3) Start MySQL and Apache from XAMPP and create database and tables(given in app.js)
4) Navigate to your player-selection directory from terminal and type `npm start`
5) Open a browser and go to port `5001`. Boom! 

# Future Goals
The website is a prototype. Future goal use to test it and host it in the server. Also update and build new versions

---
For any inquiry please contact
1. [Pulock](https://www.facebook.com/pulockdas.das)
1. [Maraz](https://marazmia.github.io/Personal_Website/)
1. [Ohee](https://www.facebook.com/profile.php?id=100007797257515)
---

## License and Agreement
© Pulock Das Kamol, Maraz Mia and Sefat Ibne Kamal, Department of Software Engineering, [Shahjalal University of Science and Technology](https://www.sust.edu/)
