```markdown
# ChromaChar

> Make every character dress like it has somewhere important to be.

ChromaChar is a fast, dependency-free text colorizer that turns ordinary text
into colorful markup for **BBCode**, **HTML**, and **Unity Rich Text**.

Type your text, choose an effect, adjust the colors, and copy the generated
code. No accounts, no build tools, no mysterious server rituals, and no
subscription asking for your credit card just to make a sentence red.

## Features

- Live color preview
- Ten color effects
- Custom start, middle, and end colors
- Font family and size controls
- Bold and italic formatting
- Multiline text support
- Whitespace preservation
- BBCode export
- HTML export
- Unity Rich Text export
- One-click clipboard copying
- Responsive desktop and mobile layout
- Accessible controls and keyboard navigation
- Zero runtime dependencies
- No frameworks
- No tracking
- No database
- No text sent to a server

Your dramatic rainbow announcement remains between you and your browser.

## Color Effects

ChromaChar includes the following effects:

| Effect | What it does |
| --- | --- |
| Horizontal | Blends smoothly from the start color to the end color |
| Reverse | Runs the horizontal blend in the opposite direction |
| Middle | Moves toward the second color and then returns |
| Three Color | Blends through start, middle, and end colors |
| Pulse | Repeats a smooth color pulse across the text |
| Stripes | Alternates between the selected colors |
| Solid | Applies one color to every character |
| Random | Gives each character a deterministic random color |
| Rainbow | Sends the entire visible spectrum to do the job |
| Pastel Rainbow | Rainbow mode after a relaxing spa appointment |

## Export Formats

### BBCode

Useful for forums, community platforms, and places where signatures are still
treated as a competitive sport.

```bbcode
[b][size=32][color=#FF5C5C]H[/color][color=#35C8B4]i[/color][/size][/b]
```

### HTML

Useful for websites, prototypes, and explaining to your browser that every
letter requires individual attention.

```html
<span style="font-size:32px;font-weight:700">
  <span style="color:#FF5C5C">H</span>
  <span style="color:#35C8B4">i</span>
</span>
```

### Unity Rich Text

Useful for game interfaces, dialogue, nameplates, and informing players that
an item is legendary before they notice it is just another wooden spoon.

```html
<b><size=32><color=#FF5C5C>H</color><color=#35C8B4>i</color></size></b>
```

## Getting Started

ChromaChar is a fully static website. You do not need Node.js, React, a
database, or seventeen environment variables whose origins have been lost to
history.

### Option 1: Open it directly

Clone or download the repository and open `index.html` in a modern browser.

```shellscript
git clone https://github.com/YOUR_USERNAME/chromachar.git
cd chromachar
```

Then open:

```plaintext
index.html
```

### Option 2: Use a local static server

Python:

```shellscript
python3 -m http.server 3000
```

Then visit:

```plaintext
http://localhost:3000
```

Node.js:

```shellscript
npx serve .
```

Any static server works. ChromaChar is not picky.

## Project Structure

```plaintext
chromachar/
├── index.html    # Page structure and accessible controls
├── style.css     # Responsive design, themes, and animations
├── script.js     # Effects, preview rendering, and exports
└── README.md     # The document currently judging your plain text
```

## How to Use

1. Enter text in the editor.
2. Add line breaks if your masterpiece requires dramatic pacing.
3. Choose a color effect.
4. Select your colors.
5. Adjust the font, size, bold, or italic settings.
6. Review the live preview.
7. Select BBCode, HTML, or Unity.
8. Click the copy button.
9. Paste the result somewhere suitable.
10. Pretend choosing the exact shade of teal was effortless.


## Privacy

All processing happens locally in the browser.

ChromaChar does not upload, store, analyze, monetize, admire, or gossip about
your text. Refreshing the page resets the editor because the application does
not use persistent browser storage.

## Browser Support

ChromaChar works in current versions of:

- Chrome
- Edge
- Firefox
- Safari


Clipboard behavior can vary when the site is opened directly from the file
system. The application includes a fallback, but serving it over `localhost`
or HTTPS provides the most reliable experience.

## Development

The project intentionally uses plain HTML, CSS, and JavaScript.

To validate the JavaScript:

```shellscript
node --check script.js
```

There is no compilation step. Saving a file and refreshing the browser is the
entire development pipeline. Somewhere, a bundler just felt a disturbance in
the force.

## Deployment

Because ChromaChar is static, it can be deployed to:

- Vercel
- GitHub Pages
- Netlify
- Cloudflare Pages
- Any server capable of returning files
- A sufficiently determined toaster with HTTP support


Set `index.html` as the entry page and publish the repository root.

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a branch:

```shellscript
git checkout -b feature/more-unreasonable-colors
```


3. Make your changes.
4. Test the editor, preview, and all export formats.
5. Open a pull request explaining what changed.


Please preserve accessibility, responsive behavior, multiline input, and
whitespace handling. Spaces deserve representation too.

## Ideas for Future Improvements

- More color interpolation modes
- Reusable palette presets
- Import and export settings
- Additional markup formats
- Contrast warnings
- Shareable configuration links
- Undo and redo controls
- A button labeled “Make it tasteful” that nobody clicks
