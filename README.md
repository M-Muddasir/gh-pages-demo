# GitHub Pages Demo

This project demonstrates the implementation of a Continuous Deployment (CD) pipeline for a static website using GitHub Actions and GitHub Pages. It's part of an MLOps assignment that showcases the principles of automation and deployment.

## Overview

This repository contains a simple MLOps portfolio website that is automatically deployed to GitHub Pages whenever changes are pushed to the main branch. The deployment process is handled by a GitHub Actions workflow.

## Features

- **Static Website**: A responsive MLOps-focused portfolio built with HTML5 and CSS3
- **Automated Deployment**: Uses GitHub Actions to automatically deploy changes
- **Continuous Delivery**: Updates are published to GitHub Pages with every push to the main branch

## How It Works

1. Static website files are stored in the `src/` directory
2. When code is pushed to the main branch, a GitHub Actions workflow is triggered
3. The workflow copies files from `src/` to a `public/` folder
4. The contents of the `public/` folder are deployed to the `gh-pages` branch
5. GitHub Pages serves the website from the `gh-pages` branch

## Deployed Site

You can view the live site at: https://YOUR_GITHUB_USERNAME.github.io/gh-pages-demo/

(Replace YOUR_GITHUB_USERNAME with your actual GitHub username after deployment)

## Local Development

To work on this project locally:

1. Clone the repository
2. Make changes to files in the `src/` directory
3. Push to the main branch to trigger automatic deployment

## Technologies Used

- HTML5
- CSS3
- GitHub Actions
- GitHub Pages
