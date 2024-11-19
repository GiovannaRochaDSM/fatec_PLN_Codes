## **fatec_PLN_Codes**
Este repositório é organizado em aulas práticas que abordam conceitos fundamentais e avançados de processamento de linguagem natural. Cada aula contém exemplos detalhados com implementações práticas para aprendizado e aplicação em projetos reais. 

### **Divisões das Aulas**
1. **Aula 01 e 02:** Introdução à sintaxe com spaCy.
2. **Aula 03:** Uso de NLTK e análise de corpora.
3. **Aula 04:** Técnicas de limpeza e pré-processamento textual.
4. **Aula 05:** Vetorização de texto com Bag of Words e TF-IDF.
5. **Aula 06:** Representação de palavras com Word2Vec e GloVe.

---

### Instruções
Para executar os códigos:

- Abrir os arquivos no Google Colab com o botão "Open in Colab".
- Faça uma cópia, e em cada linha de código, clique no botão de executar em cada bloco de código.


# Índice de Conteúdo

## **Aula 01 e 02 - Sintaxe**
### **Prática 1: Segmentação, Tokenização e Árvore de Dependência**
- Demonstração de análise sintática em diferentes idiomas utilizando modelos pré-treinados do spaCy.
  - Idiomas: Português, Inglês, Espanhol, Francês e Alemão.
- Explicação sobre os modelos pré-treinados:
  - Tamanhos: **Pequeno (sm)**, **Médio (md)** e **Grande (lg)**.
  - Como funcionam, como são treinados e suas vantagens.

---

## **Aula 03 - Bibliotecas e Corpora**
### **Prática 1: Utilização da Biblioteca NLTK**
- Exemplo de uso da biblioteca NLTK para trabalhar com corpora e categorias de texto.

### **Exemplo 2: Contagem de Palavras**
- Cálculo da frequência de palavras em um corpus específico (exemplo: categoria "notícias" do corpus Brown).

### **Exemplo 3: Eliminação de Palavras Irrelevantes**
- Discussão sobre stopwords e sua remoção para melhorar a análise textual.

### **Exemplo 4: Tokenização com NLTK**
- **Forma 1:** `word_tokenize` para dividir texto em palavras.
- **Forma 2:** `Twitter tokenize` para lidar com texto de mídias sociais.

---

## **Aula 04 - Limpeza de Dados Textuais**
### **4.1 Normalização e Remoção de Ruído**
- Técnicas para remover caracteres especiais e uniformizar o uso de maiúsculas e minúsculas.

### **4.2 Tokenização**
- Divisão de texto em tokens menores (palavras e pontuações).

### **4.3 Remoção de Stopwords**
- Exclusão de palavras irrelevantes para simplificação do texto.

### **4.4 Stemming e Lematização**
- **Stemming:** Reduz palavras aos seus radicais.
- **Lematização:** Normaliza palavras considerando o contexto gramatical.

### **4.5 Aplicação Prática**
- Integração de todas as técnicas de pré-processamento vistas na aula.

---

## **Aula 05 - Bag of Words (BoW)**
### **Exemplo 1: Vetorização de Texto com CountVectorizer**
- Demonstração de criação de matrizes de frequência com BoW.

### **Exemplo 2: Vetorização com BoW e TF-IDF**
- Uso de TF-IDF para aprimorar a representação textual.

### **Exemplo 3: Pré-processamento Completo**
- Combinação de tokenização, remoção de stopwords e lematização antes da vetorização.

---

## **Aula 06 - Representação de Palavras**
### **Word2Vec**
- Introdução à técnica de representação de palavras baseada em vetores contínuos.

### **GloVe (Global Vectors for Word Representation)**
- Explicação sobre GloVe e sua aplicação para capturar relações semânticas entre palavras.
