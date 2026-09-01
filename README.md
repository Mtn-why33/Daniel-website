# Daniel Okike – Portfolio Website

A single-page personal portfolio site for Daniel Okike, a junior web developer. Built with semantic HTML5 and external CSS.

## Sections

- **Home** – Hero intro with profile photo and links (LinkedIn, GitHub, personal site)
- **About** – Bio and key web-development terminology (semantic HTML, CSS box model, responsive design)
- **Skills** – Core technical skills (HTML5, CSS3/Flexbox/Grid, WordPress, graphic design)
- **Experience** – Education/career timeline plus a detailed experience table
- **Projects** – Featured project cards (Recipe Finder, E-commerce landing page, etc.)
- **Services** – Web development, graphic design, WordPress, and digital training offerings
- **Multimedia** – Introduction video, audio welcome note, and an embedded Google Map
- **Contact** – A detailed contact form (name, email, phone, DOB, gender, subject, message, preferred contact method, country, password fields, terms checkbox)

## Files Needed

This page expects the following assets alongside `daniel.html`:

```
daniel.html
daniel.css
images/
  ├─ project1.jpg
  ├─ project2.jpg
  └─ ... (other project screenshots)
videos/
  └─ introduction.mp4
audio/
  └─ introduction.mp3
```

Note: `daniel.css`, the project images, and the video/audio files are referenced but not included in this upload — add them to the same folder structure for the page to display and function correctly.

## External Dependencies

- **Google Fonts** – Inter font family (loaded via CDN, requires internet connection)
- **Google Maps embed** – iframe for the location section (requires internet connection)

## How to Run

1. Place `daniel.html`, `daniel.css`, and the `images/`, `videos/`, `audio/` folders in the same directory.
2. Open `daniel.html` directly in a web browser, or serve the folder with a local server (e.g. `python3 -m http.server`) for best results with relative paths.

## Notes

- The contact form currently submits to `#` (a placeholder) — it needs a real backend endpoint or a form service (e.g. Formspree) to actually send messages.
- The password fields in the contact form are unusual for a portfolio contact form — worth double-checking whether that's intentional, as collecting passwords via a public contact form is a security/privacy concern.
