# Sem-project-II

Abstract – Smart Question Paper Generator 

The Smart Question Paper generator is a role-based web application designed to streamline the creation, submission, and management of academic question papers in educational institutions. This system introduces three key dashboards: Admin, Faculty, and Exam Department, each tailored with specific functionalities to improve workflow efficiency and ensure secure, organized handling of question papers.

The Admin dashboard allows centralized control over user roles (Faculty/Exam Department), branches, and subjects, with options to add, edit, or deactivate user accounts and subject configurations. The Faculty dashboard enables authenticated users to filter by academic details and either manually enter questions (with marks and optional images) or upload complete question papers in PDF format. These submissions are stored securely in the database.

The Exam Department dashboard facilitates viewing and downloading of submitted content. It includes a smart PDF extraction feature using PyMuPDF that parses text from uploaded papers. Selected questions can then be compiled into a final question paper using PDF generation libraries such as ReportLab or FPDF.

Built using Flask (Python) and backed by a structured MySQL database, the system ensures a seamless experience for faculty and exam authorities, promoting digitization, reducing manual errors, and ensuring a more secure and scalable academic workflow.  
q
