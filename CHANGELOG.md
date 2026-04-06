# Changelog

All notable changes to this website are documented in this file.

## [1.1.0] - 2026-04-06

### Added
- `projects/` directory - project detail pages moved here for better organisation
- `insights/` directory - renamed from `blog/` to reflect modern, professional tone
- Custom favicon and Apple Touch Icon featuring "ST" initials
- Floating "Download CV" button on the CV page
- CV page integrated into the main website template (header, nav, footer)
- PDF version of CV for download
- Standalone CV file (`cv/saeed-turabzadeh-cv-print.html`) for clean PDF generation
- AI-generated images for all project and insight pages
- `README.md`, `CHANGELOG.md`, and `LICENSE` files

### Changed
- **Section rename:** "Blog" → "Insights" (folder, section ID, navigation, all references)
- **Section rename:** "Resume" → "Experience" (section heading and navigation label)
- **Section rename:** "Professional Endorsements" → "Endorsements"
- **Terminology:** "Resume" → "CV" for document references (View CV button, CV page title)
- **Terminology:** "Post" → "Insight" in navigation buttons (Previous/Next/All)
- Site logo changed from "Saeed Turabzadeh" to "ST" across all pages
- Project pages moved from root to `projects/` directory with updated asset paths
- Blog pages moved from `blog/` to `insights/` directory
- Fixed `.page-title` padding in `main.css` to prevent header overlap on all sub-pages
- "Download Resume" link now opens in same tab instead of new tab

### Fixed
- Missing vendor files that caused broken counters, portfolio filters, and slow icon loading
- Unclickable "Home" breadcrumb link on CV, project, and insight pages (header overlap)

## [1.0.0] - 2026-04-05

### Added
- Initial website based on the Style template
- Homepage with hero, about, experience, projects, publications, insights, endorsements, and contact sections
- Project detail pages for ATT, CAS, SPSS, and WIZO
- Insight articles on perception systems, leadership, LiDAR vs camera, and AI deployment
- CV page with full professional history
- Contact form
- Responsive design for mobile, tablet, and desktop
