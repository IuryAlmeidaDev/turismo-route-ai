# 🗺️ Turismo Route AI (Algoritmo Genético)

[![Python](https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-API-000000?style=for-the-badge&logo=flask)](https://flask.palletsprojects.com/)
[![AI](https://img.shields.io/badge/AI-Genetic%20Algorithm-success?style=for-the-badge)](#)

Serviço em **Python / Flask** com **Algoritmo Genético** para otimização de rotas e itinerários turísticos multi-pontos.

---

## 📌 Sobre o Projeto

O planejamento de roteiros turísticos é uma variação do clássico *Problema do Caixeiro Viajante (TSP)*, onde o objetivo é visitar múltiplos pontos turísticos com menor tempo de deslocamento e custo.

Este projeto disponibiliza uma API REST com o `TourismGeneticAlgorithm`, que recebe uma lista de coordenadas de atrativos turísticos e processa a ordem de visita mais eficiente.

## 🚀 Parâmetros do Algoritmo

- **População:** 50 indivíduos por geração
- **Gerações:** 100 iterações evolutivas
- **Taxa de Cruzamento (*Crossover*):** 80% (Order Crossover - OX)
- **Taxa de Mutação:** 5% (Swap Mutation)
- **API REST:** Endpoints em Flask prontos para integração com frontend e backend.

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Flask** (serviço web RESTful)
- **NumPy**

## ⚙️ Como Executar Localmente

```bash
git clone https://github.com/IuryAlmeidaDev/turismo-route-ai.git
cd turismo-route-ai
pip install flask numpy
python genetic_algorithm.py
```

---

## 👤 Autor

Desenvolvido por **[Iury Almeida](https://github.com/IuryAlmeidaDev)**.
