# Skillnari---AI-Powered-Skill-Diagnostic-Tool-
**Project Context:** An AI-driven system for Maynooth University to identify students’ skill gaps and recommend targeted courses for clean-energy and smart-infrastructure careers. The project was developed for the Analytics Live (MI6228[B]) module at Maynooth University (2024-2025).
** Project Overview:** Skillnari is a data-driven application designed to help students, graduates, and professionals identify critical skill gaps and navigate personalized upskilling paths. The tool works by comparing a user’s self-reported skills against the requirements extracted from real-world job postings (specifically targeting the growing renewable energy, smart systems, and energy management sectors). It then recommends relevant courses from Coursera to address the identified gaps.

**Technical Architecture:**
The application is built on a modular, two-part architecture:
1. Backend (Python/Flask): Handles all core logic, data processing, skill matching, and course recommendation via RESTful API endpoints.
2. Frontend (HTML/React/JavaScript): Provides an interactive web interface for users to input skills, search for relevant jobs, and view gap analysis and course recommendations.

| Component | Technology / File | Role |
| :--- | :--- | :--- |
| **Data Processing** | `skill_diagnostic_tool.py` | Implements tokenization, skill matching, and course search logic. |
| **Backend API** | `skill_diagnostic_tool.py` (Flask) | Exposes endpoints for job search and detailed skill gap analysis. |
| **Frontend UI** | `skill_diagnostic_tool (1).html`, `App (1).js`, `App (1).css` | The user interface for interaction. |
| **Job Market Data** | `linkedin_job_posting_with_skills_ALL_merged_clean skills v1.0.csv` | Dataset containing job titles, descriptions, and extracted skills. |
| **Learning Resource Data** | `Merged_Unique_Coursera_Courses.csv` | Dataset mapping Coursera courses to specific skills. |

**How to Run the Tool Locally**

To run this application, you need to set up the Python backend and then open the HTML frontend.

Prerequisites
Python (3.x)
pip (Python package installer)
The following Python libraries: Flask, pandas, flask-cors, difflib

**Steps**
1. Setup Environment:# Assuming you have Python installed
pip install flask pandas flask-cors
2. Place Files: Ensure all Python and CSV files (skill_diagnostic_tool.py, linkedin_job_posting_with_skills_ALL_merged_clean skills v1.0.csv, Merged_Unique_Coursera_Courses.csv) are in the same directory.
3. Run the Backend:python skill_diagnostic_tool.py.
4. Open the Frontend: Open the skill_diagnostic_tool (1).html file in your web browser. Since the JavaScript inside connects to http://127.0.0.1:5000, the tool should now be fully operational.

**Project Deliverables**: This repository also contains all the academic documentation submitted for the module:
File Name | Type | Description |
| :--- | :--- | :--- |
| `Development of Skill Dignostic Tool.pdf` | Final Report | The complete academic report detailing the motivation, methodology, data processing, results, and conclusion of the project. |
| `MI6228_12A_28_03.pptx` | Presentation | Slides used for a progress or final presentation, highlighting the system pipeline and key achievements. |
| `PosterMI6228_12A.pptx` | Poster | The visual poster summarizing the problem, solution, and future work for the **Skillnari** tool. |

**Group Members**
Ashutosh Pathak and Prashant Mishra


