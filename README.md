# GS-GOV


# Projeto Completo: Análise e Governança de IA para Serviços de Emergência

![Linguagem](https://img.shields.io/badge/Linguagem-Python-blue.svg)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen.svg)
![Versão](https://img.shields.io/badge/Versão-1.0-informational.svg)

## 1. Visão Geral do Projeto

Este repositório contém o código e a documentação de um projeto completo que simula e analisa a implementação de um assistente de IA para triagem de chamadas de emergência. O objetivo é percorrer um ciclo de desenvolvimento responsável de IA, cobrindo desde a identificação de riscos até a geração de relatórios automatizados.

---

## 2. Estrutura do Projeto

Ao executar o script principal, a seguinte estrutura de arquivos e pastas será criada:

/projeto-analise-ia/
|
|-- README.md             <-- Este documento
|-- script_analise.py     <-- O código principal listado abaixo
|
|-- logs_emergencia_simulados.csv  <-- Dataset gerado na primeira execução
|-- relatorio_emergencias.pdf <-- Relatório final em PDF gerado
|
|-- /graficos/                <-- Pasta para armazenar as imagens dos gráficos
|   |-- 1_distribuicao_despacho.png
|   |-- 2_distribuicao_resposta_ia.png
|   |-- ... (outras imagens)

---

## 3. Pré-requisitos e Instalação

Antes de executar, certifique-se de ter o **Python 3.8 ou superior** instalado.

As seguintes bibliotecas são necessárias. Instale todas de uma vez com o comando:

```bash
pip install pandas numpy plotly reportlab kaleido

pandas & numpy: Para manipulação de dados.
plotly & kaleido: Para geração e salvamento dos gráficos.
reportlab: Para a criação do relatório em PDF.

```

## 4. Como Executar

* 1. Salve o código da seção 5 abaixo em um arquivo chamado script_analise.py.
* 2. Abra um terminal na pasta onde você salvou o arquivo.
* 3. Execute o script com o comando:

  ```bash
python script_analise.py

```

