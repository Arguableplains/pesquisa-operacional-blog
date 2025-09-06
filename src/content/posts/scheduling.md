---
title: Scheduling
published: 2025-09-05
description: ''
image: ''
tags: []
category: 'PO'
draft: false 
lang: ''
---

# Escalonamento (Scheduling)

## 1. Definição
Scheduling é uma área da Pesquisa Operacional que foca na **atribuição e ordenação de tarefas** para recursos limitados (máquinas, CPUs, operadores). O objetivo: otimizar métricas como makespan, tempo de resposta, throughput ou cumprimento de prazos.

## 2. Políticas e Algoritmos Típicos
- **FCFS (First-Come-First-Served)** – ordem de chegada.  
- **SJF (Shortest Job First)** – tarefas mais curtas primeiro; reduz tempo de espera médio, mas risco de inanição.
- **Round Robin (RR)** – cada tarefa recebe uma fatia de tempo (quantum) de forma cíclica; evita inanição.
- **Job Shop Scheduling (JSSP)** – sequenciamento de operações em múltiplas máquinas; geralmente NP-difícil.  
- **Busca Tabu e heurísticas meta-heurísticas** para otimizar escalonamento complexo.
- **PERT/CPM** – redes de tarefas com cálculo de caminho crítico para gestão de projetos.

## 3. Métricas Importantes
- **Throughput (débitos de jobs/hora)**  
- **Turnaround Time** – tempo da submissão ao término da tarefa.  
- **Tempo de resposta** – importante para sistemas interativos.  
- **Utilização do recurso**, **cumprimento de deadlines**, **previsibilidade de execução**.

## 4. Exemplos Reais
- **Projeto universitário (carro elétrico)**: escalonamento de pessoal conforme disponibilidade e preferências, alcançando satisfação de 96%.
- **Job Shop com trocas de ferramenta**: minimizar atrasos, paradas e trocas via Busca Tabu em sistema de manufatura flexível (SMF).
- **Sistemas operacionais**: algoritmo Round Robin usado em Windows com múltiplas filas e envelhecimento de processos.

---
