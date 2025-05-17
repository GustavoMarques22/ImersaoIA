# Imersão em Inteligência Artificial com Gemini

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GustavoMarques22/ImersaoIA/blob/main/ImersaoIA.ipynb)

Este repositório contém um notebook do Google Colaboratory que demonstra a interação com a API do Gemini através da biblioteca `google-genai`. O objetivo principal é explorar as capacidades de modelos de linguagem para diversas tarefas, como responder a perguntas, manter conversas e até mesmo adaptar o estilo de resposta.

## Conteúdo do Notebook

O notebook `ImersaoIA.ipynb` inclui as seguintes seções:

* **Instalação da biblioteca `google-genai`:** Demonstra como instalar a biblioteca necessária para utilizar os modelos Gemini.
* **Autenticação e configuração da chave de API:** Explica como configurar a chave da API do Google Cloud para autenticação.
* **Listagem de modelos disponíveis:** Mostra como listar os diferentes modelos Gemini disponíveis para uso.
* **Geração de texto com um modelo específico (`gemini-2.0-flash`):**
    * Exemplo de pergunta direta e obtenção de uma resposta informativa.
* **Criação e interação em uma sessão de chat:**
    * Demonstra como iniciar uma conversa com o modelo.
    * Exemplos de perguntas e respostas em um contexto de diálogo.
* **Personalização do comportamento do chat através de `system_instruction`:**
    * Exemplo de como instruir o modelo a fornecer respostas claras e sucintas.
* **Histórico do chat:** Mostra como acessar o histórico das conversas.
* **Criação de um loop interativo para receber prompts do usuário:** Permite que o usuário interaja continuamente com o modelo.
* **Adaptação do estilo de resposta (sotaque Goiano/Mineiro):** Demonstra como usar o `system_instruction` para influenciar o estilo da resposta do modelo.

## Como Usar

1.  **Abrir no Colab:** Clique no badge "Open in Colab" acima para abrir o notebook diretamente no Google Colaboratory.
2.  **Configurar a chave da API:** Siga as instruções no notebook para configurar sua chave da API do Google Cloud como um segredo do usuário no Colab.
3.  **Executar as células:** Execute as células do notebook em sequência para ver os exemplos em funcionamento.
4.  **Experimentar:** Modifique as perguntas e as instruções do sistema para explorar diferentes capacidades e comportamentos dos modelos Gemini.

## Requisitos

* Conta Google
* Acesso ao Google Colaboratory
* Uma chave de API do Google Cloud com acesso aos modelos Gemini (pode ser necessário se inscrever no Google AI Studio).

## Contribuição

Se você tiver alguma sugestão de melhoria ou quiser adicionar mais exemplos a este notebook, sinta-se à vontade para criar um fork deste repositório e enviar um pull request.

## Autor

[Gustavo Marques] ([GitHub]:(https://github.com/GustavoMarques22))

---
