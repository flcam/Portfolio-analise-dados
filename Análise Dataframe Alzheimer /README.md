Análise de Dados sobre Diagnóstico de Alzheimer


Descrição do Projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) em um conjunto de dados relacionado ao diagnóstico de Alzheimer. A análise envolve a limpeza dos dados, a transformação de variáveis categóricas e numéricas, a geração de estatísticas descritivas e a visualização dos principais insights.

Estrutura do Projeto

O repositório é organizado da seguinte forma:


├── data/                # Contém os arquivos de dados (ex.: CSV)   
├── notebooks/           # Jupyter Notebooks com análises detalhadas e gráficos gerados pela análise
└── README.md            # Este arquivo


Tecnologias Utilizadas

Python Pandas: Manipulação e análise de dados

NumPy: Operações matemáticas e vetoriais

Matplotlib & Seaborn: Visualização de dados

Scikit-Learn: Análise e transformação de dados

Etapas da Análise

Importação de bibliotecas: Carregamento das principais ferramentas para manipulação e análise dos dados.
Leitura dos dados: Carregamento do arquivo CSV e verificação inicial do DataFrame.

Tratamento de dados:
Remoção de colunas irrelevantes
Renomeação de colunas para padronização
Verificação de valores nulos

Transformação de variáveis:
Conversão de variáveis categóricas para binárias
Normalização de valores numéricos

Análise descritiva:
Estatísticas descritivas da variável idade
Contagem e distribuição de diagnósticos
Correlações entre variáveis relevantes

Visualização de dados:
Gráficos de distribuição de diagnósticos por país
Percentual de diagnósticos considerando fatores genéticos e histórico familiar

Como Executar o Projeto
1. Clonar o repositório
   git clone https://github.com/seu_usuario/alzheimer_analysis.git
   cd alzheimer_analysis2.
   
2. Criar um ambiente virtual (opcional, mas recomendado)
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows

3. Executar o notebook
Abra um terminal e execute:
jupyter notebook

Em seguida, abra o notebook na pasta notebooks/ para visualizar e executar a análise.

Resultados e Conclusões:
A maior incidência de diagnósticos ocorre em determinados países, o que pode estar relacionado a fatores genéticos ou ambientais.

Indivíduos com histórico familiar têm maior propensão ao Alzheimer.

Existe uma forte correlação entre risco genético e diagnóstico positivo.

A análise visual das distribuições fornece insights sobre os fatores de risco mais relevantes.

ContatoCaso tenha dúvidas ou sugestões, entre em contato:

Email: flcam75@gmail.com

LinkedIn: www.linkedin.com/in/flaviocamargo-custódio-92a65169

GitHub: Seu Usuário
