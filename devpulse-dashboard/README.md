System 1: DevPulse Cloud Infrastructure SaaS
Assignment Category: Take Home Programming  
Deliverable Format: Public GitHub Repository link submitted to Moodle
Prerequisites: Completion of Assignment 1A, Semantic HTML5, CSS3 Box Model, Flexbox (1D),
CSS Grid (2D), Media Queries, and CSS Pseudo-classes (as shown in class demo)
Total Points: 100 Points

1. Project Context & Implementation Goal
   In Assignment 1A, you developed the user journey funnel, audited Don Norman's usability
   principles, and established the semantic component hierarchy for DevPulse. In this assignment,
   you will translate that architectural blueprint into production-grade HTML5 and CSS3. You will
   construct a fully responsive, visually polished marketing landing page and compute tier
   dashboard without using CSS frameworks (like Bootstrap, Tailwind) or JavaScript.
2. Technical Requirements
   A. Directory Structure & File Setup
   Your repository must strictly follow this file hierarchy:
   ● devpulse-dashboard/
   ○ index.html
   ○ Styles.css
   ○ README.md
   B. Semantic HTML5 Requirements
   ● Structural Landmarks: Use <header>, <nav>, <main>, <section>, <article>, and <footer>
   exclusively for document structure. Root level wrappers using <div> are prohibited.  
   ● Heading Order: Maintain a strict logical heading hierarchy (<h1> then <h2> then <h3>)
   without skipping levels.
   ● Input Boundaries & Constraints: The workload estimator and registration form must
   enforce validation natively via HTML5 attributes: required, type="email", type="number",
   min="1", max="1000", and step="1".  
   ● Zero JavaScript: Do not include any .js files or <script> tags. Interactive states and
   validation must rely entirely on native HTML/CSS capabilities
   C. Modern CSS3 Architecture & Layout Geometry
   The following are the requirements with respect to CSS script (all of these will be shown in class
   demo):  
   ● Universal Box Model Reset: You must begin your stylesheet with a universal border-box
   reset
   ● CSS Custom Properties (Design Tokens): Define a clear color palette, font stack, and
   transition timing
   ● 1D Geometry (Flexbox) usage must be present  
   ● 2D Geometry if required must be implement using CSS Grid
   ● Visual Weight & Norman Signifiers implementation with CSS (:hover states and so on)
   ● Responsive Reflows must be present (media-queries for mobile screens)
3. Git Version Control & Engineering Integrity Requirements
   To verify original work and reflect real-world developer practices, submissions must satisfy strict
   version control rules:
   ● Minimum Commit Requirement: Your repository must have at least 4 meaningful
   commits executed across distinct working sessions (e.g., initial semantic markup,
   navigation & hero styling, pricing grid implementation, responsive reflow & polish).
   ● Descriptive Commit Messages: Avoid messages like "update" or "changes". Use
   standard engineering commit conventions (e.g., feat: semantic html landmarks, style:
   flexbox navigation and hero layout, feat: responsive css grid pricing matrix).
   ● Monolithic Commit Penalty: Repositories submitted with a single bulk commit
   ("initial commit" containing the entire project) will receive an automatic 50-point
   deduction and will be flagged for a mandatory verbal code defense.
