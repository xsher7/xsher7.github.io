# Blog maintenance

This repository is xsher's Astro + Fuwari blog. Keep navigation and UI messages in English.

## Article format reference

The original template examples are backed up locally in `local-reference/fuwari-examples-2026-11-28/`. Read its `README.md` and the unchanged files under `posts/` when learning article syntax, frontmatter, code blocks, admonitions, images, or embedded videos. This directory is intentionally ignored by Git and absent from the deployed website.

Write new posts in `src/content/posts/`, using `pnpm new-post <slug>` where helpful. The schema is in `src/content/config.ts`. Use a single `category` string and an array of `tags`; the configured categories are Projects, Notes, and Updates. Do not republish the template examples unless explicitly requested.

Run `pnpm check` and `pnpm build` when changing content or behavior; the build also regenerates Pagefind search indexes.
