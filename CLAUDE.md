# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build Commands
- Development: `hugo server -D` (serves with drafts)
- Production build: `hugo --gc --minify`
- Preview build: `hugo --gc --minify --buildFuture -b $DEPLOY_PRIME_URL`

## Technical Information
- Hugo Extended v0.146.0 required
- Theme: simple-typo
- Deployment: Netlify
- Syntax highlighting: GitHub style with line numbers

## Code Style
- Markdown content in content/ directory
- Front matter should use TOML format
- Post files should be named with kebab-case
- Optimize for readability and simplicity
- Avoid unnecessary JavaScript
- HTML should be semantic and accessible
- Use relative URLs for internal links
- Reference Hugo templates using the Go templating style