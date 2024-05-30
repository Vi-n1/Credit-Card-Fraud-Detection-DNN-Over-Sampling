# Detecção de Fraude em Cartões de Crédito com Redes Neurais Profundas e Oversampling

## Visão Geral
Este projeto se concentra na detecção de fraudes em transações de cartões de crédito usando Redes Neurais Profundas (DNN) em combinação com técnicas de oversampling para lidar com dados desbalanceados. O objetivo é identificar transações fraudulentas com alta precisão utilizando métodos avançados de aprendizado de máquina.

## Conjunto de Dados
O conjunto de dados contém transações de cartões de crédito rotuladas como fraudulentas ou não. Devido à baixa proporção de fraudes, técnicas de balanceamento são necessárias para um treinamento eficaz do modelo.

## Metodologia
A metodologia empregada inclui várias etapas de pré-processamento de dados, como normalização e oversampling com SMOTE para gerar um conjunto de dados balanceado. Diferentes modelos de aprendizado de máquina são então treinados e avaliados.

### Passos:
1. **Pré-processamento**: Limpeza e normalização dos dados.
2. **Oversampling**: Aplicação do SMOTE para aumentar a representatividade das transações fraudulentas.
3. **Treinamento do Modelo**: Uso de uma DNN para aprendizado e classificação.
4. **Avaliação**: Métricas como precisão, F1 score, recall, AUC e matriz de confusão são utilizadas para avaliar o desempenho do modelo.

### Modelos Utilizados
Além da Rede Neural Profunda (DNN), foram testados outros modelos para fins de comparação:
- **Naive Bayes**: Um modelo probabilístico simples para classificação binária.
- **Regressão Logística**: Modelo linear amplamente utilizado para classificação binária.
- **Floresta Aleatória**: Conjunto de árvores de decisão que melhora a precisão e reduz o overfitting.

## Resultados
Os resultados mostram que a combinação de DNN com oversampling melhora significativamente a detecção de fraudes em comparação com métodos tradicionais. As métricas de desempenho indicam uma alta taxa de precisão e recall, destacando a eficácia do modelo.

## Conclusão
O projeto demonstra a viabilidade e eficácia do uso de técnicas avançadas de aprendizado de máquina para detecção de fraudes em cartões de crédito. Embora promissor, este projeto é destinado a fins educacionais e de pesquisa e não deve ser implementado em sistemas de produção.

Para mais detalhes, consulte o [notebook do projeto](https://github.com/Vi-n1/Credit-Card-Fraud-Detection-DNN-Over-Sampling/blob/main/src/FraudDetection(DNN).ipynb).