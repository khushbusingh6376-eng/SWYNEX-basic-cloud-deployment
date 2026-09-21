# Cloud Deployment Case Study — SWYNEX Basic Cloud Deployment

## Overview
This project demonstrates the end-to-end deployment of a simple 
static web application to a cloud host, along with monitoring 
and cost/security awareness practices.

## Architecture
- **Application type:** Static website (HTML)
- **Hosting platform:** GitHub Pages
- **Source control:** GitHub repository
- **Deployment method:** Deploy from branch (main, root folder)
- **Monitoring:** UptimeRobot (external HTTP monitoring service)

## Deployment Process
1. Created a GitHub repository: `SWYNEX-basic-cloud-deployment`
2. Added `index.html` with basic application content
3. Committed the file to the `main` branch
4. Enabled GitHub Pages via Settings → Pages
5. Selected source: "Deploy from a branch" → `main` → `/ (root)`
6. Verified the live site at the generated GitHub Pages URL

## Monitoring & Cost Awareness
- Set up UptimeRobot to monitor site availability every 5 minutes
- Configured email alerts for downtime
- Confirmed hosting is on GitHub Pages' free tier (no cost incurred)
- Verified no secrets or credentials are exposed in the repository

## Live URL
https://khushbusingh6376-eng.github.io/SWYNEX-basic-cloud-deployment/

## Lessons Learned
- Deployment is more than just "making it live" — monitoring and 
  cost/security checks are equally important for real-world reliability
- Static hosting via GitHub Pages is a fast, free way to deploy simple 
  applications without managing servers
- Setting up alerts early helps catch downtime before it becomes a 
  bigger problem
- Documenting the process clearly makes it easier to review, repeat, 
  or hand off to someone else

## Conclusion
This exercise gave hands-on exposure to the full lifecycle of a cloud 
deployment — from writing code, to publishing it live, to monitoring 
and securing it responsibly.
