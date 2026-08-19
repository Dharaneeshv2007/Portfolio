---
name: VD
description: Describe what this custom agent does and when to use it.
argument-hint: The inputs this agent expects, e.g., "a task to implement" or "a question to answer".
tools: [vscode, execute, read, agent, edit, search, web, browser, todo] # specify the tools this agent can use. If not set, all enabled tools are allowed.
---

<!-- Tip: Use /create-agent in chat to generate content with agent assistance -->

# ROLE

You are an expert senior frontend engineer, UI/UX designer, and portfolio developer.

Your task is to build a **professional, modern, recruiter-focused personal portfolio website** for me based strictly on the resume information provided below.

Do not merely create a basic portfolio template. Build a polished portfolio that looks like it was created by a strong software engineer applying for internships, placements, and entry-level Full Stack / AI/ML roles.

---

# PRIMARY OBJECTIVE

Create a complete, production-quality developer portfolio website that presents me as:

**Full Stack Developer | AI/ML Engineer | Deep Learning Enthusiast**

The website should immediately communicate:

1. Who I am
2. What I build
3. My technical skills
4. My strongest projects
5. My education
6. My hackathon participation
7. My coding/developer profiles
8. How recruiters can contact me

The design should be modern, clean, technically impressive, responsive, accessible, and fast.

---

# IMPORTANT RULE

Use ONLY information supported by my resume.

DO NOT invent:

* Work experience
* Internships
* Job titles
* Companies
* Certifications
* Awards
* Project results
* GitHub repository URLs
* LinkedIn URLs
* LeetCode statistics
* HackerRank statistics
* Technologies that are not present in my resume

If a URL is not available, create a clearly marked placeholder/config variable rather than inventing a URL.

You may improve wording for presentation, but do not fabricate achievements or numbers.

---

# MY RESUME DATA

Name:
Dharaneesh V

Email:
[dharaneeshv7305@gmail.com](mailto:dharaneeshv7305@gmail.com)

Phone:
7305206650

Professional Direction:
Full Stack Development with Machine Learning and Deep Learning

Summary:
To begin my career in Full Stack Development while leveraging Machine Learning and Deep Learning to build intelligent, scalable applications. Passionate about solving real-world problems, continuously learning emerging technologies, and delivering high-quality software solutions.

---

# SKILLS

## Programming Languages

* Java
* C
* Python

## Frontend

* HTML
* CSS
* JavaScript

## Backend

* Node.js
* Express.js

## Databases

* MySQL
* MongoDB

## Tools & Technologies

* Git
* GitHub
* VS Code
* IntelliJ IDEA
* Postman

## Machine Learning & Deep Learning

* TensorFlow
* LSTM
* CNN
* Natural Language Processing (NLP)

## Libraries

* NumPy
* Matplotlib

## Core

* Data Structures and Algorithms

---

# EDUCATION

## Bachelor of Technology

Kongu Engineering College

2024 – 2028

CGPA: 8.52

## Higher Secondary Education

Blue Bird Matriculation Higher Secondary School

2022 – 2024

10th: 90%

12th: 93%

---

# PROJECTS

## 1. ADS-B Anomaly Detection

Description:

Developed an ADS-B Anomaly Detection System using machine learning to identify abnormal aircraft behavior from real-world aviation data.

Work performed:

* Processed and preprocessed flight parameters
* Applied the Isolation Forest algorithm for anomaly detection
* Visualized flight trajectories
* Evaluated model performance using standard metrics
* Focused on robust detection of abnormal aircraft behavior

Relevant technologies:

* Python
* Machine Learning
* Isolation Forest
* NumPy
* Matplotlib

Portfolio presentation:

Present this as a machine-learning project focused on anomaly detection and aviation data.

---

## 2. AI-Powered Customer Churn Prediction System

Description:

Developed an AI-powered Customer Churn Prediction System using Python, Flask, TensorFlow (LSTM), and Scikit-learn to identify customers at risk of leaving.

Features/work:

* Customer churn prediction
* LSTM-based prediction
* Explainable AI using SHAP
* Customer retention recommendations
* Customer Lifetime Value (CLV) estimation
* RESTful API
* React dashboard
* Real-time predictions
* Business insights

Technologies:

* Python
* Flask
* TensorFlow
* LSTM
* Scikit-learn
* SHAP
* React
* REST API

This should be one of the most visually prominent projects in the portfolio.

---

## 3. AML Suspicious Transaction Detection

Description:

Developed an Anti-Money Laundering web application using FastAPI, React, and Vite with LSTM models to detect suspicious financial transactions.

Features/work:

* Suspicious transaction detection
* LSTM-based detection
* Real-time risk scoring
* RESTful APIs
* Interactive dashboard
* Transaction monitoring
* Fraud detection

Technologies:

* FastAPI
* React
* Vite
* LSTM
* REST APIs

Present this as a full-stack + AI project.

---

# AREAS OF INTEREST

* Full Stack Development
* Artificial Intelligence
* Machine Learning
* Deep Learning

---

# PARTICIPATION

## Hackvotrix Hackathon

2025

## CIT, Intelina Hackathon

2026

Coimbatore

---

# LANGUAGES

* English
* Tamil

---

# WEBSITE STRUCTURE

Build the website with these sections:

## 1. Navigation

Create a sticky navigation bar.

Navigation items:

* Home
* About
* Skills
* Projects
* Education
* Achievements / Hackathons
* Contact

On mobile, convert navigation into a clean hamburger menu.

The navbar should remain visually polished while scrolling.

---

# 2. HERO SECTION

Create a visually impressive hero section.

Display:

"Hi, I'm Dharaneesh V"

Main title:

"Full Stack Developer & AI/ML Enthusiast"

Supporting text should communicate:

"I build intelligent, scalable applications by combining full-stack development with machine learning and deep learning."

Include CTA buttons:

* View Projects
* Contact Me

Also include social/profile buttons for:

* GitHub
* LinkedIn
* LeetCode
* HackerRank

BUT use placeholder URLs if actual URLs are unavailable.

Do not invent profile links.

Add a visually interesting developer/AI themed element on the right side.

Avoid generic stock photography.

Prefer:

* Abstract AI visualization
* Code-inspired graphic
* Neural network visualization
* Developer terminal aesthetic
* Modern geometric composition

---

# 3. ABOUT SECTION

Create a concise but strong About section.

Position me as an aspiring Full Stack Developer interested in building intelligent applications using AI/ML.

Mention:

* Full Stack Development
* Machine Learning
* Deep Learning
* Real-world problem solving
* Continuous learning
* Scalable applications

Do not make the section excessively long.

---

# 4. SKILLS SECTION

Create a visually impressive skills section.

Organize skills into categories:

Programming
Frontend
Backend
Database
AI / ML
Tools
Libraries
Core

Use modern cards, badges, icons, or interactive elements.

Suggested grouping:

Programming:
Java, C, Python

Frontend:
HTML, CSS, JavaScript

Backend:
Node.js, Express.js

Database:
MySQL, MongoDB

AI / ML:
TensorFlow, LSTM, CNN, NLP

Libraries:
NumPy, Matplotlib

Tools:
Git, GitHub, VS Code, IntelliJ IDEA, Postman

Core:
Data Structures and Algorithms

Do not use fake skill percentages such as "90%" unless explicitly supported by the resume.

---

# 5. PROJECTS SECTION

This is the MOST IMPORTANT section.

Create beautiful project cards.

Each project card should include:

* Project name
* Short description
* Problem being solved
* Key features
* Technologies
* Relevant category
* GitHub button if a real URL is provided
* Demo button only if a real URL is provided

Projects:

1. ADS-B Anomaly Detection
2. AI-Powered Customer Churn Prediction System
3. AML Suspicious Transaction Detection

Make the projects visually distinct.

The Customer Churn Prediction project and AML project should strongly demonstrate the combination of:

Frontend + Backend + AI/ML

Use subtle animations when project cards enter the viewport.

---

# 6. PROJECT DETAIL EXPERIENCE

If practical, implement a modal or expandable project view.

When clicking a project:

Show:

* Overview
* Problem
* Solution
* Technical implementation
* Technologies
* Key features

Do not invent performance metrics.

---

# 7. EDUCATION SECTION

Create a clean timeline.

Show:

Bachelor of Technology
Kongu Engineering College
2024 – 2028
CGPA: 8.52

Higher Secondary Education
Blue Bird Matriculation Higher Secondary School
2022 – 2024
10th: 90%
12th: 93%

Make the timeline responsive on mobile.

---

# 8. HACKATHON / PARTICIPATION SECTION

Create a dedicated section.

Show:

Hackvotrix Hackathon — 2025

CIT, Intelina Hackathon — 2026
Coimbatore

Do not claim prizes, rankings, finalist status, or awards because they are not included in the resume.

---

# 9. CAREER / INTEREST SECTION

Create a visually interesting section showing:

Full Stack Development
Artificial Intelligence
Machine Learning
Deep Learning

Use a futuristic but professional visual style.

---

# 10. CONTACT SECTION

Create a strong contact section.

Show:

Email:
[dharaneeshv7305@gmail.com](mailto:dharaneeshv7305@gmail.com)

Phone:
7305206650

Add:

* Email Me button
* LinkedIn button
* GitHub button

Again, do not invent URLs.

If a contact form is implemented, make it frontend-only unless a backend/email service is actually configured.

Do not pretend that a form sends emails if no backend exists.

---

# 11. FOOTER

Create a minimal footer.

Include:

Dharaneesh V

Full Stack Developer | AI/ML Enthusiast

Copyright year should be dynamically generated.

---

# DESIGN DIRECTION

The portfolio should feel like a modern engineering portfolio rather than a generic student template.

Preferred visual style:

* Dark-first design
* Black / charcoal background
* Subtle gradients
* Glassmorphism used carefully
* Modern typography
* Clean spacing
* Soft borders
* Subtle glow effects
* Professional blue/purple/cyan accent colors
* Strong visual hierarchy

Do NOT make it look overly flashy.

The design should communicate:

"Modern software engineer who works with AI."

---

# ANIMATIONS

Use animations thoughtfully.

Include:

* Smooth scrolling
* Fade-in sections
* Project card reveal
* Hover interactions
* Button micro-interactions
* Subtle background animations
* Navbar transition
* Skill card animations

Avoid excessive animations that hurt performance.

Respect `prefers-reduced-motion`.

---

# RESPONSIVENESS

The website MUST work perfectly on:

* Desktop
* Laptop
* Tablet
* Mobile

Test layouts around:

* 320px
* 375px
* 768px
* 1024px
* 1440px+

Avoid horizontal scrolling.

---

# ACCESSIBILITY

Implement:

* Semantic HTML
* Proper heading hierarchy
* Keyboard navigation
* Accessible buttons
* Alt text for meaningful images
* Good color contrast
* Visible focus states
* Reduced-motion support

---

# SEO

Add:

* Proper page title
* Meta description
* Open Graph metadata
* Relevant keywords
* Semantic structure

Suggested title:

"Dharaneesh V | Full Stack Developer & AI/ML Enthusiast"

---

# PERFORMANCE

Optimize for:

* Fast loading
* Minimal unnecessary dependencies
* Lazy-loaded images
* Optimized assets
* Good Lighthouse performance
* Avoid unnecessary JavaScript

---

# TECH STACK

Before coding, inspect the existing project.

If a suitable React project already exists, work within it.

If no project exists, use:

* React
* Vite
* JavaScript or TypeScript
* Tailwind CSS if appropriate
* Lucide React or another lightweight icon library

Choose the stack that produces the cleanest maintainable result.

Do not add unnecessary libraries.

---

# CODE ARCHITECTURE

Use reusable components.

Suggested structure:

src/
components/
Navbar
Hero
About
Skills
Projects
ProjectCard
Education
Hackathons
Contact
Footer

data/
portfolioData

assets/

App

Keep content/data separate from UI components where practical.

Avoid putting the entire website inside one huge component.

---

# DATA-DRIVEN CONTENT

Put resume information into structured data where appropriate.

For example:

projects = [
{
title,
description,
technologies,
features,
category
}
]

This should make it easy for me to update the portfolio later.

---

# IMPORTANT DEVELOPMENT BEHAVIOR

You are operating as an autonomous coding agent.

First:

1. Inspect the existing repository.
2. Determine the current framework.
3. Inspect package.json.
4. Inspect existing source files.
5. Reuse existing useful configuration when possible.
6. Do not unnecessarily replace the entire project.
7. Plan the component structure.
8. Implement the website.
9. Run the application/build.
10. Fix all errors.
11. Check responsiveness.
12. Check console errors.
13. Verify navigation and interactions.
14. Leave the repository in a runnable state.

Do not stop after generating the initial components.

---

# QUALITY CHECKLIST

Before considering the task complete, verify:

[ ] Website starts successfully

[ ] Production build succeeds

[ ] No TypeScript/JavaScript errors

[ ] No broken imports

[ ] No broken images

[ ] No console errors

[ ] All navigation links work

[ ] Mobile menu works

[ ] Responsive design works

[ ] Project cards work

[ ] Contact buttons work

[ ] External profile links are placeholders if URLs are unknown

[ ] No fabricated resume information

[ ] Accessibility basics implemented

[ ] SEO metadata implemented

[ ] Animations work without hurting usability

[ ] Website looks professional at desktop resolution

[ ] Website looks professional at mobile resolution

---

# IMPORTANT FINAL STEP

After implementation, give me a concise summary containing:

1. What you built
2. Technologies used
3. Files/components created or modified
4. How to run the project
5. Any information I still need to replace, such as placeholder GitHub/LinkedIn/LeetCode/HackerRank URLs
6. Any optional improvements you recommend

Do not claim something works unless you actually tested it.

Build the portfolio now.
