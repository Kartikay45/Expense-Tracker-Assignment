<h1 align="center">My Wallet-🌟 Expense tracking app 🌟</h1>

<p align="center">
  <img alt="Static Badge" src="https://img.shields.io/badge/Spring%20Boot-darkgreen?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/React.js-blue?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/mysql-red?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/css-purple?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/jwt-orange?style=for-the-badge">
</p>

## Table of contents

1. [Descripiton](#description)
2. [How to run?](#how-to-run)
3. [Screenshots](#screenshots)

## Description

- Developed a full-stack expense tracking web application using Spring Boot, React.js, and MySQL, facilitating seamless management of day-to-day finances.
- Implemented multi-role functionality with user authentication, enabling secure access for both users and administrators, with features such as sign-in, sign-up, password reset, and email verification.
- Developed intuitive user dashboards, transaction management, upcoming/recurring transactions tracking, monthly summaries, and statistics, budget management.
- Developed categories, users and transactions management for administrators.
- Implemented management capabilities including search, filter and pagination.

## How to run?

### Step 1: Fork and Clone the Repository

1. Fork the repository to your GitHub account.

2. Clone the forked repository to your local machine.

```sh
git clone https://github.com/<your-username>/Fullstack-Expense-Tracker
```

### Step 2: Setting up e-mail and database configurations

- Configure the following credentials in the [`application.properties`] file.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/YOUR_DATABASE_NAME
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.mail.username=YOUR_USERNAME
spring.mail.password=YOUR_PASSWORD
```

### Step 3: Run the backend.

- Run the backend application. It will automatically create the required tables. 
- Add some custom data manually in the [categories] table for both [type] `expense` and `income`.
- To start as admin, Insert a new user manually with role admin in [`users`] table.

### Step 4: Run the frontend

1. Navigate to [frontend direcory](.
```
cd ./frontend
```

2. Install dependencies.
```
npm install
```

3. Run the app.
```
npm start
```

Access the application at [`http://localhost:3000/`](http://localhost:3000/).
To get started create a new account using your email.

### Screenshot

![323459796-f58e2e13-7db4-439a-b371-ce9b6e5838c7](https://github.com/user-attachments/assets/bc39ad60-88c2-43dd-8019-98295f20b223)
![323459804-dbcfdbd2-d515-4197-b5ff-11ba0aed2dcf](https://github.com/user-attachments/assets/9a888586-ac31-4ddf-b803-64268dc52a0f)
![324422041-8f8bef4e-6735-464f-a180-f2bc17633b1b](https://github.com/user-attachments/assets/8d579e34-edce-414e-b00d-26899d25ec2f)
![324421983-ed01d05e-cead-43c5-8959-6b64615fee43](https://github.com/user-attachments/assets/d725620b-ba60-4bb3-813e-f4339bd9da8a)
![324421868-a8e6d65b-626f-493e-922d-dd7c26d8294c](https://github.com/user-attachments/assets/9400b6e6-faaf-47f8-b6c7-0f9e0faa8bf9)
![324422170-7e43cb13-6187-4af0-8900-66afef908f66](https://github.com/user-attachments/assets/43713cfc-057c-415b-81a2-8a3b9efd86a1)
![323460242-06454812-f542-4404-b9bf-e7d9b96b043d](https://github.com/user-attachments/assets/b1da2144-076f-43f3-814e-59265c182534)







