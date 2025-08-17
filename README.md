# Resumo do Projeto: Classificador de Imagens com Transfer Learning
### Este projeto tem como objetivo demonstrar a eficácia do 'transfer learning' (aprendizado por transferência) na criação de um classificador de imagens preciso, mesmo com um número relativamente pequeno de amostras de treinamento. A metodologia compara duas abordagens:

### Treinamento a Partir do Zero: Um modelo de rede neural convolucional (CNN) simples foi construído e treinado do zero usando o conjunto de dados. O objetivo foi estabelecer uma linha de base de desempenho para comparação.

### Transfer Learning com VGG16: Uma rede neural VGG16, pré-treinada no conjunto de dados ImageNet, foi utilizada como base para o novo modelo. A camada final de classificação original da VGG16 foi substituída por uma nova camada, adaptada para o nosso conjunto de dados, e apenas essa nova camada foi treinada.

# Principais Resultados
### Modelo Treinado do Zero: Atingiu uma precisão de teste de aproximadamente 40%.

### Modelo com Transfer Learning: Atingiu uma precisão de teste de aproximadamente 71%.

### A comparação demonstra uma melhoria significativa de mais de 30% na precisão, validando o poder do 'transfer learning' para tarefas de classificação de imagens com dados limitados.

# Conceitos Chave
### Transfer Learning: O processo de utilizar o conhecimento aprendido por um modelo em um novo modelo.

### Extração de Características: Utiliza-se as camadas de um modelo pré-treinado como extratores de características fixos, treinando apenas uma nova e menor rede neural.

### Fine-Tuning: Ajusta-se as camadas finais de um modelo pré-treinado juntamente com uma nova camada de classificação, geralmente com uma taxa de aprendizado menor.
