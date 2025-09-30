# Low Diatribe Email Announcements

Public repository containing email announcement content for automated scheduling.

## Structure

- Each email announcement is a markdown file with frontmatter
- Filename format: `YYYY-MM-DD-slug.md`
- Frontmatter includes scheduling metadata

## Usage

This repository is consumed by the Low Diatribe email scheduler Lambda function to automatically send reflection announcements to subscribers.

## Example Format

```markdown
---
type: email
reflection: reflection-slug
date: 2025-09-30
subject: Reflection Title
scheduled_send: 2025-09-30T15:00:00Z
---

Email content here...
```