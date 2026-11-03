# Persian Soda Packaging Generator

A Persian-language, right-to-left web page for the soda packaging design skill. The skill is restricted to soda packaging and requires all visible package copy to be written in Persian script.

![Screenshot of the Persian soda packaging generator UI](ui-screenshot.png)

## Project files

- `index.html` - The interactive web page, including the skill preview, copy/download controls, and image gallery.
- `soda generator.md` - The standalone packaging design skill in Markdown format.
- `Gallery files/` - Local packaging concept images used by the page.
- `ui-screenshot.png` - Screenshot of the web page.

## Run locally

Open `index.html` in a browser. No build step or package installation is required. The page uses a Google-hosted Vazirmatn font when an internet connection is available and falls back to local system fonts otherwise.

## Use the skill

Copy or download the Markdown skill from the page, or use `soda generator.md` directly with a compatible assistant. It directs the assistant to create soda packaging only and keep every visible package word in Persian.