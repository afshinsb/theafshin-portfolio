# Afshin Saberi Portfolio

Astro + Tailwind static portfolio for:

Afshin Saberi - Infrastructure Lab & Technical Portfolio

Role: Infrastructure / Systems / Security Engineer

The site intentionally uses sanitized examples only. It does not publish email, phone number, exact location, internal hostnames, real service URLs, IP addresses, ports, private paths, logs, credentials, or screenshots with sensitive data.

## Local Development

```sh
npm install
npm run dev
```

The dev server prints its local URL in the terminal when it starts.

## Build

```sh
npm run build
```

The static output is generated in:

```text
dist/
```

Preview the production build locally:

```sh
npm run preview
```

## Cloudflare Pages

Use these settings when creating the Cloudflare Pages project:

```text
Framework preset: Astro
Build command: npm run build
Build output directory: dist
Node version: 22.12.0 or newer
```

No backend, server runtime, database, or environment variables are required for the current static site.
