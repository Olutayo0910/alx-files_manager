# 0x04. Files Manager

## Back-end
- JavaScript
- ES6
- NoSQL
- MongoDB
- Redis
- NodeJS
- ExpressJS
- Kue

## Weight
1

## Team
- OLUTAYO OGUNLADE

## Project Timeline
- Start: May 9, 2024 6:00 AM
- End: May 16, 2024 6:00 AM
- Checker released: May 11, 2024 12:00 AM
- Manual QA review required

## Overview
This project serves as a summary of the back-end trimester, covering authentication, NodeJS, MongoDB, Redis, pagination, and background processing. The objective is to build a simple platform for uploading and viewing files, incorporating user authentication via tokens, file listing, upload, permission management, file viewing, and thumbnail generation for images.

## Learning Objectives
Upon completion of this project, participants should be able to explain the following concepts without external assistance:
- Creating an API with Express
- User authentication
- Data storage in MongoDB
- Temporary data storage in Redis
- Setup and utilization of background workers

## Requirements
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files interpreted/compiled on Ubuntu 18.04 LTS using node (version 12.x.x)
- All files ending with a new line
- Mandatory README.md file at the project root
- Code should use the .js extension
- ESLint for linting
- Run `npm install` to install dependencies

## Tasks
1. **Redis utils**
   - Create a `redis.js` file in the `utils` folder containing a `RedisClient` class with specified functionalities.
   - Export an instance of `RedisClient` called `redisClient`.

2. **MongoDB utils**
   - Create a `db.js` file in the `utils` folder containing a `DBClient` class with specified functionalities.
   - Export an instance of `DBClient` called `dbClient`.

3. **First API**
   - Create an Express server in `server.js` listening on the specified port.
   - Implement two endpoints in `routes/index.js` using `AppController` to get status and stats.

4. **Create a new user**
   - Implement a POST endpoint to create a new user in `routes/index.js` and `UsersController.js`.

5. **Authenticate a user**
   - Implement endpoints for user authentication and token management in `routes/index.js` and `AuthController.js`.

6. **First file**
   - Implement a POST endpoint to create a new file in `routes/index.js` and `FilesController.js`.

7. **Get and list file**
   - Implement endpoints to get and list files in `routes/index.js` and `FilesController.js`.

8. **File publish/unpublish**
   - Implement endpoints to publish and unpublish files in `routes/index.js` and `FilesController.js`.

9. **File data**
   - Implement an endpoint to get file data in `routes/index.js` and `FilesController.js`.

10. **Image Thumbnails**
    - Update the POST /files endpoint to start a background process for generating thumbnails for image files.

## Resources
- Node JS getting started
- Process API documentation
- Express getting started
- Mocha documentation
- Nodemon documentation
- MongoDB
- Bull
- Image thumbnail
- Mime-Types
- Redis

