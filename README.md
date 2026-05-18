# Rahil Mehta

M.S. Computer Science @ Oregon State University (graduating July 2026).  
I build testing infrastructure, REST API tooling, and local-first tools.

---

### Research

**[Defects4REST](https://github.com/ANSWER-OSU/Defects4REST)** — ICSE 2026, First Author  
A benchmark of 110 real-world REST API defects across 12 open-source projects (Dolibarr, Mastodon, Podman, Kafka-REST, NetBox, and more). Includes single-command Docker deployment, bug-specific environment initialization, and OpenAPI specs per defect. Used to evaluate four automated REST API testing tools across 600+ hours of HPC test campaigns.

**[Differential Testing for Autonomous Systems](https://ojs.aaai.org/index.php/AAAI-SS/article/view/36877)** — AAAI Fall Symposium 2025, Co-First Author  
Built environment/task generation and feasibility detection for uncovering systemic errors in autonomous systems using reinforcement learning.

---

### Open Source Bug Reports

Found and reported bugs in REST API testing tools while running the Defects4REST evaluation campaigns:

| Tool | Issue | Status |
|------|-------|--------|
| [Schemathesis](https://github.com/schemathesis/schemathesis) | [#3377 — `KeyError: 'operationId'` internal crash during stateful link resolution on OpenAPI 3.1.0 specs](https://github.com/schemathesis/schemathesis/issues/3377) | Fixed by maintainer |
| [AutoRestTest](https://github.com/selab-gatech/autoresttest) | [#34 — `KeyError: 'application/xml'` crash in `mutate_values` on converted specs](https://github.com/selab-gatech/autoresttest/issues/34) | Fixed by maintainer |
| [AutoRestTest](https://github.com/selab-gatech/autoresttest) | [#36 — Graph init hangs indefinitely on large specs (Mastodon, SeaweedFS)](https://github.com/selab-gatech/autoresttest/issues/36) | Acknowledged |
| [AutoRestTest](https://github.com/selab-gatech/autoresttest) | [#31 — Value table generation stuck 1hr+ with no output on Podman spec](https://github.com/selab-gatech/autoresttest/issues/31) | Acknowledged |
| [AutoRestTest](https://github.com/selab-gatech/autoresttest) | [#30 — No support for custom API key headers (e.g. `DOLAPIKEY`)](https://github.com/selab-gatech/autoresttest/issues/30) | Feature added |
| [EvoMaster](https://github.com/WebFuzzing/EvoMaster) | [#1400 — `IllegalArgumentException: invalid start or end` crash during Dolibarr testing](https://github.com/WebFuzzing/EvoMaster/issues/1400) | Reported |

---

### Projects

| Project | What it does | Stack |
|---------|-------------|-------|
| [ScrollTone](https://github.com/rahilmehta-dev/ScrollTone) | Self-hosted EPUB→audiobook converter — 19 voices, multi-character speaker attribution via local LLM | Python · FastAPI · Kokoro TTS · Ollama · Docker |
| [ShowUp](https://github.com/rahilmehta-dev/ShowUp) | iOS habit tracker — geofence-based auto-completion, Live Activity on Dynamic Island, SwiftData persistence | Swift · SwiftUI · CoreLocation · ActivityKit |
| [FocusFeed](https://github.com/rahilmehta-dev/FocusFeed) | YouTube pre-filter using a local MLX vision model — scores videos by mood before you watch them | Python · FastAPI · MLX · SSE · Apple Silicon |
| [mornin-cli](https://github.com/rahilmehta-dev/mornin-cli) | Morning standup generator from git commits via local LLM | Python · Ollama |

---

### Stack

Python · Docker · FastAPI · REST APIs · Swift · SwiftUI · Bash · C#

---

📫 [rahilpiyushmehta@hotmail.com](mailto:rahilpiyushmehta@hotmail.com) · [rahil.online](https://rahil.online) · [LinkedIn](https://linkedin.com/in/Mehta-Rahil)
