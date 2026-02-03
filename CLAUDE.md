# CLAUDE.md - AI Assistant Guide

## Project Overview

**JyC** is a static HTML web page project for a simple shop/store website. The project uses minimal dependencies and follows a straightforward single-file structure.

- **Language:** Spanish (ES)
- **Type:** Static website
- **Status:** Development/Template

## Technology Stack

- **HTML5** - Semantic markup
- **CSS** - Inline styles (within `<style>` tags)
- **No JavaScript frameworks**
- **No build tools or bundlers**
- **No package managers**

## Project Structure

```
JyC/
├── CLAUDE.md       # This file - AI assistant guide
└── tienda          # Main HTML file (shop/store page)
```

### Key Files

| File | Description |
|------|-------------|
| `tienda` | Main HTML page (note: no `.html` extension) |

## Development Workflow

### Running Locally

Since this is a static HTML file, simply open it in a browser:

```bash
# Using a browser directly
open tienda
# or
xdg-open tienda

# Or serve with Python
python3 -m http.server 8000
# Then visit http://localhost:8000/tienda
```

### Making Changes

1. Edit the `tienda` file directly
2. Refresh the browser to see changes
3. No build step required

### Deployment

Copy the `tienda` file to any web server or static hosting service.

## Code Conventions

### Naming

- **Files:** Spanish names (e.g., `tienda` = "shop/store")
- **No file extensions** on HTML files (unconventional but intentional)

### HTML Structure

- Use semantic HTML5 elements
- Include proper meta tags for charset (UTF-8) and viewport
- Keep styles inline within `<style>` tags

### Styling

- Use inline CSS in the `<head>` section
- Font: Arial, sans-serif (fallback)
- Centered text layout
- Responsive viewport meta tag included

### Language

- All user-facing content in **Spanish**
- Code comments (if any) may be in Spanish or English

## Git Workflow

### Branch Naming

- Feature branches: `claude/claude-md-*` for AI-assisted development
- Keep branch names descriptive

### Commit Messages

- Use descriptive commit messages
- Format: Short title (imperative mood)
- Optional: Extended description after blank line

### Current Branch Structure

- Development occurs on feature branches
- Push changes with: `git push -u origin <branch-name>`

## Testing

No automated testing framework is currently configured. For this static site:

- **Manual testing:** Open in browser and verify visual appearance
- **Cross-browser:** Test in Chrome, Firefox, Safari, Edge
- **Mobile:** Use browser dev tools to test responsive design

## Important Notes for AI Assistants

1. **File extension:** The main HTML file `tienda` intentionally has no `.html` extension
2. **Language:** Maintain Spanish for all user-facing content
3. **Simplicity:** Keep the project minimal - no unnecessary dependencies
4. **Inline styles:** CSS should remain in the `<style>` tag unless project scope expands
5. **No build process:** Changes are immediately effective without compilation

## Future Considerations

When expanding this project, consider:

- Adding `.html` extension for better compatibility
- Separating CSS into external stylesheet
- Adding more pages (about, contact, products, etc.)
- Implementing JavaScript for interactivity
- Adding a `README.md` for general project documentation

## Quick Reference

| Task | Command |
|------|---------|
| View locally | `open tienda` or `python3 -m http.server` |
| Check git status | `git status` |
| Commit changes | `git add . && git commit -m "message"` |
| Push to remote | `git push -u origin <branch>` |
