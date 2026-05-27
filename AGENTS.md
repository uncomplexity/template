# AGENTS.md

## Specifications

### GitHub Workflows

- Must be in `.github/workflows` folder.
- `ci.yml` - automated integrations. runs test, create image, pushes image.
- `cd.yml` - automated deployments. pulls image, run container.

### Client

- Must be in `client` folder.
- Must be in `docker-compose.yml` as `client`.
- Uses Tanstack Start, Tanstack Query, Fontsource, Mantine, & Recharts.

### Server

- Must be in `server` folder.
- Must be in `docker-compose.yml` as `server`.
- Uses Node.js, TSConfig Bases, Hono, ORPC, Drizzle, Postgres.js, & Better Auth.

### Caddy

- Must be in `docker-compose.yml` as `caddy`.

## Managed

- We use GitHub for repository, branches, and workflows.
- We use DigitalOcean for DNS, compute, and object storage.
- We use one machine for each deployment environment (staging & production).
- We use one reserved ip address for each deployment environment (staging & production).

## Unmanaged

- PostgreSQL
- Redis
- Caddy
