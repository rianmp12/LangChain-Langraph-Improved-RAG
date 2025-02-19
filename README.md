# RAG Melhorado com LangChain e LangGraph

Este projeto implementa um **Retrieval-Augmented Generation (RAG) melhorado**, utilizando LangChain e LangGraph para criar um fluxo estruturado que busca fornecer respostas mais precisas e relevantes.

## 📌 Objetivo

A proposta deste projeto é criar um **RAG mais eficiente**, onde o fluxo de obtenção de informações é aprimorado por meio de **LangGraph**. A abordagem permite estruturar a lógica de recuperação e geração de respostas em **fluxogramas**, garantindo maior controle e refinamento na busca de informações.

## 🛠 Tecnologias Utilizadas

- **Python** 
- **LangChain**
- **LangGraph**
- **Ollama** (ou outro LLM compatível)
- **FAISS**

## 📂 Estrutura do Projeto

O notebook segue um fluxo estruturado para construir o RAG aprimorado:

1. **Configuração Inicial**: Importação das bibliotecas necessárias.
2. **Definição do Fluxo no LangGraph**: Implementação da estrutura do pipeline de recuperação e geração de respostas.
3. **Configuração do Modelo**: Integração com LLM Ollama.
4. **Integração com FAISS**: Para indexação e busca de documentos.
5. **Execução do Pipeline**: Testes e avaliação das respostas geradas.

## 🚀 Como Utilizar

### 1️⃣ Instale as Dependências

Antes de executar o notebook, instale as bibliotecas necessárias que se encontram no próprio notebook.

### 2️⃣ Instale e Configure o Ollama
Este projeto utiliza **Ollama** para rodar modelos localmente. Siga os passos abaixo:

1. Baixe e instale o Ollama seguindo as instruções do site oficial: [ollama.com](https://ollama.com)
2. Baixe os modelos necessários executando os comandos abaixo:
    
    ```bash
    ollama pull llama3
    ollama pull llama3:3.1
    ```
3. Certifique-se de que o servidor do Ollama está rodando antes de executar o notebook.
    

### 3️⃣ Execute o Notebook

Basta rodar as células do notebook para testar o fluxo.

## 🧠 Modelos Utilizados

Este projeto utiliza **modelos do Ollama**, comparando os resultados com o uso de uma única LLM do Ollama.
O objetivo é verificar se essa abordagem gera respostas mais precisas e coerentes.

## 📌 Considerações Finais

Este projeto demonstra como um **RAG pode ser melhorado utilizando LangGraph**, criando um fluxo estruturado e refinando a geração de respostas. Você pode personalizar a abordagem integrando novos **LLMs, bases de dados vetoriais e regras de fluxo**.
