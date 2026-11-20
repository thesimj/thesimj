# Nick Bubelich

![Agentic product engineer: FlyETA and TankOver](banner.jpg)

**Agentic product engineer, Vienna.** For the last 8 months, I have built real products with AI coding agents, running several agents at once on production code. FlyETA went from first commit to both app stores in 11 weeks.

### How I work

My setup came out of continuous learning, and it got simpler along the way: **Specification -> Development -> Verification**.

- **Specification:** the rules and feature specs that every agent reads before it writes any code.
- **Development:** several agents at once on production code.
- **Verification:** automated gates with tests, coverage floors and checks. Every change passes them before it ships. Whatever fails goes back into the spec, so the next run starts from more.

The harness behind it is my own: skills, rules, tools and quality gates. The agents and models inside it change as better ones come out. Two of my MCP servers are open source, listed below.

18+ years in software and SysOps/DevOps. I have led and hired engineering teams, and I work best inside one. MSc (Magister) in Computer Science.

*Every few months, the agents can do more. I bring that into the team and ship it.*

### Products

**[FlyETA](https://flyeta.app)** - follow your flight from a window seat, offline. A native iPhone app (Swift, SwiftUI, Metal) and a native Android app (Kotlin, Jetpack Compose, Vulkan) over one Rust engine, with a 3D globe of the whole planet that fits in 161 MB inside the app. First commit in August 2026, on the App Store and Google Play on 31 October. Free, with no ads and no account.

**[TankOver](https://tankover.com)** - a voxel toy tank game on a giant desk. A 16-level campaign, online team versus, free-for-all and co-op for up to 32 players. A Rust engine compiled to WebAssembly, a three.js and TypeScript view. In the browser, on the App Store, the Mac App Store and Google Play.

### Open source

- **[rust-openrouter-mcp](https://github.com/thesimj/rust-openrouter-mcp)** - MCP server and CLI for OpenRouter in a single Rust binary. Discover models and generate images, video and speech from Claude. On crates.io.
- **[rust-hetzner-mcp](https://github.com/thesimj/rust-hetzner-mcp)** - a Rust MCP server that manages Hetzner Cloud servers, networks, volumes and firewalls.
- **[envyaml](https://github.com/thesimj/envyaml)** and **[tomlev](https://github.com/thesimj/tomlev)** - Python configuration from YAML and TOML files with environment variables.
- **[ste-eli5](https://github.com/thesimj/ste-eli5)** - a writing style for agents: Simplified Technical English sentences, answer first.

### Also building

**AE Lang / SwarmGentic** - a deterministic DSL, compiler and runtime for multi-agent LLM workflows. Tokenizer, static validator, linter, JSON compiler, and a dependency-aware parallel runner with retries, journaled runs, and per-run evaluation. Reference implementation in TypeScript, second in Python.

**Knowledge Engine** - RAG pipeline over a large Obsidian knowledge base with Qdrant vector search and an agentic retrieval loop built on the Anthropic SDK.

### Before that

I started coding at 14.

- Co-built **raicoon's** Autonomous Operations Center for renewable energy. ML anomaly detection across 100+ solar plants and thousands of daily events. Later owned the architecture and hired the engineering team.
- Technical lead on a physical-security platform suite: 180+ sites, 2,000+ cameras, 100 GB+ of video and telemetry a day on a private multi-node S3 cluster. Real-time video analytics and IoT pipelines.
- Kaggle: top 11% on iMaterialist Furniture (FGVC5), 97.72% ROC on TalkingData fraud detection.

### Stack

```
languages  TypeScript · Python · Rust · Swift · Kotlin
agents     agentic coding workflows · multi-agent orchestration · MCP · RAG
           Anthropic SDK · OpenRouter · embeddings / vector search · LLM evaluation
mobile     SwiftUI · Jetpack Compose · Metal · Vulkan · Capacitor
web        three.js / WebGL · WebAssembly · Astro · Next.js · Svelte · Tailwind
backend    axum · FastAPI · gRPC · WebSockets · Tauri · Electron · PyO3
data       PostgreSQL · SQLite · Qdrant · ClickHouse · Redis · S3
infra      Docker · Kubernetes · Ansible · self-hosted GitLab CI · Hetzner · AWS · Sentry
```

### Elsewhere

[flyeta.app](https://flyeta.app) · [tankover.com](https://tankover.com) · [x.com/nbpatron](https://x.com/nbpatron) · [linkedin.com/in/mykola-bubelich](https://www.linkedin.com/in/mykola-bubelich/) · [bubelich.com](https://bubelich.com)
