# Atividade 01

1. O que é machine learning

- Machine learning (aprendizado de máquina) é um ramo da inteligência artificial que permite que sistemas aprendam padrões e façam previsões ou decisões a partir de dados, sem serem programados especificamente para cada tarefa. O modelo “treina” com exemplos e ajusta seus parâmetros para melhorar o desempenho.

2. Conjunto de treinamento, validação e teste

- Treinamento: usado para ensinar o modelo, ajustando seus parâmetros com base nos exemplos.
- Validação: serve para avaliar o modelo durante o processo de treinamento e ajudar a escolher os melhores parâmetros.
- Teste: conjunto separado, utilizado apenas no final, para medir o desempenho real do modelo em dados que ele nunca viu antes.

3. Dados ausentes

- Dependendo dos dados e do projeto poderia excluir linhas ou colunas com muitos valores faltantes (se não forem cruciais). Também poderia substituir valores ausentes por média, mediana ou moda. A escolha depende da quantidade de dados ausentes e da importância das variáveis.

4. Matriz de confusão

- É uma tabela que compara as previsões do modelo com os valores reais:

|            | Previsto Positivo | Previsto Negativo |
|------------|-------------------|-------------------|
| Real Positivo | Verdadeiro Positivo (VP) | Falso Negativo (FN) |
| Real Negativo | Falso Positivo (FP) | Verdadeiro Negativo (VN) |

- Com ela calculamos as métricas:

  - Acurácia: proporção de acertos.
  - Precisão: entre os positivos previstos, quantos estavam corretos.
  - Recall (sensibilidade): entre os positivos reais, quantos foram identificados.
  - F1-score: equilíbrio entre precisão e recall.

5. Alguns exempls de áreas de aplicação

- Saúde: diagnóstico precoce de doenças, análise de imagens médicas, medicina personalizada.
- Construção civil: manutenção preditiva de máquinas, análise de riscos em projetos, otimização de cronogramas.
- Transporte e logística: rotas inteligentes, previsão de demanda, manutenção preditiva de veículos.
