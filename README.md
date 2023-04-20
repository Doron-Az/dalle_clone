# DALL-E clone - MERN project

## Author:

Doron Azulay (doronazulay9@gmail.com)

## Introduction

DALL-E MERN Clone is a web application that uses the MERN stack to implement a clone of OpenAI's DALL-E image generator. The application allows users to generate images based on textual descriptions, as well as upload their own images and generate textual descriptions.

## Features

DALL-E MERN Clone includes the following features:

- Generate images based on textual descriptions using OpenAI's GPT-3 API.
- Upload images and generate textual descriptions using OpenAI's DALL-E API
- User authentication and registration using JWT.
- User profile with saved images and descriptions.

## Technologies Used

DALL-E MERN Clone uses the following technologies:

- MongoDB
- Express
- React
- Node.js
- OpenAI GPT-3 API
- OpenAI DALL-E API
- TailWind
- vite

## Installation

- 1. Clone the repository : git clone https://github.com/Doron-Az/dalle-mern-clone.git
- 2. Create .env file at server folder:
  - add MongoDB key "MONGODB_URL"
  - add OpenAI key "OPENAI_API_KEY"
  - add Cloudinary name "CLOUDINARY_CLOUD_NAME"
  - add Cloudinary api "CLOUDINARY_API_KEY"
  - add Cloudinary api-secret "CLOUDINARY_API_SECRET"
- 3. Go to client folder and run terminal : "npm run dev" , listen on : http://localhost:5173/
- 4. Go to server folder and run terminal : "npm start"
