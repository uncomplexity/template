# AGENTS.md

## Specifications

### GitHub Workflows

- Must be in `.github/workflows` folder.
- `ci.yml` - automated integrations. runs test, create image, pushes image.
- `cd.yml` - automated deployments. pulls image, run container.

### Client

- Must be in `client` folder.
- Must be in `docker-compose.yml` as `client`.
- Uses Tanstack Start, Fontsource, Mantine, & Recharts.

### Server

- Must be in `server` folder.
- Must be in `docker-compose.yml` as `server`.
- Uses Node.js, TSConfig Bases, Hono, ORPC, Drizzle, & Postgres.js.

### Caddy

- Must be in `docker-compose.yml` as `caddy`.

## Managed

- We use GitHub for repository, branches, and workflows.
- We use DigitalOcean for DNS, compute, and object storage.

## Unmanaged

- PostgreSQL
- Redis
- Caddy

## Documentations

### Programming Language

- TypeScript
  - https://www.typescriptlang.org/
  - https://www.typescriptlang.org/docs/

### Infrastructure

- OpenTofu
  - https://opentofu.org/
  - https://opentofu.org/docs/
  - https://github.com/opentofu/opentofu
- Terragrunt
  - https://terragrunt.com/
  - https://docs.terragrunt.com/llms.txt
  - https://docs.terragrunt.com/llms-small.txt
  - https://docs.terragrunt.com/llms-full.txt
- Docker
  - https://docs.docker.com/
  - https://docs.docker.com/llms.txt
  - https://docs.docker.com/llms-full.txt
- Ansible
  - https://docs.ansible.com/
  - https://github.com/ansible/ansible
- GitHub Provider
  - https://registry.terraform.io/providers/integrations/github/latest/docs
  - https://search.opentofu.org/provider/opentofu/github/latest
  - https://github.com/integrations/terraform-provider-github
- DigitalOcean Provider
  - https://registry.terraform.io/providers/digitalocean/digitalocean/latest
  - https://search.opentofu.org/provider/opentofu/digitalocean/latest
  - https://github.com/digitalocean/terraform-provider-digitalocean

### Package Managers

- pnpm
  - https://pnpm.io/
  - https://github.com/pnpm/pnpm
- uv
  - https://docs.astral.sh/uv/
  - https://docs.astral.sh/uv/llms.txt
  - https://github.com/astral-sh/uv

### Front-end

- React.js
  - https://react.dev/
  - https://react.dev/llms.txt
- Vite
  - https://vite.dev/
  - https://vite.dev/llms.txt
  - https://vite.dev/llms-full.txt
- Tanstack Start
  - https://tanstack.com/
  - https://tanstack.com/llms.txt
- Fontsource
  - https://fontsource.org/
  - https://fontsource.org/llms.txt
  - https://fontsource.org/llms-full.txt
  - https://fontsource.org/fonts/inter
  - https://fontsource.org/fonts/jetbrains-mono
- Mantine
  - https://mantine.dev/
  - https://mantine.dev/llms.txt
  - https://mantine.dev/llms-full.txt
  - https://github.com/mantinedev/mantine
  - https://github.com/mantinedev/ui.mantine.dev
- Recharts
  - https://recharts.github.io/
  - https://github.com/recharts/recharts

### Back-end

- Node.js
  - https://nodejs.org/
  - https://nodejs.org/docs/latest/api/
  - https://nodejs.org/docs/latest-v26.x/api/all.html
- TSConfig Bases
  - https://github.com/tsconfig/bases
  - https://www.npmjs.com/package/@tsconfig/strictest
  - https://www.npmjs.com/package/@tsconfig/node24
  - https://www.npmjs.com/package/@tsconfig/node-ts
- Hono
  - https://hono.dev/
  - https://hono.dev/llms.txt
  - https://hono.dev/llms-small.txt
  - https://hono.dev/llms-full.txt
- ORPC
  - https://orpc.dev/
  - https://orpc.dev/llms.txt
  - https://orpc.dev/llms-full.txt
- Drizzle ORM
  - https://orm.drizzle.team/
  - https://orm.drizzle.team/llms.txt
  - https://orm.drizzle.team/llms-full.txt
  - https://github.com/drizzle-team/drizzle-orm
  - https://github.com/drizzle-team/drizzle-orm-docs
- Postgres.js
  - https://github.com/porsager/postgres
- Better Auth
  - https://better-auth.com/
  - https://better-auth.com/llms.txt
  - https://github.com/better-auth/better-auth
  - https://github.com/better-auth/awesome

### Databases

- PostgreSQL
  - https://www.postgresql.org/docs/
- Redis
  - https://redis.antirez.com/
  - https://redis.antirez.com/llms.txt
- Typesense
  - https://typesense.org/
  - https://typesense.org/docs/
  - https://github.com/typesense/typesense
  - https://github.com/typesense/typesense-website
  - https://github.com/typesense/typesense-js

### Utilities

- Lodash
  - https://lodash.com/
  - https://github.com/lodash/lodash
  - https://www.npmjs.com/package/lodash-es
- date-fns
  - https://date-fns.org/
  - https://github.com/date-fns/date-fns
  - https://www.npmjs.com/package/date-fns

### Code Linting & Formatting

- Biome
  - https://biomejs.dev/

### Tools

- Mise
  - https://mise.en.dev/
  - https://github.com/jdx/mise