# :warning: This repository is no longer maintained :warning:

[![License](https://img.shields.io/github/license/dolbyio-samples/blog-commandservice-avatar-app)](LICENSE)

# Client Messaging in a Dolby.io Video Conference
Sample implementation for JavaScript (Web) of the CommandService for multiple participants to move avatars across the screen.

# Overview
[This project](https://dolby.io/blog/getting-started-with-commandservice/) will demonstrate how to send text and data between participants connected to a session with JavaScript. 

# Requirements
For this project, you need a [Dolby.io account](https://dolby.io/) to acquire an API key and Secret Key for authentication. In addition to that, you will also need CommandService API credentials, but instructions on retrieving these credentials are available in the guide and Python libraries. 

# Getting Started

Replace `CUSTOMER_KEY` and `CUSTOMER_SECRET` inside `client.js` with your own key and secret.
To run the app locally, open `index.html` in your browser with a live server.

## What's Inside

### 📁 icons/

- svg files for button icons and dolbyio logo

### 📁 scripts/

- 📄 **client.js**
  - Recieves and handles events emitted by the Conference and Command objects
  - Initializes VoxeetSDK using customer key and secret
  - Opens a Voxeet session
- 📄 **ui.js**
  - handles joining conference, leaving conference, starting video, stopping video
  - UI helper functions
- 📄 **utils.js**
  - sends CommandService object when avatar moves
  - handles movement of avatar
  - handles updating conference name in URL as user types conference name
- 📄 **video.js**
  - tracks which participant is in which video container
  - handles appending and removing video nodes on the DOM as participants join/leave conference and turns video on/off

### 📄 index.css

- styling
- additional formatting done with Bootstrap

### 📄 index.html

- main entry file

# Report a Bug 
In the case any bugs occur, report it using Github issues, and we will see to it. 

# Forking
We welcome your interest in trying to experiment with our repos. 

# Feedback 
If there are any suggestions or if you would like to deliver any positive notes, feel free to open an issue and let us know!

# Learn More
For a deeper dive, we welcome you to review the following:
 - [Communications API](https://docs.dolby.io/communications-apis/docs)
 - [Getting Started with Web SDK](https://docs.dolby.io/communications-apis/docs/getting-started-with-the-javascript-sdk)
 - [Kickstart Video Calls for Your React Web App with UIKit](https://dolby.io/blog/kickstart-video-calls-for-your-react-web-app-with-uikit/)
 - [Creating A Fixed Place Spatial Environment for Video Conferencing](https://dolby.io/blog/creating-a-fixed-place-spatial-environment-for-video-conferencing/)
 - [Blog Session - Communciations API](https://dolby.io/blog/category/communications/)

# About Dolby.io
Using decades of Dolby's research in sight and sound technology, Dolby.io provides APIs to integrate real-time streaming, voice & video communications, and file-based media processing into your applications. [Sign up for a free account](https://dashboard.dolby.io/signup/) to get started building the next generation of immersive, interactive, and social apps.

<div align="center">
  <a href="https://dolby.io/" target="_blank"><img src="https://img.shields.io/badge/Dolby.io-0A0A0A?style=for-the-badge&logo=dolby&logoColor=white"/></a>
&nbsp; &nbsp; &nbsp;
  <a href="https://docs.dolby.io/" target="_blank"><img src="https://img.shields.io/badge/Dolby.io-Docs-0A0A0A?style=for-the-badge&logoColor=white"/></a>
&nbsp; &nbsp; &nbsp;
  <a href="https://dolby.io/blog/category/developer/" target="_blank"><img src="https://img.shields.io/badge/Dolby.io-Blog-0A0A0A?style=for-the-badge&logoColor=white"/></a>
</div>

<div align="center">
&nbsp; &nbsp; &nbsp;
  <a href="https://youtube.com/@dolbyio" target="_blank"><img src="https://img.shields.io/badge/YouTube-red?style=flat-square&logo=youtube&logoColor=white" alt="Dolby.io on YouTube"/></a>
&nbsp; &nbsp; &nbsp; 
  <a href="https://twitter.com/dolbyio" target="_blank"><img src="https://img.shields.io/badge/Twitter-blue?style=flat-square&logo=twitter&logoColor=white" alt="Dolby.io on Twitter"/></a>
&nbsp; &nbsp; &nbsp;
  <a href="https://www.linkedin.com/company/dolbyio/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="Dolby.io on LinkedIn"/></a>
</div>



