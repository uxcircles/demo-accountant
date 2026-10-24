# Harbour Lin Accountants — design demo

> **Fictional firm.** A design demo by [UX CIRCLES](https://ux-circles.com/professionals). Harbour Lin Accountants is not a real business, and nothing on this site is tax advice. Regulatory numbers are placeholders.

A four-language website (English · 繁體中文 with Hong Kong wording · 廣東話 written Cantonese · 简体中文) for a London accountancy firm serving Hong Kong BN(O) families.

- `/` English · `/zh-hant/` Traditional Chinese · `/yue/` Cantonese · `/zh-hans/` Simplified Chinese, linked with `hreflang` (the Cantonese page uses `lang="yue-Hant-HK"` and `hreflang="zh-HK"`, since Google does not support `yue` in hreflang)
- `AccountingService`, `Person` and `FAQPage` structured data
- Regulatory disclosure block in the footer
- Plain HTML, CSS and JavaScript — no build step. Pages are `noindex` so the fictional firm does not appear in search results.

Live demo: https://uxcircles.github.io/demo-accountant/
