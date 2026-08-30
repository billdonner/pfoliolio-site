# pfoliolio.com

Public support + privacy pages for **Pfoliolio**, served by GitHub Pages
from this repo (`CNAME` = pfoliolio.com).

Deliberately **entity-neutral**: no company name appears, so these pages
stand unchanged when the app moves to Steve's LLC as seller of record.

```
/          support
/privacy   privacy policy (the canonical copy the App Store record points at)
```

## Setup still required

1. **IONOS DNS** for pfoliolio.com:
   - `A` @ → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` www → `billdonner.github.io`
   Then GitHub → repo Settings → Pages → Custom domain `pfoliolio.com`,
   and tick **Enforce HTTPS** once the certificate issues.
2. **Email**: the pages currently show `billdonner@gmail.com` because it
   WORKS. Set up IONOS forwarding for `support@pfoliolio.com` and swap it
   in — never publish a support address that bounces; App Review checks.
3. **pfoliolio.app** is registered too and currently unused — point it at
   the same site or leave parked.

Once live, repoint the ASC support/marketing/privacy URLs and the in-app
Settings links (Portfolio/SettingsView.swift).
