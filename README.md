# Lim Xin Yi — Purple Portfolio Study Project

This is a **learning and design reference**, not a ready-to-submit assignment. It preserves the personal information from Lim Xin Yi's already-published GitHub Pages portfolio, while exploring a modern purple layout and more browser-native interactions. It uses only HTML, CSS, and JavaScript, with no framework, build process, or third-party libraries.

The private preview is **separate from** the existing public GitHub Pages repository. Updating or downloading these files does not change the public website automatically.

## Before you submit

Your lecturer's instructions say that you must personally write, edit, and understand the final code, and that LLM-generated text and layout ideas must be modified and personalized. Use this as a reference to study and develop your own version. Do **not** submit the generated example unchanged.

1. Open `dist/index.html`. Check the name, student number, introduction, UNIMAS programme, hometown, skills, current subjects, goals, hobbies, and contact information against your real details. Expand or correct any information you want to share publicly.
2. Open `dist/script.js`. Check `SETTINGS.ownerName` and `SETTINGS.contactEmail`: these currently use the details on your existing public portfolio. The contact form does not send messages to a server; it opens a composed email for the visitor to review and send.
3. In `PROJECTS`, review all five case studies. These reflect possible coursework topics, but you must correct them to describe **your own work**, methods, role, actual progress, and genuine results. Add screenshots/working links only if real.
4. Modify the layout and styling in `dist/styles.css` so the final visual direction is yours. Check accessibility and responsive behavior after each change.
5. Remove the editable-example projects footnote **only after** you have completed and verified all project content.
6. Test every feature in desktop and mobile browsers; test all menu items, keyboard use, zoom, the contact draft, filters, case-study dialogs, and the print view.
7. When you have personally edited and understood the final code, replace the relevant files in your GitHub Pages repository. Place `index.html`, `styles.css`, and `script.js` together at the published repository root (or an enabled `/docs` directory). Submit **only the working public URL** and keep it active for at least six months.

## Project files

```
dist/
  index.html    Semantic sections and page content
  styles.css    Visual design, layout, themes, mobile and print rules
  script.js     Project data, interactions, settings and validation
```

To view locally, open `dist/index.html` in a browser, or serve `dist/` using a simple local HTTP server. No installation is required.

## JavaScript features to learn and explain

1. Light/dark theme toggle.
2. Theme preference persistence with storage fallback.
3. Responsive mobile navigation and Escape/outside-click closing.
4. Page-scroll progress indicator.
5. Back-to-top control.
6. Active navigation section based on scroll visibility.
7. Reduced-motion-aware entrance effects.
8. Data-driven rendering of five project cards.
9. Project category filtering.
10. Live text search with an empty state and reset control.
11. Alphabetical project sorting.
12. Accessible project-detail dialog.
13. Project-specific deep links.
14. Contact-form field validation.
15. Live message character count.
16. Contact email-draft / copy fallback.
17. Print-friendly résumé view and automatic footer year.
18. Rotating introduction text that respects reduced motion.
19. Keyboard-friendly tabs for the original Interests, Goals, Hobbies, and Subjects content.
20. Direct navigation from Education to the Subjects tab.

### Places to start studying

- **`escapeHTML()`** makes displayed project data safer to insert in HTML.
- **`renderProjects()`** uses `filter`, `sort`, `map`, and `join` on the project data array.
- **`setupNavigation()`** keeps a mobile menu usable by mouse and keyboard.
- **`setupWorldTabs()`** demonstrates ARIA tab states and keyboard navigation.
- **`setupDialog()`** uses a browser-native `<dialog>` for keyboard-friendly details.
- **`setupContactForm()`** validates inputs and prepares an email without storing submissions.

The five portfolio projects are editable sample narratives, not verified evidence of completed work. Do not claim an idea-stage project is a finished application.
