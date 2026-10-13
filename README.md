# OxClock Android promotional site

Standalone editable HTML/CSS/JS source for app.oxclock.com. No build or application server is required. Deploy the static files to a separate Cloudflare Pages project, never to the main OxClock project. Main pages are `/` and `/privacy/`. Local images are unchanged approved screenshots; SCREENSHOTS.md and asset-checksums.json document their origin.

Google Play: config.js intentionally starts with an empty URL. After publication, set `window.OXCLOCK_PLAY_URL` to the verified https://play.google.com/store/apps/details?id=com.oxclock.pocket listing. play-link.js accepts only that host/path/package. Until then the site displays release pending and links to the web tools. Do not invent a published listing.

The Privacy Policy is based on the supplied Android 0.13 editable source and its bundled policy. The promotional website's hosting/privacy scope is stated separately. Reconcile policy and Google Play Data safety with the final app submitted by the publisher if it changes. No analytics script or ad SDK is included in this promotional site.

Use a static web server for local inspection, then verify mobile portrait/landscape and desktop before publishing. Browser QA and hosted deployment were not available in the package-preparation environment; see the master QA report.
