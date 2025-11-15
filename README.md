# Co-Developing with Generative AI

This repository contains a reveal.js presentation introducing command line agents for AI-powered development.

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
1. **Today's Tools**: Site Studio, Terminal/PowerShell, Gemini CLI
2. **Before We Start**: Setup instructions for lab and personal computers
3. **Ice Breaker**: Site Studio demo with Claude Sonnet 4.5
4. **Command Line Basics**: Terminal fundamentals
5. **Installing Gemini CLI**: Windows (PowerShell) and macOS (Terminal) installation
6. **Login Setup**: Authenticating Gemini CLI with Google account
7. **Project Tracks**: Website, Visualization, or Program/Script options
8. **Start with a README**: Best practices for agent collaboration
9. **Hands-On Activity**: 15-20 minute building session
10. **Resources**: Links to Claude Code, Google AI for Students, GitHub Copilot, and GitHub Desktop

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
