# SaaS-Pretty-Projects · Org-Wide Knowledge Graph

**9,617 nodes · 12,581 links · 745 communities · 22 repos**

This repo hosts a merged knowledge graph spanning the entire [SaaS-Pretty-Projects](https://github.com/SaaS-Pretty-Projects) org — one graph to query all your products.

---

## 📊 Org Summary

| Rank | Repo | LOC | Concepts | Graph |
|------|------|-----|----------|-------|
| 1 | [luxuryui](https://github.com/SaaS-Pretty-Projects/luxuryui) | 116,842 | 3,602 | 🔵 |
| 2 | [tutivex](https://github.com/SaaS-Pretty-Projects/tutivex) | 92,606 | 870 | 🔵 |
| 3 | [teachenza](https://github.com/SaaS-Pretty-Projects/teachenza) | 82,406 | 870 | 🔵 |
| 4 | [cloudbase](https://github.com/SaaS-Pretty-Projects/cloudbase) | 49,340 | 664 | 🔵 |
| 5 | [eurocookflow](https://github.com/SaaS-Pretty-Projects/eurocookflow) | 48,718 | 659 | 🔵 |
| 6 | [Portlixa](https://github.com/SaaS-Pretty-Projects/Portlixa) | 41,750 | 655 | 🔵 |
| 7 | [pathenza.com](https://github.com/SaaS-Pretty-Projects/pathenza.com) | 18,821 | 184 | 🔵 |
| 8 | [gameweara.com](https://github.com/SaaS-Pretty-Projects/gameweara.com) | 16,376 | 243 | 🔵 |
| 9 | [cvantra](https://github.com/SaaS-Pretty-Projects/cvantra) | 15,779 | 198 | 🔵 |
| 10 | [lensiqa](https://github.com/SaaS-Pretty-Projects/lensiqa) | 15,739 | — | 🔵 |
| 11 | [Adaptenza](https://github.com/SaaS-Pretty-Projects/Adaptenza) | 13,849 | 158 | 🔵 |
| 12 | [kitavex](https://github.com/SaaS-Pretty-Projects/kitavex) | 13,604 | 113 | 🔵 |
| 13 | [worknira](https://github.com/SaaS-Pretty-Projects/worknira) | 13,530 | 188 | 🔵 |
| 14 | [minivexa](https://github.com/SaaS-Pretty-Projects/minivexa) | 13,166 | 143 | 🔵 |
| 15 | [imavora](https://github.com/SaaS-Pretty-Projects/imavora) | 12,205 | 151 | 🔵 |
| 16 | [skillnira](https://github.com/SaaS-Pretty-Projects/skillnira) | 12,186 | 119 | 🔵 |
| 17 | [mockenza](https://github.com/SaaS-Pretty-Projects/mockenza) | 12,137 | 124 | 🔵 |
| 18 | [lootexo.com](https://github.com/SaaS-Pretty-Projects/lootexo.com) | 9,031 | 327 | 🔵 |
| 19 | [cs2skin.market](https://github.com/SaaS-Pretty-Projects/cs2skin.market) | 7,999 | 189 | 🔵 |
| 20 | [Terrastone](https://github.com/SaaS-Pretty-Projects/Terrastone) | 7,908 | 544 | 🔵 |
| 21 | [shardoxa.com](https://github.com/SaaS-Pretty-Projects/shardoxa.com) | 7,098 | 142 | 🔵 |
| 22 | [hostevra.com](https://github.com/SaaS-Pretty-Projects/hostevra.com) | 5,693 | 132 | 🔵 |
| 23 | [pathenza](https://github.com/SaaS-Pretty-Projects/pathenza) | 5,393 | 45 | 🔵 |
| 24 | [webqora](https://github.com/SaaS-Pretty-Projects/webqora) | 98,184 | 167 | 🔵 |

> **Total: 730,360 LOC** across 25 repositories

---

## 🗺️ Graph Files

| File | Description |
|------|-------------|
| `graphify-out/graph.json` | Full merged graph (9.6K nodes, 12.5K links) |
| `graphify-out/graph.html` | **Interactive visualization** — filter by repo, search nodes, explore communities |
| `graphify-out/GRAPH_REPORT.md` | Detailed graph report with community breakdown |

---

## 🔍 How to Query

Requires [graphify](https://github.com/safishamsi/graphify):

```bash
uv tool install graphifyy

# Shortest path between two concepts across repos
graphify path "Firebase" "Stripe" --graph graphify-out/graph.json

# Explain any concept
graphify explain "AuthContext" --graph graphify-out/graph.json

# Ask a question — BFS traversal across the full org graph
graphify query "How is authentication handled across all products?" --graph graphify-out/graph.json
```

## 🏗️ Built With

- [graphify](https://github.com/safishamsi/graphify) by @safishamsi
- Merged via `graphify merge-graphs` + custom node-link reconciliation
- Generated: 2026-05-24

---

*This graph is auto-generated. To update after code changes: `graphify update <repo>` then re-merge.*