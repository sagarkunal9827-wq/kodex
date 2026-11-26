[![Kodex.sbs Open Source Codebase](./public/social_preview_index.jpg)](#)

> Welcome to the **Kodex.sbs** open-source codebase! This repo contains the core components for building **AI-powered software development tools** that run in the browser, powered by the **WebContainer API**.

### Why Build with Kodex.sbs + WebContainer API

By building with the Kodex.sbs codebase and the WebContainer API, you can create browser-based applications that let users **prompt, run, edit, and deploy** full-stack web apps directly in the browser, without the need for virtual machines. With WebContainer API, you can build apps that give AI direct access and full control over a **Node.js server**, **filesystem**, **package manager**, and **dev terminal** inside your user's browser tab. This powerful combination allows you to create a new class of development tools that support all major JavaScript libraries and Node packages right out of the box, all without remote environments or local installs.

# Get Started Building with Kodex.sbs

Kodex.sbs combines the capabilities of AI with sandboxed development environments to create a collaborative experience where code can be developed by the assistant and the programmer together. Kodex.sbs combines [WebContainer API](https://webcontainers.io/api) with [Claude Sonnet 3.5](https://www.anthropic.com/news/claude-3-5-sonnet) using [Remix](https://remix.run/) and the [AI SDK](https://sdk.vercel.ai/).

### WebContainer API

Kodex.sbs uses [WebContainers](https://webcontainers.io/) to run generated code in the browser. WebContainers provide Kodex.sbs with a full-stack sandbox environment using [WebContainer API](https://webcontainers.io/api). WebContainers run full-stack applications directly in the browser without the cost and security concerns of cloud-hosted AI agents. WebContainers are interactive and editable, and enable Kodex.sbs's AI to run code and understand any changes from the user.

The [WebContainer API](https://webcontainers.io) is free for personal and open source usage. If you're building an application for commercial usage, you can learn more about [WebContainer API commercial usage pricing here](https://webcontainers.io).

### Remix App

Kodex.sbs is built with [Remix](https://remix.run/) and
deployed using [CloudFlare Pages](https://pages.cloudflare.com/) and
[CloudFlare Workers](https://workers.cloudflare.com/).

### AI SDK Integration

Kodex.sbs uses the [AI SDK](https://github.com/vercel/ai) to integrate with AI
models. At this time, Kodex.sbs supports using Anthropic's Claude Sonnet 3.5.
You can get an API key from the [Anthropic API Console](https://console.anthropic.com/) to use with Kodex.sbs.
The integration lives in `app/lib/.server/llm`.

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v20.15.1)
- pnpm (v9.4.0)

## Setup

1. Clone your copy of the repository (if you haven't already):

```bash
git clone <your-repository-url>
pnpm install
ANTHROPIC_API_KEY=XXX
VITE_LOG_LEVEL=debug
pnpm run dev
pnpm test
pnpm run deploy
