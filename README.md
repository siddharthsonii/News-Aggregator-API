# News Aggregator API

## **Objective:**

Build a RESTful API that allows users to fetch news articles from multiple sources based on their preferences.

## **Project Description:**

In this project, we will create a RESTful API using Node.js, Express.js, and NPM packages. The API will allow users to register, log in, and set their news preferences (e.g., categories, sources). The API will then fetch news articles from multiple sources using external news APIs (e.g., NewsAPI). The fetched articles should be processed and filtered asynchronously based on user preferences.

### 1. **Set up Project:**

   - Initialize a new Node.js project.
   - Install necessary dependencies, including Express.js and Mongoose.

### 2. **Implement RESTful API:**

   - Create the following endpoints:

     - `POST /register`: Register a new user.
     - `POST /login`: Log in a user.
     - `GET /preferences`: Retrieve the news preferences for the logged-in user.
     - `PUT /preferences`: Update the news preferences for the logged-in user.
     - `GET /news`: Fetch news articles based on the logged-in user's preferences.

   - Use external news APIs to fetch news articles from multiple sources. Incorporate async/await and Promises in the process of fetching news data and filtering it based on user preferences.

   - Implement proper error handling for invalid requests.

   - Add input validation for user registration and news preference updates.

### 3. **Testing:**

   - Test the API using Postman or Curl to ensure it works as expected.

### 4. **Submission Guidelines:**

   - Initialize a new Node.js project.

   - Develop your News Aggregator API according to the project requirements and optional extensions (if implemented) in the project brief.

   - Write a clear and concise `README.md` file.

   - Provide a link to your GitHub repository for submission. Ensure the repository is public.

---

# Step-by-Step Guide:

## Step 1: Initialize a new Node.js project

 Create a new directory for your project

mkdir news-aggregator-api
cd news-aggregator-api

Initialize a new Node.js project

npm init -y

## Step 2: Install Dependencies
Install necessary packages like Express and body-parser.
npm install express body-parser

## Step 3: Implementing the API

## Step 4: Testing

## Run the application
node src/app.js
