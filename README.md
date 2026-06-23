# ByTE X Bit — Website & Free Tools

The public website and free, open security tools from **ByTE X Bit Technologies LLC** —
cybersecurity software & services. Safe, secure, and reliable. No hardware.

🌐 https://byte-x-bit.com

## What's here

- **`index.html`** — the company website. Organized by audience: small businesses, large
  businesses, and people who just want to try the tools.
- **`email-checker.html`** — **Email Security Checker.** A free, client-side tool that checks a
  domain's SPF, DKIM, and DMARC records and explains, in plain English, what's configured and
  what to fix. It runs entirely in the browser using DNS-over-HTTPS (Cloudflare `1.1.1.1`, with
  Google `8.8.8.8` as a fallback) — there is **no backend**, and nothing is logged.
- **`bxb-logo.png`, `bxb-lockup.png`, favicons** — brand assets used by the pages.

## Free tools

These are deliberately simple, build-on-public-data utilities — our reputation layer, free to use
and free to read. More are on the way (posture self-check, IR plan generator, breach-exposure
checker, and detection-engineering utilities).

The proprietary scoring and detection engines that power the paid platform are **not** in this
repository.

## Running locally

Everything here is static. Open `index.html` in a browser, or serve the folder with any static
web server:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080/
```

The pages reference assets by absolute path (e.g. `/bxb-logo.png`), so serve from the folder root.

## License

The page and tool **code** in this repository is licensed under the **Apache License 2.0** — see
[`LICENSE`](LICENSE).

The **ByTE X Bit name, logos, and brand assets** (including `bxb-logo.png` and `bxb-lockup.png`)
are trademarks and © 2026 ByTE X Bit Technologies LLC. All rights reserved. They are **not**
covered by the Apache license and may not be reused without permission.

Patent pending.
