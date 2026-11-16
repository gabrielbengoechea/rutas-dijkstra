# Dijkstra Logistics Master

> Interactive web tool to learn and apply Dijkstra's shortest-path algorithm to **outbound transport** in a distribution network.

**[▶ Live demo](https://gabrielbengoechea.github.io/rutas-dijkstra/)** · Interface in Spanish

## Overview

Built as a learning resource for Logistics Engineering (outbound transport / *Transporte de Salida*). It connects the algorithm with its operational purpose: route optimization is not only about the shortest path, but about reducing operating costs, consolidating loads and delivering on time.

## Features

- **Visual Dijkstra simulator:** pick an origin (distribution center) and destination (customer/branch), then run the algorithm step by step or jump to the optimal route.
- **Interactive node map:** drag nodes to reorganize the network; visited, evaluated and optimal-route states are color-coded.
- **Distance table and priority queue:** accumulated distance `d[v]`, predecessor `p` and status at every step.
- **Route result:** total distance, estimated fuel cost and estimated time.
- **Financial & logistics impact calculator:** cost per km, fuel consumption, monthly shipments and order-consolidation factor.
- **Practical cases, quiz and theory** sections.

## Technology

Single-file web app: HTML, JavaScript and Tailwind CSS (loaded from CDN). No build step or backend.

## Getting started

```bash
git clone https://github.com/gabrielbengoechea/rutas-dijkstra.git
cd rutas-dijkstra
# open index.html in a browser (internet connection needed for the Tailwind CDN)
```

## Roadmap

- [ ] Add screenshots to this README
- [ ] Optional English interface
- [ ] Load networks from a file (e.g. CSV of nodes and edges)

## Credits & license

Author: [Gabriel Bengoechea](https://github.com/gabrielbengoechea) — Logistics Engineering, UTEC Uruguay. No license has been chosen yet.

---

### Resumen en español

Herramienta web interactiva para aprender el algoritmo de Dijkstra aplicado al **transporte de salida**: simulador paso a paso sobre una red de distribución, tabla de distancias y cola de prioridad, calculadora de ahorro (costo por km, combustible, consolidación de pedidos), casos prácticos y cuestionario. Abrí `index.html` o la [demo en línea](https://gabrielbengoechea.github.io/rutas-dijkstra/).
