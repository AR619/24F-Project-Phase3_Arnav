# Fall 2024 Career Catalyst's Project - TalentTrail


## Description

**TalentTrail** is a data-driven platform designed to empower Northeastern University students by integrating skills and career interests to provide personalized recommendations for classes, projects, and job opportunities. Bridging the gap between education and employment, TalentTrail transforms career planning into a proactive and intuitive journey. It caters to students with curated recommendations, employers with advanced talent discovery tools, advisors with detailed co-op insights, and administrators with efficient platform management, making career planning an engaging and data-driven experience for all users.

## Key Features

1. **Personalized Job Search**  
   Utilize an intelligent tool that matches students with roles based on their affiliated skills.

2. **Gamified Experience**  
   Climb leaderboards and try making it to the top!

3. **Multi-Role Support**  
   Custom dashboards for students, employers, advisors, and administrators to ensure tailored functionality.

## Tech Stack

- **Frontend:** Streamlit
- **Backend:** Flask, Python
- **Database:** SQL (managed using DataGrip)
- **Containerization:** Docker

## Project Components

Our project consists of three major components which will each run in their own Docker Containers:

- Streamlit App in the `./app` directory
- Flask REST api in the `./api` directory
- SQL files for your data model and data base in the `./database-files` directory


## Controlling the Containers

- `docker compose build` to build or rebuild services defined in the `docker-compose.yml` file.
- `docker compose up -d` to start all the containers in the background
- `docker compose down` to shutdown and delete the containers
- `docker compose up db -d` only start the database container (replace db with the other services as needed)
- `docker compose stop` to "turn off" the containers but not delete them.

## Requirements

1. **Docker**  
   Ensure Docker is installed on your system to manage containers.  
   - [Docker Installation Guide](https://docs.docker.com/get-docker/)

2. **Docker Compose**  
   Required to manage multi-container applications.  
   - Comes bundled with Docker Desktop or can be installed separately.

3. **Python 3.8 or higher**  
   Needed for development and debugging outside the Docker environment.  
   - [Python Installation Guide](https://www.python.org/downloads/)

4. **pip**  
   Package manager for Python to install required Python packages (if testing outside Docker).

5. **Streamlit**  
   Installed automatically through Docker Compose.

6. **Flask**  
   Installed automatically through Docker Compose.

7. **DataGrip (Optional)**  
   Recommended for managing and interacting with the SQL database during development.

8. **Git**  
   For cloning the repository and version control.  
   - [Git Installation Guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)


## Instructions to use app


 
