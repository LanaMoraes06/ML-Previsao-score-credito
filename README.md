# Inteligência Artificial: Previsão de Score de Crédito 🤖📊

Este projeto de **Machine Learning** foi desenvolvido para resolver um problema real de negócios: automatizar a análise de crédito de clientes de um banco. O modelo de Inteligência Artificial analisa o histórico financeiro dos clientes e prevê automaticamente o seu Score de Crédito (Ruim, Ok ou Bom).

## 🚀 Tecnologias e Bibliotecas Utilizadas

* **Python**
* **Jupyter Notebook** (Ambiente de desenvolvimento)
* **Pandas** (Para manipulação e análise de dados)
* **Scikit-Learn** (Para criação e treinamento dos modelos de Machine Learning)

## 📁 Estrutura do Projeto

* `inicial.ipynb`: O notebook principal contendo todo o passo a passo da Análise de Dados, pré-processamento, treinamento dos modelos e previsões finais.
* `clientes.csv`: A base de dados histórica contendo as informações financeiras de milhares de clientes (usada para treinar e testar a IA).
* `novos_clientes.csv`: Uma base de dados inédita simulando novos clientes que o banco precisa avaliar usando o modelo treinado.

## ⚙️ Como a IA Funciona (Pipeline do Projeto)

1. **Importação e Tratamento de Dados:** Leitura da base de dados e tratamento de valores vazios.
2. **Pré-Processamento (Label Encoding):** Transformação de variáveis em formato de texto (como a "profissão" do cliente) em números, para que os modelos matemáticos da IA possam compreendê-los.
3. **Divisão de Treino e Teste:** Separação da base de dados (x e y) para treinar a inteligência artificial e testar sua precisão depois.
4. **Treinamento dos Modelos:** Foram testados dois algoritmos clássicos de classificação:
   * *Árvore de Decisão (Decision Tree / Random Forest)*
   * *K-Nearest Neighbors (KNN)*
5. **Avaliação (Accuracy):** O modelo baseado em Árvores de Decisão (Random Forest) obteve a melhor acurácia (aproximadamente 82%) e foi o escolhido.
6. **Previsão em Novos Dados:** O modelo vencedor foi aplicado na tabela `novos_clientes.csv` para prever os scores de crédito de forma 100% automática.

## 🛠️ Como Executar na Sua Máquina

Para rodar este notebook localmente, você precisará ter o Python instalado junto com as bibliotecas essenciais de Data Science.

Abra o terminal e instale as dependências:
```bash
pip install pandas scikit-learn jupyter
```

Abra o terminal e instale as dependências:
```bash
pip install pandas scikit-learn jupyter
