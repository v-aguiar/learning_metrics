# Projeto de Avaliação de Métricas MNIST

Este projeto demonstra como treinar uma rede neural convolucional (CNN) usando o conjunto de dados MNIST e avaliá-la utilizando métricas importantes de classificação, como acurácia, precisão, recall, F1-score e a curva ROC.

O treinamento e a avaliação são realizados diretamente no Google Colab, facilitando o uso sem a necessidade de configurar um ambiente local.

## Executando o Projeto no Google Colab

### Passos para utilização:

1. **Acesse o Notebook no Colab:**
   Abra o arquivo `learning_metrics_cf_matrix.ipynb` diretamente no Google Colab ou clique [aqui](https://colab.research.google.com/drive/1w-6x5e5Ek_B6jTAuNjPH47FC5xiPylp9?usp=sharing).

2. **Configure o ambiente no Colab:**
   O notebook já contém todo o código necessário para configurar o ambiente e instalar as dependências automaticamente.

3. **Execute as células do notebook:**
   - Carregue o conjunto de dados MNIST.
   - Treine o modelo de CNN.
   - Calcule métricas como acurácia, precisão, recall, F1-score e curva ROC.
   - Visualize a matriz de confusão e a curva ROC.

## Exemplos de Saída do Projeto

### Matriz de Confusão

A matriz de confusão é gerada após o treinamento para avaliar as previsões do modelo:

![image](https://github.com/user-attachments/assets/1a35b510-f840-4c94-9932-31beae704f38)

### Curva ROC

A curva ROC e as respectivas áreas sob a curva (AUC) são plotadas para cada classe:

![image](https://github.com/user-attachments/assets/2bba1c8c-2af3-46f6-8ad3-cf31ac5daa8a)

## Métricas Calculadas

As seguintes métricas de avaliação são geradas automaticamente:

- **Acurácia**: Mede a proporção de previsões corretas.
- **Precisão**: Calcula a proporção de positivos previstos que são realmente positivos.
- **Recall (Sensibilidade)**: Mede a capacidade do modelo em identificar todos os positivos reais.
- **F1 Score**: Média harmônica entre precisão e recall.
- **Curva ROC e AUC**: Avalia a performance do modelo em diferentes thresholds.

![image](https://github.com/user-attachments/assets/759f8291-2e92-4208-acfe-64351c908353)

## Contribuições

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões, abra uma issue ou envie um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para mais detalhes.

## Autor

[Victor Aguiar](https://github.com/v-aguiar)
