# Hamza's Portfolio — Assignment 2

## Project Overview

Personal portfolio website developed for Web and Scripting Programming 

The portfolio contains four pages: Home, About Me, Projects, and Contact Me. Express routes handle requests, while EJS templates render the pages using reusable header and footer components.

## Links

- GitHub Repository: https://github.com/hamzaalsamraaie/hamza-portfolio-a2

## Current Progress

- Generated the project using Express Generator with EJS.
- Installed and updated project dependencies.
- Verified that the Express server starts successfully.
- Verified that the homepage and CSS load correctly.
- Ran `npm audit` and confirmed 0 vulnerabilities.
- Initialized Git and created a new public GitHub repository.
- Committed and pushed the initial project structure and README.
- Created four Express routes in `routes/index.js`: `/`, `/about`, `/projects`, and `/contact`.
- Created separate EJS templates for Home, About Me, Projects, and Contact Me.
- Created reusable `header.ejs` and `footer.ejs` partials.
- Implemented shared navigation across the portfolio pages.
- Added GitHub and LinkedIn links to the footer.
- Used `res.render()` to connect Express routes to their corresponding EJS templates.
- Verified that the Projects page renders correctly with the shared header, footer, and project information.


## Project Structure

The application follows the Express Generator structure, separating routes, EJS views, and public assets.

```text
hamza-portfolio-a2/
├── app.js
├── bin/
│   └── www
├── routes/
│   ├── index.js
│   └── users.js
├── views/
│   ├── index.ejs
│   ├── about.ejs
│   ├── projects.ejs
│   ├── contact.ejs
│   ├── error.ejs
│   └── partials/
│       ├── header.ejs
│       └── footer.ejs
├── public/
│   ├── images/
│   ├── javascripts/
│   └── stylesheets/
│       └── style.css
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## Technologies

- Node.js
- Express.js
- EJS
- CSS
- JavaScript


## Testing and Validation

- Verified that the Express server starts using `npm start`.
- Verified that the original Express homepage loads correctly.
- Verified that the stylesheet is served successfully.
- Ran `npm audit` and confirmed 0 vulnerabilities.
- Verified that `/projects` displays the Projects page.
- Confirmed that the Projects page displays its headings and project descriptions.
- Verified that the shared header and footer render correctly on the Projects page.
- Confirmed that the navigation and GitHub/LinkedIn links are displayed.



## Version Control

A separate public GitHub repository was created for Assignment 2 to demonstrate version control and project development.

### Completed Git Commits
1. `a30b985` — Assignment 2: Initialize Express Generator with EJS.
2. `5047215` — Document Phase 1 setup and verification.

Additional commits will document new features, styling, testing, and deployment.

## Sources

- INFR3120U — Assignment 2 Express Portfolio instructions.
- INFR3120U — MEAN Stack Development lecture.
- INFR3120U — WebProject classroom demonstration.
- INFR3120U — Week 1–4 lecture materials.
- Connolly and Hoar — *Fundamentals of Web Development*, Chapters 8–10.
- Express Generator documentation: https://expressjs.com/en/starter/generator.html
- EJS documentation: https://ejs.co/

## Development Assistance

ChatGPT was used to explain what Express.js is and what EJS is. Any code that comes from sources will be written down properly to follow the rules about honesty, in the assignment.
