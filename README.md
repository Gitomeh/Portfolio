# Portfolio

## What it does

This is a professional portfolio website for Gerald Njoroge Gitau, an AI & Full-Stack Developer. The portfolio showcases skills, experience, projects, and contact information to help potential employers, clients, and collaborators understand the developer's capabilities and work history.

**Who it is for:** Potential employers, clients, and collaborators looking for Full-Stack and AI development services.

**What problem/purpose it serves:** Provides a centralized, professional online presence that demonstrates technical skills, showcases completed projects, and makes it easy for interested parties to get in touch.

**Main features:**
- Responsive single-page design with smooth navigation
- Hero section with profile image and call-to-action
- About section with concise professional background
- Skills section with 4 categories (Frontend, Backend, Database, DevOps & Deployment) including AI-assisted programming, Three.js, Accessibility, Machine Learning, and Vercel deployment
- Experience section showing work history
- Projects section showcasing 6 portfolio projects
- Contact form and contact information
- Social media links
- Mobile-responsive design with hamburger menu
- Smooth scrolling and animations

## Setup

### Requirements/prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required
- No server-side setup needed (static HTML/CSS/JS)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Gitomeh/Portfolio.git
   cd Portfolio
   ```

2. No additional installation steps required - this is a static website.

### How to run locally
- Simply open `index.html` in a web browser
- Or use a local server (optional):
  ```bash
  # Using Python 3
  python -m http.server 8000
  # Then navigate to http://localhost:8000
  ```

### How to build/deploy
- No build process required (static HTML/CSS/JS)
- Can be deployed to any static hosting service:
  - GitHub Pages
  - Netlify
  - Vercel
  - AWS S3
  - Any web server

## Usage

### Navigation
- Use the navigation menu to jump between sections: Home, About, Skills, Experience, Projects, Contact
- On mobile devices, tap the hamburger menu to access navigation
- Click on any section name to smoothly scroll to that section

### Viewing Projects
- Scroll to the Projects section to view portfolio projects
- Each project card shows:
  - Project image
  - Project title
  - Brief description
  - Technology tags
  - Links to live demo and source code (where available)
- Hover over project cards to see hover effects

### Contact
- Use the contact form to send a message
- Alternatively, use the provided email, phone, location, LinkedIn, or GitHub links
- Note: The contact form currently shows an alert message (no backend integration)

## Architecture

```text
User
  ↓
Portfolio UI (index.html)
  ↓
HTML Structure
  ├── Semantic sections (Hero, About, Skills, Experience, Projects, Contact)
  ├── Inline CSS styling
  └── Inline JavaScript
  ↓
Browser Rendering
  ├── DOM manipulation
  ├── CSS animations
  └── Event handling
  ↓
Skills Display
  ├── Frontend (HTML/CSS, JavaScript/TypeScript, React/Next.js, Three.js/WebGL, Accessibility)
  ├── Backend (Node.js, Express.js, Python/AI, AI-Assisted Programming, Machine Learning)
  ├── Database (SQL, MongoDB, LLM Applications)
  └── DevOps & Deployment (Vercel, GitHub/Git, CI/CD)
  ↓
Static Display
```

**Technical components:**
- Single HTML file (`index.html`) containing all content
- Inline CSS within `<style>` tags for styling
- Inline JavaScript within `<script>` tags for interactivity
- External Font Awesome CDN for icons
- Images stored in `images/` directory
- No build process, no framework dependencies

## V2 evaluation results

Evaluation results: TODO — add verified V2 evaluation evidence.

No formal evaluation results were found in the repository. The project appears to rely on manual testing rather than automated evaluation frameworks.

## Limitations

- **No backend integration:** The contact form shows an alert message instead of actually sending emails
- **Limited interactivity:** Some project links are placeholders (#) rather than actual live demos
- **Single-file architecture:** All code is in one HTML file, which may become difficult to maintain as the project grows
- **No content management:** All content is hardcoded in HTML; no CMS or database
- **No analytics:** No built-in analytics or visitor tracking
- **Limited accessibility:** While some accessibility features exist (ARIA labels, focus states), full WCAG compliance has not been verified
- **Image optimization:** Images are not optimized for web performance
- **No testing:** No automated tests or test coverage

## AI transparency

AI was used as a development partner for implementation, debugging, documentation, and refinement. I reviewed the generated work, tested the application, verified functionality, and made the final implementation decisions.

Specific areas where AI assisted:
- Initial HTML structure and layout
- CSS styling and responsive design
- JavaScript interactivity (scroll effects, mobile menu, form handling)
- Documentation and README content
- Code debugging and optimization

I personally:
- Reviewed all generated code for accuracy and security
- Tested the portfolio in multiple browsers
- Verified responsive behavior on different screen sizes
- Made final decisions on design and functionality
- Ensured all content accurately reflects my actual skills and experience

---

## How to Add the Next Case Study

**Location:** Projects section in `index.html` (lines 735-864). Each project is a `.project-card` element within the `.projects-grid` container.

**Structure: Problem → What I Did → What Came of It**

1. **Problem** — What problem does the project solve?
2. **What I Did** — What did you build/do, and what technologies or decisions were involved?
3. **What Came of It** — What was the result, impact, or measurable outcome?

**Process:**
- Add project screenshot to `images/` folder
- Copy an existing `.project-card` block from the projects section
- Update title, description (using the three-beat structure), tech tags, and links
- Test responsiveness and deploy

**Next case study:** ClipForge — AI Content Clipping Project

**Reminder:** September 9, 2026 — Add the ClipForge case study

**Maintenance approach:** Future case studies should be added using the existing portfolio components and design system rather than rebuilding the portfolio.
