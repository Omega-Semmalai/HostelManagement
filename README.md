# HostelManagement
### **System Requirements:**

1. **Node.js**: v16.x.x or later  
   [Download Node.js](https://nodejs.org/en/download/)
  
2. **MongoDB**: v5.x or later (Local or Cloud-based MongoDB instance)  
   [Download MongoDB](https://www.mongodb.com/try/download/community)  
   [MongoDB Atlas (Cloud)](https://www.mongodb.com/cloud/atlas)

3. **Angular CLI**: v14.x or later  
   Install via npm:  
   ```bash
   npm install -g @angular/cli
   ```  
   [Angular CLI Documentation](https://angular.io/cli)

4. **Express.js**: v4.x or later  
   Install via npm:  
   ```bash
   npm install express
   ```  
   [Express.js Documentation](https://expressjs.com/)


---

### **Steps to Setup the Hostel Management System**

1. **Download the project zip file**

   👉 [Download Zip File](https://github.com/Omega-Semmalai/HostelManagement)  
   
   After downloading, extract the contents of the zip file.

2. **Open the project in Visual Studio Code**

   👉 Navigate to the extracted folder and open the `hostelManagement` folder in **Visual Studio Code**.

3. **Create the `.env` file**

   👉 In the `hostelManagement` folder, create a `.env` file with the following content:

   ```bash
   NODE_ENV = development
   PORT = 4050
   MONGODB_URI = mongodb://localhost/hostel
   MONGOOSE_DEBUG = true
   JWT_SECRET = 29fe02c1-7de9-493a-b3c5-d33e56555a98
   ```

4. **Install dependencies**

   👉 Run this command in your terminal to install the necessary dependencies:

   ```bash
   npm install
   ```

5. **Start the project**

   👉 To start the application, use this command:

   ```bash
   npm run start
   ```

6. **Start the server**

   👉 To start the server, run this command:

   ```bash
   npm run server
   ```

---

