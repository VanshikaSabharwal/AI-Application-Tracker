# AI Application Tracker

The AI Application Tracker is a tool designed to automate the job application process and make it simple. 

## Features

- **Automated Job Data Collection**: Integrates with various job boards and company websites to fetch and update job listings automatically.
- **Personalized Dashboard**: Provides users with an overview of their applications, upcoming deadlines, and relevant job suggestions.
- **Application Status Tracking**: Monitors and updates the status of each application, from submission to interview stages.
- **Deadline Alerts**: Sends notifications and reminders for application deadlines and interview schedules via email.

## System Architecture

The application is structured as a monorepo using [Turborepo](https://turbo.build/repo), facilitating efficient development and deployment. The architecture includes:

- **Frontend**: Developed with [Next.js](https://nextjs.org/) for server-side rendering and a responsive user interface.
- **Backend**: Built with Python frameworks such as [FastAPI](https://fastapi.tiangolo.com/) to handle server-side logic and API endpoints.
- **Database**: Utilizes [PostgreSQL](https://www.postgresql.org/) managed with [Prisma ORM](https://www.prisma.io/) for robust data handling.
- **AI Services**: Integrates with AI platforms like [OpenAI](https://openai.com/) for generating application documents and job matching.
- **Email Notifications**: Employs [Nodemailer](https://nodemailer.com/about/) for sending email alerts and reminders.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or above)
- [Python](https://www.python.org/) (version 3.8 or above)
- [PostgreSQL](https://www.postgresql.org/) database
- [Turborepo CLI](https://turbo.build/repo/docs/getting-started)

### Installation

1. **Clone the Repository**:

   ```sh
   git clone https://github.com/VanshikaSabharwal/AI-Application-Tracker.git
   cd AI-Application-Tracker

2. **Install Dependencies**:

    For the frontend:

    ```sh
    cd apps/frontend
    npm install


    For the backend:
    
    ```sh
    cd apps/backend
    python3 -m venv venv
    source venv/bin/activate 
    pip install -r requirements.txt


### Usage

- **Dashboard**: View and manage your job applications and track their statuses.
- **Job Search**: Browse and filter job listings fetched from integrated platforms.
- **Application Materials**: Generate and download AI-crafted resumes and cover letters.
- **Notifications**: Receive email alerts for upcoming deadlines and interview schedules.

### Tasks

- [ ] Create Figma designs for the dashboard, home page, chatbot interface, and other key components.
- [ ] Implement a login page with Google authentication.
- [ ] Develop a web scraping mechanism to gather internship and job data from various online sources.
- [ ] Incorporate a chatbot to assist users with queries and provide personalized assistance.
- [ ] Develop an "About You" page for users to input and manage their personal and professional details.
- [ ] Enable users to view a list of opportunities tailored to their profiles and provide an option to apply to multiple positions simultaneously.
- [ ] Create a comprehensive dashboard to monitor and manage the status of all applications.
- [ ] Develop a Flutter-based cross-platform application to provide users with access on various devices.
