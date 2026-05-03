# Pink Glow Facial Room — Client Website

A responsive, single-page marketing website built for **Pink Glow Facial Room**, an aesthetics and Korean skincare studio located in Manasquan, NJ. Owned and operated by Nikki Fitzsimmons, Pink Glow offers luxury facial treatments, waxing, and customized Korean skincare using Ahohwa by PureRaum.

🌐 **Live Site:** [pinkglowfacialroom.com](https://pinkglowfacialroom.com)

---

## Project Overview

This is a static website designed and developed by [Crafted Digital](https://crafteddigital.co/) for the client. It serves as the primary web presence for Pink Glow Facial Room, providing visitors with information about the studio's services, brand story, and contact details — along with direct links to book appointments and purchase gift cards.

---

## Features

- Single-page layout with smooth anchor navigation
- Appointment booking integration via [Fresha](https://www.fresha.com)
- Gift card purchase link
- Contact form with success redirect page (`success.html`)
- Mobile-responsive design
- Component reference page (`elements.html`) for design system reference

---

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and markup |
| CSS3 | Styling and layout |
| SCSS | CSS preprocessor / source styles |
| JavaScript | UI interactions and behavior |

No frameworks or build tools are required to run the site. It is a fully static site that can be served from any web host.

---

## Project Structure

```
nikkis-site/
├── index.html          # Main single-page site
├── success.html        # Contact form success page
├── elements.html       # Design system / component reference
├── assets/             # JS, CSS, and other compiled assets
├── images/             # Site imagery and logos
├── package-lock.json   # Dependency lock file
├── .gitignore
└── LICENSE.txt         # Creative Commons Attribution 3.0
```

---

## Getting Started

Since this is a static site, no build process is required to view it locally.

1. Clone the repository:
   ```bash
   git clone https://github.com/robregan/nikkis-site.git
   ```

2. Open `index.html` in your browser, or serve it with a local server:
   ```bash
   npx serve .
   ```

If you are editing SCSS styles, compile them to CSS using your preferred SCSS compiler (e.g. the VS Code Live Sass Compiler extension or the `sass` CLI).

---

## Client Info

| | |
|---|---|
| **Business** | Pink Glow Facial Room |
| **Owner** | Nikki Fitzsimmons |
| **Location** | 52A Main Street, Manasquan, NJ 08736 |
| **Email** | info@pinkglowfacialroom.com |
| **Phone** | (732) 768-1769 |
| **Instagram** | [@pinkglow_facialroom](https://www.instagram.com/pinkglow_facialroom/) |
| **Facebook** | [brilliantskinbynikki](https://www.facebook.com/brilliantskinbynikki) |

---

## License

This project is licensed under the [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/). See `LICENSE.txt` for full details.

---

*Designed & developed by [Crafted Digital](https://crafteddigital.co/)*
