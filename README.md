# Sreenidhi Ramani — Portfolio

Personal portfolio site, live at **[sreenidhi15.github.io](https://sreenidhi15.github.io)**.

A single-page site covering my background in firmware security, SOC/blue team work, GRC, and offensive security — built as one self-contained `index.html` with no build step or dependencies.

## Sections

- **Home** — quick intro and stats
- **About** — experience, skills, education, extracurricular
- **Projects** — filterable by track (firmware, offensive, ai-security, grc, published), with live star counts and last-updated dates pulled from the GitHub API
- **Blog** — writeups on firmware fuzzing, SOC practice, and CTFs
- **Contact** — email, LinkedIn, GitHub, TryHackMe

## Tech

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no build tools, no npm install. Navigation between sections is handled client-side (no page reloads), and project cards fetch live repo stats from `api.github.com` at load time.

## Running locally

Just open `index.html` in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8000
```

## Deployment

Hosted via GitHub Pages, deployed from the `main` branch root. Any push to `main` updates the live site within a minute or two.

## Contact

- Email: [ramani.sr@northeastern.edu](mailto:ramani.sr@northeastern.edu)
- LinkedIn: [linkedin.com/in/sreenidhiramani](https://www.linkedin.com/in/sreenidhiramani/)
- GitHub: [@Sreenidhi15](https://github.com/Sreenidhi15)
- TryHackMe: [Ciph3r15](https://tryhackme.com/p/Ciph3r15)
