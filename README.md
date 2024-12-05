# **MediLink**  
MediLink is an innovative healthcare platform designed to assist patients in identifying diseases and connecting with the right healthcare professionals. The website incorporates advanced features such as a System Checker, ensuring accurate guidance for medical concerns. It also provides essential services like 24/7 medical support, emergency assistance, OPD facilities, medical counseling, and specialized treatments for critical conditions, including cancer and bone marrow transplants.

With a strong commitment to improving healthcare delivery and promoting community well-being, MediLink blends patient-centric care with cutting-edge medical technology to deliver superior health outcomes.

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
*MediLink* is developed using the following technologies:   

---
# Project Structure for Feature Implementation
This project is structured to ensure a step-by-step approach for feature development. Participants must fully implement Week-1 deliverables before progressing to Week-2 deliverables, and so on. Each Week feature builds on the previous one, ensuring a solid foundation for the final application.

# Features Breakdown

# Week 1: **Introduction to Web Development and Tools** 
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
  - **Lecture Video:** [MySql Lecture](https://www.youtube.com/watch?v=UzodkZUt5JY)
    
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
- Create a basic static webpage with the following navigation feature
  
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
## Description: 
- Implement a secure user registration system allowing patients to register using their email and phone number. Include OTP-based verification for authentication.
Requirements:
   - Form for user registration (HTML, CSS).
   - Backend for user data storage and verification (Spring Boot, MySQL).
   - User login and session management.
   - Learn more about Spring Boot and MySQL CRUD operation [tutorial](https://www.youtube.com/watch?v=mJtEmL5F0DU&list=PLA7e3zmT6XQXIFcweUahWz2rQtmeI8dnl)
  - *Screenshots are provided below for reference.*
  - <img width="947" alt="image" src="https://github.com/user-attachments/assets/c87ab936-a1bc-4a2a-87a7-4569b1d4a843">

---
# Feature 3: Medical Articles and Resources  
## Description: Provide users with curated health articles and resources.
## Requirements:
   - Add an "Articles" section on the frontend.
   - Create a backend system to manage and fetch articles dynamically.
   - Include filters based on medical specialties.
   - Explore one possible implementation approach [reading material](https://github.com/ankitgtron/MediLink/blob/master/Medical%20Articles%20and%20resources%20%20implementation%20idea.md)
   - *Screenshots are provided below for reference.*
  - <img width="523" alt="image" src="https://github.com/user-attachments/assets/9774ad20-5939-4c97-b343-552eb9fc31db">

  ---
# Feature 4: OPD Appointment Booking
## Description: Allow users to book outpatient department (OPD) appointments.
## Requirements:
   - Appointment booking form.
   - Backend to handle slot availability and booking confirmation.
   - Integration with a user dashboard to manage bookings.
   - Learn how to add appointment scheduling [tutorial](https://www.youtube.com/watch?v=IuYVfEuiSso)
   - *Screenshots are provided below for reference.*
   - <img width="909" alt="image" src="https://github.com/user-attachments/assets/d1b88d12-5c8e-42ae-b905-a1d305a1aef5">
   
---
# Feature 5: Disease Classification Tool (System Checker)
## Description: Create a tool that helps users classify their symptoms and suggests potential diseases and specialist doctors.
## Requirements:
   - Input form for symptoms.
   - Backend logic to classify symptoms using predefined conditions.
   - Display results with relevant doctor profiles.
   - Learn how to incoporate chatgpt [tutorial](https://www.youtube.com/watch?v=70H_7C0kMbI)
   - *Screenshots are provided below for reference.*
   - <img width="663" alt="image" src="https://github.com/user-attachments/assets/cf0cf76b-d673-4a27-a28b-c8d92ca22727">

---
