# yushanmeng.github.io

Personal academic website for Yushan Meng, designed as a lightweight static site
for GitHub Pages.

## Preview locally

From the repository directory, run:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Update the content

- Profile, affiliation, and homepage research summary: `index.html`
- Working papers and research projects: `research.html`
- Shared layout and visual styling: `styles.css`

The web-ready portrait is stored at `assets/yushan-meng-portrait.jpg`, with a
smaller responsive version at `assets/yushan-meng-portrait-480.jpg`. The
untouched upload is retained at `assets/portrait-source.jpg`. To replace the
portrait later, keep the same filenames and use a vertical 4:5 crop.

The current CV is stored at `assets/yushan-meng-cv.pdf`. Replace that file while
keeping the same filename whenever the CV is updated.

## Publish with GitHub Pages

In the repository settings, open **Pages**, choose **Deploy from a branch**, and
select the root of the `main` branch. The site will be available at
<https://yushanmeng.github.io/>.
