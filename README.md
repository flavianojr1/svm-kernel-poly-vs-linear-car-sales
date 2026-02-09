# Classificação de Clientes para Propensão à Compra de Carros: SVM Kernel Polinomial vs Linear

## 📝 Descrição
Projeto desenvolvido como parte do curso de Data Science da EBAC (Escola Britânica de Artes Criativas e Tecnologia), demonstrando a aplicação de Support Vector Machines (SVM) com diferentes kernels para classificação de clientes quanto à propensão de compra de carros.

## 🎯 Objetivo
O objetivo deste projeto é comparar o desempenho de diferentes kernels do algoritmo SVM (Support Vector Machine) na classificação de clientes baseado em características como gênero, idade e salário anual, para prever a probabilidade de compra de um carro. O foco principal é analisar as diferenças entre os kernels Polinomial e Linear.

## 🛠️ Tecnologias Utilizadas
- Python 3.x
- Scikit-learn
- Pandas
- NumPy
- Matplotlib/Seaborn
- Jupyter Notebook

## 📋 Estrutura do Projeto
```
svm-kernel-poly-vs-linear/
├── CARRO_CLIENTES.csv       # Conjunto de dados original
├── MOD40_EXERCICIO.ipynb    # Notebook com a análise e modelo
├── README.md                # Este arquivo
└── requirements.txt         # Dependências do projeto
```

## 📊 Resultados
O modelo SVM com kernel linear apresentou os seguintes resultados:

- **Acurácia**: 81.33%
- **Precisão**:
  - Classe 0 (Não comprou): 81%
  - Classe 1 (Comprou): 82%
- **Recall**:
  - Classe 0: 88%
  - Classe 1: 72%
- **F1-Score**:
  - Classe 0: 84%
  - Classe 1: 77%

### Matriz de Confusão
```
[[152  20]
 [ 36  92]]
```

## 🎯 Conclusões

1. O modelo SVM com kernel linear demonstrou bom desempenho na classificação de clientes quanto à propensão de compra de carros, com uma acurácia geral de 81.33%.

2. A análise da matriz de confusão mostra que o modelo é ligeiramente melhor em identificar corretamente os clientes que não compraram (classe 0) em comparação com os que compraram (classe 1).

3. A precisão equilibrada entre as duas classes (81% e 82%) indica que o modelo não apresenta viés significativo para nenhuma das classes.

4. O recall mais alto para a classe 0 (88%) em comparação com a classe 1 (72%) sugere que o modelo é mais eficaz em identificar corretamente os clientes que não compraram.

5. Estes resultados podem ser utilizados para direcionar campanhas de marketing mais eficazes, focando nos clientes com maior probabilidade de compra.

## 🚀 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/svm-kernel-poly-vs-linear.git
   cd svm-kernel-poly-vs-linear
   ```

2. Crie e ative um ambiente virtual (recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: .\venv\Scripts\activate
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Abra o notebook desejado na pasta `notebooks/`.

## 📝 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 🙏 Agradecimentos
- EBAC - Escola Britânica de Artes Criativas e Tecnologia
- Professores e colegas do curso de Data Science
