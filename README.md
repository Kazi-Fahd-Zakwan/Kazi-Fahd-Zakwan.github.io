# Kazi Fahd Zakwan — Portfolio & Profile Analysis

A single-page profile analysis website built from my resume, featuring an interactive skills breakdown, career timeline, certifications, and profile insights.

## Live Preview

Served locally at `http://localhost:3000` using `npx serve`.

## Project Structure

```
portfolio/
├── index.html                  # Main single-page application
├── favicon.svg                 # KFZ hexagon diamond logo (favicon)
├── profile.jpg                 # Profile headshot
├── Resume_KaziFahdZakwan.pdf   # Downloadable CV
└── .claude/
    └── launch.json             # Dev server configuration
```

## Sections

| Section | Description |
|---|---|
| **Hero** | Profile photo, name, title, social links, key stats, CV download |
| **Career Summary** | Professional objective and core skill tags |
| **Experience** | Timeline of roles at IdeaScale and Sheba Platform |
| **Skills** | Animated progress bars and radar chart across 4 skill categories |
| **Certifications** | ISTQB CTFL® and Scrum Alliance CSM® |
| **Profile Insights** | Derived strengths and growth opportunities |
| **Education** | BSc Computer Science, BRAC University (CGPA 3.56/4.00) |

## Running Locally

```bash
npx serve -p 3000 .
```

Or with Python:

```bash
python3 -m http.server 3000
```

Then open `http://localhost:3000` in your browser.

## Tech Stack

- Vanilla HTML, CSS, JavaScript — no frameworks or build tools
- [Chart.js](https://www.chartjs.org/) for the radar chart
- Inline SVG for the KFZ hexagon logo and favicon

## Features

- Animated skill bars (triggered on scroll)
- Radar chart for skill category overview
- Scroll-to-top button (appears after 300px scroll)
- Sticky navbar with smooth section navigation
- Responsive layout (mobile nav collapses)
- Hero entrance animations with staggered fade-up

---

**Kazi Fahd Zakwan** · [linkedin.com/in/fahdzakwan](https://linkedin.com/in/fahdzakwan) · [github.com/Kazi-Fahd-Zakwan](https://github.com/Kazi-Fahd-Zakwan)
