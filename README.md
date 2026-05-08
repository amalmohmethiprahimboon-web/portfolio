Project Documentation

Responsive Personal Portfolio Website  
Alfido Tech Internship – Task 1

Author: Amal Mohamed  
Date: May 2026
Repository: [Alfido-Tech-Internship] (https://github.com/amalmohmethiprahimboon-web/Alfido-Tech-Internship)  
Live URL: [https://amalmohmethiprahimboon-web.github.io/Alfido-Tech-Internship/] (https://amalmohmethiprahimboon-web.github.io/Alfido-Tech-Internship/)

 1. Introduction

This document provides a complete technical and functional overview of the Responsive Personal Portfolio Website developed as Task 1 of the Alfido Tech Internship. The project showcases a front‑end developer’s skills, projects, and contact information in a mobile‑friendly, modern layout.


2. Project Objectives

- Build a fully responsive portfolio that works on all devices (mobile, tablet, desktop).
- Use semantic HTML5, CSS3, Bootstrap 5, and vanilla JavaScript.
- Implement a fixed navbar with smooth scrolling and active section highlighting.
- Include mandatory sections: Home, Skills, Projects, Contact.
- Deploy the site via GitHub Pages and provide source code on GitHub.






 3. Technology Stack

Technology                                Version / Purpose 
HTML5                                     Structuring content 
CSS3                                        Custom styling, Flexbox, Grid, keyframe animations 
Bootstrap 5                               Responsive grid system, navbar, utilities 
JavaScript (ES6)                     Smooth scroll, active link detection, form validation, interactive buttons 
Font Awesome                        6 Icons for social links and project cards 
Google Fonts (Inter)                Typography 
GitHub Pages                            Hosting 
 4. File Structure

Alfido-Tech-Internship/
└── index.html          # Single file containing HTML, CSS, and JS

> The entire project is contained in one `index.html` file for simplicity and ease of deployment.


 5. Features & Functionality

     5.1 Responsive Navbar
- Collapses into a hamburger menu on screens ≤ 991px.
- Fixed at the top with a semi‑transparent background and blur effect.
- Links scroll smoothly to corresponding sections.

    5.2 Hero Section
- Greeting, full name, and a typed rotating role (Frontend Developer / UI Enthusiast / Creative Coder).
- Animated gradient orb (no text on image) that floats and changes shape.
- Social media icons and a "Download CV" button (simulated).


 5.3 Skills Section
- Five skill cards: HTML/CSS, JavaScript, Bootstrap 5, React.js, Git & GitHub.
- Each card has an icon, title, and short description.
- Hover effect (lift + border glow).

 5.4 Projects Section
- Three project cards: Pomodoro Timer, Weather Dashboard, Spotify UI Clone.
- Each card includes a placeholder image (icon), title, brief description, and two buttons: Live Deme and GitHub Repo (both show alert dialogs as a demo simulation).

5.5 Contact Section
- Simple contact form with fields: Name, Email, Message.
- Client‑side validation (non‑empty, valid email format).
- On successful submission, a success message appears and the form resets.
- (No backend – front‑end demo only.)


 5.6-Footer
- Copyright notice and technology credits.


6. Responsive Design Implementation

- Bootstrap 5 grid (`row`, `col-*`) ensures fluid layout.
- Custom CSS media queries fine‑tune spacing, font sizes, and stacking behaviour for:
  - `max-width: 576px` – mobile phones
  - `max-width: 768px` – tablets
  - `min-width: 992px` – desktops
- The hero orb and profile image scale proportionally with `max-width` and `aspect-ratio`.
- Touch targets (buttons, links) are at least 44px tall on mobile.



7. Testing & Validation
Test case                                                               Expected result                                          Status
Click nav link                                Page scrolls to correct section, mobile menu closes           ✅ Pass
Submit empty contact form                   Error message shown                                                 ✅ Pass
Submit with invalid email                   Error message shown                                                   ✅ Pass
Hover over skill cards                         Card lifts and border changes                                      ✅ Pass
Click Live Demo Button                      Alert popup appears                                                    ✅ Pass
Resize browser window                       Layout reflows without breaking                               ✅ Pass

8. Deployment Instructions (for reference)

1. Push `index.html` to the `main` branch of the GitHub repository.
2. Go to Settings → Pages
3. Under Branch, select `main` and folder `/ (root)`.
4. Click Save
5. After 1‑2 minutes, the site is accessible at:  
   `https://amalmohmethiprahimboon-web.github.io/Alfido-Tech-Internship/`

9. Known Limitations & Future Enhancements

Current limitation                                               Proposed enhancement
Contact form does not send emails                      Integrate Form spree or a simple backend (Node.js/Express)
Demo buttons only show alerts                            Replace with actual live demos / GitHub repos
CV button shows an alert                                     Link to a real PDF file
No dark mode                                                      Add a toggle switch for dark/light theme
No actual projects beyond placeholders               Add real projects with screenshots and deployed links




10. Conclusion

The Responsive Personal Portfolio Website successfully meets all the requirements of Task 1. It is fully responsive, uses Bootstrap and custom CSS, includes all mandatory sections, and is deployed on GitHub Pages with source code publicly available. The project demonstrates proficiency in front‑end development and serves as a foundation for further improvements.

 11. References

- [Bootstrap 5 Documentation] (https://getbootstrap.com/docs/5.3/)
- [Font Awesome Icons] (https://fontawesome.com/)
- [Google Fonts – Inter] (https://fonts.google.com/specimen/Inter)
- [GitHub Pages Guide] (https://pages.github.com/)



Prepared by: Amal Mohamed  
Internship: Alfido Tech  
Role: Frontend Developer Intern  


