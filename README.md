# Decibles — Dependencies & Website

**The official website and planned dependency distribution repository for Decibles IDE.**

Decibles is a planned, modular desktop IDE intended to simplify the process of creating, configuring, developing, testing, building, and preparing applications for distribution.

This repository contains the public-facing Decibles website and serves as a central location for dependency catalogs and downloadable components as the project develops.

> **Project status:** Planning phase. Decibles IDE implementation has not started. Website content and repository organization may change as development progresses.

## 🌐 Website

The website is hosted on Cloudflare Pages.

**Live website:** https://decibles-dependencies.pages.dev/

The website is intended to provide:

- Project overview and information
- Downloads and release information
- Documentation and guides
- Dependency and component information
- Source code links
- Project status and roadmap
- Frequently asked questions
- Contact and community resources

Some sections may contain preliminary information while the IDE remains in planning.

## 📦 Repository Contents

This repository may contain:

- **Website files:** HTML, CSS, JavaScript, images, and other static assets.
- **Dependency catalog:** Metadata describing available components, versions, compatibility, and download locations.
- **Downloadable components:** Smaller optional resources and integrations where appropriate.
- **Documentation:** Information about the project and its distribution system.

The exact directory structure may evolve as the project develops.

## ☁️ Hosting & Distribution

Decibles uses a lightweight, web-based distribution approach.

| Service                     | Intended purpose                                                                             |
| --------------------------- | -------------------------------------------------------------------------------------------- |
| Cloudflare Pages            | Hosting the public website and static content                                                |
| Cloudflare R2               | Potential storage for smaller downloadable components and optional resources                 |
| GitHub                      | Source control, dependency metadata, and project collaboration                               |
| GitHub Releases             | Distribution of versioned release artifacts and larger downloadable files, where appropriate |
| Official upstream providers | Downloading third-party tools and runtimes when appropriate                                  |

Not every component will necessarily be hosted in this repository. Download locations will depend on file size, licensing, compatibility, and maintenance requirements.

## 🛠️ Editing the Website

The website uses static web files and can be edited with a text editor or code editor.

To update the website:

1. Clone or open this repository.
2. Edit the relevant HTML, CSS, JavaScript, or asset files.
3. Ensure the homepage is named `index.html` and is located in the configured Cloudflare Pages build output directory.
4. Commit and push your changes to GitHub.
5. Allow Cloudflare Pages to deploy the updated website.
6. Verify the changes at the live website URL.

If the Pages project is configured for a repository subdirectory, make sure the homepage and other website assets are located in the correct output directory.

## 🔒 Dependency Distribution Principles

As the distribution system develops, the project aims to follow these principles:

- Publish identifiable component versions.
- Verify downloaded files using cryptographic hashes where applicable.
- Document supported platforms and compatibility requirements.
- Respect third-party licenses and redistribution restrictions.
- Prefer official sources for third-party runtimes and development tools when appropriate.
- Avoid requiring users to download unnecessary components.
- Keep download information clear and maintainable.

The presence of a component in this repository does not automatically imply that it is an official Decibles release or that it is safe to execute without verification.

## 🧩 About Decibles IDE

Decibles is planned as a modular desktop IDE initially targeting Windows, with Linux and macOS as future platform goals.

Its initial application categories are:

- Desktop applications
- Web applications
- Backend services and APIs

The current technology direction includes Python and PySide6/Qt for the IDE interface, with Python desktop development and FastAPI backend workflows among the initial candidates for integration. These choices remain subject to feasibility review.

The intended architecture emphasizes established development tools, optional components, project-scoped environments, existing project compatibility, and actionable diagnostics.

These are development goals, not claims that the corresponding features are already implemented.

## 🗺️ Roadmap

The project
