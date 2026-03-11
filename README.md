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




How to Run Locally
Clone the repository:

Bash
git clone https://github.com/your-username/it-ticketing-system.git
Update src/main/resources/application.properties with your MySQL credentials.

Run the application:

Bash
mvn spring-boot:run
Access at: http://localhost:8080

Why this project?
As an aspiring IT Support Engineer, I wanted to understand the software that runs a modern Helpdesk. Building this tool from scratch helped me master:

Logical Troubleshooting: Debugging code is similar to debugging Windows errors.

Process Documentation: Understanding why every ticket update matters for the end-user.

User Experience: Making a simple UI so non-technical employees can report issues easily.
