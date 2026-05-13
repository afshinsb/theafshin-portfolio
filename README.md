# Afshin Saberi — Infrastructure Lab & Technical Portfolio

A static technical portfolio showcasing infrastructure, systems, automation, and security-focused operations using sanitized public examples.

## Tech Stack

- Astro
- Tailwind CSS
- TypeScript
- Cloudflare Pages

## Key Features

- Responsive design
- Theme switcher
- Sanitized infrastructure architecture
- Project case studies
- Security notes
- Resume page
- Privacy-conscious contact page

## Privacy And Security

This project intentionally avoids exposing real service URLs, subdomains, IP addresses, email addresses, phone numbers, internal hostnames, credentials, logs, or private operational details.

Public examples use sanitized values such as:

- `service.example`
- `admin.internal`
- `automation.internal`
- `monitoring.internal`
- `private`
- `minimized`
- `Canada-based`

## Local Development

Install dependencies:

```sh
npm install
```

Start the local development server:

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

This site is static and Cloudflare Pages friendly.

Cloudflare Pages settings:

```text
Build command: npm run build
Output directory: dist
```

No backend, analytics, database, or server runtime is required.

## Project Structure

```text
src/
├── components/
│   ├── ArchitectureDiagram.astro
│   ├── Footer.astro
│   ├── Navbar.astro
│   ├── ProjectCard.astro
│   ├── SectionHeader.astro
│   └── TechBadge.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   ├── contact.astro
│   ├── index.astro
│   ├── infrastructure-lab.astro
│   ├── projects.astro
│   ├── resume.astro
│   └── security-notes.astro
└── styles/
    └── global.css
```

## License

License not specified.
