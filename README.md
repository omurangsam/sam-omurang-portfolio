# Sam Omurang — Personal Portfolio Website

## Project idea

Build a modern, accessible, and responsive personal portfolio website for Sam Omurang. The website introduces the developer, presents their skills and learning journey, showcases web-development practice projects, and provides a contact-form demonstration. It is designed to be viewed on desktop computers, tablets, and mobile phones.

## Project objective

The objective is to apply the fundamentals of **HTML5, CSS3, JavaScript, and responsive web design** in one complete project. The page uses semantic HTML elements, organised CSS, and JavaScript interactions to create a clear experience for visitors such as recruiters, Ausbildung employers, and other developers.

## Technologies

- **HTML5:** semantic page structure, navigation, sections, articles, project content, labels, and form fields.
- **CSS3:** layout with Flexbox and Grid, design variables, responsive breakpoints, hover/focus states, colour themes, and reduced-motion support.
- **JavaScript:** mobile navigation, light/dark theme, project filtering, form validation demonstration, active navigation state, automatic footer year, and back-to-top visibility.

## Website sections

1. **Home:** introduction, role, and links to projects and contact.
2. **About:** background, learning approach, and career goal.
3. **Skills:** HTML, CSS, JavaScript, Git/GitHub, responsive design, and debugging.
4. **Projects:** Ugandan Kigere Recipe, ReDI Café, Café Receipt Generator, and Password Validator.
5. **My Journey:** current web-development learning, previous IT training, and accounting/finance education.
6. **Contact:** a browser-validated demonstration form.

## Folder structure

```text
sam-portfolio/
├── index.html
├── README.md
├── css/
│   └── style.css
└── js/
    └── script.js
```

## How to run the project

1. Download and extract the project folder.
2. Open the `sam-portfolio` folder in Visual Studio Code.
3. Open `index.html` in your browser, or run it with the Live Server extension.
4. Test the navigation at desktop and mobile widths.
5. Try the light/dark theme, project filters, and contact-form validation.

No framework, package installation, external font, or third-party JavaScript library is required.

## JavaScript features to demonstrate

- **Responsive menu:** opens and closes using a button, updates `aria-expanded`, and closes after a section is selected.
- **Colour theme:** switches between light and dark themes and remembers the selection when browser storage is available.
- **Project filter:** displays all projects or filters by HTML/CSS and JavaScript categories.
- **Form validation:** uses built-in HTML validation and JavaScript to display a confirmation message.
- **Active navigation:** uses `IntersectionObserver` to highlight the section currently being viewed.
- **Current year and back-to-top:** updates the footer year automatically and shows a back-to-top link after scrolling.

## Semantic HTML and accessibility

The project uses landmarks and meaningful elements including `header`, `nav`, `main`, `section`, `article`, `form`, and `footer`. Form controls have labels, the mobile menu exposes its expanded state, project filters expose their selected state, keyboard focus is visible, a skip link supports keyboard users, and reduced-motion preferences are respected.

## Important note about the contact form

The contact form is intentionally **front-end only**. It validates inputs in the browser but does not send or store a message. To accept real messages, connect the form to a backend or a trusted form service and update the page text accordingly.

## Before submission

- Review the personal introduction and make sure every detail is accurate.
- Add real links to your GitHub repositories and live demos when you have them.
- Test on a phone-sized screen and a desktop screen.
- Check every navigation link and button.
- Keep project descriptions honest about whether each project is a practice project or a finished deployment.

## Expected learning outcome

After completing this project, I can demonstrate how semantic HTML, responsive CSS, and JavaScript work together to create a structured and interactive website. I can also explain my file organisation, accessibility choices, and the purpose of each interactive feature.
