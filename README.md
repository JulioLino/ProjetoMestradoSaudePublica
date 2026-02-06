# Projeto de Análise: Mestrado Fiocruz
## Avaliação de Impacto e Análise Estatística em Saúde Pública

[cite_start]Este repositório contém o notebook desenvolvido para a análise de dados e avaliação de impacto educacional na rede pública de saúde, realizado em colaboração com a Fiocruz[cite: 70, 118].

### 📋 Visão Geral do Projeto
[cite_start]O objetivo central foi mensurar cientificamente a eficácia de intervenções educacionais (treinamentos) comparando o nível de conhecimento dos participantes em dois momentos: **pré e pós-intervenção**[cite: 109, 124].

### 🛠️ Tecnologias e Ferramentas
* [cite_start]**Linguagem:** Python [cite: 114, 126]
* **Bibliotecas Principais:**
    * [cite_start]**Pandas:** Manipulação, limpeza e pareamento dos dados de questionários[cite: 108, 127].
    * [cite_start]**SciPy (stats):** Execução de cálculos estatísticos avançados[cite: 114, 127].
    * [cite_start]**NumPy:** Suporte para operações matemáticas e vetoriais[cite: 114].
* [cite_start]**Ambiente de Desenvolvimento:** Google Colab / Jupyter Notebooks[cite: 116].

### 📊 Metodologia Estatística Aplicada
* [cite_start]**Tratamento de Dados:** Processamento de bases brutas para garantir a integridade histórica e o pareamento correto por participante[cite: 108, 112].
* [cite_start]**Teste de Hipótese:** Aplicação do **Teste t de Student para Amostras Pareadas** (*Paired Sample t-test*)[cite: 109, 128].
* [cite_start]**Análise de Significância:** Uso do **p-valor** (p-value) com nível de confiança de 95% ($\alpha = 0,05$) para validar se a evolução do aprendizado foi estatisticamente relevante[cite: 111, 131].
* [cite_start]**Segmentação (GroupBy):** Análise granular por função profissional para identificar perfis com maior ou menor absorção do conteúdo[cite: 110, 132].

### 🚀 Impacto e Resultados
[cite_start]A estruturação deste pipeline de dados permitiu isolar o efeito do aprendizado, gerando insights validados que fundamentaram a tomada de decisão acadêmica e a transição da pesquisa para a fase de **Doutorado**[cite: 112, 135].
