# Saeed Turabzadeh - Portfolio Website

Personal portfolio website for Saeed Turabzadeh, Perception Technical Lead. Built with HTML, CSS, and JavaScript, hosted on GitHub Pages.

**Live site:** [saeedturabzadeh.github.io](https://saeedturabzadeh.github.io)

## Project Structure

```
saeedturabzadeh.github.io/
├── index.html                  # Main homepage (single-page layout)
├── cv/
│   ├── saeed-turabzadeh-cv.html        # CV page (website-integrated)
│   ├── saeed-turabzadeh-cv-print.html  # CV standalone (for PDF generation)
│   ├── saeed-turabzadeh-cv.pdf         # Downloadable PDF
│   └── README.md                       # CV update instructions
├── projects/
│   ├── project-autonomous-trucks.html  # Autonomous Terminal Trucks (ATT)
│   ├── project-chassis-alignment.html  # Chassis Alignment System (CAS)
│   ├── project-ship-scanning.html      # Ship Profile Scanning System (SPSS)
│   └── project-wizo-robot.html         # Humanoid Robot (WIZO)
├── insights/
│   ├── 2026-04-05-future-of-perception.html
│   ├── 2026-03-20-leadership-in-tech.html
│   ├── 2026-03-05-lidar-vs-camera.html
│   ├── 2026-02-15-deploying-ai-production.html
│   └── blog-template.html              # Template for new insight posts
├── assets/
│   ├── css/main.css                    # Main stylesheet
│   ├── js/main.js                      # Main JavaScript
│   ├── img/                            # Images, favicon, icons
│   ├── video/                          # Project videos
│   └── vendor/                         # Third-party libraries
├── forms/
│   └── contact.php                     # Contact form handler
├── CHANGELOG.md
├── LICENSE
└── README.md
```

## Sections

| Section | Description |
|---------|-------------|
| **Home** | Hero section with introduction and social links |
| **About** | Professional summary and core competencies |
| **Experience** | Work history and education timeline |
| **Projects** | Featured project portfolio with detail pages |
| **Publications** | Academic and industry publications |
| **Insights** | Technical articles and leadership posts |
| **Endorsements** | Professional testimonials |
| **Contact** | Contact form and information |

## Tech Stack

- **HTML5 / CSS3 / JavaScript** - Core technologies
- **Bootstrap 5** - Responsive grid and components
- **AOS** - Animate on Scroll library
- **Swiper** - Touch-friendly sliders
- **GLightbox** - Image lightbox
- **Isotope** - Filtering and sorting layouts
- **Typed.js** - Typing animation effect
- **Bootstrap Icons** - Icon library
- **PureCounter** - Animated counters

## Local Development

Open `index.html` in a browser, or use a local server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve .
```

Then visit `http://localhost:8000`.

## Deployment

This site is deployed via [GitHub Pages](https://pages.github.com/). Push changes to the `main` branch and the site updates automatically.

```bash
git add .
git commit -m "description of changes"
git push origin main
```

## Updating the CV

See [`cv/README.md`](cv/README.md) for detailed instructions on editing the CV and regenerating the PDF.

## Adding a New Insight Post

1. Copy `insights/blog-template.html` and rename with the date and slug (e.g., `2026-05-01-new-topic.html`)
2. Edit the content, title, meta description, and images
3. Add navigation links (Previous/Next Insight) to the new post and update the adjacent post
4. Add the post card to the Insights section in `index.html`

## Adding a New Project

1. Copy an existing project page from `projects/` as a template
2. Update the content, images, tech stack, and achievements
3. Update Previous/Next Project navigation links on the new and adjacent pages
4. Add the project card to the Projects section in `index.html`
