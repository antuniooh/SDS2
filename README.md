<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/antuniooh/dsDeliver-sds2">

  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/antuniooh/dsDeliver-sds2">
  
  <a href="https://github.com/antuniooh/dsDeliver-sds2/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/antuniooh/dsDeliver-sds2">
  </a>
  
   <img alt="GitHub" src="https://img.shields.io/github/license/antuniooh/dsDeliver-sds2">
</p>

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/antuniooh/dsDeliver-sds2">
    <img src="https://github.com/antuniooh/dsDeliver-sds2/blob/master/front-web/src/Home/main.svg" alt="Logo" width="550">
  </a>
</p>

<p align="center">
  <img alt="Spring" src="https://img.shields.io/badge/SpringBoot-yellow?style=for-the-badge&logo=spring&logoColor=white"/>
  <img alt="Java" src="https://img.shields.io/badge/Java-orange?style=for-the-badge&logo=java&logoColor=white"/>
  <img alt="Angular" src="https://img.shields.io/badge/Angular-red?style=for-the-badge&logo=angular&logoColor=white"/>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-blue?style=for-the-badge&logo=typescript&logoColor=white"/>
    <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-yellow?style=for-the-badge&logo=javascript&logoColor=white"/>
  <img alt="HTML" src="https://img.shields.io/badge/HTML-orange?style=for-the-badge&logo=html5&logoColor=white"/>
  <img alt="CSS" src="https://img.shields.io/badge/CSS-darkblue?style=for-the-badge&logo=css3&logoColor=white"/>
</p>


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#-about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#-how-to-run">How To Run</a>
    </li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## 💻 About The Project
DSDeliver project, this project taught in the week of dev superior 2.0. It consists of a web/mobile application where the user can place orders at a restaurant, as well as delivery people can cancel orders. Connecting in this way, user and delivery people
There is an API developed in Spring Boot, in which requests are registered / removed / edited in the database, this API also returns the available products. In addition, the entire interface is done with the user through a React application that is consuming this Java API.

![app](https://github.com/antuniooh/dsDeliver-sds2/blob/main/images/app.gif)


<!-- HOW TO RUN -->
## 🚀 How To Run
⚠️ For a better experience, open the project in the following link: https://ds-deliver-antonio.netlify.app/ ⚠️

On both Windows and Linux, the execution is done from an IDE of your choice, to run a Java API. The API will be running locally on port 8080.

In addition to the API, it is also necessary to run the Angular application. For this you must execute:

```bash

# Clone the repository
$ git clone https://github.com/antuniooh/dsDeliver-sds2.git

# Access the project folder in your terminal / cmd
$ cd dsDeliver-sds2/front-web

# Install libs
$ npm install

# Deploy 
$ npm start

```
The project will be hosted at "localhost:3000"
