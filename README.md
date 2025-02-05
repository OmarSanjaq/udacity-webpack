NLP Article Analyzer

Overview

This project analyzes the sentiment of news articles using an NLP API. Built with Node.js, Express, Webpack, and Sass, it demonstrates essential web development skills, including API integration, service workers, and responsive design.

Features

Webpack setup with loaders and plugins

API integration for sentiment analysis

Dynamic UI updates based on analysis results

Service worker for offline functionality

Jest testing for validation

Setup



Install dependencies:

npm install

Start the development server:

npm run build-dev

Run in production mode:

npm run build-prod
npm start

API Usage

The server forwards text to Udacity's NLP API.

Example input:

{ "text": "This project is amazing!" }

Example response:

{ "sentiment": "POSITIVE", "sentiment_scores": { "Positive": 0.95, "Negative": 0.02 } }


Developer

Built by Omar Sanjaq
