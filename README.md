# DaemonLayer Website

This is the DaemonLayer marketing site built with **Astro**.

## Getting Started

Clone the repository and install dependencies:

```bash
npm install
````

Start the development server:

```bash
npm run astro dev
```

The site will be available at **[http://localhost:4321](http://localhost:4321)**

## Content Management

We use [PagesCMS](https://pagescms.org) to edit website content.
PagesCMS is connected directly to this GitHub repository and manages Markdown files stored in the `/src/content` directory.

When you edit or add content through PagesCMS, it automatically commits the changes to the repo — no database or external storage is used.

To update content:

1. Go to [PagesCMS Dashboard](https://app.pagescms.org)
2. Log in with your GitHub account
3. Open the **DaemonLayer** project
4. Select the company-site repository
5. Edit the content and click **Save**

All updates are committed to the `main` branch and deployed automatically.

## Deployment

The site is deployed through **Railway**.
Each commit to the `main` branch triggers an automatic build and deploy.

## Early Access Form

The “Apply for Early Access” form sends a confirmation email to the user and an internal notification to the DaemonLayer team