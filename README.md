# Case Study: Sistema de Gestão de Portfólio para a Mesa de Energia

> Este repositório descreve um projeto de alto impacto que liderei na Statkraft, focado na automação da análise de performance e risco para a **gestão de um portfólio complexo de energia**.

---

### 🏆 **Resultados-Chave em Destaque**

| Métrica | Impacto Gerado |
| :--- | :--- |
| ⚡ **Eficiência Operacional** | **Redução de 98%** no tempo de análise (de 6 horas para 5 minutos) |
| 🎯 **Precisão** | **Redução de 90%** nos erros de cálculo em comparação ao processo manual |
| 👥 **Adoção** | Ferramenta primária para **mais de 50 usuários**, incluindo traders e gestores de portfólio |
| decision **Tomada de Decisão** | Análises de risco e simulações de cenários em tempo real |

---

## business Problema de Negócio

A área de **Gestão de Portfólio** da Statkraft necessitava de uma ferramenta robusta para monitorar riscos e avaliar a performance de suas carteiras. O processo existente era manual, intensivo em planilhas, lento e propenso a erros, dificultando a agilidade necessária para a tomada de decisão em um mercado volátil.

## 💡 Minha Solução

Desenvolvi do zero uma **aplicação web interativa e centralizada** que automatizou todo o fluxo de análise de risco e performance. A solução integrou dados de mercado em tempo real, eliminou a dependência de planilhas e forneceu uma interface intuitiva para que os usuários pudessem extrair insights complexos de forma simples.

## 🛠️ Arquitetura e Tecnologias

- **Interface/Frontend:** Dash / Plotly
- **Lógica de Negócio/Backend:** Python (Pandas para manipulação de dados, NumPy para cálculos)
- **Banco de Dados:** Azure SQL

## ✨ Principais Funcionalidades Implementadas

- **Dashboard Unificado:** Apresentação consolidada de 13 KPIs de risco e performance.
- **Cálculo de Risco Automatizado:** Implementação de métricas como **Value at Risk (VaR)** para o portfólio.
- **Simulador de Contratos:** Ferramenta para análise de cenários e **stress testing**, permitindo que os gestores medissem o impacto de novas operações antes da execução.
- **Atribuição de Performance:** Módulos que permitiam decompor o resultado da carteira para entender quais estratégias ou contratos geraram maior retorno.
- **Gestão de Prêmios:** Acompanhamento e análise dos prêmios de risco associados aos produtos estruturados do mercado de energia.

## 🚧 Desafios Técnicos e Soluções

- **Integridade dos Dados:** Garantir a qualidade dos dados de mercado era crucial. **Solução:** Implementei rotinas de validação e limpeza no pipeline de dados para tratar outliers e dados faltantes antes dos cálculos.
- **Performance de Cálculos:** Com o aumento do volume de dados, alguns cálculos se tornaram lentos. **Solução:** Otimizei as queries no Azure SQL e refatorei o código Python, vetorizando operações com Pandas e NumPy para ganhos expressivos de performance.
- **Usabilidade:** A ferramenta precisava ser intuitiva para traders e gestores. **Solução:** Realizei sessões de feedback semanais com os usuários finais, ajustando a interface e os fluxos de navegação para criar uma experiência de baixa latência e alta usabilidade.

## 🌱 Principais Lições Aprendidas

- **Técnica:** A importância de um design de software modular desde o início, que facilitou a adição de novos KPIs e modelos de risco sem a necessidade de grandes refatorações.
- **Negócio:** A colaboração estreita com os usuários finais não é apenas útil, é essencial. Entender profundamente o "porquê" por trás de uma solicitação leva a uma solução muito mais eficaz.

> *Nota: Por se tratar de um projeto interno e proprietário da Statkraft, o código-fonte não pode ser compartilhado publicamente. Este repositório serve como uma documentação detalhada da arquitetura do projeto, dos desafios superados e do valor gerado para o negócio.*
