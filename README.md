IT Helpdesk Ticketing System (osTicket Inspired)
A full-stack IT Support Management tool built to streamline the ticket lifecycle, from issue reporting to resolution. This project demonstrates my understanding of ITIL processes, SLA management, and technical troubleshooting.

Key Features
Ticket Lifecycle Management: Complete flow of Add, Update, and Resolve tickets.

Live Dashboard: Real-time tracking of ticket counts (Open, In-Progress, Resolved).

Manual Stress Testing: Populated with 50+ real-world IT scenarios to test system performance and queue management.

Categorization: Logical sorting of issues into Hardware, Software, Network, and Access Requests.

Role-Based Simulation: Designed with different views for Users (Employees) and Agents (IT Technicians).

Tech Stack
Backend: Java, Spring Boot, Spring Data JPA

Frontend: HTML5, CSS3 (Professional Admin Dashboard UI)

Database: MySQL / PostgreSQL

Tools: Maven, Git

Project Structure and Logic
I built this system to solve common helpdesk challenges:

Issue Triage: Priority-based sorting (Low, Medium, High) to handle urgent server/network issues first.

Audit Trail: Every ticket update is logged to maintain documentation, which is crucial for IT Support audits.

Data Persistence: Managed 50+ manual entries to ensure the database handles search and filtering efficiently.

Dashboard Preview
<img width="1893" height="865" alt="image" src="https://github.com/user-attachments/assets/5aab46b6-bcbd-46f1-8f92-6c95b8e4c9b9" />
<img width="1867" height="858" alt="image" src="https://github.com/user-attachments/assets/989118af-ab22-4e3f-8f0f-090b1cb2551f" />
<img width="1869" height="852" alt="image" src="https://github.com/user-attachments/assets/2a2a7412-8275-403f-91c4-c1e4222d428e" />
<img width="1804" height="845" alt="image" src="https://github.com/user-attachments/assets/35de6c60-0be2-4068-ae9e-5c2e0263403a" />
<img width="1825" height="840" alt="image" src="https://github.com/user-attachments/assets/1a049351-c9c4-41ee-a4f9-8ad0d935e2ce" />
<img width="1918" height="868" alt="image" src="https://github.com/user-attachments/assets/90ba7bdb-bb57-405c-95dc-3f3280040eba" />
<img width="1893" height="863" alt="image" src="https://github.com/user-attachments/assets/05bab668-b222-4a81-ace8-2c87ac5662e4" />



How to Run Locally
Clone the repository:

Bash
git clone https://github.com/patushinde14/it-ticketing-system.git
Update src/main/resources/application.properties with your MySQL credentials.

Run the application:

Bash
mvn spring-boot:run
Access at: http://localhost:8081

Why this project?
As an aspiring IT Support Engineer, I wanted to understand the software that runs a modern Helpdesk. Building this tool from scratch helped me master:

Logical Troubleshooting: Debugging code is similar to debugging Windows errors.

Process Documentation: Understanding why every ticket update matters for the end-user.

User Experience: Making a simple UI so non-technical employees can report issues easily.
