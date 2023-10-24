
# Bug-Bounty-Brigade

Bug Bounty Brigade is a vibrant community of cybersecurity professionals and ethical hackers dedicated to enhancing the security of digital systems. Our mission is to cultivate a thriving community of bug hunters, by bug hunters, for bug hunters.
While Bug Bounty Brigade is a vibrant community of cybersecurity professionals and ethical hackers dedicated to enhancing the security of digital systems. Our mission is to cultivate a thriving community of bug hunters, by bug hunters, for bug hunters
By promoting responsible disclosure and ethical hacking practices, we strive to enhance the security of digital systems and protect organizations from cyber threats.!

# Bug-Bounty-Brigade Backend Service

Welcome to the backend service of the Bug-Bounty-Brigade blog app. This service is built using Node.js, Express, and MongoDB. It provides the backend functionality for managing user blogs, including uploading, fetching, updating, and deleting blogs.

## Prerequisites

Before you get started with this backend service, ensure you have the following prerequisites installed:

- Node.js: You can download it from [nodejs.org](https://nodejs.org/).
- MongoDB: You should have a MongoDB instance set up and its connection details configured in your environment.

## Configure Environment Variables 

Before running the application, make sure to set up your environment variables. Create a `.env` file in the root directory of the project:

- MONGO_URL="your_custom_mongo_db_connection_string"
- PORT=3000
- ClOUD_NAME="your_cloudinary_cloud_name"
- API_KEY="your_cloudinary_api_key"
- API_SECRET="your_cloudinary_api_secret"

## Getting Started

Follow these steps to set up and run the Bug-Bounty-Brigade backend service:

1. Clone this repository:
   git clone https://github.com/your-username/Bug-Bounty-Brigade-Backend.git
2. Navigate to the project directory:
   cd Bug-Bounty-Brigade-Backend
3. Install the project dependencies:
   npm install
4. Run the application:
   npm start (The backend service should now be running on your specified port (usually port 3000 by default)).

## API ENDPOINTS

The Bug-Bounty-Brigade backend service provides the following API endpoints:

- POST /upload/{userId}: Upload a user blog with an image to Cloudinary.
- GET /fetch/{userId}: Fetch user's blog data.
- GET /fetchall: Fetch all blog data.
- DELETE /delete/{id}: Delete a blog by ID.
- PUT /update/{id}: Update a blog by ID.

## API Documentation

The API documentation can be generated using Swagger or similar tools. To generate and host the documentation, you can refer to the code comments for each API endpoint.




