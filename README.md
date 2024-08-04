# JSON Resume Generator

## Overview

This repository contains the JSON representation of a resume based on the details provided during a conversation. The JSON structure is organized into multiple sections to encapsulate personal details, education, work experience, projects, skills, publications, and certifications. This README outlines the steps taken to generate the JSON and includes the JSON output itself.

## Sections Included

1. **Personal Details**
   - Name, email, phone number, GitHub, and LinkedIn profile.

2. **Education**
   - Degree information, including institute, year, and CGPA/percentage.

3. **Experience**
   - Details of work experience, including the role, company, duration, and key responsibilities.

4. **Projects**
   - Details of projects worked on, including the project name, technologies used, descriptions, and GitHub links.

5. **Skills**
   - A list of technical skills relevant to the candidate's profile.

6. **Publications**
   - Academic and technical publications, including titles and publication venues.

7. **Certifications**
   - Professional certifications obtained by the candidate.

## JSON Structure

The JSON output is organized into the following structure:

```json
{
  "personal_section": [
    {
      "name": "Aditya Kanawade",
      "email": "aditya.kanawade20@vit.edu",
      "phone": "+91 9405657088",
      "github": "https://github.com/AdityaKanawade0565",
      "linkedin": "https://www.linkedin.com/in/aditya-kanawade-643549242/"
    }
  ],
  "Education_section": [
    {
      "degree": "B. Tech in Artificial Intelligence and Data Science",
      "institute": "Viswakarma Institute of Technology, Pune",
      "year": "2020 - 2024",
      "CGPA": "8.7"
    },
    {
      "degree": "HSC",
      "board": "Maharashtra State Board",
      "year": "2019 - 2020",
      "percentage": "88.15%"
    },
    {
      "degree": "SSC",
      "board": "Maharashtra State Board",
      "year": "2017 - 2018",
      "percentage": "93.60%"
    }
  ],
  "Experience_section": [
    {
      "title": "Trainee Software Engineer",
      "company": "Itanta Analytics",
      "duration": "Feb 2024 - Present",
      "responsibilities": [
        "Developed backend for interactive Pareto chart component using Python.",
        "Implemented REST APIs, MongoDB, and RabbitMQ for data operations and real-time updates.",
        "Processed user configurations via API requests, enabling dynamic UI interactions.",
        "Leveraged RabbitMQ to communicate between the web server and Pareto component for efficient request handling.",
        "Executed database queries and processed results for analysis and PDF report generation.",
        "Conducted keyword analysis to determine optimal chart types based on user queries.",
        "Implemented OpenAI Langchain LLM to generate SQL queries from natural language inputs.",
        "Developed an SQLite-based system to execute generated SQL queries.",
        "Utilized ECharts to dynamically plot data from executed queries."
      ]
    }
  ],
  "Projects_section": [
    {
      "name": "Social Media Analytics Dashboard",
      "technologies": ["YouTube Data API", "Python", "Flask", "JavaScript"],
      "description": [
        "Developed a dynamic Flask application providing real-time analytics for YouTube and Instagram data.",
        "Successfully interfaced with YouTube Data API for comprehensive channel statistics and video analytics.",
        "Overcame security challenges in Instagram data extraction, enabling user-specific metrics without compromising sensitive information."
      ],
      "github_link": "https://github.com/AdityaKanawade0565/Social-Media-Analytics-Dashboard-"
    },
    {
      "name": "CheatFit Fitness Web Application",
      "technologies": ["Flask", "ML", "HTML"],
      "description": [
        "Developed an app to estimate body fat percentage based on user measurements and provide personalized diet plans tailored to individual caloric needs.",
        "The body fat percentage is estimated using a Machine learning model.",
        "The communication with the ML model is done via Flask API."
      ],
      "github_link": "https://github.com/AdityaKanawade0565/Body-fat-percentage-estimation-"
    }
  ],
  "Skills_section": [
    "Python",
    "C / C++",
    "Pandas",
    "Django",
    "JavaScript",
    "NodeJS",
    "OOP",
    "NumPy",
    "MongoDB",
    "REST APIs",
    "Flask"
  ],
  "Publication_section": [
    {
      "title": "CheatFit: 360º Fitness Application",
      "conference": "ICCIXAI-2023"
    },
    {
      "title": "Street Light Control System",
      "journal": "IJRASET-2022"
    }
  ],
  "Certification_section": [
    {
      "name": "Google IT Automation with Python",
      "type": "Professional Certificate"
    },
    {
      "name": "AWS Educate Introduction to Cloud 101"
    }
  ]
}
