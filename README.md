# Manutenção Preditiva Industrial

Projeto avaliativo de ciência de dados para prever falhas mecânicas em equipamentos industriais a partir de medições de sensores. O alvo é `falha_maquina` (0: funcionamento normal; 1: falha).

> **Estado:** preparação do repositório (P01). O pipeline, os resultados e a comparação dos modelos ainda serão desenvolvidos pelo estudante.

## Objetivo e escopo

A solução será organizada em um único notebook Jupyter. O trabalho previsto inclui análise exploratória, limpeza e preparação, criação de uma variável numérica, divisão estratificada dos dados, balanceamento exclusivo do treino, escalonamento para KNN, ajuste de KNN e árvore de decisão e comparação final pela acurácia no teste. As decisões técnicas e os resultados serão registrados no próprio notebook.

## Fontes

- [Enunciado original do projeto](https://docs.google.com/document/d/1z5z3OLMUzl7k6qD7WMYlLhUIDJF4-S9tVqKTtG7mgUA/edit).
- [Pasta com o CSV e as anotações de Engenharia](https://drive.google.com/drive/folders/1_QcYvhSoJO6SxOJz8Om6gaVuWyPZKdMs?usp=sharing).
- [Instruções para obter e posicionar os dados](data/README.md). Os arquivos originais da atividade não são versionados neste repositório.

## Estrutura em preparação

- `manutencao_preditiva_industrial.ipynb`: notebook principal.
- `data/README.md`: procedência e instruções para obter o CSV.
- `data/manutencao_preditiva.csv`: base local, obtida da fonte indicada acima.
- `requirements.txt`: versões das dependências Python utilizadas.
- `referencias/`: cópia local opcional das anotações de Engenharia.

## Preparar e abrir

Requer Git, Conda e Python 3.13. No terminal:

```bash
git clone https://github.com/CorreaBrunoMiguel/manutencao-preditiva-industrial.git
cd manutencao-preditiva-industrial
conda create -n manutencao-preditiva python=3.13
conda activate manutencao-preditiva
python -m pip install -r requirements.txt
```

Baixe o CSV conforme `data/README.md`. Com o ambiente ativo e na raiz do repositório, execute `jupyter lab` e abra `manutencao_preditiva_industrial.ipynb`. Durante o desenvolvimento, o notebook ainda não contém a solução completa.

## Acompanhamento

As tarefas, os critérios de aceite e o fluxo de branches estão no [GitHub Project](https://github.com/users/CorreaBrunoMiguel/projects/3/views/1) e na [issue guia P00](https://github.com/CorreaBrunoMiguel/manutencao-preditiva-industrial/issues/1). `develop` concentra as integrações; `main` receberá a versão final após a revisão do projeto.
