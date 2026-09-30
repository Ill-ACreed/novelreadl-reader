# novelreadl-reader

Deployed static reader for the private [novelreadl](https://github.com/Ill-ACreed/novelreadl) project.

**Data is encrypted.** The published `*.db.enc` files are SQLite databases
wrapped in AES-GCM (PBKDF2-SHA256, 200 000 iterations). The reader prompts
for a passphrase on first load; nothing is readable without it.

- Source: <https://github.com/Ill-ACreed/novelreadl>
- Deploy: `NR_PASS='…' reader/scripts/deploy-pages.sh` from the source repo
- Reader: <https://ill-acreed.github.io/novelreadl-reader/>
