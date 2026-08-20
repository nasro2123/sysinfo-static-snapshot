# SysInfo — Static Public Snapshot

This is a static snapshot of the public frontend for the SysInfo website. It was generated from the publicly accessible pages and resources on the `sys-info.xyz` domain, as authorized by the site owner.

## What's Included

This repository contains public HTML pages, CSS, JavaScript, and local image assets downloaded from the site. It preserves the overall layout and basic navigation between pages.

## Running Locally

You can run this snapshot using any static file server. For example, using Python:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080/` in your browser.

## Important Notes

This is **not** a copy of the original backend server. Features such as Discord login, checkout, dynamic shopping cart, product status checks, and any requests relying on sessions or backend APIs will not work unless connected to an independently managed backend.

CSRF tokens and session data have been removed from the HTML files prior to publishing. No API keys, passwords, or credentials are included.

Some external product links or resources may require additional configuration if deployed under a subpath on GitHub Pages.

## Source

Original visual source: <https://sys-info.xyz/>.

This repository serves as a deployable static snapshot, not a complete backup of the server application or database.
