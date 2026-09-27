# personal-website
Personal portfolio website showcasing my experience, skills, and projects.

This website is in progress. Content and projects will be added over time.

[View the website](https://tate-curtis-nunberg-2026.tcnunberg.chatgpt.site/)

## Code

The site uses HTML and CSS, with no framework or build step. The editable website files live in `dist/`.

| File | What it controls |
| --- | --- |
| `dist/index.html` | Home page |
| `dist/styles.css` | Colors, fonts, spacing, and layout across all pages |
| `dist/blog/index.html` | Writing page |
| `dist/experience/index.html` | Experience page |
| `dist/projects/index.html` | Projects page |
| `dist/about/index.html` | About page |
| `dist/favicon.svg` | Browser tab icon |

Open this repository folder in a code editor such as Visual Studio Code. Edit the HTML for words and links, and the CSS for appearance.

## Preview locally

With Python 3 installed, run this from the repository folder:

```sh
python3 -m http.server 8000 --directory dist
```

Then open http://localhost:8000 in a browser. Press Control+C in the terminal to stop the preview. Use the local server because navigation and styles use paths beginning with `/`.

## Save and publish changes

1. Edit and save the files.
2. In GitHub Desktop, review the changes and enter a short summary.
3. Click **Commit to main** to save a version on your computer.
4. Click **Push origin** to upload that version to GitHub.

The live website is hosted through Sites. A GitHub push saves the code online; it does not automatically update the live website. Publishing to Sites is a separate step. `.openai/hosting.json` records the existing site and its publishing directory.
