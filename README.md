# anima — the web page

The page behind [animaai.io](https://animaai.io): one `index.html`, one `style.css`, an `img/`
folder of screenshots from a fixture house (a keeper called Sam; no real journal, no real friend),
and a `CNAME` for the domain. Hosted on GitHub Pages from `main`, no build step, nothing fetched
from anywhere but one request to GitHub's releases API for the version line (the page says
"anima 0.13" on its own when that request fails).

The engine itself lives at [PsychohistorianDev/Anima](https://github.com/PsychohistorianDev/Anima);
this repository is only the page.

To change the page, edit `index.html` and push. The screenshots are re-taken from a fresh copy of the
template with `USER_NAME = "Sam"` and Ollama's answers stubbed in-process (the panel on a 12 GB
card with `gemma4:12b` loaded), headless, at 2× scale; the engine files are never edited for it.
