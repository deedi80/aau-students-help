# AAU Students Helpdesk - Frontend

Welcome to the frontend repository for the AAU Students Helpdesk, a web application designed to assist students of Ambrose Alli University with various support requests. This README provides an overview of the project, setup instructions, and usage details for the frontend components.

## Overview

This project was originally developed in 2019 as part of the requirements 
for the award of a BSc in Computer Science at Ambrose Alli University, Ekpoma, Nigeria. 
It has been uploaded here for reference, version control, and knowledge sharing. 

The AAU Students Helpdesk frontend is a static website built with HTML, CSS, and JavaScript. It includes pages for user registration, login, password reset, and a dashboard to submit and view support requests. The design is responsive and uses Bootstrap for styling.

## Project Structure

```
aau-students-helpdesk/
├── css/
│   ├── half-slider.css
│   └── style.css
├── img/
│   ├── chris-oyakhilome-building.jpg
│   ├── fps-building.jpg
│   ├── fls-building.jpg
│   ├── logo-footer.png
│   ├── aau.png
│   └── favicon.png
├── users/
│   ├── index.html          - Login page
│   ├── registration.html   - Registration page
├── index.html              - Landing page
└── README.md
```

- **`css/`**: Contains custom stylesheets for the web application.
- **`img/`**: Stores images used in the frontend (e.g., logo, sliders).
- **`users/`**: Houses the main user interface pages.
- **`index.html`**: The entry point or landing page.

## Features

- **User Registration**: Allows new students to sign up.
- **Login**: Authenticates registered users.
- **Forgot Password**: Enables password reset requests.
- **Dashboard**: Displays submitted requests and allows new submissions.
- **Responsive Design**: Optimized for desktop and mobile devices.

## Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge).
- No server setup required for the static frontend.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/deedi80/aau-students-helpdesk.git
   cd aau-students-helpdesk
   ```

2. **Serve Locally**:
   - Use a local server to test (e.g., Live Server extension for VS Code or Python’s HTTP server):
     ```bash
     python -m http.server 8000
     ```
   - Open `http://localhost:8000` in your browser.

3. **Deploy**:
   - Upload the files to a static hosting service (e.g., Vercel Render, Netlify, GitHub Pages).
   - vercel link - https://aau-students-helpdesk.vercel.app/


## Contributing

Feel free to fork this repository and submit pull requests for improvements. Please follow these guidelines:
- Use consistent indentation (2 spaces).
- Add comments for complex logic.
- Test changes locally before submitting.

## Contact

For questions or support, contact Davison Isesele at [davison.isesele@deedixtech.com](mailto:davison.isesele@deedixtech.com).


### Notes
- This README assumes the frontend is static and doesn’t rely on the backend API. If you plan to integrate it later, we can update the document.
- Special thanks to Cephas Oselumese for his meaningful contribution towards achieving this project.