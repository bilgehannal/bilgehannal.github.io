# Blog Posts

## Example Files (for Testing)

The markdown files in this directory are **example files** for local development and testing. They demonstrate the format and will be used when running `npm run dev`.

## Production Setup

In production (GitHub Pages), blog posts will be stored in your **GitHub Pages repository** (the repo where you copy the built output). Place your actual blog post markdown files there.

## File Format

Each file should follow this format:

```markdown
---json
{
  "title": "Your Post Title",
  "date": "2025-01-15",
  "tags": ["tag1", "tag2"],
  "excerpt": "Optional excerpt. If not provided, it will be auto-generated from content."
}
---

Your markdown content here...
```

## Required Fields

- `title`: The title of the blog post
- `date`: Publication date in YYYY-MM-DD format

## Optional Fields

- `tags`: Array of tags
- `excerpt`: Custom excerpt (auto-generated if not provided)
- `author`: Author name
- `category`: Post category
