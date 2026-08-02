# Keerthana Gunaretnam — Portfolio

Personal research portfolio of **Keerthana (Ana) Gunaretnam**, computational biology and disease-omics researcher working across bioinformatics, astrobiology, and space biology.

A single-page static site covering research roles, publications, manuscripts, awards, projects, science writing, and contact details.

🔗 **Live site:** https://astro-keerthana.github.io/ *(update if your Pages URL differs)*
📄 **CV:** [`keerthana-gunaretnam-cv.pdf`](keerthana-gunaretnam-cv.pdf)
🧬 **ORCID:** [0000-0002-3979-7489](https://orcid.org/0000-0002-3979-7489)

---

## Sections

| Section | Contents |
|---|---|
| **About** | Bio, contact details, ORCID, social and writing links |
| **Resume** | Education (SLIIT, Bversity) and current research roles |
| **Expertise** | Computational biology, astrobiology, data science, hardware interfacing, science communication |
| **Skills** | Technical and research proficiency |
| **Projects** | Nine research and technical projects, plus design work |
| **Publications** | Published works with DOIs, and manuscripts under review |
| **Awards** | Honours, competitive selections, certifications and training |
| **Blog** | Medium articles on space biology and astronomy |
| **Wordsmith** | Creative writing on Wattpad |
| **Contact** | Email, phone, meeting booking, ORCID |

---

## Built with

- HTML5 / CSS3 / JavaScript
- [Bootstrap 4](https://getbootstrap.com/)
- jQuery, Owl Carousel, AOS, Waypoints, Magnific Popup, Scrollax
- Google Fonts (Poppins), Icomoon, Ionicons, Flaticon
- Base template by [Colorlib](https://colorlib.com), licensed CC BY 3.0

---

## Run locally

Clone the repository and open the page — no build step is needed.

```bash
git clone https://github.com/Astro-Keerthana/<repository-name>.git
cd <repository-name>
```

Open `index.html` in a browser, or serve it locally so paths resolve exactly as they do in production:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

---

## Structure

```
.
├── index.html          # the entire single-page site
├── css/                # theme and vendor stylesheets
├── js/                 # jQuery and plugin scripts
├── images/             # photos, project thumbnails, video assets
└── keerthana-gunaretnam-cv.pdf
```

Custom overrides (navigation spacing, collaboration band styling) live in a `<style>` block at the end of `<head>` in `index.html`, so they sit after `css/style.css` in the cascade and win without needing `!important` everywhere.

---

## Editing the content

- **Text, links, dates:** edit `index.html` directly — each section is commented and self-contained.
- **Project cards:** duplicate a `.project` block inside `#projects-section` and point `background-image` at your own file in `images/`.
- **Publications and awards:** add a `.resume-wrap` block with a `date`, an `h2` title, and a `position` line.
- **Images:** keep filenames free of spaces where possible; existing ones with spaces are escaped in the inline styles.

---

## Support this work

I publish research, science writing, and open-science resources independently. If something here helped you — a method, an article, a dataset walk-through — you can support the next piece of work.

☕📚 **[Buy me a book](https://buymeacoffee.com/keerthanaag)**

Contributions go toward:

- Journal and conference fees for manuscripts under review
- Books, papers, and reference material behind paywalls
- Compute and storage for bioinformatics and omics analyses
- Time spent writing open science communication and tutorials

Not able to contribute? Sharing an article, citing published work, or starring this repository helps just as much.

> The support link points to Buy Me a Coffee, where the support item is set to a book.

---

## Collaboration

Open to research collaboration in computational biology, disease omics, astrobiology, and space biology.

- **Email:** keerthana@aracreate.group
- **LinkedIn:** [keerthana-g-1ba8b3207](https://www.linkedin.com/in/keerthana-g-1ba8b3207)
- **Medium:** [@astro-keerthana](https://medium.com/@astro-keerthana)
- **Book a meeting:** [calendar link](https://calendar.app.google/hWJATgZzLvVmnFZH7)

---

## License

Site content, text, research descriptions, and images © Keerthana Gunaretnam. Please ask before reusing written content or images.

The underlying template is by [Colorlib](https://colorlib.com) under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/); the attribution in the footer is required by that license and should stay in place.
