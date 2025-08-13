# 🍹 Bora Bills Bar — Integrações via API (Projeto SENAI)

**Curso:** Desenvolvimento de Sistemas — SENAI  
**Tema:** Integrações via API usando Django

---

## 📌 Sobre o Projeto
O **Bora Bills Bar** é um sistema web desenvolvido em **Django** inspirado no universo de **Dragon Ball Z**, trazendo a personalidade e o humor do Deus da Destruição, **Bills**.  
O projeto integra múltiplas APIs públicas para oferecer funcionalidades dinâmicas e divertidas:

- **🍸 Cardápio Cósmico:** Busca drinks da [TheCocktailDB API](https://www.thecocktaildb.com/) com fotos, ingredientes e modo de preparo.
- **🏆 Ranking Gamificado:** Lista e ranqueia clientes com base em pontos, mostrando avatares e personagens favoritos de **Dragon Ball Z**.
- **🐉 Curiosidades DBZ:** Exibe informações e curiosidades de personagens via [Dragon Ball API](https://dragonball-api.com/).
- **🌦 Previsão do Tempo:** Mostra o clima da sua cidade em tempo real usando [Open-Meteo API](https://open-meteo.com/).

---

## 🛠 Tecnologias Utilizadas
- **Backend:** [Python 3.12](https://www.python.org/) + [Django](https://www.djangoproject.com/)
- **Frontend:** HTML, CSS, Django Templates
- **APIs:**
  - TheCocktailDB (drinks)
  - Dragon Ball API (personagens)
  - Open-Meteo (clima)
- **Outros:** Django REST Framework, Requests

---

## 📂 Estrutura dos Apps
- `menu` → Páginas principais, home, cardápio e curiosidades.
- `clientes` → Cadastro, ranking e integração com personagens DBZ.
- `api` → Funções utilitárias para consumo de APIs externas.

