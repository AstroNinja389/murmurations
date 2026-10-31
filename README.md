# Murmurations

An animated statement of the murmuration phenomenon for weight-2 modular forms,
from the paper *Murmurations* by Nina Zubrilina (arXiv:2310.07681, Invent. Math. 2025).

Live site: https://astroninja389.github.io/murmurations/

- `index.html`: landing page
- `film.html`: the statement, an animated walk from one modular form to the murmuration density (Theorem 1)
- `limit_k42.html`: the weight-42 density settling onto the universal limit of Theorem 3

Each page is a self-contained HTML file; the Theorem 3 page shows `limit_k42.webp` (GIF fallback). Data: the newform 1433.2.a.a and
five other rational newforms of squarefree conductor between 1400 and 1600, with
a_p computed by point counting and checked against the LMFDB; the two pile sums
run over all 10,734 weight-2 newforms with trivial character and squarefree level
in [1400, 1600), from exact LMFDB trace data; the dashed curves are the density
of Theorem 1 of the paper.
