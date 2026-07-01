# Architecture

This document describes the technical architecture of the *Building AI with Simon* website. It explains how the system is structured, how files interact, and how the site is delivered to users.

---

## 1. System Overview

The website is a **static frontend application** built using:

- HTML (structure)
- CSS (styling and layout)
- JavaScript (minimal interactivity where needed)

There is no backend, database, or external server logic.

The system is designed for simplicity, performance, and easy deployment via GitHub Pages.

---

## 2. High-Level Architecture

User Browser
↓
HTML Pages (Structure Layer)
↓
CSS Stylesheets (Presentation Layer)
↓
JavaScript (Behavior Layer - optional)
↓
Static Assets (Images, icons, documents)

## 3. Project Structure

```text id="archtree1"

Building-AI-with-Simon/
│
├── index.html
├── vision.html
├── about.html
├── projects.html
├── journey.html
├── skills.html
├── contact.html
│
├── assets/
│ ├── images/
│ ├── icons/
│ └── fonts/
│
├── css/
│ ├── main.css
│ ├── layout.css
│ └── components.css
│
├── js/
│ └── main.js
│
├── docs/
│ ├── Project-Charter.md
│ ├── Project-Scope.md
│ ├── Site-Map.md
│ ├── User-Stories.md
│ ├── Design-System.md
│ ├── Architecture.md
│ └── Development-Log.md
│
└── README.md

```

## 4. Layered Architecture Model

### 4.1 Presentation Layer (HTML + CSS)

Responsible for UI structure and visual design
Uses semantic HTML5 elements
CSS handles layout, typography, responsiveness

### 4.2 Behaviour Layer (JavaScript)

Minimal interactivity (if needed)
Example uses:
Navigation toggles (mobile menu)
Smooth scrolling
Future enhancements (animations)

### 4.3 Content Layer

All content is hard-coded into HTML pages
No CMS or dynamic content system
Markdown documents are used for planning only

---

## 5. Navigation Flow

Users enter through index.html
Navigation is consistent across all pages
Each page is independently accessible

```text id="archtree1"
Home → Vision → About → Projects → Journey → Skills → Contact
```

---

## 6. Data Flow

There is no dynamic data processing.

Instead:

Content is written directly into HTML files
CSS controls how it is displayed
JavaScript optionally enhances user interaction

---

## 7. Deployment Architecture

Hosted via GitHub Pages
Static files served directly from repository
No build step required (v1)
Deployment flow:

Local Development → Git Commit → GitHub Repository → GitHub Pages → Live Website

---

## 8. Design System Integration

The architecture supports a consistent design system:

Typography: Montserrat
Colors:
Background: White
Text: Black
Accent: #220647
Layout: Responsive grid/flexbox system
Components reused across pages

---

## 9. Future Architectural Expansion (Not in V1)

The following are intentionally excluded but planned:

Backend API layer
Database integration
Authentication system
CMS or admin dashboard
Dynamic content rendering (React or frameworks)
User interaction systems (comments, accounts)

---

## 10. Summary

This architecture prioritises:

Simplicity
Maintainability
Fast deployment
Clear learning progression
Strong documentation discipline
It is intentionally designed as a foundation that can later evolve into more complex systems.


