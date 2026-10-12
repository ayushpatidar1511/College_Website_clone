# Raja Mahendra Pratap Singh University, Aligarh – Website

A responsive front-end website for Raja Mahendra Pratap Singh University (RMPSU), Aligarh. Built with plain HTML, CSS and Bootstrap 5, it works on mobile, tablet and desktop screens.

---

## Features

- **Top contact bar** with email, phone and quick links (Sitemap, Accessibility, Login, Contact Us)
- **Header** with university logo, English and Hindi name, and action buttons (Admission, About University, Results)
- **Sticky main menu** with dropdowns (About University, Academics, Facilities); hover on desktop, tap on mobile
- **Hero section** with a full-width background video and "Apply Now" button
- **About section** with a short welcome text
- **Achievements section** with animated cards (certifications, students, tie-ups, publications)
- **Quick Access** cards (Admission, Examination, Results, Student Helpdesk, Syllabus, Online Services, Academic Calendar, Contact Us)
- **Notices | Events | Circulars** with auto-scrolling lists (pause on hover)
- **Important Websites** with an infinite logo slider (pauses on hover)
- **Footer** with address, phone, email, useful links, social icons and a subscribe box
- Fully **responsive** layout and `prefers-reduced-motion` support

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Custom styling and animations |
| [Bootstrap 5.3.8](https://getbootstrap.com/) | Grid, navbar, cards, buttons |
| [Font Awesome 7](https://fontawesome.com/) | Icons |
| [Google Fonts – Poppins](https://fonts.google.com/specimen/Poppins) | Typography |

All libraries are loaded from a CDN, so an internet connection is required.

---

## Folder Structure

```
project-folder/
│
├── index.html            # Home page
├── history.html          # History page
├── vission & Mission.html
├── glance.html           # University at a Glance
├── governance.html
├── Acts.html
│
├── css/
│   └── style.css         # All custom styles
│
└── image/
    ├── video1.mp4        # Hero section video
    └── history.jpg       # History page banner
```

> Only `index.html` and `css/style.css` are included in this version. The other pages and the `image/` folder need to be present for every menu link and media file to work.

---

## How to Run

1. Download or clone the project folder.
2. Make sure the structure matches the one above (`index.html` outside, `style.css` inside `css/`).
3. Open `index.html` in any modern browser.

**Recommended:** use the **Live Server** extension in VS Code (right-click `index.html` → *Open with Live Server*) so that video and assets load smoothly.

---

## Responsive Behaviour

| Screen | Behaviour |
|---|---|
| Mobile (< 576px) | Single or two-column cards, collapsed menu, stacked header and buttons |
| Tablet (576px – 991px) | Two-column cards, collapsed menu |
| Desktop (≥ 992px) | Full menu with hover dropdowns, 3 to 4 column layouts |

---

## Customization

- **Colours:** the main theme colour is `#972727` (maroon). Other accents are `#B71C1C`, goldenrod and orange. Change them in `css/style.css`.
- **Hero video:** replace `image/video1.mp4` with your own video, or edit the `<source>` tag in `index.html`.
- **About image:** the current image is a placeholder from Wikimedia Commons. Replace the `src` in the About section with your university photo.
- **Notices, Events, Circulars:** edit the `<li>` items inside the `.ticker-list` lists. Keep the repeated (`aria-hidden`) items identical to the originals so the loop scrolls smoothly.
- **Important Websites:** add or remove `.website-card` blocks. Keep the second (duplicate) set the same as the first.
- **Contact details:** update the email, phone and address in the top bar and the footer.

---

## To-Do

- [ ] Add real links for the Academics and Facilities dropdown items
- [ ] Create the remaining pages (Faculties, College List, Research, Campus, Career, etc.)
- [ ] Replace placeholder text and the About image with official content
- [ ] Add links to the Quick Access cards
- [ ] Connect the Subscribe form to a backend or mailing service
- [ ] Add a favicon and meta description for SEO

---

## Browser Support

Latest versions of Chrome, Edge, Firefox and Safari.

---

## License

This project is for educational and institutional use. Update this section with the license of your choice.