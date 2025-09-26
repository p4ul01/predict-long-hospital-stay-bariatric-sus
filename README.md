# predict-long-hospital-stay-bariatric-sus
Machine Learning model to predict prolonged hospital stay after bariatric surgery in SUS patients

Modelo de Machine Learning para Prever Internação Longa em Cirurgia Bariátrica no SUS

Este repositório contém o código e os dados utilizados no estudo "Modelo de machine learning para prever internação longa em cirurgia bariátrica como ferramenta de apoio à tomada de decisão no SUS", submetido para publicação.

O objetivo é prever, com base em dados do SIH/SUS, quais pacientes têm alto risco de internação hospitalar prolongada (>3 dias) após cirurgia bariátrica, apoiando gestores na alocação eficiente de recursos.

RESULTADOS PRINCIPAIS
- AUC-ROC: 0,750 (Random Forest)
- F1-Score: 0,710
- Taxa de internações longas: 40,5% (média 2018–2023), com queda de 90% (2018) para 21% (2023)
- Disparidade regional: MG (88%) vs. SP (36%)
- Principais preditores: Diagnóstico principal, doença hepática, hipertensão, diabetes e depressão pré-operatória

ESTRUTURA DO REPOSITÓRIO
.
├── algoritmo_002.ipynb        # Notebook com todo o código de análise e modelagem
├── bariatrica_sp_mg_2018_2023.xlsx  # Dados brutos do SIH/SUS (SP e MG, 2018–2023)
├── requirements.txt           # Dependências do Python
├── LICENSE                    # Licença MIT
└── README.txt                 # Este arquivo

COMO EXECUTAR
1. Baixe os arquivos do repositório (clique em “Code” → “Download ZIP”).
2. Extraia a pasta.
3. Instale as dependências (recomenda-se usar um ambiente virtual):
   pip install -r requirements.txt
4. Abra o notebook:
   jupyter notebook algoritmo_002.ipynb

OBSERVAÇÃO: Os dados são públicos do DATASUS e foram anonimizados. O uso é exclusivamente para fins acadêmicos e de pesquisa.

CONTEXTO CLÍNICO
A cirurgia bariátrica é o tratamento mais eficaz para a obesidade mórbida, mas sua alta demanda no SUS exige gestão eficiente. Internações prolongadas consomem leitos, aumentam custos e risco de complicações. Este modelo permite estratificação de risco pré-operatória, viabilizando:
- Alocação inteligente de leitos
- Protocolos diferenciados de cuidado
- Redução de custos operacionais

LICENÇA
Este projeto está licenciado sob a MIT License — veja o arquivo LICENSE para detalhes.
