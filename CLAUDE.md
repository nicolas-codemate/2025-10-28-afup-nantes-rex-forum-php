# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Slidev presentation for AFUP Nantes 2025 (REX Forum PHP 2025). Slidev is a presentation framework designed for developers that uses Markdown files to create slides with Vue components, code highlighting, and interactive features.

## Presentation Context

This presentation is a return of experience (REX) talk given at AFUP Nantes in October 2025 about Forum PHP 2025, which took place on October 9-10, 2025 (https://event.afup.org/forum-php-2025/programme/).

**Main Objective**: Inspire the audience to watch the replay videos of the conferences that will be available online.

**Content Approach**: The presentation covers summaries of the conferences attended at Forum PHP 2025. Each conference summary in the `notes/` directory represents a talk that will be featured in this presentation to generate interest and encourage viewers to watch the full videos.

## Common Commands

### Development
- `pnpm install` - Install dependencies
- `pnpm dev` - Start development server (opens at http://localhost:3030)
- `pnpm build` - Build the presentation for production
- `pnpm export` - Export the presentation (to PDF or other formats)

### Package Manager
This project uses **pnpm** (not npm or yarn). Always use `pnpm` for package management.

## Project Structure

### Presentation Content
- `slides.md` - Main presentation file containing all slides in Markdown format with frontmatter configuration
- `pages/` - Additional slide pages that can be imported into main slides (e.g., `pages/imported-slides.md`)
- `notes/` - Conference notes and references (Markdown files with French content about various PHP/development topics)

### Components & Assets
- `components/` - Vue components used in slides (e.g., `Counter.vue`)
- `snippets/` - Code snippets that can be referenced in slides (e.g., `external.ts`)

### Configuration
- Theme: Uses `seriph` theme (configured in `slides.md` frontmatter)
- Build output: `dist/` directory
- Deployment: Configured for both Netlify (`netlify.toml`) and Vercel (`vercel.json`)

## Working with Slides

### Slide Format
Slides are written in Markdown with YAML frontmatter. Each slide is separated by `---`. Key features:
- Frontmatter configuration (theme, layout, transitions, etc.)
- Support for Vue components inline with `<script setup>` blocks
- Animation directives: `v-click`, `v-motion`, `v-mark`
- Code blocks with syntax highlighting and line highlighting
- Mermaid diagrams, PlantUML, LaTeX support

### Importing Slides
External slide pages can be imported using:
```md
---
src: ./pages/imported-slides.md
---
```

### Adding Components
- Place Vue components in `components/` directory
- They are auto-imported and available in slides
- Use standard Vue 3 Composition API with `<script setup>`

### Code Snippets
- Store reusable code in `snippets/`
- Reference them in slides with: `<<< @/snippets/filename.ts#snippet`

## Deployment

The project is configured for deployment on:
- **Netlify**: Uses Node 20, builds with `npm run build`, publishes `dist/`
- **Vercel**: Uses same build command, outputs to `dist/`

Both platforms are configured with SPA routing (all routes redirect to `index.html`).

## Conference Notes

The `notes/` directory contains French-language summaries of each conference attended at Forum PHP 2025. These notes are the source material for the presentation and will be used to create engaging slides.

**Purpose of Notes**: Each Markdown file in `notes/` summarizes a specific talk from Forum PHP 2025. These summaries will be featured in the AFUP Nantes presentation to:
- Give the audience a taste of the content
- Highlight key takeaways and interesting points
- Generate excitement to watch the full replay videos

**Conference Topics Covered**:
- 01: Créer un serveur MCP avec Symfony (MCP servers with Symfony)
- 02: Comment être un bon dev à l'heure de l'IA (Being a good developer in the AI era)
- 03: Overcoming our primitive obsessions
- 04: SQL vs les préjugés (SQL vs prejudices)
- 05: Sous le capot de Composer (Under the hood of Composer)
- 06: FrankenPHP en dehors des sentiers battus (FrankenPHP off the beaten path)
- 07: Perf et injection de dépendance - êtes-vous assez paresseux? (Performance and dependency injection)
- 08: Créer un RAG en PHP - démystifier l'IA (Creating a RAG in PHP - demystifying AI)
- 09: Quatre patterns avancés pour améliorer la résilience d'une application (4 advanced patterns for application resilience)
- 10: Évaluation des IAs - la recette secrète des agents pas trop bête (AI evaluation - the secret recipe for smart agents)
- 11: 180,000 requêtes par seconde (180,000 requests per second)
- 12: 10 ans de Clean Architecture chez OpenClassroom (10 years of Clean Architecture at OpenClassroom)
- 13: Symfony UX Live Component - construire un tableau de bord interactif sans une seule ligne de JS (Build an interactive dashboard without a single line of JS)
- 14: Les bases de la sécurité en développement web (Web development security basics)

**Note**: These files are reference materials and source content - they are not directly built into the presentation but should be transformed into engaging slides in `slides.md`.