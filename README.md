# nhmtri.github.io

The source of my portfolio — one self-contained HTML file, no build step, no framework.

**Live: [nhmtri.github.io](https://nhmtri.github.io/)**

It covers the quality gate I own at NielsenIQ, the animated recognition section, the field-work
story told through one interviewer, and the seven projects with their diagrams and numbers.
Everything is inline SVG and CSS animation, so it runs from a single file and degrades to a
static page when a reader has `prefers-reduced-motion` on.

| | |
|---|---|
| **Page** | `index.html` — one file, ~640 KB, inline SVG and CSS, no JavaScript framework |
| **Deploy** | pushed to `main`, published by `.github/workflows/pages.yml` |
| **Also at** | [portfolionhmtri.netlify.app](https://portfolionhmtri.netlify.app) |

The two interactive pieces live in their own repositories, because the rule and the query are the
point rather than the page around them:

- [voucher-abuse-detection](https://github.com/nhmTri/voucher-abuse-detection) — move four
  thresholds, see precision and recall move
- [rfm-segmentation-sql](https://github.com/nhmTri/rfm-segmentation-sql) — drag the cut-offs,
  the SQL rewrites itself

No client data, client names or client figures appear anywhere in this repository. Every number
shown is either my own measured work or synthetic.
