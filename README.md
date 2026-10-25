# MediNova Hospital Website

A responsive, multi-page hospital website built with **HTML**, **Bootstrap 5** and **Font Awesome** as a Bootstrap assignment.

## Pages

| Page | File | What it has |
|---|---|---|
| Home | `home.html` | Image carousel, short about section, featured services |
| About | `about.html` | Hospital overview, stats, mission and vision, doctors |
| Services | `services.html` | Emergency, Cardiology, Dental, Neurology, Pharmacy, Laboratory |
| Contact | `contact.html` | Message form with validation, contact details, Google Map, WhatsApp button |

## Features

- Responsive layout that works on mobile, tablet and desktop
- Navbar with services dropdown and active-page highlighting
- Bootstrap carousel on the home page
- Contact form with client-side validation
- Click-to-call (`tel:`) and click-to-email (`mailto:`) links
- Embedded Google Map

## Built With

- HTML5
- [Bootstrap 5.3.8](https://getbootstrap.com/) (via CDN)
- [Font Awesome 6.5.2](https://fontawesome.com/) (via CDN)
- A little vanilla JavaScript (form validation)

## How to Run

1. Clone or download this repository.
2. Open `home.html` in any browser.

An internet connection is needed because Bootstrap and Font Awesome load from a CDN.

## Project Structure

```
Bootstrap Assignment/
├── home.html
├── about.html
├── services.html
├── contact.html
└── *.png / *.jpg      (logo, banners, doctor photos)
```

## Notes

- The contact form validates input and shows a confirmation message, but it does not send data anywhere because there is no backend.
- The address, phone number and emails are sample data.

## Author

Made by **Your Name**
