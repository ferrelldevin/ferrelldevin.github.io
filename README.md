# ferrelldevin.github.io

**Moved 26 Oct 2026.** This user site now forwards to [devinferrell.com](https://devinferrell.com/):

- `/` goes to the homepage.
- `/projects/` goes to [devinferrell.com/work](https://devinferrell.com/work/). Old section links (`#kurikaeshi`, `#benefits`, `#studykit`) go to the matching case study; the rest go to the list.

The forwards are instant `meta refresh` redirects with a canonical link, because GitHub Pages cannot send server-side 301s. Google reads an instant meta refresh as a permanent redirect ([Google Search Central](https://developers.google.com/search/docs/crawling-indexing/301-redirects)). Keep them for at least a year.

Project sites under this account keep their own addresses and are not affected: veteran-resources (printed QR codes point at it), studykit, vetkit, cmai-tracker. Do **not** add a custom domain to this repo: a user site's custom domain is inherited by every project site ([GitHub Docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages)), which would move the kit off the addresses its QR codes use.

To restore the old pages, `git revert` the redirect commit. The old Projects page is at 6b5a5c6.

© 2026 Devin Ferrell.
