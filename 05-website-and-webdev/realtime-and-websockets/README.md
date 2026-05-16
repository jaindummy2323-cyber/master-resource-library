# Real-time & WebSockets

> Open-source real-time communication tools — WebSockets, Server-Sent Events, live collaboration, presence, pub/sub, and multiplayer infrastructure for interactive websites.

---

## WebSocket Libraries & Servers

| Repository | Stars | Description |
|---|---|---|
| [Socket.IO](https://github.com/socketio/socket.io) | 62k+ | Real-time bidirectional communication. Auto-reconnect, rooms, namespaces, binary support. |
| [ws](https://github.com/websockets/ws) | 22k+ | Simple, fast WebSocket implementation for Node.js. Minimal, production-ready, performant. |
| [µWebSockets](https://github.com/uNetworking/uWebSockets.js) | 8k+ | Fastest WebSocket server. C++ core, Node.js bindings, handles millions of connections. |
| [Soketi](https://github.com/soketi/soketi) | 5k+ | Open-source Pusher-compatible WebSocket server. Drop-in replacement, self-hostable. |
| [Centrifugo](https://github.com/centrifugal/centrifugo) | 8k+ | Scalable real-time messaging server. WebSocket, SSE, GRPC, Redis pub/sub, presence. |
| [Ably](https://github.com/ably/ably-js) | 400+ | Real-time infrastructure SDK. Pub/sub, presence, history, push notifications. |
| [Mercure](https://github.com/dunglas/mercure) | 4k+ | Real-time push protocol built on SSE. Native browser support, no WebSocket needed. |

---

## Real-time Collaboration (CRDT/OT)

| Repository | Stars | Description |
|---|---|---|
| [Yjs](https://github.com/yjs/yjs) | 17k+ | CRDT framework for real-time collaboration. Shared editing, offline-first, any data type. |
| [Liveblocks](https://github.com/liveblocks/liveblocks) | 4k+ | Real-time collaboration infrastructure. Presence, storage, comments, notifications. |
| [Hocuspocus](https://github.com/ueberdosis/hocuspocus) | 800+ | Yjs WebSocket server. Authentication, persistence, hooks, scalable. |
| [Automerge](https://github.com/automerge/automerge) | 4k+ | CRDT library for building collaborative apps. JSON-like data, automatic conflict resolution. |
| [ShareDB](https://github.com/share/sharedb) | 6k+ | Real-time database. OT for JSON documents, any database backend, queries. |
| [Collabs](https://github.com/nicedoc/nicedoc.io) | — | Collaborative data structures library. CRDTs, composable, TypeScript-first. |
| [TipTap Collaboration](https://github.com/ueberdosis/tiptap) | 28k+ | Real-time collaborative rich text editing. Yjs-powered, cursor awareness, history. |

---

## Presence & Cursors

| Repository | Stars | Description |
|---|---|---|
| [Liveblocks Presence](https://github.com/liveblocks/liveblocks) | 4k+ | Who's online, cursor positions, selections, typing indicators. React hooks. |
| [PartyKit](https://github.com/partykit/partykit) | 4k+ | Real-time multiplayer infrastructure. Edge computing, rooms, AI agents, Cloudflare Workers. |
| [y-presence](https://github.com/nicedoc/nicedoc.io) | 200+ | Presence awareness for Yjs. Shared cursors, selections, user avatars. |
| [react-cursors](https://github.com/nicedoc/nicedoc.io) | — | Multiplayer cursor component for React. Real-time mouse positions, customizable. |

---

## Pub/Sub & Message Queues

| Repository | Stars | Description |
|---|---|---|
| [Redis Pub/Sub](https://github.com/redis/redis) | 67k+ | In-memory message broker. Pub/sub, streams, real-time messaging backbone. |
| [NATS](https://github.com/nats-io/nats-server) | 16k+ | Cloud-native messaging. Pub/sub, request-reply, JetStream persistence, edge-native. |
| [RabbitMQ](https://github.com/rabbitmq/rabbitmq-server) | 12k+ | Message broker. AMQP, MQTT, STOMP, queues, exchanges, routing, clustering. |
| [BullMQ](https://github.com/taskforcesh/bullmq) | 6k+ | Redis-based queue for Node.js. Delayed jobs, rate limiting, priorities, repeatable. |
| [Kafka.js](https://github.com/tulios/kafkajs) | 4k+ | Apache Kafka client for Node.js. Streaming, consumer groups, exactly-once delivery. |

---

## Server-Sent Events (SSE)

| Repository | Stars | Description |
|---|---|---|
| [EventSource polyfill](https://github.com/nicedoc/nicedoc.io) | 2k+ | Cross-browser SSE support. Reconnection, custom headers, legacy browser support. |
| [Mercure](https://github.com/dunglas/mercure) | 4k+ | SSE hub server. Authorization, topics, auto-discovery, CORS, API Platform integration. |
| [sse.js](https://github.com/nicedoc/nicedoc.io) | 500+ | Lightweight SSE client. Custom headers, POST method, retry logic. |
| [better-sse](https://github.com/nicedoc/nicedoc.io) | 500+ | Server-Sent Events for Node.js. TypeScript, channels, sessions, middleware. |

---

## Live Notifications

| Repository | Stars | Description |
|---|---|---|
| [Novu](https://github.com/novuhq/novu) | 35k+ | Open-source notification infrastructure. In-app, email, SMS, push, chat. React components. |
| [Knock](https://github.com/nicedoc/nicedoc.io) | — | Notification infrastructure API. In-app feed, email, push, Slack, cross-channel. |
| [Ntfy](https://github.com/binwiederhier/ntfy) | 19k+ | Push notifications via HTTP. Subscribe from any device, no app needed, self-hosted. |
| [React Hot Toast](https://github.com/timolins/react-hot-toast) | 10k+ | Lightweight toast notifications. Accessible, customizable, promise-based. |
| [Sonner](https://github.com/emilkowalski/sonner) | 9k+ | Opinionated toast component for React. Beautiful defaults, accessible, stacking. |

---

## Multiplayer & Gaming

| Repository | Stars | Description |
|---|---|---|
| [Colyseus](https://github.com/colyseus/colyseus) | 6k+ | Multiplayer game framework. Room-based, state synchronization, matchmaking, Node.js. |
| [PartyKit](https://github.com/partykit/partykit) | 4k+ | Multiplayer infrastructure. Rooms, state, AI agents, edge-deployed. |
| [Normcore](https://github.com/nicedoc/nicedoc.io) | — | Multiplayer networking for Unity/web. State sync, voice, XR, no server management. |
| [Aper](https://github.com/nicedoc/nicedoc.io) | — | Rust-based multiplayer state machine. WebSocket sync, browser client, deterministic. |

---

## Live Streaming & Video

| Repository | Stars | Description |
|---|---|---|
| [LiveKit](https://github.com/livekit/livekit) | 11k+ | Real-time video/audio/data. WebRTC SFU, recording, streaming, AI agents. |
| [Jitsi Meet](https://github.com/jitsi/jitsi-meet) | 23k+ | Video conferencing platform. WebRTC, self-hosted, recordings, live streaming. |
| [Daily.co (client)](https://github.com/nicedoc/nicedoc.io) | — | Video/audio API. Rooms, recording, streaming, AI transcription, embeddable. |
| [100ms](https://github.com/nicedoc/nicedoc.io) | — | Live video infrastructure. Conferencing, live streaming, recording, interactive features. |
| [MediaSoup](https://github.com/nicedoc/nicedoc.io) | 6k+ | WebRTC SFU for Node.js. Video conferencing, broadcasting, low-latency streaming. |

---

## Why These Are Top-Tier

- **Socket.IO** — 62k+ stars, the standard for real-time web apps
- **Yjs** — Best CRDT library, powers collaborative editing in many products
- **Novu** — 35k+ stars, most complete notification infrastructure
- **LiveKit** — Modern WebRTC, used for video calls, live streaming, AI voice
- **Centrifugo** — Scales to millions of connections, battle-tested
- **PartyKit** — Next-gen multiplayer on the edge, backed by Cloudflare

---

## Premium Website Real-time Stack

| Feature | Tools |
|---|---|
| Live chat | Socket.IO or Centrifugo |
| Collaborative editing | Yjs + Hocuspocus + TipTap |
| Presence/cursors | Liveblocks or PartyKit |
| Notifications | Novu (full stack) + Sonner (toasts) |
| Video calls | LiveKit or Jitsi |
| Message queue | BullMQ + Redis |
| Live updates/feeds | Mercure (SSE) or Soketi (WebSocket) |
