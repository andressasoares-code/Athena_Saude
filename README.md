# Athena Saúde — Painel de Contas a Receber

Dashboard de contas a receber com aging analysis, variação mês a mês e importação acumulada de bases mensais.

## Como usar

1. Acesse o painel pelo link do Streamlit Cloud
2. Use a barra lateral para importar novos arquivos `.xlsx` todo mês
3. Os dados Março e Abril 2025 já estão pré-carregados

## Estrutura do projeto

```
athena-dashboard/
├── app.py                        # Aplicação principal
├── requirements.txt              # Dependências
├── Consolidado_MARÇO.xlsx        # Base pré-carregada
└── Consolidado_ABRIL.xlsx        # Base pré-carregada
```

## Deploy no Streamlit Cloud

1. Faça upload deste repositório no GitHub
2. Acesse share.streamlit.io
3. Conecte o repositório e selecione `app.py` como arquivo principal
