# Yoser Bichiou — Portfolio

My personal portfolio site: about, skills, experience, projects, education, and a way to get in touch.

Built on top of [DevFolio](https://github.com/AnilSeervi/DevFolio) by Anil Seervi, a one page portfolio template, then heavily rewritten with my own content and a custom design.

## Live site

Not deployed yet. To publish it, enable GitHub Pages for this repository (Settings → Pages → deploy from the `master` branch), and it will be served at `https://bichiouyosr.github.io/DevFolio/`.

## Structure

Everything lives in a single `index.html`: hero, about, expertise, skills, experience, projects, blog, education, and contact sections, each with an anchor in the top nav. Styling is inline in the file rather than a separate stylesheet, and there's no build step, no dependencies, no `npm install`, just static HTML.

```
index.html      the whole site
assets/
  profile.jpg   the photo used in the About section
```

## Running locally

Open `index.html` directly in a browser, or serve it with any static file server, for example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Known gap

The two "Download CV" buttons point at `assets/YOSER_Bichiou_DS.pdf`, which isn't in the repo yet. Drop the actual resume file at that path and the buttons will work.

## Credits

Original template: [DevFolio](https://github.com/AnilSeervi/DevFolio) by Anil Seervi, MIT licensed. See [LICENSE](LICENSE).
