# Great Valley Playbook — team page

A read-only, password-locked copy of the team playbook, published with GitHub Pages.

- `index.html` holds the playbook encrypted (PBKDF2-SHA256 → AES-GCM). Without the team password it shows only an unlock screen; the play data is not readable from the page source.
- Rebuilt and pushed whenever the plays change. The link stays the same.
