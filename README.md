# SkillShare

A web-based platform prototype for connecting people who want to share and discover skills. Designed with a focus on clean visual hierarchy, intuitive navigation, and accessible interface patterns.

## Tech Stack

| Category   | Technology                                      |
|------------|-------------------------------------------------|
| Structure  | HTML5 (semantic markup)                         |
| Styling    | CSS3 (Flexbox, Grid, custom properties)         |
| Typography | Google Fonts (Julius Sans One, Bentham)          |
| Design     | Responsive layout, card-based UI, tag system     |

## Features

- **Split-screen landing** -- Clear visual separation between "Find Skills" and "Find Projects" entry points, guiding users to their goal immediately.
- **Skill and project cards** -- Consistent card components displaying name, role, tags, and descriptions for quick scanning.
- **Search interface** -- Dedicated search pages for browsing skills and projects by category.
- **User profiles** -- Profile pages displaying skills with proficiency levels (Beginner, Intermediate, Master) and associated projects.
- **Category navigation** -- Visual icon grid for skill categories including Design, Filming, and Coding.
- **Tag system** -- Color-coded tags for quick identification of skill areas and project types.

## Pages

| Page             | Description                                              |
|------------------|----------------------------------------------------------|
| `index.html`     | Landing page with split-screen layout and sample cards   |
| `skills.html`    | Search and browse skills by category                     |
| `projects.html`  | Search and discover projects                             |
| `profile.html`   | User profile with skills, proficiency levels, and projects |

## Design Decisions

- **Color palette** -- Black and white foundation with green accent (#4f9951) for interactive elements and tags, creating a clean and professional feel.
- **Typography** -- Julius Sans One for headings (modern, geometric) paired with Bentham for body text (readable, elegant).
- **Layout** -- CSS Flexbox for component alignment and CSS Grid for card and icon layouts, ensuring responsive behavior across screen sizes.
- **Card pattern** -- Bordered cards with consistent padding and structure for both skill and project listings, making content easy to scan.

## Getting Started

```bash
git clone https://github.com/MelodyccLo/SkillShare.git
cd SkillShare
```

Open `index.html` in a browser to view the prototype. No build step or server required.

## Future Enhancements

- Backend API with user authentication and database storage
- Dynamic skill and project creation
- Search and filtering functionality
- Messaging system for user connections
- Responsive mobile-first redesign

## Project Structure

```
SkillShare/
├── index.html          # Landing page
├── profile.html        # User profile page
├── skills.html         # Find Skills page
├── projects.html       # Find Projects page
├── styles/
│   ├── styles.css      # Main stylesheet
│   └── skills.css      # Skills page specific styles
└── images/             # Logos, icons, and assets
```
