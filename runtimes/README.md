# JavaScript Runtimes Documentation

This directory contains documentation for JavaScript runtimes supported by Zerops.

## Created Documentation

### Node.js (`nodejs/`)
Complete documentation with 5 pages:
1. **overview.mdx** - Introduction to Node.js on Zerops
2. **quickstart.mdx** - Quick deployment guide
3. **build-pipeline.mdx** - Complete zerops.yaml configuration reference
4. **deployment.mdx** - Deployment process and zero-downtime updates
5. **scaling.mdx** - Auto-scaling configuration and optimization

### Deno (`deno/`)
Essential documentation with 2 pages:
1. **overview.mdx** - Introduction to Deno on Zerops
2. **quickstart.mdx** - Quick deployment guide

### Bun (`bun/`)
Essential documentation with 2 pages:
1. **overview.mdx** - Introduction to Bun on Zerops
2. **quickstart.mdx** - Quick deployment guide

## Content Highlights

All documentation includes:
- Real examples from the source repositories
- Actual zerops.yaml configurations
- Database connection examples (PostgreSQL)
- Environment variable setup
- Step-by-step deployment procedures
- Code examples in JavaScript/TypeScript
- Links to GitHub recipes

### Node.js Specific Features
- Complete build pipeline reference with all options
- Deployment process with readiness checks
- Comprehensive scaling guide (vertical & horizontal)
- Multiple package manager examples (npm, yarn, pnpm)
- Health check configurations
- Troubleshooting sections

### Deno Specific Features
- Permission flags (--allow-net, --allow-env, etc.)
- Native TypeScript support
- Deno-specific imports from deno.land

### Bun Specific Features
- Fast package manager usage
- Native bundler examples
- TypeScript without compilation
- Node.js compatibility notes

## Component Usage

The documentation uses Mintlify components:
- `<Steps>` and `<Step>` for procedures
- `<Tabs>` and `<Tab>` for code alternatives
- `<Card>` and `<CardGroup>` for navigation
- `<Accordion>` and `<AccordionGroup>` for expandable content
- `<CodeGroup>` for multiple code examples
- `<Info>`, `<Warning>`, `<Note>` for callouts

## Next Steps

These pages are ready to be added to your navigation in `docs.json`.
