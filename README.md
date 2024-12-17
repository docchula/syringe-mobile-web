# Syringe Games Portal Website


![App Screenshot](https://github.com/user-attachments/assets/f73dbd30-1aaf-4be9-ad67-c21418a42475)

## Features

- **No Dependencies**: Apart from Astro, this theme does not use any external dependencies.
- **Fully Customizable**: Customize every element of the theme including fonts, images, and text by simple edits.
- **Responsive Design**: Ensures your app looks stunning on both desktop and mobile devices.

## Getting Started

1. Navigate to the project directory and install dependencies with `pnpm install`.
2. Start the development server with `pnpm start`.

## Customization Guide

### Content

Edit the frontmatter section at the top of `/src/pages/index.html` to update the website content, including text and images.

### Styles

All CSS is located in `/src/styles/main.css`. Modify this file to change the look and feel of the site.

### Images

Replace images by uploading new ones to the `/public/images` folder and update the references in the frontmatter of `index.html`.

### Fonts

Add new font files to `/public/fonts` and reference them in `/src/styles/main.css` to change fonts. For easy integration of Google Fonts into your project, check out [Hermes](https://github.com/cadensstudio/hermes).

## Project Structure

- `/src/pages/index.html`: The main HTML file for your landing page.
- `/src/styles/main.css`: CSS file for styling your landing page.
- `/public/images`: Directory for storing images.
- `/public/fonts`: Directory for storing fonts.

## Deployment

This theme can be deployed on any static site hosting service that supports Astro. Follow the hosting provider's instructions for deploying an Astro project.