# Elephant Presentation

## Compiling the LaTeX Presentation

### Requirements
- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- Required packages: beamer, tikz, fontawesome5, listings

### Compilation

```bash
# Basic compilation
pdflatex presentation.tex

# Full compilation (for references and table of contents)
pdflatex presentation.tex
pdflatex presentation.tex

# Or use latexmk for automatic compilation
latexmk -pdf presentation.tex
```

### Viewing
```bash
# Linux
evince presentation.pdf
# or
xdg-open presentation.pdf

# macOS
open presentation.pdf

# Windows
start presentation.pdf
```

## Presentation Structure

1. **Introduction** - Title and overview
2. **The Problem** - Why citation tracking matters
3. **What is Elephant?** - Core concept and features
4. **How It Works** - Architecture and data flow
5. **Usage Demo** - Installation and commands
6. **Recommendation Engine** - Smart suggestions
7. **Technical Details** - Implementation stack
8. **Results & Benefits** - Impact and time savings
9. **Future Work** - Roadmap and enhancements
10. **Conclusion** - Summary and Q&A

## Customization

You can customize the presentation by:
- Changing the theme: `\usetheme{Madrid}` (other options: Berlin, Copenhagen, Warsaw)
- Modifying colors: Edit `\definecolor` definitions
- Adding your logo: `\logo{\includegraphics[height=1cm]{logo.png}}`
- Adjusting fonts: Add `\usepackage{...}` for different font packages

## Tips for Presentation

- Use the arrow keys to navigate slides
- Press 'F' for fullscreen mode
- Press 'Esc' to exit fullscreen
- Use presenter mode if available in your PDF viewer
