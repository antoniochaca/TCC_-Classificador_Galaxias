# 🌌 Classificação Automatizada de Morfologia de Galáxias usando Deep Learning

> **Trabalho de Conclusão de Curso (TCC)**  
> **Autor:** Antônio Pedro Chacarosque de Castro  
> **Curso:** Engenharia de Computação — Universidade Federal de Santa Catarina (UFSC)  

---

## 📌 Visão Geral do Projeto

A classificação morfológica de galáxias é um pilar fundamental da astrofísica moderna para compreender a formação e a evolução do universo. Com o volume massivo de dados gerados por grandes levantamentos astronômicos (como o *Sloan Digital Sky Survey - SDSS*), o processo de classificação manual torna-se inviável.

Este repositório contém o código-fonte, scripts de pré-processamento, experimentos e a documentação completa do projeto de TCC dedicado a automatizar a classificação de imagens de galáxias utilizando arquiteturas de Aprendizado Profundo (*Deep Learning*), comparando redes convolucionais consolidadas (**AlexNet** e **ResNet**).

---

## 🛠️ Tecnologias e Dependências

O projeto foi desenvolvido em Python utilizando as seguintes ferramentas principais:

* **Linguagem:** Python 3.8+
* **Frameworks de Deep Learning:** PyTorch / TensorFlow
* **Processamento de Imagens:** OpenCV, Pillow, scikit-image
* **Análise e Manipulação de Dados:** NumPy, Pandas, scikit-learn
* **Visualização de Dados:** Matplotlib, Seaborn
* **Ambiente de Desenvolvimento:** Jupyter Notebook / Visual Studio Code

---

## 📂 Estrutura do Repositório

```text
.
├── classes/          # Definições das arquiteturas de redes e loaders de datasets
├── codigo/           # Scripts de treinamento, avaliação e pré-processamento de imagens
├── docs/             # Artigo final, relatórios e recursos gráficos
│   └── imagens/      # Figuras, gráficos e matrizes de confusão
├── notebooks/        # Notebooks Jupyter para análise exploratória e testes
├── .gitignore        # Arquivos e pastas ignorados pelo controle de versão
├── LICENSE           # Licença de uso do código
└── README.md         # Documentação principal do projeto
