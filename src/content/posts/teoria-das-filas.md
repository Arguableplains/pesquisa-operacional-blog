---
title: Teoria das filas
published: 2025-09-05
description: ''
image: ''
tags: []
category: 'PO'
draft: false 
lang: 'pt-br'
---

# Teoria das Filas

## 1. Definição
A Teoria das Filas (Queueing Theory) estuda **sistemas de espera** onde "clientes" (pessoas, dados, veículos, etc.) aguardam atendimento por "servidores". Utiliza-se modelos matemáticos para estimar desempenho, como tempo médio de espera, tamanho da fila e utilização dos recursos.

## 2. Componentes-chaves
- **Taxa de chegada (λ)** – frequência com que clientes chegam.  
- **Taxa de serviço (μ)** – frequência com que são atendidos.  
- **Servidores** – quantidade de atendentes ou máquinas (modelo c).  
- **Disciplina de fila** – FIFO (primeiro a chegar, primeiro atendido), prioridade, LIFO etc.  
- **Capacidade de fila** – se é finita ou infinita.

## 3. Modelos Clássicos
- **M/M/1** – chegadas Poisson e serviços exponenciais com 1 servidor.  
- **M/M/c** – múltiplos servidores.  
- **M/G/1** – serviço com distribuição geral.  
- **Distribuição de Erlang** – soma de k serviços exponenciais; útil quando atendimento envolve várias etapas. Fórmulas:  
$$
\begin{equation*}
L_q = \frac{(1 + k)\lambda}{2k\mu(\mu - \lambda)}, \quad
W_q = \frac{(1 + k)\lambda}{2k\mu(\mu - \lambda)}, \quad
W = W_q + \frac{1}{\mu}
\end{equation*}
$$

## 4. Medidas de Desempenho

$$
\begin{equation*}
- [
L_q
]: \textnormal{número médio de clientes na fila}.
\end{equation*}
$$

$$
\begin{equation*}
- [
W_q
]: \textnormal{tempo médio de espera na fila}.  
\end{equation*}
$$

$$
- [
W
]: \textnormal{tempo médio no sistema (espera + atendimento)}.
$$

$$
- [
\rho = \frac{\lambda}{c \cdot \mu}
]: \textnormal{utilização dos recursos.}  
$$

## 5. Exemplos Práticos
- **Lava-rápido em Porto Velho (RO)**: análise com modelo M/M/S de fila finita para medir desempenho do serviço e sugerir melhorias.
- **Sala de emergência hospitalar**: modelar chegadas e atendimentos para prever tempos de espera e dimensionar pessoal.
- **Call center**: usar M/M/c para definir número de atendentes conforme demanda e alternativas via programação inteira.

> Esses exemplos mostram a aplicação real da teoria para avaliar e melhorar sistemas de atendimento, promovendo eficiência e satisfação.

---
