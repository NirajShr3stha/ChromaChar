<div align="center">

# ChromaChar

### Make every character dress like it has somewhere important to be.

A fast, private, zero-dependency text colorizer with live previews and clean exports for **BBCode**, **HTML**, and **Unity Rich Text**.

[Try It Live](https://v0-chromaflow.vercel.app/) · [Report a Bug](https://github.com/NirajShr3stha/prismatic-text/issues) · [Request a Feature](https://github.com/NirajShr3stha/prismatic-text/issues)

</div>

---

## About

**ChromaChar** turns ordinary text into colorful, ready-to-use markup.

Enter your text, select an effect, adjust the colors, and copy the generated code. There are no accounts, subscriptions, build tools, databases, or mysterious servers judging your choice of neon green.

Everything runs locally in your browser.

## Features

- Live color preview
- Ten built-in color effects
- Custom start, middle, and end colors
- Adjustable font family and text size
- Bold and italic formatting
- Multiline text support
- Whitespace preservation
- BBCode export
- HTML export
- Unity Rich Text export
- One-click clipboard copying
- Responsive desktop and mobile interface
- Accessible controls and keyboard navigation
- Zero runtime dependencies
- No frameworks, tracking, accounts, or databases

> Your dramatic rainbow announcement remains between you and your browser.

---

## Color Effects

| Effect | Description |
|:---|:---|
| **Horizontal** | Blends smoothly from the start color to the end color |
| **Reverse** | Runs the horizontal blend in the opposite direction |
| **Middle** | Moves toward the second color and then returns |
| **Three Color** | Blends through start, middle, and end colors |
| **Pulse** | Repeats a smooth color pulse across the text |
| **Stripes** | Alternates between the selected colors |
| **Solid** | Applies one color to every character |
| **Random** | Gives each character a deterministic random color |
| **Rainbow** | Sends the entire visible spectrum to do the job |
| **Pastel Rainbow** | Rainbow mode after a relaxing spa appointment |

---

## Export Formats

### BBCode

Useful for forums, community platforms, and places where signatures are still treated as a competitive sport.

```bbcode
[b][size=32][color=#FF5C5C]H[/color][color=#35C8B4]i[/color][/size][/b]
```

### HTML

Useful for websites and prototypes where every individual letter requires personal attention.

```html
<span style="font-size:32px;font-weight:700">
  <span style="color:#FF5C5C">H</span>
  <span style="color:#35C8B4">i</span>
</span>
```

### Unity Rich Text

Useful for game interfaces, dialogue, nameplates, and informing players that an item is legendary before they discover it is another wooden spoon.

```html
<b>
  <size=32>
    <color=#FF5C5C>H</color><color=#35C8B4>i</color>
  </size>
</b>
```

---

## Getting Started

ChromaChar is a fully static website. You do not need Node.js, React, a database, or seventeen environment variables whose origins have been lost to history.

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/chromachar.git
cd chromachar
```

### Option 1: Open it directly

Open the following file in a modern browser:

```text
index.html
```

### Option 2: Start a local static server

Using Python:

```bash
python3 -m http.server 3000
```

Then visit:

```text
http://localhost:3000
```

Using Node.js:

```bash
npx serve .
```

Any static server works. ChromaChar is not picky.

---

## How to Use

1. Enter your text in the editor.
2. Add line breaks if your masterpiece requires dramatic pacing.
3. Choose a color effect.
4. Select your preferred colors.
5. Adjust the font, size, bold, or italic settings.
6. Review the result in the live preview.
7. Choose **BBCode**, **HTML**, or **Unity**.
8. Select the copy button.
9. Paste the generated markup into your destination.
10. Pretend choosing the exact shade of teal was effortless.

---

## Project Structure

```text
chromachar/
├── index.html     # Page structure and accessible controls
├── style.css      # Responsive design, themes, and animations
├── script.js      # Effects, preview rendering, and exports
├── package.json   # Optional development scripts
├── LICENSE        # MIT License
└── README.md      # The document currently judging plain text
```

---

## Privacy

All processing happens locally in your browser.

ChromaChar does **not**:

- Upload your text
- Store your text
- Analyze your text
- Track your activity
- Require an account
- Send your content to a server
- Monetize your questionable color combinations
- Gossip about your font choices

Refreshing the page resets the editor because the application does not use persistent browser storage.

---

## Browser Support

ChromaChar works in current versions of:

| Browser | Support |
|:---|:---:|
| Chrome | Supported |
| Edge | Supported |
| Firefox | Supported |
| Safari | Supported |

Clipboard behavior can vary when opening `index.html` directly from the file system. Serving the project through `localhost` or HTTPS provides the most reliable clipboard experience.

---

## Development

The project intentionally uses plain HTML, CSS, and JavaScript.

There is no compilation step. Saving a file and refreshing the browser is the entire development pipeline. Somewhere, a bundler just felt a disturbance in the force.

### Validate the JavaScript

```bash
node --check script.js
```

### Start the development server

```bash
npm run dev
```

Then open:

```text
http://localhost:3000
```

---

## Deployment

Because ChromaChar is static, it can be deployed to:

- Vercel
- GitHub Pages
- Netlify
- Cloudflare Pages
- Any traditional web server
- A sufficiently determined toaster with HTTP support

Publish the repository root and use `index.html` as the entry page.

### Deploy to Vercel

1. Import the GitHub repository into Vercel.
2. Select **Other** as the framework preset.
3. Leave the build command empty.
4. Set the output directory to the project root.
5. Deploy.

---

## Contributing

Contributions are welcome.

### Contribution workflow

1. Fork the repository.
2. Create a feature branch:

```bash
git checkout -b feature/more-unreasonable-colors
```

3. Make your changes.
4. Test the editor, preview, color picker, and export formats.
5. Commit the changes:

```bash
git commit -m "Add more unreasonable colors"
```

6. Push the branch:

```bash
git push origin feature/more-unreasonable-colors
```

7. Open a pull request explaining what changed.

Please preserve:

- Accessibility
- Responsive behavior
- Multiline input
- Whitespace handling
- Clipboard fallback behavior
- Dependency-free architecture

Spaces deserve representation too.

---

## Ideas for Future Improvements

- More color interpolation modes
- Reusable palette presets
- Import and export settings
- Additional markup formats
- Contrast accessibility warnings
- Shareable configuration links
- Undo and redo controls
- Downloadable output files
- A button labeled “Make it tasteful” that nobody clicks

---

## Reporting Issues

Found a bug?

[Open an issue](https://github.com/YOUR_USERNAME/chromachar/issues) and include:

- What you expected to happen
- What actually happened
- Your browser and operating system
- Steps to reproduce the issue
- A screenshot, if relevant
- The color combination responsible for the incident

---

## License

ChromaChar is released under the [MIT License](LICENSE).

You may use, copy, modify, merge, publish, distribute, sublicense, and build upon the project. Attribution is appreciated, and tasteful color combinations are strongly encouraged.

---

## Acknowledgments

Built for everyone who has looked at ordinary text and thought:

> This needs significantly more color.

<div align="center">

**If ChromaChar helped your text escape a life of monochrome, consider giving the repository a star.**

Made with plain HTML, CSS, JavaScript, and an unreasonable commitment to colorful letters.

</div>
