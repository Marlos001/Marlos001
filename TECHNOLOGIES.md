# Technology map

My work spans private business applications, AI copilots, integrations,
infrastructure, public tools, and earlier learning projects. This is a map of
that breadth, not a proficiency ranking or a claim that every technology was
used in the same system. The main profile highlights the most relevant areas.

## Languages and application frameworks

- TypeScript, JavaScript, Python, SQL, Bash, HTML, CSS.
- Frontend: React, Next.js, Angular, React Router, RxJS, Vite, Tailwind CSS.
- Backend: Node.js, Bun, NestJS, Express, Fastify, Hono, Elysia, FastAPI, Uvicorn.
- Monorepos and packages: pnpm workspaces, Turborepo, npm, Bun.

## Frontend state, interaction, and visualization

- TanStack Query, TanStack Table, TanStack Virtual, Zustand, SWR.
- React Hook Form, Zod, shadcn/ui, Radix UI, Base UI, Angular CDK, Spartan UI.
- Tiptap, React Markdown, remark-gfm, DOMPurify.
- Recharts, D3 scales, React Simple Maps, Three.js, React Flow, Dagre.
- Motion/Framer Motion, GSAP, Anime.js, dnd-kit, next-intl.

## Databases and persistence

- PostgreSQL and TimescaleDB, including time-series/audit database setup.
- MongoDB and Mongoose.
- Redis, ioredis, SQLite, better-sqlite3, PGlite, libSQL, DuckDB integrations.
- Google Cloud Firestore and Azure Cosmos DB.
- Drizzle ORM/Kit, Prisma, Sequelize; schema migrations, seeds, and data repair.

## AI engineering and custom harnesses

I build application-specific copilot harnesses largely from scratch around
model APIs, as well as integrations that use existing agent frameworks.

- Custom TypeScript agent execution loops, typed tool schemas, argument/result
  validation, domain-specific tools, and scoped tool-result reuse.
- Persisted sessions, messages, turns, and work plans; streamed events;
  context loading, pruning, compaction, and evidence retention.
- Permission and approval policies, tenant/user scoping, delegated tasks,
  cancellation, durable recovery, and bounded retries.
- Token, cost, iteration, and tool-call budgets; provider-usage accounting;
  evaluation fixtures, regression checks, and execution traces.
- Model API integrations: OpenAI-compatible APIs, OpenRouter, Anthropic,
  and Google GenAI.
- Frameworks and connectivity: Mastra, Vercel AI SDK, MCP, Composio.
- Retrieval, search, and collection: Apify, Exa, Perplexity, Google
  Search/News/Trends, YouTube, and social-data integrations.
- Browser automation: Playwright, Stagehand, Cheerio, HTTP collection pipelines.
- Observability: Laminar, Mastra observability/evaluation integrations,
  structured logging, and source-linked outputs.

## Cloud and infrastructure

- Infrastructure as code: Terraform, AWS CDK.
- Containers and delivery: Docker, Docker Compose, GitHub Actions,
  Railway, Render, Linux.
- Google Cloud: Cloud Run, Cloud Run Jobs, Cloud Functions,
  Compute Engine, Artifact Registry, Cloud Storage, Pub/Sub,
  Firestore, Secret Manager, IAM, Cloud Build.
- AWS: S3, SQS, Lambda, API Gateway, Cognito, DynamoDB,
  EventBridge, Step Functions, ECS, VPC; SDK and infrastructure integrations.
- Azure: Functions, Durable Functions, Blob Storage, Cosmos DB,
  Communication Services email, Monitor/OpenTelemetry, Log Analytics.
- Cloudflare R2 and S3-compatible object storage.

## Authentication, APIs, and asynchronous work

- Clerk, Better Auth, Auth0, Cognito, JWT/JOSE, Svix.
- REST APIs, OpenAPI/Swagger, JSON Schema, Ajv, Zod.
- Server-sent events, WebSockets, webhooks, background workers, scheduled jobs,
  Redis/Bee-Queue, Pub/Sub, and SQS.
- Google APIs, Google Sheets, Airtable, Resend, React Email,
  messaging and WhatsApp integrations, payment/billing APIs,
  Meta Ads integrations, and fiscal/financing systems.

## Documents, spreadsheets, and media

- PDFKit, pdf-lib, pdf-parse, PDF.js, React PDF, PyMuPDF.
- ExcelJS, SheetJS/xlsx, CSV processing, spreadsheet-driven PDF generation.
- docx, Mammoth, DOCX Preview, template-based document workflows.
- FFmpeg/ffprobe, Sharp, canvas, SVG rendering, audio/transcription pipelines,
  and media processing.
- Streamlit interfaces for Python automation tools.

## Testing, quality, and operations

- Bun Test, Vitest, Jest, pytest, pytest-asyncio, Jasmine, Karma.
- Playwright, Testing Library, Supertest, MSW, axe-core accessibility checks.
- TypeScript checks, Biome, ESLint, Prettier, Knip, Husky, lint-staged,
  conventional-commit tooling.
- OpenTelemetry, Sentry, Pino, Laminar, audit logs, and runtime diagnostics.

## Earlier projects and exploration

- Rust, Dart/Flutter, C/C++, Arduino, PHP.
- Linux desktop tooling, Omarchy/Hyprland, native desktop automation,
  browser extensions, and MCP servers.

## Scope

This map was expanded from project manifests, infrastructure configuration,
integration/runtime source, public projects, and my own stated experience.
Private repository identifiers, client information, credentials, internal
addresses, and proprietary source are intentionally not included. Third-party
transitive dependencies and incidental utility packages are not presented as
standalone skills.
