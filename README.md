# Análise e Governança de IA para Serviços de Emergência

![Linguagem](https://img.shields.io/badge/Linguagem-Python-blue.svg)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen.svg)
![Versão](https://img.shields.io/badge/Versão-1.0-informational.svg)

## 1. Visão Geral do Projeto

Este projeto demonstra um ciclo completo de desenvolvimento e governança de um sistema de Inteligência Artificial para o setor de serviços de emergência. O script simula a operação de um assistente de IA que ajuda na triagem de chamadas, analisa sua performance, identifica gargalos e vieses, e por fim, gera um relatório consolidado em PDF.

O foco principal é a aplicação de práticas de **IA Responsável**, garantindo que o sistema seja não apenas eficaz, mas também justo, transparente e auditável.

## 2. Funcionalidades Principais

-   **Simulação de Dados Realistas:** Gera um dataset (`.csv`) com logs de chamadas, incluindo diferentes categorias de emergência, bairros, e simulação de erros da IA e gargalos operacionais.
-   **Análise de Performance (KPIs):** Calcula automaticamente indicadores chave como Tempo Médio de Resposta da IA, Acurácia de Classificação e Tempo Médio Total para Despacho.
-   **Visualização de Dados:** Cria e salva múltiplos gráficos (histogramas e boxplots) para visualizar a performance geral e identificar gargalos por tipo de emergência ou localização geográfica.
-   **Relatório Automatizado em PDF:** Consolida todos os indicadores e gráficos gerados em um relatório final, pronto para ser compartilhado.

## 3. Tecnologias Utilizadas

-   **Python 3.8+**
-   **Pandas:** Para manipulação e análise de dados.
-   **NumPy:** Para operações numéricas.
-   **Plotly:** Para a criação de gráficos interativos.
-   **Kaleido:** Para salvar os gráficos do Plotly como imagens estáticas.
-   **ReportLab:** Para a geração do relatório final em PDF.

## 4. Instalação

Para executar este projeto, clone ou baixe os arquivos e instale todas as dependências com um único comando:

```bash
pip install pandas numpy plotly reportlab kaleido
```
