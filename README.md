# node-app-cicd
# 🚀 Jenkins CI/CD Pipeline for Node.js App Deployment

This project demonstrates a **Jenkins CI/CD pipeline automation** setup to fetch a Node.js application (`app.js`) from a **GitHub repository**, build and test it, and automatically deploy the code to a **Node.js server**.


## 📁 Project Overview

This Jenkins pipeline automates the following process:

1. **Pull Source Code** – Clone the Node.js project from GitHub.
2. **Install Dependencies** – Install required Node packages using `npm install`.
3. **Build & Test** – Run automated tests or linting if configured.
4. **Deploy** – Deploy the updated application code to a remote Node.js server using SSH.
5. **Start/Restart Server** – Start or restart the Node.js app using `pm2` or `node`.


## ⚙️ Project Structure

jenkins-node-cicd/
├── app.js
├── package.json
├── Jenkinsfile
└── README.md

## Steps 
1. lauching 2 ec2 instances
(node-server)
![Node-server](images/node3.PNG)
(Jenkins-server)
![Node-server](images/node4.PNG)
2. create an nodejs file, jenkinsfile,
 ![Node-server](images/node6.PNG)

3. add and push the code to GIthub
    ![Node-server](images/node5.PNG)
4. setup Jenkins and build the project
   ![Node-server](images/node2.PNG)

5. Deployement ![Node-server](images/node1.PNG)



