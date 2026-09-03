# iOS Developer Roadmap 2026 — Landing Page

A single page, fully responsive landing page for the **iOS Developer Roadmap 2026** guide, covering Swift, Xcode, SwiftUI and native app development. Built with plain HTML, CSS and JavaScript, no frameworks or build step required.

## Preview

Open `index.html` directly in a browser, or serve the folder with any static host (GitHub Pages, Netlify, Vercel).

## Design

The page borrows its visual language from the tools an iOS developer actually lives inside every day:

- A hero section styled as an Xcode style code editor window, with a typing animation that "writes" a short Swift snippet outlining the roadmap
- A numbered timeline for the four learning stages, since the content is genuinely sequential
- A skills grid styled as file tiles rather than generic shadowed cards
- A course directory styled as clickable rows, similar to a file browser or App Store list
- Dark, editor inspired palette (deep navy background, Swift's own orange as the primary accent, iOS system blue and mint as supporting accents)
- Typeset in JetBrains Mono for code adjacent elements and Inter for body copy

## Structure

```
.
├── index.html      # complete landing page (HTML + CSS + JS in one file)
└── README.md       # this file
```

## Features

- Fully responsive, from a 1120px desktop layout down to small mobile screens
- Respects `prefers-reduced-motion` for the typing animation and hover transitions
- Visible keyboard focus and semantic HTML throughout
- All linked courses and articles open in a new tab with `rel="noopener"`
- Zero dependencies beyond Google Fonts

## Links used on this page

- iOS Training in Pune
- Android App Development in Pune
- Flutter Training in Pune
- React Native Training in Pune
- iOS Developer Roadmap 2026 (blog)
- iOS Development Tutorials (blog)
- iOS Developer Training (blog)

## License

Free to use and adapt for JustAcademy's own marketing pages.
