# Issac Yurui Hu website — v6

v6 moves the site toward a simpler academic/economist profile:
- only “Issac Yurui Hu” and “胡雨瑞” are shown as names
- adds Education
- adds both World Bank and personal email addresses
- keeps the existing research and report sections
- remains mobile responsive
- retains Google indexing metadata, `robots.txt`, and `sitemap.xml`

Keep the existing `headshot.jpg` in the repository root.

Upload/replace:
- `index.html`
- `styles.css`
- `robots.txt`
- `sitemap.xml`
- `CNAME`
- `favicon.svg`

For the public personal email, `yrui.hu11@gmail.com` is suitable as a permanent professional address. To avoid missing messages, set that Gmail account to forward incoming mail to the Gmail account you actually check every day.


## v6.1 correction
- Confirmed DOI links for *Taxing Times*, *Women, Jobs, and Growth*, and *Jobs for Resilience*.
- Corrected *Jobs for Resilience*: research assistance was for the Spotlight only, not Chapter 2.


## v7 mobile hotfix
The mobile portrait is now fixed at 180 × 225 CSS pixels and the mobile layout
uses simple block flow instead of responsive grid/vw sizing. This specifically
prevents the oversized portrait seen in iPhone Safari.
