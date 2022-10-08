# E-commerce Back End

With all that has gone on in the world in the last few years, our way of life has shifted. We try to maintain our distances, clean our hands and often-touched surfaces, and honestly, we just like being in sweatpants. All these reasons have boosted e-commerce! With more business turning to e-commerce, we need a fast, efficient, and reliable way to easily access our inventories, create new inventory, update our inventory, and delete inventory once it's sold out! Enter: our newly developed back-end application! This will help you access your data quickly and efficiently so you can get back to focusing on what's really important.

In building this application, I re-learned the importance of organization! It is key to keeping all files, routes, seeds in functioning fashion! It also makes it easy to access and address when there are bugs to be found. I learned that to easily find linked files, you can right click on the route, and go to "Go to Definition" to get to nested routes easily and cleanly. I learned that these databases that we access everyday from our smartphones are quite complex and easy to break. I learned there are many ways to do one action.

## Table of Contents

-[Installation](#installation)

-[Usage](#usage)

-[Screenshots](#screenshots)

-[Resources](#resources)

-[License](#license)

-[Walkthrough-Video](#walkthrough-video)

## Installation

npm i mysql2

npm i express

npm i sequelize

npm i dotenv

Insomnia Core

## Usage

You will possibly need to add your own MySQL username and password to initiate MySQL:

mysql -u root -p

Then you will be prompted to enter your password.

Open Integrated Terminal, run command:

node seeds/index.js

Can check "MySQL Workbench" to see data populated in tables.

Then run command:

node server.js

### Screenshots

1) Initiating schema from MySQL:
![Screenshot1](https://user-images.githubusercontent.com/108099192/194694541-61dbce6c-4dff-4627-80e9-0d1805a18ad3.png)

2) Seed database from command line:
![Screenshot2](https://user-images.githubusercontent.com/108099192/194694543-fc1c9ca2-5559-402f-836f-715659078d95.png)

3) Databases as seen in MySQL Workbench:
![Screenshot3](https://user-images.githubusercontent.com/108099192/194694544-2d6a6172-be8e-493c-b575-103bc2cfa6a1.png)
![Screenshot4](https://user-images.githubusercontent.com/108099192/194694545-b74e6dc8-48a8-4f33-9706-ed21770ee650.png)
![Screenshot5](https://user-images.githubusercontent.com/108099192/194694547-9e02904d-41ba-423a-931a-0427dd5b9a4e.png)
![Screenshot6](https://user-images.githubusercontent.com/108099192/194694548-31f6cadc-305a-4a88-8c6e-19482e944847.png)

4) GET all categories:
![Screenshot7](https://user-images.githubusercontent.com/108099192/194694549-6c4275cc-875e-454f-a56f-727be4f28dda.png)

5) GET one category by ID:
![Screenshot8](https://user-images.githubusercontent.com/108099192/194694550-af7fe5db-1277-46e6-8d45-d69de2cf0df8.png)

6) POST/create a new category: 
![Screenshot9](https://user-images.githubusercontent.com/108099192/194694551-de5f596b-a4a5-4446-9001-e65024f8c23a.png)

7) PUT/update a category:
![Screenshot10](https://user-images.githubusercontent.com/108099192/194694553-c857e5d4-f379-4719-8674-eb4164bb119a.png)

8) DEELETE a category:
![Screenshot11](https://user-images.githubusercontent.com/108099192/194694554-1dbb99f4-7cc9-4622-b1d0-76138718ed55.png)

## Resources

- Hoang, Andrew. "Module 13 Challenge Speedrun." <https://zoom.us/rec/play/MIK9GK09dZvKPpV27VtXl40XQBPiq2Tg8mGgdjMQXRSJvOU6NZ9EUXjjLNyKBouPgFGpHFmclcWiQqvK.Ut6QDWbJCqvaV09P?continueMode=true&_x_zm_rtaid=x4ubyAg3TPiXSWIwtho35A.1665201824585.e92c3a150ae6a3220da5dd800694ba77&_x_zm_rhtaid=90>. Date accessed: October 7, 2022.
- "Associations." <b>Sequelize.org</b>. <https://sequelize.org/v3/docs/associations/#foreign-keys_1>. Date accessed: October 7, 2022.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
This project is licensed under the terms of the MIT license.

## Walkthrough Video

<https://drive.google.com/file/d/1egf-X3DTYrRZB382eycqI_W1CP6T4a-H/view>