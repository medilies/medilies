# Hi, I'm Ilies 👋

Backend & AI engineer from Algeria. Since 2022 I've been building [DiData](https://swissdidata.com), a Swiss life-science platform (LIMS, EDC, biobanking), remotely. Today I lead the backend of its AI assistant.

I work mostly in **PHP/Laravel**, and lately in **Go** for my own tools. I'd rather go deep on software architecture and core technologies than chase frameworks. I learned my craft before LLMs were a thing; now I build AI agents.

### 🧠 What I'm building

**DiBrain**, DiData's AI assistant. I lead its backend architecture.

- **Multi-agent.** A main agent delegates to 9 specialized agents that write plugins, event handlers, validation rules, API routes, PDF reports and email templates, or plan a whole instance setup.
- **Safe writes.** Agents change data only through the app's permission-checked API, with a manual approval mode, change previews and audit logs.
- **Long runs.** Agent runs are queued jobs on their own worker pool, streamed live to the UI over WebSockets.
- **Self-checking.** Agents verify their own work: layout tools for forms and workflow boards, and headless-Chrome tests of the plugins they generate.
- **Under the hood.** The Laravel AI SDK, RAG over the product docs and OpenAPI spec (Qdrant), long-term memory, and Anthropic, OpenAI, Gemini or self-hosted Ollama models.

### 🔧 Upstream

When my work hits a bug in a library, I fix it there.

- **[Laravel AI SDK](https://github.com/laravel/ai):** [6 merged PRs](https://github.com/laravel/ai/pulls?q=is%3Apr+author%3Amedilies+is%3Amerged) on sub-agents, streaming, broadcast jobs and Ollama embeddings, [more in review](https://github.com/laravel/ai/pulls?q=is%3Apr+author%3Amedilies+is%3Aopen).
- **[Laravel](https://github.com/laravel/framework/pull/50454):** the `list` validation rule, shipped in Laravel 11.
- **[Laravel Pulse](https://github.com/laravel/pulse/pull/196):** a small fix.

### 📦 Open source

| Project | What it does |
| --- | --- |
| [weaver](https://github.com/medilies/weaver) | Opens a project's tmux session (windows, panes, commands) from one YAML file, with a live project browser and a visual config editor. Go. Featured in [Charm in the Wild](https://github.com/charm-and-friends/charm-in-the-wild). |
| [nerve](https://github.com/medilies/nerve) | Carries one person's agent skills, settings and instructions to every Claude Code config and to claude.ai. Go. Mine live in [brain](https://github.com/medilies/brain). |
| [xssless](https://github.com/medilies/xssless) | Cleans rich text from XSS threats, following OWASP recommendations. Featured on Laravel News. |
| [RowBloom](https://github.com/row-bloom/row-bloom) | Renders tabular data into templates and generates PDFs, with pluggable data loaders, template interpolators and PDF renderers. |
| [rm-q](https://github.com/medilies/rm-q) | Queues file deletions inside a database transaction, so they roll back with it. Laravel. |

Older: [ctrl-p](https://github.com/medilies/ctrl-p) (HTML to PDF through the browser), localization libraries ([php-json-tongue](https://github.com/elaborate-code/php-json-tongue), [laravel-json-tongue](https://github.com/elaborate-code/laravel-json-tongue), [jigsaw-localization](https://github.com/elaborate-code/jigsaw-localization)), Laravel packages for the Algerian market ([education system](https://github.com/al-jazair/laravel-algerian-education-system), [provinces](https://github.com/al-jazair/laravel-algerian-provinces)), [glpi-docker](https://github.com/medilies/glpi-docker), [Eazy IP](https://eazyip.github.io) (network calculations PWA), [php-pong](https://github.com/medilies/php-pong) (Pong in pure OpenGL, from PHP), and the IoT backend I built as CTO of a startup ([safitech-dz](https://github.com/safitech-dz)).

### 🛠️ Tech

[![Skills](https://skillicons.dev/icons?i=php,laravel,go,mysql,docker,linux,bash,js,vue)](https://skillicons.dev)

Also: SQL Server, Qdrant, MCP, WebSockets (Laravel Reverb), Pest, PHPStan, Claude Code.

### 💬 Elsewhere

I answer Laravel and PHP questions on [Stack Overflow](https://stackoverflow.com/users/17873304) (2.3k reputation) and sometimes write on [dev.to](https://dev.to/medilies).

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:medilies.contact@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/medilies)
[![Stack Overflow](https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/17873304)
[![dev.to](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/medilies)
[![Packagist](https://img.shields.io/badge/Packagist-F28D1A?style=for-the-badge&logo=packagist&logoColor=white)](https://packagist.org/users/medilies/packages)
