# Clink & Think — Public Docs

Public documentation for **Clink & Think**, a gentle marble-and-tubes puzzle game
for young children (ages ~4–6) on iPhone & iPad. No ads, no tracking, works
offline.

🌐 **Website:** https://peltriaux.com/clinknthink

## Documents

- 📄 [Privacy Policy](PRIVACY.md)
- 🛟 [Support & FAQ](SUPPORT.md)
- 📜 [Terms of Use](TERMS.md)

## Repository layout

- `*.md` — the public documents above (source of truth).
- `site/` — the marketing website deployed to https://peltriaux.com/clinknthink
  (`index.html`, `privacy.html`, `support.html`, `assets/`). Deploy with:
  `rsync -az site/ pascal@10.254.254.2:/var/www/peltriaux/clinknthink/`
- `screenshots/raw/{iphone,ipad}/` — unframed App Store captures
  (iPhone 6.9" 1320×2868, iPad 13" 2064×2752).
- `screenshots/marketing/{iphone,ipad}/` — the same captures with marketing
  headlines + device frames (what's shown on the site and uploaded to App Store Connect).

## App Store links

- **Privacy Policy URL:** https://peltriaux.com/clinknthink/privacy.html
- **Support URL:** https://peltriaux.com/clinknthink/support.html

## Contact

Questions or support: **dev@peltriaux.com**

---

*This repository contains only public-facing documents. The game itself is a
separate, private project.*
