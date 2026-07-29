# Yashasvi Yadav

**Software supply-chain security · Python · Kubernetes**

I work on the systems that decide whether the software you install is genuine. Right now that means [The Update Framework](https://theupdateframework.io/) and the tooling built around it.

India · [LinkedIn](https://www.linkedin.com/in/yashasviyadav458) · [yashasviydv30@gmail.com](mailto:yashasviydv30@gmail.com)

---

## Currently

**OpenSSF 2026 Mentee** at [Repository Service for TUF](https://github.com/repository-service-tuf) · June–August 2026
Mentors: Kairo de Araujo · Camila Vilarinho · Srinjoy Dutta

RSTUF secures software distribution with signed TUF metadata, but that metadata is invisible: signed JSON sitting in storage. Answering *is anything expired, which roles still need signatures, what does the delegation actually look like* means fetching and verifying files by hand.

I'm building the **TUF metadata visualizer** that answers those questions, and landing it in RSTUF's Helm charts as a first-class service. It runs as a real TUF client — establishes a trusted root, walks and verifies the metadata chain, and renders the delegation tree with per-role status. Every request is a read; it changes nothing.

**→ [rstuf-visualizer-design](https://github.com/yashasviyadav30/rstuf-visualizer-design)** — system design, tested FastAPI + `python-tuf` backend, and the deployment path

---

## Shipped upstream

| Project | Contribution | |
|---|---|---|
| **cartography** · CNCF | AWS CloudFormation Stack ingestion — new module, 8 files | [#2478](https://github.com/cartography-cncf/cartography/pull/2478) |
| **krkn** · CNCF | GCP zone-outage rollback for chaos scenarios | [#1200](https://github.com/krkn-chaos/krkn/pull/1200) |
| **cartography** · CNCF | HTTP retry with backoff for transient Tailscale failures | [#2463](https://github.com/cartography-cncf/cartography/pull/2463) |
| **krkn-chaos/website** | Document GCP zone outage in supported rollback scenarios | [#249](https://github.com/krkn-chaos/website/pull/249) |

[**All my pull requests, live →**](https://github.com/pulls?q=is%3Apr+author%3Ayashasviyadav30+sort%3Aupdated-desc) · [**issues →**](https://github.com/issues?q=is%3Aissue+author%3Ayashasviyadav30)

---

## Selected projects

**[rstuf-visualizer-design](https://github.com/yashasviyadav30/rstuf-visualizer-design)** · Python, FastAPI, python-tuf
A read-only window into a TUF repository. Verified metadata chain, interactive delegation tree, status badge on every role. Tested backend, CI, and written architecture, trust-model and deployment docs.

**[Omnibox](https://github.com/yashasviyadav30/Omnibox)** · Python
CLI assistant with voice input. Turns natural language into shell commands.

**[Grid-Pathfinder](https://github.com/yashasviyadav30/Grid-Pathfinder)** · Python
BFS, DFS, Dijkstra, A\*, Greedy and bidirectional BFS, visualised side by side on the same grid.

---

## Stack

Python · TypeScript · React · FastAPI · pytest · Docker · Kubernetes · Helm · Neo4j · AWS · GCP
