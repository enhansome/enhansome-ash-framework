# Awesome Ash Framework with stars

A curated list of awesome Ash Framework extensions, layers and resources.

## Contents

* [Official Resources](#official-resources)
* [Tools](#tools)
* [Extensions](#extensions)
* [AI-related](#ai-related)
* [Demo Projects](#demo-projects)
* [Tutorials](#tutorials)
* [Reviews](#reviews)
* [Contributing](#contributing)
* [License](#license)

## Official Resources

* [Ash Framework Official Website](https://ash-hq.org/) - The official Ash Project website.
* [Ash Framework Official Documentation](https://hexdocs.pm/ash/readme.html) - The official Ash Manual.
* [Ash Framework Github](https://github.com/ash-project/ash) ⭐ 2,483 | 🐛 112 | 🌐 Elixir | 📅 2026-08-28 - The offial Ash Framework Project on Github.

## Tools

### Editors

* [Ash Studio VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ketupia.ash-studio) - Enables quick navigation between Ash sections and visualizing Ash code with mermaid diagrams.

### Online

* [Ash Resource Generator](https://albinkc.github.io/ashgen/) - Web based interface to generate mix ash.gen.resource commands.

## Extensions

### Data Layer

* [ash\_postgres](https://github.com/ash-project/ash_postgres) ⭐ 189 | 🐛 27 | 🌐 Elixir | 📅 2026-08-30 - The PostgreSQL data layer for Ash Framework.
* [ash\_sqlite](https://github.com/ash-project/ash_sqlite) ⭐ 31 | 🐛 3 | 🌐 Elixir | 📅 2026-08-30 - The SQLite data layer for Ash Framework.
* [ash\_csv](https://github.com/ash-project/ash_csv) ⭐ 16 | 🐛 0 | 🌐 Elixir | 📅 2026-04-13 - The CSV data layer for Ash Framework.
* [ash\_neo4j](https://github.com/diffo-dev/ash_neo4j/) ⭐ 16 | 🐛 39 | 🌐 Elixir | 📅 2026-06-27 - Ash Neo4j datalayer.
* [ash\_blog](https://github.com/ash-project/ash_blog) ⚠️ Archived - A Blog data layer backed by markdown files.

### API

* [ash\_graphql](https://github.com/ash-project/ash_graphql) ⭐ 97 | 🐛 20 | 🌐 Elixir | 📅 2026-08-18 - The extension for building GraphQL APIs with Ash.
* [ash\_json\_api](https://github.com/ash-project/ash_json_api) ⭐ 94 | 🐛 18 | 🌐 Elixir | 📅 2026-08-02 - The JSON:API extension for the Ash Framework.

### Observabiliy & Telemetry

* [ash\_paper\_trail](https://github.com/ash-project/ash_paper_trail) ⭐ 53 | 🐛 18 | 🌐 Elixir | 📅 2026-08-30 - Track changes to your Ash resources.
* [opentelemetry\_ash](https://github.com/ash-project/opentelemetry_ash) ⭐ 15 | 🐛 1 | 🌐 Elixir | 📅 2026-08-04 - OpenTelemetry integration for Ash Framework.
* [ash\_appsignal](https://github.com/ash-project/ash_appsignal) ⭐ 10 | 🐛 0 | 🌐 Elixir | 📅 2026-08-03 - . The AppSignal APM integration for Ash Framework

### other

* [ash\_admin](https://github.com/ash-project/ash_admin) ⭐ 180 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-27 - Super-admin UI dashboard for Ash Framework applications, built with Phoenix LiveView.
* [ash\_authentication](https://github.com/team-alembic/ash_authentication) ⭐ 165 | 🐛 6 | 🌐 Elixir | 📅 2026-08-26 - Ash Authentication framework.
* [ash\_phoenix](https://github.com/ash-project/ash_phoenix) ⭐ 163 | 🐛 3 | 🌐 Elixir | 📅 2026-08-28 - Utilities for integrating Ash and Phoenix.
* [ash\_events](https://github.com/ash-project/ash_events) ⭐ 45 | 🐛 7 | 🌐 Elixir | 📅 2026-06-29 - Event-architecture extension for Ash.
* [ash\_oban](https://github.com/ash-project/ash_oban) ⭐ 41 | 🐛 2 | 🌐 Elixir | 📅 2026-08-30 - Extension for integrating Ash resources with Oban.
* [ash\_state\_machine](https://github.com/ash-project/ash_state_machine) ⭐ 36 | 🐛 0 | 🌐 Elixir | 📅 2026-08-29 - State machine functionality for Ash resources.
* [ash\_sync](https://github.com/ash-project/ash_sync) ⭐ 31 | 🐛 0 | 🌐 Elixir | 📅 2025-05-20 - Real-time sync for Postgres-backed Ash & Phoenix applications.
* [ash\_double\_entry](https://github.com/ash-project/ash_double_entry) ⭐ 30 | 🐛 0 | 🌐 Elixir | 📅 2026-08-01 - Double-entry accounting for Ash Framework.
* [ash\_cloak](https://github.com/ash-project/ash_cloak) ⭐ 30 | 🐛 0 | 🌐 Elixir | 📅 2026-08-30 - Ash extension to seamlessly encrypt and decrypt resource attributes.
* [ash\_archival](https://github.com/ash-project/ash_archival) ⭐ 27 | 🐛 0 | 🌐 Elixir | 📅 2026-08-03 - Ash extension to implement archival (soft deletion) for resources.
* [ash\_rate\_limiter](https://github.com/ash-project/ash_rate_limiter) ⭐ 18 | 🐛 0 | 🌐 Elixir | 📅 2026-08-17 - Rate limiting for Ash Framework.
* [ash\_money](https://github.com/ash-project/ash_money) ⭐ 16 | 🐛 0 | 🌐 Elixir | 📅 2026-08-30 - Money handling for Ash Framework.
* [ash\_ops](https://github.com/ash-project/ash_ops) ⭐ 13 | 🐛 0 | 🌐 Elixir | 📅 2026-08-01 - Ash extension which generates mix tasks for actions.
* [ash\_circuit\_breaker](https://github.com/christianalexander/ash_circuit_breaker) ⭐ 10 | 🐛 2 | 🌐 Elixir | 📅 2026-02-05 - Protects applications from cascading failures by adding circuit breaker functionality to actions.

### Phoenix LiveView Components

* [cinder](https://hexdocs.pm/cinder/) - Powerful data table component for Ash Framework resources, in your Phoenix LiveView applications.

## AI Related projects

* [ash\_ai](https://github.com/ash-project/ash_ai) ⭐ 189 | 🐛 13 | 🌐 Elixir | 📅 2026-08-21 - Structured outputs, vectorization and tool calling for your Ash application.

## Demo projects

* [Realworld](https://github.com/team-alembic/realworld) ⭐ 223 | 🐛 0 | 🌐 Elixir | 📅 2026-07-10 - A fullstack Phoenix LiveView application with backend built with Ash Framework.
* [Tunez](https://github.com/sevenseacat/tunez) ⭐ 120 | 🐛 1 | 🌐 Elixir | 📅 2026-01-11 - The starter application for the Ash Framework book.
* [Orca Site](https://github.com/orcasound/orcasite) ⭐ 80 | 🐛 132 | 🌐 TypeScript | 📅 2026-08-16 - Orca Live-listening web app.
* [Fleetms](https://github.com/jmnda-dev/fleetms) ⭐ 30 | 🐛 6 | 🌐 Elixir | 📅 2026-05-08 - An open source Fleet Maintenance and Management software.
* [Tuesday](https://github.com/devcarrots/tuesday) ⭐ 30 | 🐛 1 | 🌐 Elixir | 📅 2025-05-01 - Project management app built with Ash accompanying the book "Domain Modeling with Ash Framework".
* [League of replays](https://github.com/mrdotb/leagueofreplays) ⚠️ Archived - Record & Replay league of legends games.
* [Red](https://github.com/dewetblomerus/red) ⭐ 12 | 🐛 2 | 🌐 Elixir | 📅 2026-08-25 - Practice spelling Red Words.

## Tutorials

* [elixir-phoenix-ash](https://elixir-phoenix-ash.com) - An Elixir, Phoenix and Ash Beginner's Guide.
* [A Gentle Primer to Ash](https://jon.hk/elixir/ash/a-gentle-primer-to-ash) - A Gentle Primer to Ash.
* [Getting Started with Ash Framework in Elixir](https://optimum.ba/blog/getting-started-with-ash-framework-in-elixir) - Getting Started with Ash Framework in Elixir.
* [Part 1 — Ash Framework For Phoenix Developers | Intro](https://medium.com/@lambert.kamaro/ash-framework-for-phoenix-developpers-c29b0a147552) - Part 1 of a large serie of Ash Framework tutorials.
* [Adding full text search](https://blog.1-800-rad-dude.com/posts/2025/08-13-Adding-Postgres-Full-Text-Search-to-an-Ash-Project.html) - Tutorial Adding Postgres Full Text Search to an Ash Project.

## Books

* [Ash Framework, Create Declarative Elixir Web Apps](https://pragprog.com/titles/ldash/ash-framework/) - Book written by Rebecca Le and Zach Daniel.
* [Domain Modeling with Ash Framework](https://shankardevy.gumroad.com/l/domain-modeling-with-ash/) - Book written by Shankar Dhanasekaran.

## Audio & Video

* [Ash Framework on Youtube](https://www.youtube.com/watch?v=vjnPjrCF4rs\&list=PLFiGINXG7oyFh5B_2SiHI9LtdQ_f1k7pz) - Playlist with video's about Ash.
* [The Phoenix Rises From the Ash Framework](https://www.youtube.com/watch?v=5BOr3Bm_gfs) - Two hours coding session exploring Ash Framework by famous NeoVim youtuber TJ de Vries.

## News

* [Ash Weekly News](https://ashweekly.substack.com/) - Weekly news on substack authored by Zach himself.

## Community

* [Ash Forums](https://elixirforum.com/c/ash-framework-forum/) - Ash forums in elixirforum.com.
* [Discord](https://discord.com/invite/w3AXeARR2p) - Ash Discord server.
* [Answerflow](https://www.answeroverflow.com/c/711271361523351632) - Content from the Ash Discord server.

## Reviews

* [My First Impressions of Ash](https://dewetblomerus.com/2023/11/26/first-thoughts-on-ash.html) - My First Impressions of Ash.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
