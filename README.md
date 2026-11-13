# Ansh
**Software Engineer** â€” Real-Time Communications, Network Protocols & Distributed Systems

---

I build high-performance web systems with a focus on real-time peer-to-peer protocols, custom proxy runtimes, and low-latency client-server architectures. My work centers on eliminating network overhead, handling media streams at scale, and architecting resilient full-stack applications.

---

### Primary Engineering Domains

#### 1. Real-Time Communications & Media Streaming
- **WebRTC Mesh Architecture**: Native `RTCPeerConnection` signaling, dynamic ICE candidate negotiation, and dual STUN/TURN traversal failover for peer-to-peer audio and video transmission.
- **WebSocket Protocols**: Low-latency bidirectional event dispatchers and connection management without reconnection thrash.
- **Audio & Video Processing**: Browser-level `Web Audio API` pipeline engineering (`AnalyserNode`, `AudioContext`) for active speaker detection, mic test sampling buffers, and hardware track control.
- **Stream Relaying**: Custom HLS / M3U8 video stream scrapers, edge proxies on Cloudflare Workers, and CORS mitigation servers.

#### 2. Backend & System Architecture
- **Runtimes & Frameworks**: Node.js, Next.js (App Router / Turbopack), Hono.js.
- **Data Engineering**: Schema modeling, connection management, and queries with Prisma ORM, PostgreSQL, and SQLite.
- **Security & Session Management**: Stateless JWT auth pipelines, bcrypt salt hashing, and scoped role-based access control.

---

### Selected Open Source Work

#### [Arise â€” Real-Time Voice, Video & Community Engine](https://github.com/ansh44233/arise)
*Next.js 16 â€¢ React 19 â€¢ TypeScript â€¢ WebRTC â€¢ Socket.io â€¢ Prisma*
- Engineered a full-mesh WebRTC voice channel stage supporting simultaneous multi-peer audio and 1080p 60fps desktop screen sharing.
- Decoupled signaling listeners from dynamic React render lifecycles (`createPeerConnectionRef` pattern) to guarantee 100% persistent voice calls during client-side route transitions.
- Designed real-time active speaker rings via local frequency analysis, eliminating server audio telemetry overhead.

#### [Media & M3U8 Stream Proxy Engines](https://github.com/ansh44233)
*Cloudflare Workers â€¢ Node.js â€¢ HLS*
- Deployed edge-based proxies resolving cross-origin stream restrictions for live video feeds and HLS playlists.
- Implemented high-throughput stream wrappers for media aggregation and playback pipelines.

---

### Technical Proficiency

- **Languages**: TypeScript, JavaScript, SQL, Rust, HTML/CSS
- **Frameworks & Libraries**: React, Next.js, Socket.io, Tailwind CSS, Framer Motion
- **Protocols & Standards**: WebRTC, WebSockets, HTTP/2, HLS / M3U8, REST
- **Databases & Tools**: PostgreSQL, SQLite, Prisma ORM, Git, Linux / Bash, Docker

---

<p align="left">
  <a href="https://github.com/ansh44233/arise">Explore Arise</a> &nbsp;â€¢&nbsp;
  <a href="https://github.com/ansh44233?tab=repositories">All Repositories</a>
</p>
