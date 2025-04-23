Celestial Bodies Database
Description
The Celestial Bodies Database is a project that stores and organizes data on various celestial bodies such as stars, planets, moons, and galaxies in an SQL database. This database allows users to efficiently store and query important attributes of celestial bodies like mass, size, distance, and more. It serves as a comprehensive resource for astronomers, space enthusiasts, and anyone interested in the study of space.

Features
Comprehensive data: Includes detailed information about celestial bodies like stars, planets, moons, and galaxies.

SQL queries: The database supports complex queries to retrieve information such as the mass, size, and distance of celestial bodies.

Easy to use: The SQL file can be easily imported into any MySQL database for use.

Installation
To get started with this project, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/Shehani688/celestial-bodies-database.git
Navigate into the project directory:

bash
Copy
Edit
cd celestial-bodies-database
Import the SQL file into your MySQL database:

bash
Copy
Edit
mysql -u <username> -p < universe.sql
Replace <username> with your MySQL username. You’ll be prompted to enter your password.

Start using the database: You can now query the database using SQL commands to explore the data.

Usage
Once the database is set up, you can run various SQL queries to explore the data. Here are a few example queries you can try:

To find all planets with moons:

sql
Copy
Edit
SELECT * FROM planets WHERE has_moons = 1;
To find the stars within a certain distance from Earth:

sql
Copy
Edit
SELECT * FROM stars WHERE distance < 1000;
To find galaxies by size:

sql
Copy
Edit
SELECT * FROM galaxies ORDER BY size DESC;
Contributing
Contributions are welcome! If you would like to contribute to the Celestial Bodies Database, follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature-name).

Commit your changes (git commit -m 'Add feature').

Push to the branch (git push origin feature-name).

Open a pull request.

License
This project is licensed under the MIT License.

Contact
For any questions or issues regarding this project, feel free to reach out to:

Shehani Rasanjalika Gunasekara

Email: rasanjalikagunasekara@gmail.com

