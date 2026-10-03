# Zumba with Lenka

A one-page static website for Lenka's Zumba classes. It uses dark black/purple styling and opens on a full-screen dance video.

## Files

- `index.html` contains the whole site (HTML, CSS and JS in one file)
- `assets/hero-720.mp4` is the background video (720p, about 3.8 MB), loaded on desktop only
- `assets/hero-poster.jpg` is the first frame of the video, shown on phones and tablets, with reduced motion or data saver on, and while the video loads

## Preview

Double-click `index.html` to open it in your browser.

## Editing

The site is in Slovak (`lang="sk"`).

- **Texts:** the About section, testimonials and FAQ are plain HTML in `index.html`

### Temporarily hidden sections

These are commented out in `index.html` and can be brought back later:

- **Class styles ("Štýly hodín"):** remove the `<!-- ===== DOČASNE SKRYTÉ: Štýly hodín` comment wrapper, and uncomment the "Hodiny" link in the menu
- **Weekly timetable ("Týždenný rozvrh"):** remove the `<!-- ===== DOČASNE SKRYTÉ: Týždenný rozvrh` comment wrapper, and uncomment the "Rozvrh" link in the menu. Class times are in the `SCHEDULE` object at the top of the `<script>`.

## Hosting on GitHub Pages

Push to `main`, then go to **Settings → Pages → Deploy from branch → main / root**.
