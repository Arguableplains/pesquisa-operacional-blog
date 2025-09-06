---
title: Algoritmos de Caminho Minimo
published: 2025-09-05
description: ''
image: ''
tags: []
category: 'PO'
draft: false 
lang: ''
---

# Algoritmos de Caminho Mínimo

## 1. Definição
Caminho mínimo é encontrar a rota de menor custo (distância, tempo, valor) entre nós em um grafo
Solução essencial em roteamento, logística, redes e planejamento.

## 2. Algoritmos Principais
- **Dijkstra** – grafos com pesos não-negativos, eficiente para single-source shortest path. Muito usado em GPS e redes.
- **Bellman–Ford** – suporta arestas com peso negativo e detecta ciclos negativos.
- **Floyd–Warshall** – resolve todos os pares (all-pairs) usando programação dinâmica, ideal para grafos menores.  
- **Johnson** – combina Bellman-Ford e Dijkstra para todos os pares com arestas negativas (sem ciclos).
- **Problemas com restrições** (RCSP – Resource Constrained Shortest Path) ou multicritério são NP-difíceis; resolvidos via programação dinâmica ou heurística.

## 3. Aplicações Práticas
- **Tráfego urbano e redes elétricas**: otimização de trajetos e infraestrutura.
- **Projetos e caminhos críticos (PERT)**: uso do algoritmo como subrotina em planejamento de projetos.
- **Roteamento de veículos (VRP)** e **fluxos em redes de comunicação**: encontrar trajetos que respeitam custos e QoS.

## 4. Exemplos Reais
- **Distribuidora**: aplicação do problema do caminho mais curto para otimizar rotas.
- **Problema de Caminho Mínimo com Restrições**: usado para escalonamento de agentes móveis, QoS em redes veiculares e roteamento em redes de computadores.

---
