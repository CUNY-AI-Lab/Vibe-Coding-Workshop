# Vibe Coding Workshop Presentation

This repository contains a reveal.js presentation for the Vibe Coding Workshop focused on AI-powered development tools.

## Viewing the Presentation

### Option 1: Open Locally
Simply open `index.html` in your web browser:
- Double-click the file, or
- Right-click and select "Open with" your preferred browser

### Option 2: Use a Local Server
For the best experience, serve the presentation using a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Presentation Controls

- **Next slide**: Space, Right Arrow, or N
- **Previous slide**: Left Arrow or P
- **Full screen**: F
- **Overview mode**: ESC or O
- **Speaker notes**: S

## Workshop Content

The presentation covers:
1. Introduction to AI development tools
2. Site Studio ice breaker activity
3. Command line basics
4. Installing Gemini CLI (Windows & macOS)
5. Project tracks (Website, Visualization, Program/Script)
6. Google AI Student Account information
7. GitHub Copilot and GitHub Desktop
8. Claude Code final demo

## Technologies Used

- [Reveal.js](https://revealjs.com/) - HTML presentation framework
- CDN-hosted for easy deployment and zero dependencies

## Customization

To customize the presentation theme, modify the CSS link in `index.html`:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reveal.js@5.0.4/dist/theme/[THEME].css">
```

Available themes: black, white, league, beige, sky, night, serif, simple, solarized, blood, moon

## License

This presentation is for educational purposes for the CUNY AI Lab Vibe Coding Workshop.
