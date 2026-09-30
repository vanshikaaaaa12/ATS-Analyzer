# ATS Analyzer

An AI-powered Applicant Tracking System (ATS) designed to streamline the recruitment process by managing job postings, student/candidate profiles, resume uploads, applications, and AI-assisted resume analysis.

## 🚀 Overview

ATS Analyzer is a web-based recruitment management platform that connects candidates and recruiters through a centralized Applicant Tracking System.

The platform provides separate workflows for students/candidates and administrators, while integrating the **Groq API** for AI-powered resume analysis and insights.

## ✨ Key Features

### 👨‍🎓 Candidate / Student
- Student registration and login
- Candidate profile management
- Resume upload
- Job browsing
- Job application management
- Application status tracking
- Resume analysis using AI

### 👨‍💼 Admin / Recruiter
- Admin authentication
- Post and manage job opportunities
- View registered candidates
- View applicants for posted jobs
- Manage applications
- Recruitment workflow management

### 🤖 AI-Powered Resume Analysis
- AI-assisted resume analysis using Groq API
- Resume insights and evaluation
- Helps identify relevant information from candidate resumes
- Supports AI-assisted recruitment decisions

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Java
- Spring Boot
- REST APIs
- Maven

### Database
- H2 Database
- Hibernate / JPA

### AI Integration
- Groq API

### Development Tools
- Git
- GitHub
- VS Code
- Maven

## 🏗️ Project Structure

```text
ATS-Analyzer/
│
├── frontend/
│   ├── index.html
│   ├── login2.html
│   ├── student_login.html
│   ├── student_register.html
│   ├── student_dashboard.html
│   ├── resume_upload.html
│   ├── jobs.html
│   ├── applications.html
│   ├── admin_login.html
│   ├── admin_dashboard.html
│   └── ...
│
└── backend/
    └── ats-portal-backend-main/
        └── ats-system/
            ├── src/
            ├── pom.xml
            ├── Dockerfile
            └── ...
