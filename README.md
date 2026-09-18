# Smart Candidate Screening System

A web-based candidate screening interface for evaluating and shortlisting students using academic performance, skills, projects, internship experience, and certifications.

## Project links:

Live Demo : https://jagdishgoski31-glitch.github.io/smart-candidate-screening-system/


Github Repositories : https://github.com/jagdishgoski31-glitch/smart-candidate-screening-system.git

## Overview

The application provides a centralized view of student profiles and assigns each candidate a screening category based on a defined scoring system.

Candidates can be searched and filtered using:

- Name or email
- Minimum CGPA
- Skill
- Branch
- Screening category

Each candidate profile also provides a score and a breakdown explaining how the score was calculated.

## Key Features

- Candidate search by name or email
- Minimum CGPA filtering
- Skill and branch filtering
- Category-based filtering
- Student shortlist with key candidate information
- Candidate profile view
- Score calculation out of 10
- Explanation of the factors contributing to each score
- Reset filters option
- Responsive layout for different screen sizes

## Screenshots

##  Dashboard and Student List
The dashboard provides a quick summary of the student batch, including total students and the number of students in each screening category. The student shortlist displays key information such as branch, CGPA, skills, projects, internship experience, certifications, and category.
<img width="1366" height="720" alt="1" src="https://github.com/user-attachments/assets/d2fd19df-e2a4-470b-93c9-44b4c60e4c9f" />


## Category Filtering
The category filter allows placement coordinators to quickly view students belonging to a specific category, such as Strong.
<img width="1366" height="716" alt="2" src="https://github.com/user-attachments/assets/04cab247-3d56-4467-9c59-be6fb15f1331" />

## Branch and Category Filtering
Multiple filters can be combined to narrow the shortlist. For example, coordinators can filter students by branch and screening category at the same time.
<img width="1366" height="720" alt="3" src="https://github.com/user-attachments/assets/6e3b0e26-eddf-41ac-99e4-38d763336953" />

## Minimum CGPA Filtering
The minimum CGPA filter allows coordinators to display candidates who meet a selected academic threshold.
<img width="1366" height="712" alt="4" src="https://github.com/user-attachments/assets/2de0aece-bb2b-4970-a215-ab3b770ec336" />


## Candidate Profile and Score Explanation
The candidate profile view displays detailed information about an individual student, including CGPA, skills, projects, internship, certifications, screening score, and a plain-language explanation of how the category was assigned.
<img width="1366" height="718" alt="5" src="https://github.com/user-attachments/assets/152bc454-df70-44e7-9d19-03a0a1834448" />

## Screening Criteria

The screening score is calculated using the following factors:

| Criteria | Maximum Points |
|----------|----------------|
| CGPA | 4 |
| Skills | 2 |
| Projects | 2 |
| Internship | 1 |
| Certifications | 1 |
| **Total** | **10** |

Candidates are grouped into three categories:

- **Strong** — Score 8 or above
- **Average** — Score 5 to 7
- **Needs Improvement** — Score below 5

## Tech Stack

- HTML5
- CSS3
- JavaScript

## Project Structure

```text
smart-candidate-screening-system/
├── index.html
└── README.md
