# 🐾 VetBot AI: Seu Assistente Virtual Inteligente para Triagem Veterinária Inicial (Projeto de Demonstração) ✨

**Bem-vindo ao Triagem Veterinária!** Um projeto inovador e educacional que explora o potencial da Inteligência Artificial do Google para auxiliar tutores de pets em momentos de aflição, oferecendo uma triagem inicial de sintomas.

[![Google Colab]https://colab.research.google.com/drive/1kRjS8KoXyMgjw-uMJGo-vcYTVFdvyVut?usp=sharing
---

## 🌟 O que este projeto faz?

O VetBot AI é um chatbot interativo desenvolvido em Python e executado no Google Colab, que utiliza a poderosa API Generativa do Google (com modelos como o Gemini) para:

* **Simular uma conversa de triagem:** Coleta informações básicas sobre o pet e seus sintomas.
* **Interação Inteligente:** Faz perguntas relevantes para entender melhor a situação.
* **Foco Educacional:** Demonstra como a IA pode ser aplicada para criar assistentes virtuais úteis.
* **⚠️ Promover a Responsabilidade:** Enfatiza **CONSTANTEMENTE** que **NÃO SUBSTITUI** a avaliação, o diagnóstico e o tratamento de um médico veterinário profissional.

Este projeto é uma excelente ferramenta para estudantes, desenvolvedores e entusiastas de IA interessados em:
* Desenvolvimento de Chatbots
* Aplicações de Modelos de Linguagem Grandes (LLMs)
* Inteligência Artificial na área da saúde (com as devidas ressalvas e foco educacional)
* Interação humano-máquina

---

## 🚀 Tecnologias Utilizadas

* **Python:** A linguagem de programação principal.
* **Google Colab:** Ambiente de notebook interativo para desenvolvimento e execução.
* **Google Generative AI (API do Gemini):** O cérebro por trás da inteligência conversacional do VetBot AI.
* **Markdown:** Para exibição formatada das mensagens no Colab.

---

## 🛠️ Pré-requisitos

Antes de mergulhar, você vai precisar de:

1.  **Uma Conta Google:** Para acessar o Google Colab e o Google AI Studio.
2.  **Uma API Key do Google AI Studio:**
    * Vá para [Google AI Studio](https://aistudio.google.com/app/apikey).
    * Crie um novo projeto (ou use um existente).
    * Gere uma nova API Key. Mantenha-a em segurança!
3.  **Navegador da Web:** Chrome, Firefox, etc.

---

## ⚙️ Como Configurar e Executar o VetBot AI 

Siga estes passos simples para colocar o VetBot AI em funcionamento:

1.  **Abra no Google Colab:**
    * Clique no emblema "Open in Colab" no topo deste README (depois de adicionar o link do seu notebook!) ou copie e cole o código Python em um novo notebook do Colab.

2.  **Instale as Dependências:**
    * A primeira célula do notebook contém o comando:
        ```python
        !pip install -q google-generativeai
        ```
    * Execute esta célula para instalar a biblioteca necessária.

3.  **Configure sua API Key (MUITO IMPORTANTE):**
    * No painel à esquerda do Colab, clique no ícone de **chave (🔑) chamado "Secrets"**.
    * Clique em **"+ Add a new secret"**.
    * **Nome do Secret:** `GOOGLE_API_KEY` (exatamente assim, sensível a maiúsculas e minúsculas).
    * **Valor do Secret:** Cole a sua API Key que você obteve do Google AI Studio.
    * **Habilite "Notebook access"** para este secret.
    * *Esta é a maneira mais segura de usar sua API Key no Colab, evitando expô-la diretamente no código.*

4.  **Execute o Código do Chatbot:**
    * Após configurar o secret, execute a célula principal que contém o código do chatbot.

5.  **Interaja com o VetBot AI **
    * O chatbot iniciará a conversa no console de saída da célula. Responda às perguntas para simular a triagem.
    * Para encerrar, digite `sair`, `fim` ou `tchau`.

---

## ⚠️ **AVISO MUITO IMPORTANTE!** ⚠️

Este projeto é estritamente para **FINS EDUCACIONAIS E DE DEMONSTRAÇÃO**.

* 🐶 **NÃO SUBSTITUI UM VETERINÁRIO:** O VetBot AI  **NÃO** é um profissional de saúde veterinária. As informações e sugestões fornecidas são baseadas em um modelo de linguagem e **NÃO CONSTITUEM UM DIAGNÓSTICO MÉDICO**.
* 🐱 A saúde do seu pet é séria! Se você tem preocupações sobre o bem-estar do seu animal de estimação, **PROCURE IMEDIATAMENTE UM MÉDICO VETERINÁRIO QUALIFICADO.**
* 🚨 **NÃO UTILIZE ESTE CHATBOT PARA DECISÕES MÉDICAS REAIS.**

---

## 💡 Ideias para Evolução Futura

Este é apenas o começo! Algumas ideias para expandir e melhorar o VetBot AI:

* **Integração com Dialogflow CX:** Para fluxos de conversa mais complexos, gerenciamento de estado e integrações mais ricas.
* **Base de Conhecimento Veterinário:** Conectar a uma base de dados estruturada (desenvolvida e validada por veterinários) para informações mais específicas.
* **Interface Gráfica:** Desenvolver uma interface web mais amigável usando Streamlit ou Flask.
* **Níveis de Urgência:** Implementar uma lógica mais sofisticada para classificar a urgência dos sintomas (sempre com o aviso de consulta veterinária).
* **Multi-idiomas:** Tornar o VetBot AI acessível para mais tutores.

---

## 🤝 Contribuições

Sinta-se à vontade para fazer um fork deste projeto, experimentar e melhorá-lo! Se tiver ideias ou correções, abra uma *issue* ou um *pull request* (se estiver em uma plataforma como o GitHub).

---

## 📄 Licença

Este projeto é distribuído sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes (se aplicável, ou adicione uma seção de licença se desejar).

---

**Divirta-se explorando o mundo da IA com o VetBot AI ! E lembre-se: cuide bem dos seus amigos de quatro patas consultando sempre um veterinário!** 🐕❤️🐈
