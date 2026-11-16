# madebykapec.github.io

The GitHub Pages user site of the madebykapec account: the madebykapec brand site (a work in progress) and the sub site of the personal Google OAuth app "madebykapec backup".

Google requires a home page and a privacy policy on an authorized domain before an external OAuth app can be switched to production. In Testing mode its logins expire after 7 days.

- `index.html`: the brand site's home page, with a link to the privacy policy.
- `backup/index.html`: the app's home page (Branding: Application home page, `https://madebykapec.github.io/backup/`).
- `backup/privacy.html`: the app's privacy policy (Branding: Application privacy policy link, `https://madebykapec.github.io/backup/privacy.html`).

**Change:** edit the HTML, commit, push to `main`; GitHub Pages redeploys in about a minute. If the two backup URLs change, update the Branding page in the Google Cloud console too.

**Undo:** the OAuth app needs the two backup URLs while it is in production. To remove them, first move the app back to Testing or delete the Google Cloud project.

Static HTML, no scripts, no external resources.
