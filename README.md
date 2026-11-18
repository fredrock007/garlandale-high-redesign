# Garlandale High School — Reece Digital independent concept

**Version:** 0.1 local review build, 18 November 2026

This project follows `REECE_DIGITAL_SCHOOL_WEBSITE_MASTER_BLUEPRINT_v2_GITHUB_RELEASE` as a standalone Garlandale High concept; it does not copy Garlandale Primary's identity or assets. It is **not the official website** and does not imply school approval.

## Open and review

For full browser functionality, extract this ZIP, then serve the folder with a local HTTP server, e.g. run `python3 -m http.server 8000` inside the extracted folder and open http://localhost:8000/ in Firefox or Chrome. Static links will also work by opening `index.html` directly, but browser storage restrictions can vary with `file://`.

## Pages

Home; Our School; Academics; Updates; Calendar; Documents; Admissions; Gallery; Contact; Staff Login; Staff Dashboard.

## Demo staff dashboard

Visit `staff-login.html` and enter username `staff` and password `demo123`. This is a **public, intentionally insecure local demo**, not school authentication. Announcements, events, document links and sourced story cards save in browser `localStorage` only. Nothing is uploaded or synchronized. For a real launch, build secure login and a shared content backend.

## Publishing and approval

Before a public GitHub Pages release, secure permission for official school identity and photographs, verify current principal/contact details, check admissions accuracy, replace the GH concept monogram with an approved school crest and run visual browser tests. Do not imply an official affiliation. `docs/SOURCE_MANIFEST.md` and `docs/QA_REPORT.md` track pending tasks. No school photographs or third-party news photos are republished in this package.

## Architecture

Standalone HTML/CSS/JS without a framework or third-party CDN. CSS in `css/site.css`; JavaScript in `js/site.js`; school details and source article references in `data/*.json`. Responsive heroes use unique inline SVG motion and position their illustration below text on phones. JavaScript escapes user-entered text before rendering.


## 18 Nov 2026 revision
- Added 3 community review cards from the supplied Facebook review screenshots.
- Replaced generic gallery/updates illustrations with sourced concept photography and added public links.
- Reworked the badge usage to use the supplied Garlandale crest and a distinct animated hero treatment.
- Removed any cursor-trail concept from the banner interactions; hover effects are restrained.
- Replaced immature placeholder image treatments with a more premium collage and photo-card style.
