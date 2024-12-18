# Dublin Coding Website

Welcome to **Dublin Coding**, an educational platform offering coding classes in Dublin. This website is designed to provide users with essential information about the classes offered, including an easy-to-use sign-up form and contact details. The site is fully responsive and integrates with social media platforms for community engagement.

Deployment link - https://pauld95-git.github.io/Coding-class/

![Dublin Coding Website](/assets/images/amiresponsive.png)

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [How to Use](#how-to-use)
5. [Credits](#credits)
6. [Bugs](#bugs)
7. [Validator](#validator)
8. [Deployment](#deployment)
9. [Code Structure](#code-structure)

---

## Project Overview

The **Dublin Coding Website** is the main digital presence for a coding school based in Dublin, offering coding courses for students of all levels. The website provides key sections such as:

- Home
- About Us
- Sign Up
- Contact

It is designed to be intuitive, responsive, and easy to navigate, allowing users to quickly access information about the classes and easily sign up for them.

---

## Features

### 1. **Navigation Bar**
   - The top navigation bar includes links to important sections: Home, About Us, Sign Up, and Contact.
   - The design is responsive: on mobile devices, the navigation collapses into a hamburger menu for ease of access.

### 2. **Home Section**
   - The homepage features a welcoming header, including a brief introduction to Dublin Coding and a prominent "Get Started" button that links to the sign-up page.

### 3. **About Us Section**
   - Provides information about Dublin Coding's mission, its approach to teaching, and the benefits of joining the platform.
   - Includes a team section with detailed descriptions of the instructors, highlighting their expertise and passion for teaching coding.

### 4. **Sign-Up Form**
   - A simple sign-up form allows users to register for coding classes by entering their name and email.
   - The form submits data to an external service (`https://formdump.codeinstitute.net`).

### 5. **Contact Page**
   - Users can easily reach out or connect through social media platforms such as Facebook, YouTube, Instagram, and Twitter via the contact page.

### 6. **Footer with Social Media Links**
   - Each page includes a footer with social media icons linking to the company's profiles on major platforms.
   - These links open in new tabs to ensure a smooth browsing experience.

---

## Technologies Used

- **HTML5**: Used for structuring the content of the website.
- **CSS3**: For styling the website and ensuring a responsive design.
- **Font Awesome**: For adding social media icons.
- **External Service**: Form data is submitted to `https://formdump.codeinstitute.net` via the sign-up form.

---

## How to Use

### Navigation
- The website includes a navigation bar linking to the **Home**, **About Us**, **Sign Up**, and **Contact** pages.
- On smaller screens, the navigation becomes a hamburger menu for easier access.

### Signing Up
1. Go to the **Sign Up** page.
2. Fill in your **first name**, **last name**, and **email address**.
3. Click the **"Let's Code!"** button to submit the form.

### Social Media
- Connect with Dublin Coding through the social media links in the footer or contact page. These links open in new tabs.

---

## Bugs

- No known issues.

---

## Validator

- HTML5 validation passed with no errors.
- CSS3 validation passed with no errors.

---

## Deployment

This website has been deployed to **GitHub Pages**. Here are the steps for deployment:

1. Push the project to a GitHub repository.
2. Go to the repository's **Settings**.
3. Under the **Pages** section, select the branch to deploy from (usually `main` or `master`).
4. The site will be available at the provided GitHub Pages URL.

---

## Credits

- **Navbar Inspiration**: CodingNepal - [codingnepalweb.com](https://www.codingnepalweb.com)
  
---

## Code Structure

```plaintext
dublin-coding/
│
├── assets/
│   ├── css/
│   │   └── style.css            # Main CSS stylesheet for the website
│   ├── images/                  # Folder for images used in the site
│   └── favicon/                 # Folder for favicon images
│
├── index.html                   # Homepage of the website
├── aboutus.html                  # About Us page
├── signup.html                   # Sign-Up page
├── contact.html                  # Contact page
└── README.md                     # Documentation file

