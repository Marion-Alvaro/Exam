Technical Exam
Build a Full-Stack Web Application with Authentication & CRUD Operation

How It's Made:
Tech used: ReactJS, NodeJS/Express, XAMPP (MySQL)

Frontend was made using ReactJS with Tailwind CSS to achieve a secure and responsive UI/UX, for Backend NodeJS/Express for verfying, comparing, checking authentication and tokens, as for XAMPP (MySQL) it is used for the database connection and saving the inputs from the front end

Improvements:
CRUD Operations was not implemented properly as it was having troubles with it
Deployment to test if it is working live

How to run:

Download XAMPP
Once XAMPP Control Panel is open, kindly click start on apache and MySQL
After kindly click admin on MySQL
It will take to an admin page and you will see a new with a plus sign and a database icon
Click that and name the database "authentication", it has 4 rows named id, username, email and password
id click on auto increment and primary key, as for username, email and password turn it into varchar 30, 40, 150.
Clone repository then open through VS Code
Once, VS Code is open kinly pull up terminal and add another terminal. The first terminal you will have to type cd web, npm install -D tailwindcss@3, npm install axios react-router-dom tailwindcss postcss autoprefixer.
The second terminal type cd server and npm start.
Once the the server is running go back to the first terminal and then type npm run dev
It should be up and running
To exit the just q+enter on the first terminal
