# Divine Health Homeopathy Website

Official website for **Divine Health Homeopathy**
https://divinehealthhomeopathy.com

---

# Project Status

Current Version: **v1.2**

Status:
- Azure Static Web App
- GitHub source control
- Astro framework
- Production deployment active

---

# Technology

- Astro
- HTML
- CSS
- Azure Static Web Apps
- GitHub Actions

---

# Local Development

Start the development server:

```bash
npm install
npm run dev
```

Open:

http://localhost:4321

---

# Build

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

---

# Deployment

Deployment is automatic.

Workflow:

VS Code
↓

Git Commit
↓

GitHub
↓

GitHub Actions
↓

Azure Static Web App
↓

Production Website

---

# Repository Structure

```
public/
    images/
    favicon/

src/
    components/
    layouts/
    pages/
    styles/

.github/
```

---

# Current Pages

- Home
- About
- Consultations
- FAQ

Planned

- Resources
- Contact

---

# Design Philosophy

The site is intentionally designed to reflect:

- Classical
- Timeless
- Elegant
- Warm
- Trustworthy
- Historically grounded

The visual inspiration comes from:

- antique botanical illustrations
- historical pharmacy
- nineteenth-century books
- parchment
- navy and gold typography

---

# Brand Colors

Primary Navy

Gold Accent

Warm Cream Background

Soft Taupe

---

# Git Workflow

Save changes

```bash
git add .
git commit -m "Description"
git push origin main
```

Tag important milestones

```bash
git tag -a v1.2 -m "Version 1.2"

git push origin v1.2
```

---

# Recovery

Clone repository

```bash
git clone https://github.com/wallentm/divine-health-homeopathy.git
```

Install

```bash
npm install
```

Run

```bash
npm run dev
```

---

---

# Disaster Recovery & Project Restoration

If this computer is ever lost, replaced, or reformatted, the entire Divine Health Homeopathy website can be restored from GitHub.

## What is backed up?

The GitHub repository contains:

- All website source code
- Images and assets
- Git history
- Version tags
- Documentation
- Deployment configuration
- Azure Static Web App workflow

No manual backup of the website files is required beyond GitHub.

---

## Restoring on a New Computer

### 1. Install Required Software

Install the following:

- Git
- Node.js (Current LTS)
- Visual Studio Code

---

### 2. Clone the Repository

```bash
git clone https://github.com/wallentm/divine-health-homeopathy.git
```

Change into the project directory:

```bash
cd divine-health-homeopathy
```

---

### 3. Install Dependencies

```bash
npm install
```

This restores all required packages.

---

### 4. Start the Local Development Server

```bash
npm run dev
```

Open:

http://localhost:4321

The website should now be running locally.

---

## Deploying Changes

After making changes:

```bash
git add .

git commit -m "Describe changes"

git push origin main
```

Azure Static Web Apps automatically builds and deploys the website.

No manual deployment is necessary.

---

## Creating a Release

For important milestones:

```bash
git tag -a vX.X -m "Release description"

git push origin vX.X
```

Version history is documented in:

CHANGELOG.md

---

## Production Website

Azure Static Web App

Production updates automatically after every successful push to the **main** branch.

---

## Important Documentation

README.md

Project overview and setup.

CHANGELOG.md

Version history.

CLAUDE.md

Project philosophy, branding, and development guidance.

AGENTS.md

Instructions for AI coding assistants.

---

## If Something Goes Wrong

### Check Git

```bash
git status
```

Should report:

```
On branch main
nothing to commit, working tree clean
```

---

### Update Local Repository

```bash
git pull origin main
```

---

### Reinstall Dependencies

```bash
rm -rf node_modules

npm install
```

---

### Start Development Again

```bash
npm run dev
```

---

## Azure Deployment

If Azure does not update automatically:

1. Verify the GitHub push succeeded.
2. Check GitHub Actions for build errors.
3. Verify Azure Static Web App is connected to the repository.
4. Redeploy from Azure if necessary.

---

## Source of Truth

GitHub is the authoritative copy of this project.

All development should flow through Git:

Local Development
↓

Git Commit
↓

GitHub
↓

GitHub Actions
↓

Azure Static Web Apps
↓

Production Website

---

## Last Reminder

If you're reading this after a long break:

Take your time.

Pull the latest code.

Run `npm install`.

Run `npm run dev`.

Everything else will come back quickly.

---

## Project Vision

This website is intended to become more than a business website.

It is a permanent digital home for Divine Health Homeopathy that reflects:

- The history of classical homeopathy
- Scholarly integrity
- Compassionate individualized care
- Beauty through timeless design
- Trust built through honesty and education

When making future changes, always favor clarity, elegance, and authenticity over trends or marketing gimmicks.

The goal is that visitors feel welcomed, informed, and confident in the care they will receive.

---

# Maintained By

Mindy and Sean Wallent

Website development

Architecture

Azure hosting

GitHub management.