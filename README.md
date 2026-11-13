# Hamza's Portfolio — Assignment 2

## Project Overview

Personal portfolio website developed for INFR3120U — Web and Scripting Programming at Ontario Tech University.

The portfolio contains four pages: Home, About Me, Projects, and Contact Me. Express routes handle requests, while EJS templates render the pages using reusable header and footer components. Bootstrap and Font Awesome are used for responsive design and icons.

## Links

- GitHub Repository: https://github.com/hamzaalsamraaie/hamza-portfolio-a2


## Current Progress

### Phase 1 — Express Generator Setup

- Generated the project using Express Generator with EJS.
- Installed and updated project dependencies.
- Verified that the Express server starts successfully.
- Ran `npm audit` and confirmed 0 vulnerabilities.
- Initialized Git and created a public GitHub repository.
- Committed and pushed the initial project files and README.

### Phase 2 — Express Routes and EJS Views

- Created four Express routes in `routes/index.js`: `/`, `/about`, `/projects`, and `/contact`.
- Created separate EJS templates for Home, About Me, Projects, and Contact Me.
- Created reusable `header.ejs` and `footer.ejs` partials.
- Implemented shared navigation between portfolio pages.
- Added GitHub and LinkedIn links to the footer.
- Used `res.render()` to connect Express routes to EJS templates.
- Tested the pages locally using the Express server.

### Phase 3 — Bootstrap, Font Awesome, and Responsive Design

- Installed Bootstrap and Font Awesome using npm.
- Organized framework assets inside the `public/vendor` folder.
- Implemented responsive Bootstrap navigation with a mobile hamburger menu.
- Added Font Awesome icons to navigation, cards, buttons, and social links.
- Updated the shared header and footer with consistent styling.
- Redesigned the Home page with an introduction and four overview cards.
- Updated the About Me page with education, certification, technical skills, and career interests.
- Redesigned the Projects page with five responsive Bootstrap project cards.
- Updated the Contact Me page with GitHub and LinkedIn contact cards.
- Added custom CSS using the blue-and-teal color scheme from Assignment 1.

## Project Structure

The application follows the Express Generator structure, separating Express routes, EJS views, and public assets.

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
│   ├── stylesheets/
│   │   └── style.css
│   └── vendor/
│       ├── bootstrap/
│       └── fontawesome/
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## Technologies

- Node.js
- Express.js
- EJS
- JavaScript
- HTML markup within EJS templates
- CSS
- Bootstrap 5
- Font Awesome


## Testing and Validation

### Phase 1 — Express Setup

- Verified that the Express server starts using `npm start`.
- Verified that the original Express homepage loaded correctly.
- Verified that the stylesheet was served successfully.
- Ran `npm audit` and confirmed 0 vulnerabilities.

### Phase 2 — Express Routes and EJS

- Verified that the four portfolio pages render using EJS.
- Confirmed that the shared header and footer display correctly.
- Tested the portfolio navigation and page content.

### Phase 3 — Responsive Design

- Verified that Bootstrap and Font Awesome load correctly.
- Confirmed that all four pages display their Bootstrap components and icons.
- Tested mobile layouts at 375 px and tablet layouts at 768 px.
- Confirmed that Bootstrap cards stack vertically on smaller screens.
- Checked the mobile navigation layout.
- Ran `npm audit` and confirmed 0 vulnerabilities.

## Version Control

A separate public GitHub repository was created for Assignment 2 to demonstrate version control and project development.

### Completed Git Commits

1. `a30b985` — Assignment 2: Initialize Express Generator with EJS.
2. `5047215` — Document Phase 1 setup and verification.

Additional commits document the EJS pages, responsive styling, and further development. The complete commit history is available in the public GitHub repository.

## Sources

- INFR3120U — Assignment 2 Express Portfolio instructions.
- INFR3120U — MEAN Stack Development lecture.
- INFR3120U — WebProject classroom demonstration.
- INFR3120U — Week 1–4 lecture materials.
- Connolly and Hoar — *Fundamentals of Web Development*, Chapters 8–10.
- Express Generator documentation: https://expressjs.com/en/starter/generator.html
- EJS documentation: https://ejs.co/
- Bootstrap documentation: https://getbootstrap.com/docs/5.3/
- Font Awesome documentation: https://docs.fontawesome.com/

Bootstrap and Font Awesome are third-party libraries used for the assignment's required responsive framework and icons. Their distributed assets are kept separately in the `public/vendor` directory.

## Development Assistance

ChatGPT was used to explain Express.js and EJS concepts, review assignment requirements, suggest design ideas, troubleshoot development, and provide initial examples for EJS templates, Express routes, Bootstrap components, and CSS.

