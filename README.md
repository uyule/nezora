Nezora is a lightweight science-focused web platform designed to make scientific ideas, projects, and educational content more accessible to a global audience. The site is built entirely with HTML/CSS/JavaScript and operates as a front-end-only application with a simple, scalable deployment workflow.
-----------------
Overview

Nezora was designed and managed to support over 4,000+ interactions across 60+ countries, with outreach efforts extending to schools, organizations, and international collaborators. Alongside development, the project included content strategy, social media management, and partnership outreach to help expand the platform’s global reach.

The website architecture prioritizes simplicity, scalability, and low operational overhead.

Tech Stack
HTML
CSS
JavaScript
GitHub
Vercel
Custom Domain Integration
Deployment Workflow

-----------
The deployment pipeline follows a straightforward static-site workflow:

Create and develop the website locally using HTML/CSS/JS
Upload the project files to GitHub
Connect the GitHub repository to Vercel
Vercel automatically builds and deploys the site
Attach a custom domain to publish the live website

Deployment Architecture:
Local Development
        ↓
     GitHub
        ↓
     Vercel
        ↓
 Custom Domain
        ↓
   Live Website
   
   
-----------------
Nezora operates with a lightweight, stateless architecture and does not maintain a proprietary backend or database layer.

Because the website does not collect or store sensitive user information — such as passwords, financial data, or personal records — it avoids the complexity associated with:

Authentication APIs
OAuth systems
Session-based login management
Encrypted database pipelines
Server-side user state management

The platform is purely front-end based.
