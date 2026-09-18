# Smart Candidate Screening System

A web-based candidate screening interface for evaluating and shortlisting students using academic performance, skills, projects, internship experience, and certifications.

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
