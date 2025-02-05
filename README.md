# Classificação de Emails (Spam e Ham) e Detecção de Anomalias com LSTM, Naive Bayes, SVM e GMM

Este repositório contém o código e os recursos utilizados para realizar a classificação de emails em spam (mensagens não desejadas) e ham (mensagens legítimas), bem como a detecção de anomalias em emails. O projeto emprega modelos de aprendizado de máquina, incluindo LSTM (Long Short-Term Memory), Naive Bayes e SVM (Support Vector Machine) para classificação, e GMM (Gaussian Mixture Model) para detecção de anomalias.

## Descrição do Projeto

O objetivo deste projeto é desenvolver um sistema capaz de classificar emails em spam e ham, além de identificar emails que se desviam do padrão normal, caracterizando-os como anomalias. A classificação de emails é uma tarefa importante para garantir a segurança e a organização de caixas de entrada, enquanto a detecção de anomalias pode auxiliar na identificação de emails maliciosos ou suspeitos.

## Metodologia

O projeto foi desenvolvido seguindo as seguintes etapas:

1.  **Coleta e Pré-processamento de Dados:** Os dados foram coletados de fontes de dados públicas e privadas. Em seguida, foi realizado o pré-processamento dos dados, incluindo limpeza, tratamento de valores faltantes, remoção de ruídos e tokenização.

2.  **Engenharia de Atributos:** Foram criados atributos relevantes para a classificação de emails, como frequência de palavras, presença de caracteres especiais, tamanho do email, entre outros.

3.  **Treinamento dos Modelos:** Os modelos LSTM, Naive Bayes e SVM foram treinados utilizando os dados pré-processados e os atributos de engenharia. Foi utilizada a técnica de validação cruzada para otimizar os parâmetros dos modelos e garantir a generalização.

4.  **Avaliação dos Modelos:** Os modelos foram avaliados utilizando métricas de desempenho, como acurácia, precisão, recall e F1-score. Os resultados obtidos demonstraram a eficácia dos modelos na classificação de emails.

5.  **Detecção de Anomalias:** O modelo GMM foi utilizado para identificar emails que se desviam do padrão normal. Foi definido um limiar de probabilidade para classificar emails como anomalias.

## Modelos Utilizados

### Classificação de Emails (Spam e Ham)

*   **LSTM (Long Short-Term Memory)**: Um tipo de rede neural recorrente capaz de aprender padrões em sequências de dados, como textos. O LSTM é adequado para tarefas de processamento de linguagem natural, como a classificação de emails.

*   **Naive Bayes**: Um algoritmo probabilístico simples e eficiente para classificação de textos. O Naive Bayes é baseado no teorema de Bayes e assume que as características de um email são independentes entre si.

*   **SVM (Support Vector Machine)**: Um algoritmo de aprendizado de máquina que busca encontrar o hiperplano que melhor separa as classes de emails (spam e ham) no espaço de características.

### Detecção de Anomalias

*   **GMM (Gaussian Mixture Model)**: Um modelo probabilístico que representa a distribuição de probabilidade de um conjunto de dados como uma soma de distribuições Gaussianas. O GMM é utilizado para identificar emails que não se encaixam no padrão normal, caracterizando-os como anomalias.

## Estrutura do Repositório

O repositório está organizado da seguinte forma:

*   **`data`**: Contém os conjuntos de dados utilizados para treinamento e teste dos modelos.
*   **`models`**: Contém os modelos de aprendizado de máquina treinados.
*   **`scripts`**: Contém os scripts em Python utilizados para pré-processamento dos dados, treinamento dos modelos, avaliação de desempenho e geração de resultados.
*   **`notebooks`**: Contém notebooks Jupyter com exemplos de uso dos modelos e análise dos resultados.
*   **`README.md`**: Este arquivo, com a descrição do projeto e instruções de uso.

Os resultados obtidos com os modelos de classificação e detecção de anomalias são apresentados nos notebooks Jupyter. Os modelos LSTM, Naive Bayes e SVM demonstraram bom desempenho na classificação de emails, com alta acurácia e precisão. O modelo GMM foi capaz de identificar anomalias em emails, auxiliando na detecção de mensagens suspeitas.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests com melhorias, correções ou novas funcionalidades.

