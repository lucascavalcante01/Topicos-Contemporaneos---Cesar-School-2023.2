# Projeto Final

## 1. Fine-Tuning de uma CNN para Classificação

Um dataset de sua escolha deverá ser coletado e preparado para realizar o fine-tuning de uma CNN. O projeto será avaliado nos seguintes aspectos:
- Construção do Dataset
- Data Augmentation
- Uso de Modelos Pré-Treinados
- Construção do Modelo Classificador
- Congelamento de Camadas
- Treinamento e Curvas de Desempenho

>Para este projeto, utilizou-se uma base de dados de imagens de raios-X pulmonares disponível no [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/data) para a classificação de pneumonia. O problema foi abordado utilizando __Transfer Learning__ com a rede ResNet50.

## 2. Construção de um RAG utilizando LangChain

Deverá ser desenvolvido um sistema RAG (Retrieval-Augmented Generation) utilizando a biblioteca LangChain para um ou mais documentos de sua escolha. Podendo ser arquivos PDF, de texto, páginas da web etc. O projeto será avaliado nos seguintes aspectos:
- Escolha do Documento
- Splitting do Documento
- Criação de Vector Store
- Retrieval
- Geração de Respostas

>Para este projeto, foi implementado um sistema de Perguntas e Respostas (RAG - Retrieval-Augmented Generation) utilizando o livro de Provérbios da Bíblia Sagrada em português brasileiro. O objetivo é construir um pipeline que permita recuperar trechos relevantes do livro para responder a perguntas específicas, utilizando a biblioteca LangChain e o modelo GPT-4o.
