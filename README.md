# Gitor - GitHub for Tor

Gitor is a proprietary Git hosting platform designed exclusively for the Tor network. It provides GitHub-like features with a focus on privacy, anonymity, and decentralization.

## What is Gitor?

Gitor is a web-based Git repository hosting service accessible only through the Tor network. Like GitHub on the clearnet, Gitor allows users to:

- Host Git repositories
- Collaborate on projects
- Manage issues and pull requests
- Create organizations and teams
- Share code with the privacy community

Unlike GitHub, Gitor is:
- **No JavaScript** - Pure HTML/CSS with server-side rendering
- **Tor-Native** - Optimized for Tor network access
- **Anonymity-First** - Top-notch operational security procedures
- **Private** - No tracking, no analytics, no surveillance
- **Censorship-Resistant** - No compliance with takedown requests

## Accessing Gitor

Visit Gitor on the Tor network by using Tor Browser and navigating to the Gitor .onion address.

**Requirements:**
- Tor Browser
- Internet connection
- A Tor-compatible device (Linux, macOS, Windows, etc.)

## Features

- 📚 **Repository Hosting** - Create unlimited public and private Git repositories
- 👥 **Organizations** - Create teams and manage members
- 🐛 **Issues & PRs** - Track bugs and collaborate on code changes
- 📖 **Wiki & Documentation** - Built-in wiki for each repository
- 🔐 **SSH Access** - Clone and push over SSH via Tor
- 🔗 **Webhooks** - Integrate with CI/CD tools
- 🏷️ **Tags & Releases** - Manage version releases
- 🛡️ **Branch Protection** - Enforce code review policies
- 📊 **Activity Tracking** - Monitor repository activity

## How to Use Gitor

### Create an Account

1. Visit the Gitor .onion address in Tor Browser
2. Click "Register"
3. Choose a username (no email required)
4. Set a password
5. Start creating repositories

### Create a Repository

1. Log in to Gitor
2. Click "New Repository"
3. Enter repository name and description
4. Choose public or private
5. Initialize with README (optional)
6. Click "Create"

### Clone a Repository

```bash
git clone https://gitor.example.onion/username/reponame.git
```

### Push Your Code

```bash
cd your-project
git remote add origin https://gitor.example.onion/username/reponame.git
git push -u origin main
```

## Technology

Gitor is built with:
- **Go** - Backend server
- **PostgreSQL/MySQL/SQLite** - Database
- **Git** - Version control
- **HTML5 & CSS3** - Frontend (no JavaScript)

## Pricing

Gitor is **completely free** for all users. We accept and appreciate donations, we are a small team.

## Privacy Policy

Gitor does not:
- Collect personal data
- Track user behavior
- Execute JavaScript
- Log IP addresses
- Store identifying information
- Share data with third parties

Gitor commits to protecting your anonymity and privacy.

## Support

For help using Gitor, visit the documentation at the Gitor .onion address or create an issue in the Gitor help repository.

## Community

- **Report Bugs** - Create an issue in the Gitor repository
- **Request Features** - Open a discussion for new ideas
- **Contribute** - Submit pull requests with improvements

## Status

Gitor is currently in **active development**. New features are added regularly.

---

**Gitor: The Git service for privacy.** 🧅🔐
