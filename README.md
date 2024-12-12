# **MediLink**  
MediLink is an innovative, **AI-powered** healthcare platform designed to assist patients in identifying diseases and connecting with the right healthcare professionals. Leveraging advanced AI algorithms, the website incorporates features such as a System Checker, ensuring accurate guidance for medical concerns based on user-reported symptoms. The platform also provides essential services like 24/7 medical support, emergency assistance, OPD facilities, medical counseling, and specialized treatments for critical conditions, including cancer and bone marrow transplants.

With a strong commitment to improving healthcare delivery and promoting community well-being, MediLink blends patient-centric care with cutting-edge medical technology and artificial intelligence to deliver superior health outcomes. By harnessing the power of AI, MediLink ensures that patients receive personalized and precise recommendations, transforming healthcare experiences for both patients and providers.

---
## **Mission and Objectives**  
### **Goal:**  
By the end of the course, participants will develop a fully functional health care website using modern full-stack technologies

### **Objectives:**  
- Expand services to meet customer needs on a financially sustainable basis.
- Ensure a safe and therapeutic environment for all patients, staff, and visitors.
- Enhance patient satisfaction and improve healthcare efficiency.
- Foster systematic feature implementation, starting with foundational functionalities like User Registration and Login and progressing to advanced tools such as System Checker AI and Appointment Scheduling. 

---
## **Technology Stack**  
### **Technology Stack for MediLink**

#### **Frontend**
1. **HTML**  
   - **Purpose**: Provides the foundational structure of the web application.  
   - **Use Case**: Used for creating static and semantic elements of the pages, such as the homepage, navigation bar, and form inputs.  

2. **CSS**  
   - **Purpose**: Styles the web application to ensure a visually appealing and responsive user interface.  
   - **Use Case**: Enhances the design of components, including buttons, headers, and layouts, ensuring a professional look.  

3. **JavaScript**  
   - **Purpose**: Adds interactivity and dynamic functionality to the application.  
   - **Use Case**: Enables features like dynamic form validations, navigation enhancements, and animations on pages.  

4. **jQuery** (optional)  
   - **Purpose**: Simplifies DOM manipulation and event handling.  
   - **Use Case**: Facilitates features like AJAX requests, event handling for UI elements, and interactive form submissions.  

---

#### **Backend**
1. **Spring Boot**  
   - **Purpose**: A robust framework for building RESTful APIs and managing backend logic efficiently.  
   - **Use Case**: Manages user authentication, article retrieval, appointment scheduling, and System Checker logic.  

2. **Spring Data JPA**  
   - **Purpose**: Simplifies database interaction by abstracting CRUD operations.  
   - **Use Case**: Handles database operations for users, articles, and appointments in MySQL.  

3. **Spring Security**  
   - **Purpose**: Provides secure authentication and authorization mechanisms.  
   - **Use Case**: Protects endpoints and ensures role-based access control for the backend APIs.

---

#### **Database**
1. **MySQL**  
   - **Purpose**: A reliable relational database for managing structured healthcare data.  
   - **Use Case**: Stores user information, appointment details, article content, and symptom-related data for the System Checker.

---

#### **AI and ML Integration**
1. **ChatGPT or OpenAI API**  
   - **Purpose**: Leverages natural language processing to analyze symptoms and provide healthcare recommendations.  
   - **Use Case**: Powers the AI-driven System Checker feature to classify symptoms and recommend doctors.  

---

#### **Deployment**
1. **AWS**  
   - **Purpose**: Provides a secure and scalable platform for backend hosting.  
   - **Use Case**: Hosts the Spring Boot backend for handling API requests and data management.  

2. **Vercel**  
   - **Purpose**: Optimized for deploying modern static websites and serverless frontend frameworks.  
   - **Use Case**: Hosts the frontend (HTML, CSS, JavaScript) for seamless and fast user interaction.  

--- 


*MediLink* is developed using the following technologies:   
- ![image](https://github.com/user-attachments/assets/0914ab9a-4b4c-4d57-ae3c-5a2066bda966)
![image](https://github.com/user-attachments/assets/794b4289-6d04-439e-80ab-ab2be6c924be)
![image](https://github.com/user-attachments/assets/65a57468-b9b7-49c3-bbdc-81379fb5f9ef)
![image](https://github.com/user-attachments/assets/3d105cf6-0620-4441-82a9-f18c77c9117c)
![image](https://github.com/user-attachments/assets/64e0373e-2597-4569-b6f6-a570f56b4b8d)
![image](https://github.com/user-attachments/assets/394ebde4-ff9b-49d8-8396-7f7ffe206afc)
![image](https://github.com/user-attachments/assets/098a1488-ca5b-4c29-8b8e-ea3be28ec96f)
![image](https://github.com/user-attachments/assets/e6f87067-3084-46af-afa4-5b88b7eaca10)


---
### **Workflow Overview**
This section illustrates the complete workflow for users and administrators in the **MediLink** application, covering key functionalities such as user registration, symptom checking, appointment scheduling, and emergency support.

---

### **System Architecture**
This section demonstrates the high-level architecture of the **MediLink** app, showcasing the interaction between:
- The **frontend** (HTML, CSS, JavaScript, jQuery) for the user interface.
- The **backend** (Spring Boot, Spring Security) for handling authentication, appointment scheduling, and AI-driven logic.
- The **AI system** (ChatGPT or OpenAI API) for analyzing user symptoms and providing healthcare recommendations.
- The **database** (MySQL) for storing user profiles, appointments, and healthcare data.
- ![image](https://github.com/user-attachments/assets/cce18e9f-5f05-4194-9423-f24e245ea1fe)


---

# Project Structure for Feature Implementation
This project is structured to ensure a step-by-step approach for feature development. Participants must fully implement Week-1 deliverables before progressing to Week-2 deliverables, and so on. Each Week feature builds on the previous one, ensuring a solid foundation for the final application.

# Features Breakdown

# Week 1: **Introduction to Web Development and Tools** 
**Goal:** Set up the development environment and develop the basic structure of the web app.
## Week-1 Tasks:
- Overview of Full-Stack Development
   - **Lecture Video:** [Overview](https://www.youtube.com/watch?v=8KaJRw-rfn8)
- Tool and Environment setup
   ### (1) Frontend:
  Install VSCode for frontend development. VSCode is a great choice due to its flexibility and extensions for HTML, CSS, JavaScript, and React.
  - Learn more about VSCode setup [VSCode Lecture](https://www.youtube.com/watch?v=TeZdo8mx0gc&t=882s)
  
  ### (2) Backend:
  Install IntelliJ IDEA or Spring Tool Suite (STS) for Spring Boot development. These IDEs provide integrated support for Spring Boot and related technologies.
     -  **Reading Material:** [Spring Boot Guide](https://spring.io/guides/gs/spring-boot)
     -  **Lecture Video:** [SpringBoot Lecture](https://www.youtube.com/watch?v=Zxwq3aW9ctU&list=PLsyeobzWxl7qbKoSgR5ub6jolI8-ocxCF)
  
  ###  (3) Version Control:
   - Install Git and set up a GitHub repository for version control.
   - **Lecture Video:** [Git Version Control Lecture](https://www.youtube.com/watch?v=Ez8F0nW6S-w)
     
   ### (4) Database:
  Set up MySQL for the backend database. Install MySQL Workbench.
  - **Lecture Video:** [MySql Lecture](https://www.youtube.com/watch?v=uj4OYk5nKCg)
    
- Basics of HTML (HyperText Markup Language): HTML forms the backbone of the website, providing its basic structure and content.
  -    **Reading Material:** [HTML Guide](https://www.w3schools.com/html/default.asp)
  -    **Lecture Video:** [HTML Lecture](https://www.youtube.com/watch?v=BsDoLVMnmZs)  

- Basics of CSS(Cascading Style Sheets): CSS styles and enhances the visual appeal of the website, making it responsive and user-friendly.  
   - **Reading Material:** [CSS Guide](https://www.w3schools.com/css/default.asp)  
   - **Lecture Video:** [CSS Lecture](https://www.youtube.com/watch?v=wRNinF7YQqQ)
      
- Basics of Javascript: JavaScript adds dynamic functionalities and interactivity to the website.  
   - **Reading Material:** [JavaScript Guide](https://www.w3schools.com/js/default.asp)  
   - **Lecture Video:** [JavaScript Lecture](https://www.youtube.com/watch?v=hKB-YGF14SY)  


## Week-1 Deliverables
- Understand the structure of Healthcare Website
- Create a basic structure with HTML, CSS, and JavaScript for the homepage, services, about, FAQ, contact, and system checker pages, sign up/ login, appointment booking .
- Add navigation between these sections (Home, Services, About, FAQ, Contact).
- Add basic content to the pages.
  
1. **Home:**  
   Navigate to the homepage of the website for an overview of services and features.  

2. **Services:**  
   Explore all the healthcare services provided, including specialized care options.  

3. **About:**  
   Learn about the organization, its mission, and the team behind the services.  

4. **FAQ:**  
   Access answers to frequently asked questions about the website and services.  

5. **Contact:**  
   Get contact details and reach out for any queries or assistance.

6.  **System Checker**  
   Get your symptoms for better diagnosis .

7. **Sign Up/Login**  
   Sign Up and login patient .

8.  **OPD Appointment Booking**
    Book appointment

*Screenshots are provided below for reference.*  
## **Screenshots**  
![Home Screenshot](https://github.com/user-attachments/assets/101e2bfd-180f-4613-a072-742a85f71d1b)  

![Services Screenshot](https://github.com/user-attachments/assets/d9599803-f284-4d3a-9669-2f53704fa18b)  
 
![About Screenshot](https://github.com/user-attachments/assets/9e265f44-8baa-42c1-a2c1-e77bd16de794)  
  
![FAQ Screenshot](https://github.com/user-attachments/assets/07d602e9-ee98-4fa8-8e29-acd90f356f68)  
  
![Contact Screenshot](https://github.com/user-attachments/assets/00d1e9ba-f2ed-4b6e-8a3d-4396745aefe4) 
 
<img width="664" alt="image" src="https://github.com/user-attachments/assets/ce8c6546-4ab0-48f6-8bd4-518c62a4a52f">

---
# Week 2: Database Design and Integration
**Goal:** Implement a secure user registration system with OTP verification and integrate a database for user data storage.
## Week-2 Task:
- Create a table for users in MySQL with fields like id, email, phone number, password, OTP, etc.
   - **Reading Material:** [MySql Guide](https://www.geeksforgeeks.org/crud-operations-in-mysql/)  
   - **Lecture Video:** [MySql Lecture](https://www.youtube.com/watch?v=M21rXLWOnFs)  

- Design the users table schema.
  - **Reading Material:** [MySql Guide](https://www.integrate.io/blog/complete-guide-to-database-schema-design-guide/)
  - **Lecture Video:** [MySql Lecture](https://www.youtube.com/watch?v=Dlx8_LJ3rek&list=PLDmvslp_VR0yhBmSTEbDGcoeZqOZMJQ_L)  
- Integrate Spring Boot with MySQL using Spring Data JPA for CRUD operations.
   - **Reading Material:** [Spring Boot MySql Guide](https://hevodata.com/learn/spring-boot-mysql/)
   - **Lecture Video:** [Spring Boot MySql Lecture](https://www.youtube.com/watch?v=Ey_Oilhvao0)  

  ## Week-2 Deliverable
  ### Backend Development:
  - Implement the User Registration API in Spring Boot.
  - Add functionality for OTP-based verification.
  - Create a login system for users.
  
  ### Frontend Development:
   - Create forms for User Registration and Login.
   - Add client-side validation for form inputs.
   - Implement OTP verification UI on the frontend.
   - *Screenshots are provided below for reference.*
   - <img width="947" alt="image" src="https://github.com/user-attachments/assets/c87ab936-a1bc-4a2a-87a7-4569b1d4a843">

---
# Week 3: Medical Articles and Resources  
**Goal:** Create an "Articles" section and build a system to manage and filter articles based on medical specialties.

## Week-3 Task:
- Create a table for article with id(Unique identifier), title (Title of the article), content (Full content of the article), author (Author's name), specialty (Medical specialty of the article), publishedDate (Publication date), etc.
   - **Reading Material:** [MySql Guide](https://www.geeksforgeeks.org/crud-operations-in-mysql/)  
   - **Lecture Video:** [MySql Lecture](https://www.youtube.com/watch?v=M21rXLWOnFs)
- Rest API's in springboot
     - **Reading Material:** [RestApi Guide](https://spring.io/guides/tutorials/rest)  
     - **Lecture Video:** [RestApi Lecture](https://www.youtube.com/watch?v=iBGkJln9BPo&list=PLcs1FElCmEu121gqGwlQt47d0SqNkzSTK)
  

## Week-3 Deliverable:
### Backend Development:
- Implement an Article entity class with fields like id, title, content, author, specialty, and publishedDate.
- Set up an API for creating, fetching, and filtering articles based on specialty.
- Use Spring Data JPA for handling article-related CRUD operations.

### Frontend Development:
- Add an Articles Section on the frontend.
- Create a dropdown filter for articles based on medical specialties.
- Display article titles, authors, dates, and snippets. Use a "Read More" link for full content.
- Fetch and display data from the backend using fetch.

  **Tip** Explore one possible implementation approach [reading material](https://github.com/ankitgtron/MediLink/blob/master/Medical%20Articles%20and%20resources%20%20implementation%20idea.md)
- *Screenshots are provided below for reference.*
  - <img width="523" alt="image" src="https://github.com/user-attachments/assets/9774ad20-5939-4c97-b343-552eb9fc31db">

  ---
# Week-4: OPD Appointment Booking
**Goal:** Enable users to book OPD appointments and manage bookings
## Week-4 Task:
- Create appointment booking form using HTML, CSS, and JavaScript. You can add Email, Phone, Address, Appointment Id etc.
  - **Reading Material:** [Appointment Guide](https://www.geeksforgeeks.org/appointment-scheduling-system-in-spring-boot/)
  - **Lecture Video:** [Appointment Lecture](https://www.youtube.com/watch?v=M21rXLWOnFs)
- Use Spring Boot to handle user data, manage appointment slots, and store bookings in a MySQL database.
   - **Reading Material:** [Spring Boot MySql Guide](https://hevodata.com/learn/spring-boot-mysql/)
   - **Lecture Video:** [Spring Boot MySql Lecture](https://www.youtube.com/watch?v=Ey_Oilhvao0)  
- Design tables to store available slots and appointments.
   - **Reading Material:** [MySql Guide](https://www.geeksforgeeks.org/crud-operations-in-mysql/)  
   - **Lecture Video:** [MySql Lecture](https://www.youtube.com/watch?v=M21rXLWOnFs)
- API Integration: Create RESTful APIs in Spring Boot to manage appointment data.
   - **Reading Material:** [RestApi Guide](https://spring.io/guides/tutorials/rest)  
   - **Lecture Video:** [RestApi Lecture](https://www.youtube.com/watch?v=iBGkJln9BPo&list=PLcs1FElCmEu121gqGwlQt47d0SqNkzSTK)

## Week-4 Deliverable:
### Backend Development:
- Design a Booking system where users can book an appointment for OPD services.
- Implement a slot availability system.
- Create a confirmation API for successful bookings.
- Integrate user data with the appointments table in the database.

### Frontend Development:
- Create a form for OPD Appointment Booking.
- Display available slots dynamically from the backend.
- Show appointment details on the user dashboard.
- Send booking confirmation emails to users.
- *Screenshots are provided below for reference.*
- <img width="689" alt="image" src="https://github.com/user-attachments/assets/110c1622-01c9-4b6d-923c-046db7bde7bf">
  
---
# Week 5: Disease Classification Tool (System Checker)
**Goal**: Create a tool that helps users classify their symptoms and suggests potential diseases and specialist doctors.
## Week-5 Task:
- Implement AI Powered tools in app
   - **Reading Material:** [ChatGpt Guide](https://www.baeldung.com/spring-boot-chatgpt-api-openai)
   - **Lecture Video 1:** [ChatGpt Lecture 1](https://www.youtube.com/watch?v=HlDkuFy8xRM)
   - **Lecture video 2:** [ChatGpt Lecture 2](https://www.youtube.com/watch?v=B8UQ5s4kLXg)
## Week-5 Deliverable:
### Backend Development:
- Implement an AI-powered disease classification tool (e.g., using predefined symptoms).
- Add a backend API for symptom input and disease classification logic.
- Display doctor profiles based on classified diseases.

### Frontend Development:
- Create an input form where users can enter symptoms.
- Display potential diseases and doctor recommendations based on the input.
- Integrate ChatGPT for symptom analysis.
- *Screenshots are provided below for reference.*
- <img width="663" alt="image" src="https://github.com/user-attachments/assets/cf0cf76b-d673-4a27-a28b-c8d92ca22727">

# Week 6: Final Testing and Deployment
**Goal:** Test the application thoroughly and deploy it to a cloud platform.

## Week-6 Task:
- Spring boot unit testing
   - **Reading Material:** [Spring Boot Unit Testing Guid](https://spring.io/guides/gs/testing-web)
   - **Lecture Video:** [Spring Boot Unit Lecture](https://www.youtube.com/watch?v=qpK1AoFWY8k)
-  Api testing in postman
   - **Lecture Video:** [Backend Api Testing Lecture](https://www.youtube.com/watch?v=CLG0ha_a0q8)
- Deploy spring boot to AWS
   -  **Lecture Video:** [Deploy springboot to Aws Lecture](https://www.youtube.com/watch?v=jrxIubdf3O8&list=PLSg8jHkYTg9FG9v5VEikhYwhT_9SdXHcU)
- Deploy frontend to Vercel
   - **Lecture Video:** [Deploy frontend to vercel Lecture](https://www.youtube.com/watch?v=b2bIdtSwDhc)
  
## Week-6 Deliverble:
### Testing:
- Test all features (registration, articles, appointments, system checker) for functionality and security.
- Use Postman or Swagger to test backend APIs.
- Ensure frontend-backend communication is seamless.
- Perform unit testing for both frontend and backend.

### Deployment:
- Deploy the backend (Spring Boot) on AWS.
- Deploy the frontend (React app) on Vercel.
- Ensure everything works in the live environment.
- Monitor application performance and user activity.
---

**The End**
