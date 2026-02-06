# Africa Bora Soccer Academy

A public website showcasing our soccer academy, teams, and coaches. Built with plain HTML and optimized for slow/remote connections in Africa.

## About

Africa Bora Soccer Academy is dedicated to developing young talent while building character, discipline, and teamwork. We provide opportunities for youth in our community to learn, grow, and excel both on and off the field.

## Location

**Africa Bora Sport Training Center**
- Village: Kibaya
- Cell: Rugerero
- Sector: Rugerero
- District: Rubavu
- Western Province, Rwanda

## Website Structure

- **Homepage** (`index.html`) - Overview of the academy and mission
- **About Page** (`about.html`) - Organization story, values, and community impact
- **Teams Directory** (`teams.html`) - Overview of all age group teams
  - U8 Team (`teams/u8.html`) - Ages 6-8
  - U11 Team (`teams/u11.html`) - Ages 9-11
  - U13 Team (`teams/u13.html`) - Ages 12-13
  - U15 Team (`teams/u15.html`) - Ages 14-15
  - U17 Team (`teams/u17.html`) - Ages 16-17
- **Coaches Directory** (`coaches.html`) - Coaching staff overview
  - Individual coach profiles in `coaches/` directory

## Technology

- **HTML5** - Plain HTML for maximum compatibility
- **Pico CSS** - Lightweight (~10kb) classless CSS framework delivered via CDN
  - Optimized for slow connections
  - No JavaScript required
  - Works without CSS classes
  - Mobile responsive

## GitHub Pages Deployment

To enable GitHub Pages for this repository:

1. Go to repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch you want to deploy (e.g., `main` or `copilot/build-soccer-academy-site`)
4. Click "Save"
5. Your site will be published at: `https://africaboraministries.github.io/SoccerSiteDemo/`

The `.nojekyll` file ensures GitHub Pages serves the HTML files directly without Jekyll processing.

## Local Development

To test the site locally:

```bash
# Using Python 3
python3 -m http.server 8000

# Then open http://localhost:8000 in your browser
```

## Features

- ✅ Multiple team pages with rosters and schedules
- ✅ Coach directory with detailed profiles
- ✅ Organization information and community impact
- ✅ Lightweight design optimized for slow connections
- ✅ Mobile responsive
- ✅ No JavaScript required
- ✅ Works offline once CSS is cached
