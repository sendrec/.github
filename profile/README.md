## SendRec

The async video platform built for Europe. Record, share, and track video messages with your team.

Open source (AGPLv3), GDPR native, hosted entirely in the EU.

### Features

- **Screen & camera recording** — pause/resume, drawing annotations, webcam overlay, mobile support
- **Automatic transcription** — whisper.cpp, closed captions, full-text search
- **AI summaries & chapters** — via any OpenAI-compatible API (Mistral, OpenAI, Ollama)
- **Sharing** — password protection, email gate, expiry, download controls, custom thumbnails, CTA buttons
- **Viewer analytics** — completion funnel, per-viewer engagement, CTA click-through rates
- **Embeddable player** — lightweight iframe with captions and milestone tracking
- **Custom branding** — logo, colors, footer, custom CSS injection
- **Folders & tags** — organize your library with single-level folders and color-coded tags
- **Webhooks & integrations** — generic webhooks, Slack notifications, Nextcloud, per-user API keys
- **Dark/light mode** — system preference detection with manual toggle
- **Subscription billing** — optional Creem integration for free/Pro tiers
- **Self-hostable** — single Go binary, Docker Compose, PostgreSQL, S3-compatible storage

### Quick Links

- **[Try it free](https://app.sendrec.eu)** — no credit card required
- **[Website](https://sendrec.eu)** — features, pricing, and blog
- **[Self-Hosting Guide](https://github.com/sendrec/sendrec/blob/main/SELF-HOSTING.md)** — run it on your own server
- **[API Docs](https://app.sendrec.eu/api/docs)** — interactive OpenAPI reference
- **[Blog](https://sendrec.eu/blog)** — engineering posts on building an EU-native video platform

### Self-Host

```bash
git clone https://github.com/sendrec/sendrec.git
cd sendrec
cp .env.example .env
docker compose -f docker-compose.dev.yml up --build
```

Open http://localhost:8080, register an account, and start recording.

### Contributing

We welcome contributions. See the [contributing guide](https://github.com/sendrec/sendrec/blob/main/CONTRIBUTING.md) to get started.
