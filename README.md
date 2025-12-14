# Learnify - Online Learning Platform (Capstone Lab 5)

**Student Name:** Shourya Pratap  
**Theme:** Online Learning Platform  
**Course:** B. Tech CSE Core  
**Section:** A  
**Roll No:** 30  
**Lab Assignment: 5**

## 📖 Project Description
Learnify is a fully responsive, static website designed for an online education platform. It serves as a landing page where users can browse course categories, view featured classes, meet instructors, and contact support. The project demonstrates the use of semantic HTML5 and modern CSS3 techniques without reliance on JavaScript frameworks.

## 🚀 Features Implemented
* **Responsive Navigation:** A flexbox-based navbar that stacks gracefully on smaller screens.
* **Hero Section:** Features a CSS keyframe animation (`slideUpFade`) for visual engagement.
* **Course Listing:** Utilizes **CSS Grid** to create a responsive card layout for courses.
* **Instructors & Reviews:** semantic sections displaying mentor profiles and student testimonials.
* **FAQ Section:** Uses the HTML `<details>` and `<summary>` tags for an interactive accordion effect.
* **Contact Form:** A functional layout for user inquiries (Name, Email, Message).
* **Accessibility:** Includes a "Skip to main content" link and proper ARIA labels.

## 🛠️ Technical Details & Layout Techniques
This project follows the "Mobile-First" approach (via logic) but implements specific breakpoints for larger screens.

* **Main Layout:** CSS Grid for 2D layouts (Courses, Articles) and Flexbox for 1D alignment (Navbar, Footer, Search bars).
* **Styling:** Uses CSS Variables (`:root`) for consistent color management and maintenance.
* **Typography:** Google Fonts "Inter" for a clean, modern aesthetic.

### Breakpoints Used
1.  **Desktop (Default):** Multi-column grid, expanded navigation.
2.  **Tablet (max-width: 900px):** Navigation search bar moves to its own row; Footer columns stack vertically.
3.  **Mobile (max-width: 600px):** Single-column grid for all cards; Typography scales down; Buttons expand to full width for easier tapping.

## 📂 How to Run Locally
1.  Download or clone this repository.
2.  Ensure the folder structure includes `index.html`, `style.css`, and the `images/` folder (if local images are used).
3.  Double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Edge).
