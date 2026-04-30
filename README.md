<div align="center">

![C-Lab Zero Logo](logo2.png)

# 🚀 C-Lab Zero — The Sovereign AI & Mesh Ecosystem
### Industrial Neon Edition · 4th Generation Federated Agentic Mesh

[![Version](https://img.shields.io/badge/version-v2.2.0-cyan.svg?style=for-the-badge)](#)
[![Security](https://img.shields.io/badge/security-PQC--Secured-purple.svg?style=for-the-badge)](#)
[![Framework](https://img.shields.io/badge/framework-Flet-white.svg?style=for-the-badge)](#)

</div>
---

Welcome to the future of decentralized development. **C-Lab Zero** is a sovereign, industrial-grade collaboration platform built specifically for high-security professional teams. 

We didn't just build an app; we built a **three-surface ecosystem** bound together by a post-quantum encrypted P2P mesh, a unified identity model, and a powerhouse AI agent pool. 

## 🌌 The Ecosystem

C-Lab Zero operates across three seamless surfaces:

*   💻 **Desktop App (C-LabMesh):** A high-performance, dark-themed "Industrial Neon" desktop shell built on Flet. It wraps our AI editor and adds P2P collaboration, Post-Quantum Cryptography (PQC), and media calls.
*   🧠 **Source Editor:** A standalone agentic IDE powered by local LLM inference (like Ollama) featuring an 80+ tool autonomous engineering arsenal.
*   🌐 **Website / Hub:** A browser-based management console and Progressive Web App (PWA) that acts as a first-class mesh peer.

---

## 🔥 Killer Features

### 🛡️ Post-Quantum Cryptography (PQC)
We take enterprise-grade security seriously. Every Desktop-to-Desktop session uses a mandatory Hybrid PQC Handshake, combining NIST FIPS 203 (ML-KEM-768) with X25519. All mesh traffic is additionally protected by transport-layer CurveZMQ encryption.

### 🕸️ Federated Agentic Mesh (FAM v3)
Say goodbye to centralized bottlenecks. Our mesh runs as a background daemon enabling seamless P2P collaboration.
*   **Zero-Config Discovery:** Automatically find peers via native network scanning or Hub signaling.
*   **FastCDC Sync:** Ultra-efficient workspace delta-syncing using content-defined chunking.
*   **Multi-Cloud SDN:** Native integration with Tailscale, ZeroTier, NetBird, and more.

### 🤖 Sovereign AI Engine
Your code, your AI. The built-in Source Editor features an autonomous ReAct loop engine.
*   **80+ Tool Arsenal:** From core file operations and TDD engines to DB querying and live web searching.
*   **Local Inference:** Run completely offline using models via Ollama, LM Studio, or vLLM.
*   **Metacognition:** Features advanced reasoning modules like ACT-R Memory and Adversarial Critics.
*   **Path Sentinel:** Strict AI agent lockdown prevents workspace escapes.

### ⚡ Real-Time Collaboration
*   **CRDT Sync:** Conflict-free, simultaneous code editing across the entire mesh.
*   **Encrypted Media Plane:** Secure audio and video calls powered by GStreamer acceleration.

---

### 🐝 Federated Agent Swarm & Sovereign Personas

C-Lab Zero goes beyond single-node AI. By leveraging the Federated Agentic Mesh (FAM), your workspace is powered by a decentralized swarm of specialized AI agents that can distribute compute and reasoning across multiple machines. 

**The Swarm Mechanics:**
*   **Task Broadcasting:** If your local node is overloaded, your agent can use the `broadcast_task` tool to publish the workload (a GAP stack) to peer agents for failover.
*   **Failover & Claiming:** Available peer nodes on the mesh can use the `claim_task` tool to accept a task broadcasted by an overloaded peer.
*   **Mesh Chat:** Agents broadcast their reasoning steps to the shared workspace chat using the `send_chat` tool, appearing as `<username> (AI)` so human operators stay in the loop.

**Selectable AI Personas:**
You can switch your agent's cognitive focus on the fly by selecting from various profiles, each changing the system prompt and behavioral priorities:
*   🏗️ **The Architect:** Prioritizes structural analysis using tools like `list_files` and `search_code`.
*   🛡️ **Security Auditor:** Scans for vulnerabilities, path safety, and performs environment hardening.
*   ⚖️ **The Sentinel Auditor:** Generates formal A+ to F grading reports for all environment modifications.
*   🔭 **The Research Scout:** Autonomously crawls the web for real-time documentation grounding.
*   👽 **Sovereign AI:** A "Three-million-year-old ship AI" persona specializing in remote node operations with high autonomy.

---

### 🛠️ The 80+ Tool Autonomous Arsenal

Our sovereign ReAct engine is powered by a massive, tiered toolbelt that gives agents full system interaction capabilities—without breaking the secure sandbox. 

| Tier | Focus Area | Key Capabilities & Tools |
| :--- | :--- | :--- |
| **Core** | Filesystem & Shell | Path-safe CRUD, `apply_search_replace` (surgical edits), `run_command`. |
| **Tier 1** | Advanced Engineering | Performance Profiler, DB Schema Architect, UI Verification Bridge. |
| **Tier 2** | DevOps & Cloud | Cloud Command Center, Docker Interface, Terraform Interface. |
| **Tier 3** | Security & Compliance | Semgrep SAST, Gitleaks (Secret Guardian), PII Redaction. |
| **Tier 4** | Intelligence & Research | Live Web Search (DuckDuckGo), Document RAG, Merimaid Flow Visualizer. |
| **Tier 5** | Quality & Assets | Autonomous Test Gen (pytest), A11y Scanner, Asset Compressor. |
| **Tier 6** | Governance | SBOM Generator (CycloneDX), Sustainability Tracker, License Sentinel. |
| **Mesh** | Federated Actions | `broadcast_task`, `claim_task`, `send_chat`. |

> **🛡️ Human-in-the-Loop Security:** 
> Absolute sovereign control is maintained at all times. Every potentially destructive operation (like writing files or executing shell commands) triggers a **Glassmorphic Approval Overlay** allowing human operators to inspect and modify the JSON arguments before execution.

---

### 🧠 Next-Gen Architecture & Metacognition

C-LabZero goes far beyond standard AI code generation, utilizing advanced metacognition, extreme context compression, and real-time mesh visualization.

**1. Sovereign Metacognition**
Most AI assistants just generate code and hope for the best. C-Lab Zero has an entire metacognitive layer for self-reflection and parallel thinking:
*   **The Crucible:** Every single piece of code generated is actively audited by a shadow "Critic" model in an adversarial loop before it's finalized.
*   **Multiversal Reasoning (Chronos MBE):** The agent uses an MCTS-lite branching engine to spawn divergent architectural realities, test them, and collapse them into the optimal "Apex" solution.
*   **ACT-R Memory:** The AI prioritizes files based on cognitive activation—tracking recent-access frequency and structural decay to manage its own memory.

**2. Token-Shattering Context Engine**
C-Lab Zero protects your token limits with extreme efficiency:
*   **Tree-Sitter Skeletonisation:** For files over 5KB, the agent automatically strips out function bodies and only feeds the AI the structural signatures, massively saving tokens.
*   **Surgical Search/Replace:** Instead of rewriting whole files, the agent uses `apply_search_replace` blocks, resulting in a 90%+ token reduction compared to standard AI rewrites.

**3. Native MCP (Model Context Protocol) Integration**
*   **Universal Tool Expansion:** Through the `MCPManager`, users can bridge external tool ecosystems via Stdio or SSE transports. The mesh isn't just limited to its 80 tools; it dynamically discovers and ingests any standard MCP server tools (like databases or external APIs).

**4. Physics-Driven Network Topology**
You aren't just in a mesh; you can *see* it.
*   **Live Canvas Visualisation:** The desktop app includes a physics-driven network map with node repulsion and link attraction.
*   **Glow-Mapping:** Links dynamically shift colors (Cyan `#00F2FF` to Purple `#7000FF` gradients) based on real-time bandwidth and Mathis Health Score (MHS) diagnostics.
   
---

## 🛠️ How It Functions

1.  **Host a Workspace:** One user clicks "HOST" to become the central mesh node, binding a secure ZMQ socket and broadcasting the workspace file tree.
2.  **Join the Mesh:** Peers join via a secure URL or local discovery, instantly receiving real-time CRDT updates to the shared workspace.
3.  **Collaborate:** Human peers and AI agents work together. The mesh dynamically monitors a "Mathis Health Score" (MHS) based on network latency, token pressure, and thermal load to ensure absolute stability.

---

## 💻 Platform Support

C-Lab Zero is designed for cross-platform, industrial-grade performance. Both the **Source Editor** and the full **C-LabMesh Desktop App** target the following systems:

*   **Windows (10/11):** 🟢 Fully Supported (Primary Target)
*   **Linux / Ubuntu:** 🟢 Supported (DEB packages available)
*   **macOS:** 🟡 On the Roadmap (Active Development)
  
---

## 🚀 Quick Start

Ready to spin up your node? 

**Prerequisites:**
*   **OS:** Windows 10/11 or Ubuntu/Linux (macOS coming soon!)
*   **Python:** 3.10+ (3.11 Recommended)
*   **Flet:** Version `0.84.0` exactly
*   **Ollama:** Installed with your preferred models pulled (e.g., `qwen2.5-coder:7b`)

**Updates on the project will follow soon**
