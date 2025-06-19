
# Avaliação da Disciplina de Inteligência Artificial

Este repositório contém o projeto de avaliação da disciplina de Inteligência Artificial, cujo objetivo é aplicar algoritmos clássicos de aprendizado de máquina para problemas de classificação, com foco especial em cibersegurança.

## Projeto: Classificação de Ataques de Rede com Random Forest e SVM

### Descrição

O projeto consiste em implementar e comparar os algoritmos Random Forest e SVM (Support Vector Machine) na tarefa de classificação de diferentes tipos de ataques de rede, utilizando dados reais de tráfego. O objetivo é explorar técnicas de pré-processamento, seleção de características, ajuste de hiperparâmetros e análise de métricas em um contexto realista e desafiador de segurança da informação.

### Base de Dados Utilizada

- **CICIDS2017**  
  - Mais de 80 características de fluxo de rede, classificação multi-classe.
  - [Link oficial](https://www.unb.ca/cic/datasets/ids-2017.html)
  - Detalhes estão descritos no arquivo `Dataset (CIC-IDS2017).pdf`.

### Modelos Utilizados

- **SVM (Support Vector Machine)**: Algoritmo de classificação baseado em hiperplanos de separação.
- **Random Forest**: Conjunto de árvores de decisão para classificação robusta.

## Objetivos de Aprendizado

- Implementar técnicas de pré-processamento para dados de tráfego de rede
- Explorar métodos de seleção de características para reduzir a dimensionalidade
- Comparar diferentes estratégias de kernel em SVM para dados de rede
- Analisar a importância de diferentes características no Random Forest
- Implementar técnicas para lidar com classes desbalanceadas
- Avaliar os modelos usando múltiplas métricas

## Métricas de Avaliação

- Acurácia  
- Precisão  
- Recall  
- F1-score por classe  
- Matriz de confusão  
- Tempo de treinamento e inferência  

## Estrutura do Repositório

```
Classificação de Ataques de Rede com Random Forest e SVM/
├── CICIDS2017/                      # Diretório de dados (dataset original)
├── Classificação_de_Ataques_de_Rede_com_Random_Forest_e_SVM.ipynb
├── Docs/Dataset (CIC-IDS2017).pdf       # Documento explicativo sobre o dataset
├── Docs/Requisitos.pdf                  # Lista dos requisitos para avaliação
└── README.md                       # Este documento
```

## Artigo

O artigo (não incluso neste repositório) aborda:

1. Introdução - Introduzindo o problema e tarefa a ser desenvolvido;
2. Background - Descrição das tecnologias que serão utilizadas;
3. Métodos - Método proposto, com figuras e dividido por etapas;
4. Resultados e Discussões - Apresentação dos resultados, como modelo utilizado, valores das
métricas obtidos e discussão dos resultados;
5. Conclusões - Suas conclusões acerca do trabalho.

## Avaliação

- **Código (40% da nota)**
  - Implementação correta (60%)
  - Experimentação e análise (30%)
  - Criatividade (10%)

- **Artigo (30%)**

- **Apresentação (30%)**
  - Duração entre 15 e 20 minutos
  - Avaliação da clareza, domínio do tema e capacidade de responder perguntas

---

**Autor:**  
Jhonatas Gomes Ribeiro
