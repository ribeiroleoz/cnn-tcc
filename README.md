# 🧬 CNN para Caracterização de Padrões de Pigmentação Sintética

Este repositório contém os notebooks desenvolvidos no **Google Colab** durante a elaboração do Trabalho de Conclusão de Curso (TCC) intitulado *“Uso de Redes Neurais Convolucionais para a Caracterização Supervisionada de Padrões de Pigmentação Sintéticos”*.

O projeto investiga o uso de **redes neurais convolucionais (CNNs)** para identificar e classificar padrões visuais gerados a partir do **modelo de reação–difusão de Gray–Scott**, utilizando aprendizado supervisionado.

O modelo proposto realiza a predição dos parâmetros de reação (*ratio* e *scale*) com base em imagens sintéticas de 32×32 pixels, avaliando métricas de desempenho.

---

### 🧩 Estrutura do repositório

- [dataset_generator.ipynb](https://colab.research.google.com/drive/1ELJc6pnwt7w5MDftZ37YnKOuTTsvD4SW?usp=sharing) → geração e preparação do conjunto de dados sintético  
- [model.ipynb](https://colab.research.google.com/drive/1NRBF8RkJz7tiKA7_fBeluYGZBQ4cR8Za?usp=sharing) → definição da arquitetura, treinamento da CNN e avaliação das curvas de aprendizado e métricas  
- [tests.ipynb](https://colab.research.google.com/drive/1NLbn7FcLfvlwEpQlrCqAyqaMTkd0wYEG?usp=sharing) → experimentação do modelo em imagens reais

---

### 🧠 Tecnologias e bibliotecas utilizadas

- Python 3.x  
- TensorFlow / Keras  
- NumPy e Matplotlib  
- Scikit-learn
