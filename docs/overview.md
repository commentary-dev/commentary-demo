# Enterprise Launch Brief

Commentary helps teams review Markdown specs like living documents while preserving the pull-request workflow engineers already use.

## Current objective

Ship a public demo that lets product, design, and engineering leaders experience document-first review without needing their own repository on day one.

## Success criteria

| Measure | Target |
| --- | --- |
| Demo loads without login | Yes |
| Commenting works after GitHub sign-in | Yes |
| Review shows multiple Markdown files | Yes |
| Commit-specific diff navigation is meaningful | Yes |

## Key messages

1. The rendered document is the primary review surface.
2. Comments stay anchored to semantic blocks instead of raw diff lines.
3. Reviewers can still submit a normal GitHub review when they are ready.

## Early rollout notes

- Start with a public pull request so the homepage path is frictionless.
- Keep branch review secondary to the pull-request story.
- Use resettable fixture content so the demo stays legible after repeated reviews.
