# Flare - IN DEVELOPMENT

## Description

Flare is a student-built and maintained web application that visualizes data generated by Artificial Intelligence models. Flare helps stakeholders and researchers track model progress, assess performance, and gain valuable information from AI outputs.

## Prerequisites
 - Docker Desktop: Ensure Docker Desktop is installed and running to manage containerized applications.
 - Node.js and NVM: Use Node Version Manager (NVM) to manage Node versions, ensuring compatibility with the frontend Vue app.

## To set up and run Flare in a Docker container:
0. Set Up Environment Variables:
    - Create a .env file in the project’s root directory. This file will contain environment variables needed by Docker.
    - Copy the contents from env.dist and update the values with your own variables.
1. Ensure that Docker Desktop is running on your machine.
2. Start in the root directory: 'cd CDL-Broadcast'
2. Run 'docker compose build' and 'docker compose up' (run 'docker compose up -d' to run in the background)
3. If you make changes to the code make sure you 'docker compose down' and then repeat step 2.

## Vue Development Setup(Frontend)
1. Use nvm (Node Version Manager) to switch to the Node version specified in the frontend container.
2. Change to the Vue app directory 'cd CDL-Broadcast/src/ui-vue'
3. Run the development enviornment : 'npm run dev'

## Authors
* [@Anointiyae Beasley](https://github.com/abeasley1722) - anointiyae.beasley@tamucc.edu
* [@Matthew Kastl](https://github.com/matdenkas) - mkastl@islander.tamucc.edu
* [@Beto Estrada](https://github.com/bestrada33) - bestrada4@islander.tamucc.edu
* [@Savannah Stephenson](https://github.com/lovelysandlonelys) - sstephenson2@islander.tamucc.edu
* [@Florence Tissot](https://github.com/ccftissot)