# Team page

A read-only, password-locked copy of a basketball playbook, published with GitHub Pages.

`index.html` holds the playbook encrypted (PBKDF2-SHA256, 200k iterations → AES-GCM-256). Without the
password the page shows only an unlock screen; nothing about the plays is readable from the file.
