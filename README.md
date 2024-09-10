# Capstone Project: proma

## Description:

- **Introduction:** 
    - **proma** is a project management platform that allows project managers and their teams to easily visualize work across their organization. It allows on-site and off-site teams to easily "clock in" and record time spent on their projects.

-  **Features:**
    - Boards: A list of all boards that a user is a member of and allows for the creation of new boards and addition of members to them.
    - Projects: Several views for projects are offered. PM's can look at all of their team's projects while a user can view all projects assigned to them. Boards show a list of all projects assigned to them.
    - Sessions: Users can record sessions on projects, which serves as a timer, allowing for a category option and optional comment so that PM's and the organization as a whole maintains constant visibility.

- **Technologies Used:**
    - Front-End: React.js
    - Back-End: RESTful API using Node.js

- **Goals:**
    - Separate unnecessary metadata from users' views
    - Give PM's the information they need while hiding the unnecessary clutter from users who do not
    - Allow users to track their time spent on projects to allow visibility across organizations

- **Usage:**
    - This project can be viewed on the live site deployed through render here: [proma on render](https://proma.onrender.com)
    - This project can be ran locally by the following commands
    ```
    $ git clone https://github.com/rkchitwood/proma.git
    $ npm install
    $ createdb proma
    $ cd backend
    $ npm start
    #in a separate terminal window
    $ cd frontend
    $ npm run dev
    ```

- **Contributors:**
    - This project was completed in its entirety by [Ryan Chitwood](https://github.com/rkchitwood)