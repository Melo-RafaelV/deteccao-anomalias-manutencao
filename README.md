# Projeto 2 - Detecção de Anomalia para Realização de Manutenção Preventiva

Este repositório contém o Projeto 2 da disciplina de Estatística e Probabilidade para Computação (2026.1) do Centro de Informática (CIn) da Universidade Federal de Pernambuco (UFPE).

Link para o código no Colab: https://colab.research.google.com/drive/1K1BzWmWdCpUFTOLotCNUivioRBr6D6PV?usp=sharing

## Alunos
- **RAFAEL VICTOR PEREIRA DE MELO (RVPM)**
- **JOAO LUCAS TAVARES FERREIRA (JLTF)**
- **DANTTE ROBERTO ALVES DE ALMEIDA FREITAS (DRAAF)**
- **JULIA ANDRADE LIMA GONCALVES BEZERRA (JALGB)**
- **FABIO HENRIQUE UCHOA LOPES (FHUL)**
- **PEDRO HENRIQUE FERREIRA DA SILVA (PHFS)**
- **LUIZ FELIPE CAMPOS GOUVEIA (LFCG)**

## Sobre o Projeto
O objetivo principal deste projeto é aplicar técnicas estatísticas e métodos de análise de dados para detectar anomalias em equipamentos industriais, auxiliando na tomada de decisão para a manutenção preventiva. A análise busca identificar padrões em dados operacionais para entender e prever quando uma máquina está sujeita a falhas (Machine Failure), evitando paradas inesperadas.

## Base de Dados
O conjunto de dados consiste em 10.000 registros com diversas características capturadas durante a operação. Os dados incluem:
- Identificadores de produto e variantes de qualidade (Baixa, Média, Alta).
- Temperatura do ar e temperatura do processo.
- Velocidade de rotação e torque aplicado.
- Tempo de desgaste da ferramenta.

A falha da máquina pode ser ocasionada por cinco modos distintos: falha por desgaste da ferramenta (TWF), falha na dissipação de calor (HDF), falha de energia (PWF), falha por sobrecarga (OSF) e falhas aleatórias (RNF). A variável alvo indica se ocorreu qualquer uma dessas falhas.

## Métodos Utilizados
Seguindo as especificações da disciplina, a abordagem metodológica de detecção contou com as seguintes etapas:
1. Análise Exploratória de Dados (EDA): Limpeza de dados, análises univariadas, bivariadas e multivariadas para mapeamento de distribuições e correlação entre as variáveis operacionais.
2. Testes de Hipóteses: Validação estatística rigorosa baseada nos insights da EDA para confirmar a significância dos padrões relacionados à falha das máquinas.
3. Modelagem e Detecção: Pré-processamento e aplicação de técnica de modelagem estatística focada na detecção de anomalias, como agrupamento ou classificação, para prever as falhas a partir dos padrões encontrados (o modelo final e seus parâmetros estão documentados internamente no notebook).

## Estrutura
O desenvolvimento está documentado em um Notebook contendo todo o pipeline em linguagem R, organizado como um relatório técnico com explicações, gráficos e códigos.
