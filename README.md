# Valentine Interactive Web Experience

An interactive single-page web experience built using HTML, CSS, and JavaScript, focused on user interaction, animation, and clean frontend deployment.

This project demonstrates how thoughtful UI/UX design, lightweight client-side logic, and a professional hosting workflow can be combined into a polished, production-ready static website.

## Live Demo: https://valentine-c1b1d.web.app 

## Overview

The goal of this project was to design and deploy a small but complete web experience that emphasizes intentional user flow, responsive design, animation, and interaction feedback. Although the theme is personal and creative, the implementation reflects real-world frontend engineering practices.

## Features

- Multi-step interactive user flow
- Responsive layout optimized for mobile and desktop browsers
- Client-side state handling using vanilla JavaScript
- CSS animations for smooth transitions and visual feedback
- Interactive UI elements with hover and touch support
- Embedded third-party media (Spotify)
- Custom 404 error page for hosted environments

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Firebase Hosting
- Git and GitHub

No frontend frameworks or external JavaScript libraries were used to keep the project lightweight and dependency-free.

## Design and Implementation Details

- Single-file application architecture for simplicity and reliability
- Embedded CSS and JavaScript to minimize configuration overhead
- Event-driven UI logic to control navigation between screens
- Mobile-first styling with scalable typography
- Careful handling of browser constraints such as iOS Safari autoplay restrictions
- Firebase CLI used for repeatable and professional deployments

## Hosting and Deployment

The site is hosted using Firebase Hosting and deployed via the Firebase CLI.

Deployment workflow:

1. Initialize Firebase Hosting
2. Configure the project root as the public hosting directory
3. Deploy using a single command


This approach enables fast iteration, consistent deployments, and clean separation between development and hosting.

## Repository Structure
.
├── index.html Main application file
├── firebase.json Firebase Hosting configuration
├── .firebaserc Firebase project mapping
├── 404.html Custom error page
├── .gitignore Ignored local cache and log files


## What This Project Demonstrates

- Strong understanding of frontend fundamentals
- Ability to build interactive experiences without frameworks
- Attention to detail in UI behavior and animations
- Clean Git workflow and version control practices
- Experience deploying and managing a live production site
- End-to-end ownership of a small but complete product

## Potential Improvements

- Accessibility enhancements such as ARIA labels and keyboard navigation
- Reduced-motion mode for animations
- Modular JavaScript structure for scalability
- CI/CD-based automatic deployments
- Performance optimizations for low-end devices

## About

This project was built as a creative technical exercise to explore how small, well-executed ideas can be shipped cleanly from concept to production. It reflects a focus on user experience, maintainable code, and professional deployment practices.
