# portfolio

Personal site of Jakub Kaczmarski: [jakubkaczmarski.github.io/porfolio](https://jakubkaczmarski.github.io/porfolio/).

A single static page with no build step: projects, experience, hackathons, about and contact.

## Run it locally

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Files

- `index.html`: all the content
- `style.css`: all the styles
- `favicon.svg`: the tab icon
- `assets/`: screenshots and videos, one folder per project, plus `og.png` (the link preview image)
- `previews/`: screenshots of the page itself, not used by the site

## Editing

- After changing `style.css`, raise the version number in the stylesheet link in `index.html` (`style.css?v=…`) so browsers load the new file.
- Landscape screenshots are 1600×1000 JPEGs.
- The link preview tags in `index.html` use full `https://jakubkaczmarski.github.io/porfolio/` addresses. Change them if the site moves.
