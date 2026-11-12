# Workshop on Learning, Optimization and Decision-Making

An English-language, responsive workshop website for Digital Futures, Stockholm.

Website: https://zifan-5528.github.io/workshop-2026-dcs/

## Preview locally

From this directory, run:

```sh
python -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173/. No package installation or build is required.

## Update the website

- Edit `index.html` for the date, description, program, venue and organizers.
- Edit `assets/styles.css` for colors, spacing and responsive layouts.
- `assets/favicon.svg` is the site icon.
- `assets/workshop-figure.svg` is the standalone workshop illustration; `assets/workshop-figure.png` is its high-resolution 2536 × 2288 PNG export.
- Keep asset URLs relative so they work under `/workshop-2026-dcs/`.

The supplied program lists both the brief welcome and the first talk at 08:30. Both entries are preserved. The 11:05–11:50 slot contains student presentations by Alice Harting and Yulun Wu; the individual time allocation has not been specified. Confirmed presentation titles are shown alongside their speakers; remaining titles are marked TBD.

The workshop takes place on Friday, November 27, 2026. All program times are local to Stockholm.

Provided abstracts appear beneath their talk titles in native HTML disclosures. Click or use the keyboard on **Abstract** to expand or collapse a summary; multiple abstracts can remain open. Navid Azizan, Daniel Kuhn and Fredrik D. Johansson have full abstracts. Alice Harting and Yulun Wu currently display **Abstract coming soon.** Replace each placeholder with the same disclosure markup when their text is available.

The public schedule concludes with closing remarks at 11:50. Private arrangements are omitted from the website. About describes robust learning, optimization under uncertainty and data-driven decision-making.

## Publish with GitHub Pages

After the first push to `main`, open **Settings → Pages** in this repository:

1. Set **Source** to **Deploy from a branch**.
2. Select **main** and **/ (root)**.
3. Click **Save**.

GitHub Pages will publish the static files. `.nojekyll` disables Jekyll processing. Future pushes to `main` update the site automatically.

## Verified references

These sources informed affiliations, contact details, the venue address and the general research themes in About. The About copy describes the workshop's scope, rather than claiming specific talk topics.

- [Navid Azizan, MIT](https://azizan.mit.edu/)
- [Daniel Kuhn, EPFL](https://people.epfl.ch/daniel.kuhn?lang=en)
- [Fredrik D. Johansson, Chalmers](https://www.chalmers.se/en/persons/frejohk/) and [research interests](https://www.fredjo.com/)
- [Digital Futures: contact and directions](https://www.digitalfutures.kth.se/contact/)
- KTH profiles: [Zifan Wang](https://www.kth.se/profile/zifanw?l=en), [Alice Harting](https://www.kth.se/profile/aharting?l=en), [Karl H. Johansson](https://www.kth.se/profile/kallej?l=en)
