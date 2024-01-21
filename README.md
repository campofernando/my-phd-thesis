# my-phd-thesis
This repository contains the latex files for my PHD Thesis at LCQAr UFSC

## TO-DO:
1. Adicionar gráficos de leituras dos sensores vs. referência incluindo fator de 2 e densidade de Kernel
    - Estudar sobre o que essas métricas representam, densidade de Kernel indica frequência de ocorrência
2. Dividir melhor as tabelas de contabilização dos dados (adicionar linha vertical entre dados 15 mins e dados horários)
3. Incluir tratamento de NO2 e SO2
4. Scatter plots
    - Reduzir o tamanho dos gráficos
    - Adicionar densidade de Kernel
    - Manter a mesma escala nos eixos X e Y
5. Mudar a cor (para cinza) dos intervalos que foram descartados nos gráficos das séries temporais
6. Nos histogramas de O3 e CO explicar que é possível visualizar dois padres no O3 e no CO, alta emissão durante o dia e baixa emissão à noite, madrugada. No caso do ozônios é pela radiação, que coincide com a temperatura
7. Nos dados de MP explicar que foram melhores pq é um sensor digital
8. Melhoras as tabelas de resumo de desempenho dos modelos, as colunas estão muito apertadas
9. Fixar as escalas dos gráficos de desempenho dos modelos
    - Escala fixa -1 a 1 no R2
    - Escala fixa de 0 a um valor máximo no RMSE
10. Nas figuras:
    - Legendas e descrição bem detalhadas, deve ser possível olhar a figura e entender tudo
    - Remover Fonte: Criado pelo autor
11. Sobre o capítulo do processamento dos dados:
    - Separar em dois capítulos: Metodologia de pré-processamento e Metodologia de calibração
    - No capítulo da calibração separar entre "univariada" e multivariada
12. Incluir AIC e BIC que estima o erro modelos considerando o numero de covariaveis, utilizar eles para determinar melhor modelo, não usar R2
13. Incluir fluxogramas:
    - Fluxograma da calibração em campo, equipamentos que tem lá, quanto tempo, quantas horas de coleta, nossa proposta é parear
    - Incluir fluxograma da metodologia de pré-processamento e calibração
14. Adicionar figuras de compilação com o melhor modelo para cada sensor, o modelo usado, as variáveis, scatters do Léo
15. Adicionar rascunho do segundo paper nos Anexos (Opcional)
    - No paper ir direto para a multivariada
16. Explicar no resumo que estamos propondo metodologia de correção com equipamento, mesmo não sendo boa