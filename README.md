# Project Unity — Website Rebuild

A full static-site rebuild of [projectunitynfp.org](https://projectunitynfp.org), a youth-development nonprofit — built as the foundation for migration into a custom WordPress theme on SiteGround.

🔗 **Preview:** <https://tahvia127.github.io/ProjectUnity/>

---

## What this is

The existing site had outgrown its template: cohort information was scattered, the programs weren't distinguishable from one another, and there was no clear donation path. This rebuild restructures the whole thing around the organization's two programs and their cohort history, adds an interactive map of where the organization operates, and puts donation one click from every page.

Everything is plain HTML, CSS, and JavaScript — no build step — so it can be dropped into a WordPress theme without untangling a bundler first.

## Pages

| Page | Contents |
|---|---|
| `index.html` | Home, with an interactive US presence map |
| `about.html` | About, Leadership, Board, and Advisory — tabbed |
| `catalyst-academy.html` | Program overview, mentors, speakers, mentor signup, applications |
| `catalyst-academy-2023/-2024/-2025.html` | Individual cohort pages |
| `yphic.html` | Y-PHIC program |
| `research.html` | Research and press |
| `support.html` | Donations, via an embedded Zeffy form |
| `contact.html` | Contact |
| `privacy-policy.html` | Privacy policy |

## Local preview

Open any `.html` file directly, or serve the folder:

```bash
python3 -m http.server 8000
```

## Notes

- `images/hero-animation.mp4` drives the home-page hero; it's the largest asset in the repo.
- Donation handling is delegated entirely to Zeffy — no payment details are collected or stored by this site.
