# 📌 Bucket List Tracker (AWS Amplify + React + AppSync)

This project is the final capstone in the AWS Amplify learning series. It demonstrates how to build and deploy a full-stack **serverless bucket list application** using AWS Amplify, React, GraphQL, and DynamoDB.

---

## 🧾 Overview of Project ☁️

The goal of this project is to deploy a "Bucket List Tracker" application on AWS Amplify. This will take longer than the other projects but will teach you how to build a fully functioning, scalable serverless app from frontend to backend.

---

## 🛠 Services Used

| AWS Service     | Purpose                                                                 |
|------------------|-------------------------------------------------------------------------|
| **AWS Amplify**  | Deployment of both frontend and backend (Hosting + CLI/Studio)         |
| **AWS AppSync**  | Serverless GraphQL API for CRUD operations                             |
| **GraphQL API**  | Fine-grained API that serves exactly the requested data                |
| **DynamoDB**     | NoSQL database for storing bucket list items                           |
| **S3 Bucket**    | Storage for user-uploaded images (e.g., photo proof of achievements)   |

---

## 🗺️ Architectural Diagram

This is the overall system architecture illustrating how each AWS service interacts:

![Architectural Diagram](https://github.com/Yuehan07/bucketlistapp/blob/main/Architectural%20Diagram.png)

---

## 🧑‍💻 Steps to be Performed

In this project, we go through the following key steps:

1. **Develop a bucket list tracker** in **React**
2. **Initialize a GitHub repository** and connect it to your local project
3. **Host the frontend** using **AWS Amplify Hosting**
4. Use **Amplify Studio or Amplify CLI** to:
   - Configure **user authentication** (login/signup)
5. **Create an AWS AppSync GraphQL API**
   - Define GraphQL schema
   - Integrate with **DynamoDB** for data storage
6. **Deploy the backend** via Amplify to handle business logic, storage, and authentication

---


## ✅ Final Result

Once completed, your app will look like this:

![Final Screenshot](https://github.com/Yuehan07/bucketlistapp/blob/main/BucketList%20Screenshot.png)

The frontend is fully functional, users can:
- Sign up and log in with Amplify Auth
- Add, delete, and update their bucket list items
- Persist their data via GraphQL and DynamoDB
- Upload and store images to S3

---

## 📌 Notes

- ✅ Hosted via Amplify Console with GitHub connected
- ✅ Backend infrastructure managed via Amplify CLI
- ✅ Responsive React frontend
- ✅ AWS Free Tier compatible
- ✅ Real-world deployment example for portfolio projects

---

## ✨ Author

Developed by [Yuehan Chen (Olivia)](https://github.com/Yuehan07)

If you like the project, consider starring 🌟 the repo!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
