# Premium Audit build plan

This repository exists only to host one page on GitHub Pages.

`index.html` is a sign-in form plus an AES-256-GCM ciphertext of the page. The key is derived
from the password with PBKDF2-SHA256 at 250,000 iterations; the password is not in this
repository, this README, or the commit history. Without it the page is noise.

`status.csv` is the team's board and is **deliberately in the clear**. A story id and a status
mean nothing without the page that defines them, and keeping it readable is what lets the page
save straight to it.

**Notes in this file are public. Do not write anything in a note that should not be.**

Edit the board from the page (Share with the team) or directly here. Do not hand-edit
`index.html`: it is generated, and a publication will overwrite it.

The plan sources live in the private repository and are never published here.
