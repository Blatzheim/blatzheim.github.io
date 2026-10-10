# blatzheim.github.io

Source of the personal academic homepage of Alexander Blatzheim, PhD student at the
Chair for Software Engineering and AI, Hasso-Plattner-Institut, Potsdam.

Live site: https://blatzheim.github.io/

## Structure

- `index.html`: the complete page (markup, styles and scripts)
- `photo.jpg`, `cover.jpg`: portrait and cover image
- `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`: site icons
- `fonts/`: self-hosted Literata and Schibsted Grotesk (SIL Open Font License, see the `OFL-*.txt` files)
- `slides/`: documents linked from the page

## Publishing

GitHub Pages builds the site from `main` with Jekyll. The front matter in `index.html` lets Jekyll
insert the "Last updated" month in the footer at build time.

## Local preview

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000. The footer date placeholder is only filled in by the Pages build.

## License

Text © Alexander Blatzheim, licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).
Cover photo © Hasso-Plattner-Institut. Fonts under the SIL Open Font License.
