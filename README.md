# madebykapec.github.io

The GitHub Pages user site of the madebykapec account: a home page and the privacy policy of the personal Google OAuth app "madebykapec backup".

Google requires a home page and a privacy policy on an authorized domain before an external OAuth app can be switched to production. In Testing mode its logins expire after 7 days.

- `index.html`: the home page (Branding: Application home page, `https://madebykapec.github.io/`).
- `privacy.html`: the privacy policy (Branding: Application privacy policy link, `https://madebykapec.github.io/privacy.html`).

**Change:** edit the HTML, commit, push to `main`; GitHub Pages redeploys in about a minute. If the URLs change, update the Branding page in the Google Cloud console too.

**Undo:** the OAuth app needs these URLs while it is in production. To remove the site, first move the app back to Testing or delete the Google Cloud project, then archive or delete this repository.

Static HTML, no scripts, no external resources.
