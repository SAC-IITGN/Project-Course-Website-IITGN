# Project-Courses-Website

Website to showcase the project courses undertaken by students at IITGN during an academic year. Currently hosted using Cpanel on the IITGN domain: [https://students.iitgn.ac.in/student-acad-council/project-courses/](https://students.iitgn.ac.in/student-acad-council/project-courses/)

## Getting Started

- Ensure that you have Node and npm installed on your laptop. Run the following commands to check the versions of node and npm installed.
```
node --version
npm --version
```

- Clone the repository
```
git clone https://github.com/Reuben27/Project-Courses-Website.git
cd Project-Courses-Website
```

- Install the required node modules.
```
npm install
```

- Save the credentials file for the API (client_secret.json). This is required for the login system to work. In case you don't have it contact the developers or set up your own credentials for the same.

- Run the application and you can then view it on your browser. [http://localhost:3000](http://localhost:3000)
```
npm run dev
```

## Source Code Structure

Structuring the folders is a very important first step in organizing good code. The below figure shows the general structure of the my repository.

```
Project-Courses-Website
│   .gitignore
│   app.js
│   Procfile
│   README.md
│   package.json
└─── public
    └─── css
        │   index.css
        │   login.css
    └─── images
        │   *.jpg and *.png files
    └─── js
        │   index.js
        │   list.js
        │   login.js
└─── views
    │   index.ejs
    │   login.ejs
```

## Tech Stack

The website has been built using HTML, CSS, JS, NodeJS, and Google APIs.
