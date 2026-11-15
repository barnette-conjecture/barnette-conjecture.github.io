# Every Vertex Once

A static site about Barnette's conjecture. No build step: serve the folder (`python3 -m http.server`) and open it.

| File | What it is |
| --- | --- |
| `index.html` | The game. Hold → to run the Hamiltonian cycle, ← to run back; the thread already laid stays. Below it, links to the two pages. |
| `history.html` | From Hamilton's Icosian game (1856) to the proof (2026). Picture credits at the bottom. |
| `proof.html` | The interactive walkthrough of OpenAI's proof, from `barnette-proof-walkthrough.html` in [mathathon-Barnette-s-Conjecture](https://github.com/Tomodovodoo/mathathon-Barnette-s-Conjecture). Only its colours, type and top bar differ from the original. |
| `site.css` | Shared colour tokens (light and dark), type, and the top bar. The game reads its scene colours from these tokens. |
| `three.min.js` | three.js r187, used by the game. |
| `images/` | Pictures for the history page. `solid-120.jpg` and `proof-figure.jpg` are screenshots of this site; the rest come from Wikimedia Commons. |
