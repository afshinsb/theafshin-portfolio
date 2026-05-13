# Afshin Saberi - Infrastructure & Systems Operations Portfolio

A static Astro portfolio for presenting hands-on infrastructure, systems, and operational security work in a privacy-safe way.

The site focuses on Linux service operations, Docker workloads, reverse proxy routing, Cloudflare-style exposure patterns, private access workflows, automation, monitoring, and restore-aware infrastructure practice.

## Stack

- Astro
- Tailwind CSS
- TypeScript
- Cloudflare static deployment

## Content

- Homepage with concise infrastructure positioning
- Infrastructure Lab with sanitized operating model examples
- Projects page with representative operational work areas
- Operational Notes covering logging, restore testing, public exposure, Docker boundaries, private access, and automation scope
- Capabilities & Operations page for recruiter-friendly skill review
- Contact page with professional profile links

## Design Goals

- Minimal, readable, and recruiter-friendly
- Practical infrastructure language instead of buzzwords
- No fake metrics, companies, uptime, audits, or certifications
- Sanitized examples only
- Static, lightweight, and easy to deploy

## Privacy And Safety

This project intentionally avoids exposing real infrastructure details, including:

- service URLs
- subdomains
- IP addresses
- email addresses
- phone numbers
- private hostnames
- credentials
- raw logs
- local file paths
- service inventory

Public examples use safe placeholders such as:

- `service.example`
- `private-access`
- `admin-workflow`
- `monitoring-workflow`
- `automation-workflow`
- `Canada-based`

## Local Development

Install dependencies:

```sh
npm install
```

Start the development server:

```sh
npm run dev
```

Build the static site:

```sh
npm run build
```

Preview the production build:

```sh
npm run preview
```

## Deployment

The project builds to static files in `dist/`.

Typical Cloudflare Pages settings:

```text
Build command: npm run build
Output directory: dist
```

Before public indexing, update production URL placeholders in Astro config, `robots.txt`, and `sitemap.xml` to match the final domain.

## Project Structure

```text
src/
  components/
    ArchitectureDiagram.astro
    Footer.astro
    Navbar.astro
    ProjectCard.astro
    SectionHeader.astro
    TechBadge.astro
  layouts/
    Layout.astro
  pages/
    contact.astro
    index.astro
    infrastructure-lab.astro
    projects.astro
    resume.astro
    security-notes.astro
  styles/
    global.css
```

## Runtime

No backend, database, analytics, tracker, or server runtime is required.

## License

License not specified.
