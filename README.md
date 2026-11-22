# Mithun R Naik · Personal Portfolio

A single-page portfolio for Mithun R Naik, B.E. Electronics and Communication Engineering (3rd semester), Acharya Institute of Technology, Bengaluru (VTU).

## Sections

- **Hero:** name, role, availability indicator, social icons (GitHub, LinkedIn, email)
- **About:** short profile statement
- **Academic timeline:** school and college education with years and percentages
- **Projects:** project laboratory (ongoing, upcoming, completed). Empty until projects are ready to describe.
- **Learning journey:** current learning focus and career interests
- **Learning record:** certifications (with image previews) and workshops
- **Contact:** LinkedIn, GitHub, email and location icons

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: HTML, CSS and JavaScript in one file |
| `photo.jpg` | Portrait used in the hero |
| `c-programming.jpg` | Certificate preview: C Programming Basics |
| `copilot-prompt-writing.jpg` | Certificate preview: Microsoft Copilot, Art of Prompt Writing |
| `generative-ai.jpg` | Certificate preview: Generative AI Literacy |

Keep the image files in the same folder as `index.html`. The page refers to them by relative name.

## Running locally

Open `index.html` in a browser. No build step or install is needed.

## Hosting on GitHub Pages

1. Create a repository, for example `mithunaik24-maker.github.io`.
2. Add `index.html`, the images and this README, then push.
3. In the repository settings, open **Pages**, choose the `main` branch and the root folder, and save.

## Editing content

Content is defined near the bottom of `index.html` in these arrays:

- `PROFILE`: email and profile facts
- `AVAILABILITY`: availability label (set `open` to `false` to hide the indicator)
- `TIMELINE`: education entries
- `JOURNEY`: learning journey steps
- `INTERESTS`: career interests
- `CERTS`: certifications (`image` is the file name; leave it empty to show a placeholder)
- `WORKSHOPS`: workshops and sessions

Only add facts that are true and verifiable. Projects should appear only when they are complete enough to describe honestly.

## Technical notes

- Fonts: Google Fonts (Sora, Instrument Serif, DM Sans)
- 3D hero: Three.js
- Scroll animation: GSAP with ScrollTrigger
- Light and dark themes follow the system setting and can be switched by the toggle. The choice is saved in the browser.
- Motion is reduced automatically for users who prefer reduced motion.

## Contact

- Email: mithunaik24@gmail.com
- LinkedIn: linkedin.com/in/mithun-r-naik-340607386
- GitHub: github.com/mithunaik24-maker
