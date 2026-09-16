# Maina Wycliffe

**Founder & Chief Builder at [Garatropic Studios](https://garatropic.com) · Creator of [skein-js](https://github.com/skein-js/skein-js) · Author of [All Things TypeScript](https://www.allthingstypescript.dev) · Google Developer Expert for Angular**

> Your frontend is TypeScript. Your backend is TypeScript. Why should your AI stack be somewhere else?

I build open-source infrastructure and practical software—from reliable TypeScript agent runtimes to safe, generative interfaces.

## What I'm building

### [skein-js](https://github.com/skein-js/skein-js)

The open-source LangGraph Platform alternative for TypeScript. I created Skein because JavaScript and TypeScript developers should not have to leave their ecosystem—or depend entirely on a commercial platform—to put an AI agent into production.

LangGraph.js already gives us a strong foundation for defining agents. Skein builds the open infrastructure around it: the server, persistence, queues, streaming, scheduling, deployment, and operational tools a real product needs. My goal is to help the TypeScript AI ecosystem grow beyond demos by making the production path as capable and natural as the development experience.

- **Agent applications:** persistent threads, token and tool streaming, memory, durable execution, human approval, time travel, and crash recovery.
- **Workflows:** run classifiers, extractors, enrichment jobs, and other non-chat graphs as simple HTTP endpoints—without forcing everything into a conversation model.
- **Channels:** connect agents to WhatsApp, Slack, GitHub, or any webhook, with early acknowledgement, progress signals, durable reply delivery, automatic retries, and replay when something fails.
- **Your infrastructure:** develop in memory, move to PostgreSQL and Redis for production, and run on your own servers with no licence key or per-run bill.

```sh
npm create skein-js@latest my-agent
```

[Read the docs](https://skein-js.github.io/skein-js/) · [Explore workflows](https://skein-js.github.io/skein-js/serving-a-single-graph) · [Build a channel](https://skein-js.github.io/skein-js/channels) · [Explore the source](https://github.com/skein-js/skein-js)

### [Garatropic Studios](https://garatropic.com)

I founded Garatropic to solve real business problems with useful, well-made software—from products and internal tools to automation and carefully applied AI.

We start with the problem rather than a preferred technology, understand how the work actually happens, and leave teams with software they can understand, use, and control.

### [ng-json-render](https://github.com/garatropic/ng-json-render)

The Angular integration for [json-render](https://json-render.dev/), the generative UI framework for turning constrained JSON specifications into native interfaces. Developers define a trusted catalog of components; an agent or server produces a spec; `ng-json-render` maps it to real Angular components—without `eval`, arbitrary generated code, or an iframe.

It brings json-render's catalog, state, actions, and progressive rendering model into the Angular ecosystem with signals, standalone components, zoneless change detection, and components that remain under the application's control.

### [All Things TypeScript](https://www.allthingstypescript.dev)

I write practical explanations of TypeScript and modern web engineering for thousands of developers. The aim is simple: make difficult ideas understandable enough to use in real work.

## What has my attention

Building agents, agentic workflows, and integrations in TypeScript—and designing the interfaces through which people use them—is where my attention is right now.

I am interested in agents that do more than answer a prompt: workflows that classify, extract, and enrich; background agents that monitor changing conditions, respond to schedules or events, and surface what needs attention; and systems that pause for human decisions and recover when infrastructure fails. Just as important are the integrations that make them useful inside existing products, frameworks, business systems, and channels such as WhatsApp, Slack, email, and GitHub.

[A2UI](https://a2ui.org/introduction/what-is-a2ui/) and the wider generative-interface space complete that picture. Chat should not be the final interface for every agent. Agents should be able to stream safe, declarative, context-specific interfaces—forms, dashboards, choices, and workflows—while the host application keeps control of its components, design system, data, and security boundaries.

Skein helps agents and workflows run reliably and connect to the systems around them; generative UI helps them meet people through the right interface for the task.

## Other open-source work

- [npm-packages-lookup](https://github.com/mainawycliffe/npm-packages-lookup) — package documentation and repository links directly inside VS Code.
- [nx-toolkits](https://github.com/mainawycliffe/nx-toolkits) — Nx generators for Firebase Functions, Hosting, and Genkit-powered applications.

## Let's talk

If your team is building—or struggling to ship—AI in TypeScript, or wants to move beyond the chat box into useful, task-specific interfaces, let's have a conversation.

[Website](https://mainawycliffe.dev) · [LinkedIn](https://www.linkedin.com/in/mainawycliffe) · [Bluesky](https://bsky.app/profile/mainawycliffe.dev) · [Email](mailto:wmmaina7@gmail.com)
