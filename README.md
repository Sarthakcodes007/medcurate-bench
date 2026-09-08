# MedCurate-Bench project page

Static site, no build step.

Deploy on Vercel:

    npm i -g vercel
    vercel            # from this folder; accept defaults (framework: Other, output: ./)

Or drag the `website/` folder onto vercel.com/new.

Before deploying, fill the four links at the bottom of `index.html`:

    var LINKS = { paper: "...", supp: "...", code: "...", poster: "..." };

Figures come from `../make_poster_figures.py` (`figures_poster/*.png`) and
`../make_figures.py` / `../make_appendix.py` rendered at 300 dpi.
