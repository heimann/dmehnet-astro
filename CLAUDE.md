# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

- `npm run dev` - Start local dev server at localhost:4321
- `npm run build` - Run type checking and build to `./dist/`
- `just run` - Alias for `npm run dev`

## Architecture

This is a personal website (dmeh.net) built with Astro 4 and Tailwind CSS.

**Layout structure:**
- `src/layouts/BaseLayout.astro` - Main layout with Nav, uses Inter font
- `src/layouts/MarkdownPostLayout.astro` - Layout for markdown blog posts

**Pages:**
- `src/pages/index.astro` - Homepage
- `src/pages/writing.astro` - Blog post listing
- `src/pages/books.astro` - Book list
- `src/pages/posts/` - Markdown blog posts

**Components:**
- `src/components/Nav.astro` - Navigation sidebar
- `src/components/NavLink.astro` - Styled nav links

## Formatting

Uses Prettier with prettier-plugin-astro for .astro files.
