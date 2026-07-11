# Lorem Ipsum Generator

Generate lorem ipsum placeholder text in your browser. No server, no tracking, no third-party scripts.

**Live demo:** https://0xelitesystem.github.io/lorem-ipsum-generator/

## Use

Open `index.html` in any modern browser, or visit the GitHub Pages link in the repo description.

1. Set an amount.
2. Choose a unit: paragraphs, sentences, or words.
3. Toggle "Start with Lorem ipsum..." on or off.

The output updates live as you change the options. Click Copy text to put it on your clipboard. A word and character count sits under the output.

## Why this exists

Most lorem ipsum sites are covered in ads and load third-party scripts to generate a few sentences of Latin. This is a single file that does the same thing offline, with a live preview and a copy button.

## Privacy

Everything runs in your browser. The generated text never leaves your machine. There are no network requests, no analytics, and no external scripts. Verify by viewing the page source or watching the network tab in DevTools.

## Run locally

```bash
git clone https://github.com/0xelitesystem/lorem-ipsum-generator
cd lorem-ipsum-generator
# Open index.html in your browser, or:
python -m http.server 8000
```

## Build

There is no build. It is a single HTML file.

## License

MIT.

## Related

- [mock-data-generator](https://github.com/0xelitesystem/mock-data-generator)
- [htaccess-redirect-generator](https://github.com/0xelitesystem/htaccess-redirect-generator)
- [jwt-inspector](https://github.com/0xelitesystem/jwt-inspector)
