# Infraestrutura Escolar e Desempenho no ENEM (2023)

Este repositório contém materiais do meu TCC (MBA em Analytics e Big Data) focado em analisar como fatores de **infraestrutura escolar** e **contexto socioeconômico** se relacionam com o desempenho em matemática no ENEM 2023, com apoio de modelos estatísticos e Machine Learning.

## Objetivo
Investigar:
- Quais variáveis de infraestrutura estão associadas ao desempenho municipal
- Como variáveis socioeconômicas explicam risco de baixo desempenho
- Como modelos preditivos podem apoiar decisões em políticas educacionais e iniciativas data-driven

## Fontes de dados
- INEP (Censo Escolar 2023)
- INEP (Microdados ENEM 2023)
- IBGE (dados municipais)

> Observação: dados brutos não estão versionados neste repositório. Veja a seção "Reprodução".

## Metodologia (resumo)
- Limpeza e consistência dos dados
- Agregação municipal e análises exploratórias
- Regressões (infraestrutura e socioeconomia)
- Modelos de classificação (Logistic, Random Forest, XGBoost, etc.)
- Interpretabilidade (Feature Importance / SHAP)
- Simulações de perfis para estimar risco

## Principais resultados (highlights)
- Infraestrutura tem associação positiva com desempenho, mas
- Fatores socioeconômicos (renda, raça/cor, tipo de escola) aparecem como os principais drivers de risco
- XGBoost como modelo final (melhor equilíbrio de performance e interpretabilidade)

## Reprodução
1. Baixe os microdados nas fontes oficiais do INEP/IBGE
2. Coloque os arquivos em `data/raw` (não versionado)
3. Execute os notebooks/scripts em ordem

## Autor
Pedro Henrique Lofiego Sampaio da Silva
