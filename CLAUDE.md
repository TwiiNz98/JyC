# CLAUDE.md - AI Assistant Guide for JyC Repository

## Project Overview

**JyC** is a simple web project containing a basic HTML webpage in Spanish. The project appears to be in its early stages of development.

## Repository Structure

```
JyC/
├── tienda          # Main HTML webpage (Spanish: "store")
└── CLAUDE.md       # This file - AI assistant guide
```

### Key Files

| File | Description |
|------|-------------|
| `tienda` | A standalone HTML file containing a basic Spanish-language webpage with embedded CSS styling |

## Technology Stack

- **Frontend**: Pure HTML5 with embedded CSS
- **Language**: Spanish (es)
- **No build tools or frameworks** - Static HTML only

## Code Conventions

### HTML Standards
- Use HTML5 doctype (`<!DOCTYPE html>`)
- Set language attribute appropriately (`lang="es"` for Spanish content)
- Include viewport meta tag for responsive design
- Use UTF-8 character encoding

### CSS Guidelines
- Embedded styles are acceptable for single-page projects
- Use readable color values (hex format preferred)
- Keep styling simple and maintainable

### File Naming
- Files may use Spanish names (e.g., `tienda` = "store")
- No file extensions are currently used for HTML files

## Development Workflow

### Getting Started
1. Clone the repository
2. Open HTML files directly in a browser (no build step required)

### Making Changes
1. Create a feature branch from main
2. Edit HTML/CSS files directly
3. Test by opening in a browser
4. Commit changes with descriptive messages
5. Push and create a pull request

### Testing
- Manual browser testing (open files directly)
- Check responsive design on multiple viewport sizes
- Verify proper rendering of Spanish characters (accents, ñ, etc.)

## Git Conventions

### Branch Naming
- Feature branches: `claude/<description>-<session-id>` (for AI-assisted development)
- Standard branches: `feature/<description>` or `fix/<description>`

### Commit Messages
- Keep messages concise but descriptive
- Use imperative mood ("Add feature" not "Added feature")
- Messages can be in English or Spanish

## AI Assistant Guidelines

### When Working on This Project

1. **Preserve Language**: Content is in Spanish - maintain Spanish text in user-facing content
2. **Keep It Simple**: This is a minimal project; avoid over-engineering
3. **No Build Tools**: Don't introduce build systems unless explicitly requested
4. **Direct Editing**: Files can be edited directly without compilation

### Common Tasks

- **Adding new pages**: Create new HTML files following the `tienda` template structure
- **Styling updates**: Modify embedded `<style>` tags or consider extracting to external CSS if complexity grows
- **Content updates**: Edit HTML content directly, preserving Spanish language

### Things to Avoid

- Don't add unnecessary dependencies or frameworks
- Don't change the language from Spanish without explicit request
- Don't add complex build processes for this simple static site

## Future Considerations

As the project grows, consider:
- Extracting CSS to separate stylesheet files
- Adding proper file extensions (`.html`)
- Implementing a simple folder structure for assets
- Adding a README.md for general project documentation

---

*Last updated: 2026-02-03*
