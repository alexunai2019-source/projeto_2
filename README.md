# projeto_2Projeto de Análise de Dados da Produção de Soja no Brasil
Descrição

Este projeto foi desenvolvido em Python com o objetivo de realizar análises exploratórias da produção de soja no Brasil utilizando técnicas de Ciência de Dados. O sistema permite carregar dados históricos da cultura, gerar estatísticas descritivas e visualizar o comportamento da produção ao longo dos anos por meio de gráficos.

Objetivos
Analisar a evolução da produção de soja no Brasil.
Avaliar o crescimento da área cultivada.
Comparar a produtividade das diferentes safras.
Aplicar conceitos de análise de dados utilizando Python.
Gerar visualizações gráficas para facilitar a interpretação dos resultados.
Tecnologias Utilizadas
Python 3
Pandas
Matplotlib
Jupyter Notebook
VS Code
Estrutura do Projeto
Projeto2_aula/
│
├── soja_brasil.csv
├── analise.ipynb
├── README.md
└── .venv/
Instalação
Criar ambiente virtual
python -m venv .venv
Ativar ambiente virtual
Windows (CMD)
.venv\Scripts\activate
Instalar dependências
pip install pandas matplotlib jupyter notebook
Base de Dados

O arquivo soja_brasil.csv contém informações referentes à produção nacional de soja entre os anos de 2015 e 2024.

As variáveis analisadas foram:

Ano
Área cultivada (ha)
Produção total (t)
Produtividade média (kg/ha)
Funcionalidades
Leitura de Dados

Carregamento automático do arquivo CSV utilizando a biblioteca Pandas.

Análise Estatística

Cálculo de indicadores estatísticos como:

Média
Desvio padrão
Valores mínimos e máximos
Quartis
Visualização Gráfica

Geração de gráficos para análise da evolução da produção de soja ao longo dos anos.

Exploração dos Dados

Visualização tabular das informações e identificação de tendências produtivas.

Exemplo de Saída

O sistema apresenta:

Tabela contendo os dados da produção de soja.
Estatísticas descritivas da base de dados.
Gráfico da evolução da produção.
Informações sobre produtividade e área cultivada.
Principais Resultados
Crescimento contínuo da área cultivada ao longo dos anos.
Aumento significativo da produção nacional.
Oscilações na produtividade devido a fatores climáticos e tecnológicos.
Maior produção observada nas safras mais recentes.
Possíveis Melhorias
Inclusão de dados por estado.
Integração com bases oficiais da CONAB e IBGE.
Desenvolvimento de dashboards interativos.
Aplicação de modelos de previsão de safra.
Geração automática de relatórios em PDF.
Autor

Alex Alves Borges

Graduando em Agronomia

Licença

Projeto desenvolvido para fins acadêmicos e educacionais.