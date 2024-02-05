[![Create Docker Image and Push to Private Repository](https://github.com/KevJimenez/Hugo-Static/actions/workflows/docker-img.yml/badge.svg)](https://github.com/KevJimenez/Hugo-Static/actions/workflows/docker-img.yml)

## Overview
A personal website that is made with Hugo and hosted by an EC2 instance. Automated also by Github Actions and instantly updates the website for every push trigger. Made into a Docker image and web server runs Watchtower to check for newer image revision of website. Website can be visited at https://kojimenez.site

## Diagrams:
- Personal-Website

![hugo](/public/hugo.png)

- Whole CI/CD Pipeline of the Project [(Link to the IaC-for-Automation Repository)](https://github.com/KevJimenez/IaC-for-Automation)

![whole](/public/whole.png)
