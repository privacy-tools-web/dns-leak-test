# DNS & IP Leak Test

A lightweight, client-side DNS and IP leak checker. No dependencies, no tracking, no server — everything runs directly in your browser.

## Features

- **WebRTC IP Leak detection** — checks whether your real IP address is exposed via WebRTC, even behind a VPN
- **DNS-over-HTTPS check** — verifies whether your browser is using encrypted DNS
- **Public IP display** — shows your visible IP address as seen by external servers
- **DNS resolver info** — identifies the DNS resolver your browser is using
- Summary with clear pass/fail status and actionable recommendations
- Zero dependencies — no frameworks, no external scripts, no Font Awesome

## Privacy

All tests run locally in your browser. The only external requests made are the WebRTC STUN request and the DNS resolver lookup — these are the tests themselves, not data submissions.

No cookies. No analytics. No data collection of any kind.

## Usage

Download `dns-leak-test.html` and open it in any modern browser. No build step, no install, no server required.

```bash
git clone https://github.com/privacy-tools-web/dns-leak-test.git
open dns-leak-test/dns-leak-test.html
```

## Live Version

Available at [pc-privacytools.org/tools/dns-leak-test](https://pc-privacytools.org/tools/dns-leak-test)

## License

MIT — free to use, modify, and distribute.

---
