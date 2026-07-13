readme_content = """# Olá, eu sou a Gabriela 👋

**Data Analyst | Data Engineer | BI**

Transformo dados brutos em pipelines e dashboards que geram decisão.

## 🛠️ Stack
- **Linguagens:** Python, SQL
- **BI:** Power BI
- **Dados:** Engenharia de dados, pipelines em tempo real, PostgreSQL

## 📌 Projetos em destaque
- **[Portfolio](https://github.com/gxlobato/Portfolio)** — Projetos de engenharia de dados e analytics
- **[OrderStream](https://github.com/gxlobato/OrderStream)** — Pipeline de dados em tempo real que simula pedidos de e-commerce, processando eventos um a um e gravando métricas em Postgres na nuvem

## 📫 Contato
- LinkedIn: [gabriela-lobato-003a7b40](https://linkedin.com/in/gabriela-lobato-003a7b40)
"""

with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme_content)

print("README.md gerado com sucesso!")
