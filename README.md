# Opulent Touch

A responsive, single-page website for Opulent Touch Cleaning Services. It introduces the business, presents its cleaning services, and lets visitors prepare an enquiry.

## Features

- Sections for the business story, service highlights, and client preferences
- Three service options: home care, deep refresh, and moving home
- Responsive navigation with a mobile menu
- Enquiry form with browser validation and service preselection from service cards
- Accessible labels, keyboard focus styles, and reduced-motion support

## Run locally

This project is plain HTML, CSS, and JavaScript; it has no build step or package dependencies. Open `index.html` directly in a browser, or serve the project directory locally:

```sh
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Project files

- `index.html` — page structure and content
- `styles.css` — layout, visual styling, responsive behavior, and animations
- `script.js` — menu interactions, service selection, enquiry feedback, and footer year

## Enquiry form

The form currently runs only in the browser. After validating the required fields, it displays a confirmation message; it does not send or store submitted details. Connect it to an enquiry service or backend before using the site to receive real enquiries.

Google Fonts and the Unsplash background images are loaded remotely, so an internet connection is needed to display those assets.
