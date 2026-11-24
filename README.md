# ArogyaMitra – Health Companion

ArogyaMitra is a browser-based symptom guidance website. Users can describe symptoms by typing or voice, answer follow-up questions, and view general health guidance in a simple chat interface.

## Features

- Symptom search and guided symptom check-ins
- Voice input and read-aloud support (browser support required)
- Five interface/input languages: English, Telugu, Hindi, Tamil, and Kannada
- Severity, duration, age-group, and existing-condition questions
- Emergency-warning prompts for selected serious symptoms
- Recent check-in history saved in the current browser using `localStorage`
- Responsive layout for desktop and mobile screens

## Built with

- HTML5
- CSS3
- Vanilla JavaScript
- Browser Web Speech API (where supported)
- Browser `localStorage`
- Google Fonts

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. For the most reliable voice input, use a supported browser such as Chrome or Edge and allow microphone access. Browser speech recognition may require a secure context (HTTPS or localhost) and an internet connection.

No build step or package installation is required.

## Deploy with GitHub Pages

1. Push these files to a GitHub repository.
2. Open the repository on GitHub and select **Settings**.
3. Select **Pages** in the left sidebar.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/(root)` folder, then save.
6. Wait for the deployment to finish. GitHub will display the public website URL in the Pages section.

The repository root must contain `index.html` for this setup.

## Important health and privacy notice

ArogyaMitra provides general, rule-based symptom information for educational guidance only. It is **not a medical diagnosis**, does not replace a qualified healthcare professional, and should not be used to make treatment decisions or delay urgent care. In an emergency, contact local emergency services or go to the nearest emergency department.

Check-in history and preferences are stored in the browser on the device being used. They are not synchronized to a hospital system or cloud database by this version. Avoid entering names, contact details, medical record numbers, or other personally identifying or sensitive health information on a public demo.

## Current scope

This repository contains the standalone symptom-guidance interface supplied for ArogyaMitra. It is not, by itself, a complete Hospital Management System: it does not currently provide patient/doctor accounts, appointment booking, hospital administration, cloud medical records, billing, or a Gemini-powered AI backend.

## Project structure

```text
ArogyaMitra-GitHub/
├── index.html
├── README.md
├── .gitignore
└── assets/
    └── arogyamitra-logo.png
```

The logo is an optional branding asset; the website works without it.

## License

No license has been added. Unless you add a license, others do not automatically receive permission to reuse, modify, or distribute this project.
