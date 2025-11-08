# 🧬 CNN para Caracterização de Padrões de Pigmentação Sintética

Este repositório contém os notebooks desenvolvidos no **Google Colab** durante a elaboração do Trabalho de Conclusão de Curso (TCC) intitulado *“Uso de Redes Neurais Convolucionais para a Caracterização Supervisionada de Padrões de Pigmentação Sintéticos”*.

O projeto investiga o uso de **redes neurais convolucionais (CNNs)** para identificar e classificar padrões visuais gerados a partir do **modelo de reação–difusão de Gray–Scott**, utilizando aprendizado supervisionado.

O modelo proposto realiza a predição dos parâmetros de reação (*ratio* e *scale*) com base em imagens sintéticas de 32×32 pixels, avaliando métricas de desempenho como **acurácia**, **precisão**, **revocação** e **F1-score**.

---

### 🧩 Estrutura do repositório

- [dataset_generator.ipynb](https://colab.research.google.com/drive/1ELJc6pnwt7w5MDftZ37YnKOuTTsvD4SW?usp=sharing) → geração e preparação do conjunto de dados sintético  
- [criação_do_modelo.ipynb](https://colab.research.google.com/drive/1NRBF8RkJz7tiKA7_fBeluYGZBQ4cR8Za?usp=sharing) → definição da arquitetura e treinamento da CNN  
- [experimentação.ipynb](https://colab.research.google.com/drive/1NLbn7FcLfvlwEpQlrCqAyqaMTkd0wYEG?usp=sharing) → análise dos resultados, curvas de aprendizado e métricas  

---

### 🧠 Tecnologias e bibliotecas utilizadas

- Python 3.x  
- TensorFlow / Keras  
- NumPy e Matplotlib  
- Scikit-learn

### 📚 Referências principais

- GOODFELLOW, Ian; BENGIO, Yoshua; COURVILLE, Aaron. *Deep Learning.* MIT Press, 2016.  
- KIRANYAZ, Serkan et al. *A Review of 1D Convolutional Neural Networks toward Unknown Signal Classification.* arXiv preprint arXiv:1905.03554, 2019.  

---

📄 **Autor:** Leonardo Vinicius Ribeiro  
📘 **Instituição:** Oderco / TCC - 2025  
