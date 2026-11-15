# Every Vertex Once

A static site about Barnette's conjecture. No build step: serve the folder (`python3 -m http.server`) and open it.

| File | What it is |
| --- | --- |
| `index.html` | The game. Hold → to run the Hamiltonian cycle, ← to run back; the thread already laid stays. Beside it (below it on a phone), links to the two pages. |
| `history.html` | A timeline from Hamilton's Icosian game (1856) to the proof (2026), one screen per step. Move with ← →, the rail, a swipe or the wheel; `#1946` links to a step. Each slide is a `<section>`, and the rail is built from them. |
| `proof.html` | The interactive walkthrough of OpenAI's proof, from `barnette-proof-walkthrough.html` in [mathathon-Barnette-s-Conjecture](https://github.com/Tomodovodoo/mathathon-Barnette-s-Conjecture). Its text and scripts are the original's, except that the second row of steps is always drawn (and hidden outside steps 4a–4d) so nothing below it moves. On a desktop screen the walkthrough is one screen: the figure is one fixed square, its buttons or slider sit in a band under it, and the text scrolls beside it. The references are below. |
| `site.css` | Shared colour tokens (light and dark), type, and the top bar. The game reads its scene colours from these tokens. |
| `three.min.js` | three.js r187, used by the game. |
| `images/` | Pictures for the history page. `solid-120.jpg` and `proof-figure.jpg` are screenshots of this site; the rest come from Wikimedia Commons. |
