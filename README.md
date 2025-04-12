
# 🧠 Previsão de Score de Crédito com Machine Learning

Este projeto foi desenvolvido como parte do meu processo de aprendizado no curso de Python e Inteligência Artificial da **Hashtag Treinamentos**. O objetivo principal foi aplicar conceitos de Machine Learning supervisionado para prever o **score de crédito** de clientes — classificando-os como **Ruim**, **Ok** ou **Bom**.

A proposta é simular um cenário real, em que um banco precisa automatizar a análise de risco de seus clientes com base em dados como profissão, histórico de pagamentos e mix de crédito.

---

## 🚀 Tecnologias Utilizadas

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Etapas do Projeto

1. **Importação e exploração inicial dos dados**
2. **Pré-processamento**: transformação de variáveis categóricas com `LabelEncoder`
3. **Divisão dos dados** em treino e teste
4. **Criação e treinamento de modelos** com `RandomForestClassifier` e `KNeighborsClassifier`
5. **Avaliação da performance dos modelos** com acurácia
6. **Aplicação prática** em uma nova base de clientes
7. **Análise de importância das variáveis** no modelo final

---

## 📈 Resultados

Durante os testes, o modelo baseado em **Árvore de Decisão (Random Forest)** obteve melhor desempenho do que o modelo de Vizinhos Mais Próximos (**KNN**), sendo escolhido como o modelo ideal para realizar as previsões.

---

## 📦 Como Executar Localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/Azaxhel/seu-repositorio.git
   ```

2. Instale as dependências:
   ```bash
   pip install pandas scikit-learn
   ```

3. Coloque os arquivos `clientes.csv` e `novos_clientes.csv` na mesma pasta do notebook.

4. Execute o notebook `score_credito_projeto_formatado.ipynb`.

---

## 💬 Observações Finais

Este projeto tem fins educacionais e foi feito com base em um conjunto de dados fictício. Mesmo assim, ele me ajudou bastante a entender na prática como funciona um fluxo completo de Machine Learning.

Sinta-se à vontade para deixar sugestões, dicas ou feedbacks — estou sempre buscando melhorar! 😄

---

## 📫 Contato

- [Meu GitHub](https://github.com/Azaxhel)
- [Meu LinkedIn](https://www.linkedin.com/in/enrique-linhares-683728330/)
