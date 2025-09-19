# Pangolins in Disguise FTC Team Website

This repository contains the files for the official Pangolins team website. It's a simple, single-page static site designed to be easily updated and deployed.

## How to Customize the Website

All the content is located in the `index.html` file. You don't need to be a coding expert to make changes!

1.  **Open `index.html` in a text editor.**
2.  **Find the section you want to edit.** The sections are clearly marked with comments like `<!-- About Us Section -->`.
3.  **Change the text:** Simply replace the placeholder text with your team's information.
4.  **Change images:** The images use placeholder links from `https://via.placeholder.com`. To use your own images:
    *   Add your image files (e.g., `team-photo.jpg`) to the project folder.
    *   Find the `<img>` tag you want to change.
    *   Change the `src` attribute from the placeholder link to your file name. For example: `src="team-photo.jpg"`.
    *   **Important:** Also update the `alt` attribute to describe the new image. This is for accessibility.

### Customizing the Theme

You can easily change the website's colors in the `style.css` file.

1.  Open `style.css`.
2.  At the very top, you'll see a `:root` section with CSS variables.
3.  Change the color hex codes to match your team's branding:
    *   `--primary-color`: The main color (used for headings, etc.).
    *   `--secondary-color`: The accent color (used for buttons, etc.).

## How to Deploy to Vercel

Vercel makes hosting this website for free incredibly easy.

1.  **Sign up for a Vercel account** using your GitHub, GitLab, or Bitbucket account.
2.  **Create a new Git repository** (e.g., on GitHub) and push these files (`index.html`, `style.css`, `script.js`, `vercel.json`, and this `README.md`) to it.
3.  **On your Vercel dashboard, click "Add New... > Project".**
4.  **Import your Git repository.**
5.  Vercel will automatically detect that it's a static site. You don't need to change any build settings.
6.  **Click "Deploy".**

That's it! Your website will be live in a few seconds. Vercel will automatically redeploy your site every time you push a change to your Git repository.
