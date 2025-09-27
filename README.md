📊 Plataforma de Análise de Dados para Empresa de Climatização
Este projeto consiste no desenvolvimento de uma plataforma modular de análise de dados para uma empresa de serviços de climatização, utilizando dados simulados armazenados em um banco SQLite. A solução integra extração, análise estatística e geração de insights interpretativos por meio de um modelo de linguagem (LLM), preparando o terreno para a criação de dashboards interativos.

🧩 Funcionalidades
📂 Estruturação e Leitura de Dados: Conexão com banco SQLite e carregamento dos dados em DataFrames do Pandas.

📈 Análise Intermediária: Cálculo de métricas financeiras e operacionais (receita, despesa, lucro, ticket médio, frequência de manutenções, etc.).

🤖 Geração de Insights com LLM: Uso do modelo Llama3 (via Ollama) para transformar resumos estatísticos em relatórios interpretativos.

🧱 Arquitetura Modular: Facilita a integração com futuras visualizações (Streamlit, Plotly, Flask) e adição de novas fontes de dados.

🎯 Alinhamento com o Tema do Projeto
O projeto se alinha ao tema:
“Desenvolver análise de dados em escala utilizando dados existentes ou capturados por IoT e aprendizagem de máquina, preparando uma interface para visualização dos resultados.”

Escalabilidade: Arquitetura preparada para grandes volumes de dados.

IA/ML: Uso de LLM para interpretação estratégica dos dados.

Visualização: Estrutura modular permite fácil exportação para dashboards.

❓ Exemplos de Perguntas Suportadas
💰 Financeiro
Qual foi a tendência de receita e despesa nos últimos meses?

O lucro líquido atual é sustentável?

Se as despesas crescerem 10% no próximo mês, qual seria o impacto no lucro?

🔧 Operacional
Quais clientes têm maior número de manutenções?

A frequência média de manutenção está dentro do esperado para o setor?

⚠️ Riscos
Há sinais de risco de inadimplência ou queda na base de clientes?

Quais pontos de atenção devo monitorar?

🚀 Estratégia
Como aumentar a receita com a base atual?

Vale mais a pena reduzir custos ou investir em expansão?

📅 Projeções
Qual a previsão de receita e lucro para os próximos 3 meses?

Se eu aumentar os preços em 5%, o que pode acontecer?

🗂️ Estrutura do Projeto
text
projeto-climatizacao/
├── leitura_db.py          # Leitura e conexão com SQLite
├── analise.py             # Análise estatística e métricas
├── llm_insights.py        # Geração de insights com LLM
├── database/
│   └── climatizacao.db    # Banco de dados simulado
├── media/                 # Imagens e gráficos
└── README.md
🛠️ Tecnologias Utilizadas
Python

Pandas

SQLite

Ollama + Llama3

(Futuro) Streamlit / Plotly / Flask

📌 Próximos Passos
Integração com dashboard interativo (Streamlit)

Adição de fontes de dados em tempo real (IoT)

Implementação de modelos preditivos para projeções automáticas

👨‍💻 Autor: Gabriella Wandeur
Desenvolvido como parte do projeto de curso em Análise de Dados e IA.