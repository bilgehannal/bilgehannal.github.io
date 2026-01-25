# Projects

## Example Files (for Testing)

The markdown files in this directory are **example files** for local development and testing. They demonstrate the format and will be used when running `npm run dev`.

## Production Setup

In production (GitHub Pages), projects will be stored in your **GitHub Pages repository** (the repo where you copy the built output). Place your actual project markdown files there.

## File Format

Each file should follow this format:

```markdown
---json
{
  "title": "Project Name",
  "date": "2025-01-10",
  "tags": ["tag1", "tag2"],
  "description": "Project description",
  "github": "https://github.com/username/repo",
  "demo": "https://demo-url.com"
}
---

Your project markdown content here...
```

## Required Fields

- `title`: The project title
- `date`: Project date in YYYY-MM-DD format

## Optional Fields

- `tags` or `labels`: Array of technology tags
- `description`: Project description (used in card view)
- `github`: GitHub repository URL
- `demo`: Demo/live URL
- `image`: Project image URL
- `links`: Object with `github` and `demo` properties
