# Assistente Virtual de Investimentos Financeiros - Bradesco
<br><br>
## 📄 Descrição

Link para o projeto que utiliza a API de Inteligência Artificial para conversar por voz com o usuário, aplicando também a linguagem Python (Google Colab).
Este projeto foi realizado como desafio final do Bootcamp **Bradesco - GenAI & Dados** da DIO (Digital Innovation One).
Fiz o meu o projeto replicando o projeto apresentado em aula pelo Prof. Venilton Falvo Jr.
Porém, fiz algumas alterações e também adicionei uma nova interação com o usuário.

Link do projeto (Google Colab): https://colab.research.google.com/drive/1_EKOFfwRqEfqkQEEYl4ZQ0gHJvlKtBV1?usp=sharing

O código do projeto também pode ser visualizado [neste repositório](virtual_assistant_bradesco_dio.ipynb).
<br><br><br>


## 🎯 Objetivo

O projeto visa utilizar, de maneira prática, as tecnologias **Speech-To-Text** e **Text-To-Speech** em interações por voz com o usuário.
<br><br><br>

## 💻 Tecnologias Utilizadas

- **Google Text-To-Speech (gTTS)** - converte texto em áudio.
- **Whisper (OpenAI)** - sistema de reconhecimento automático de voz (ASR) que converte áudio em texto.
- **Gemini** - API do Gemini, a Inteligência Artificial do Google. No projeto, irá responder à dúvida do usuário.
- **Python e Javascript** - linguagens de programação. Python no Google Colab (praticamente todo o projeto) e Javascript apenas no utilitário de gravação de áudio do microfone do usuário.
<br><br><br>


## ✨ Características

Minha ideia foi criar uma assistente virtual para responder (por voz) dúvidas específicas sobre investimentos no Bradesco.
Conforme especificado na descrição, eu repliquei o projeto original (apresentado em aula pelo Prof. Venilton) porém com alterações e adição de nova interação com o usuário.

### Alterações

- Tentei replicar o trecho de código "Integração com a API do ChatGPT".
  Porém, mesmo após várias tentativas diferentes (com muitas pesquisas), infelizmente não consegui realizar a integração com a API do ChatGPT.
  Eu decidi então substituir o ChatGPT pelo Gemini como IA a ser usada e fiz a integração com a API do Gemini.

- Como a minha ideia é criar uma assistente virtual financeira que responda dúvidas específicas sobre investimentos no Bradesco, eu orientei o Gemini com o seguinte prompt:
  "Dentro do escopo de Bradesco Investimentos, fale em poucas palavras sobre {transcription}.
Caso {transcription} não esteja relacionado a Bradesco Investimentos, retorne a frase 'Desculpe, esse assunto não está relacionado a investimentos.'"

\* {transcription} é o arquivo de áudio (gravado pelo usuário) que foi convertido em texto pelo Whisper.


### Interação

- Seguindo a ideia de uma assistente virtual financeira para investimentos no Bradesco, eu criei a assistente *Bri* (Bradesco Investimentos) e fiz uma apresentação inicial em áudio, usando o Google Text-To-Speech (gTTS), com a seguinte mensagem:
 ""Oi, eu sou a Bri, prima da Bia. Bri significa Bradesco Investimentos.
Estou aqui para te ajudar a fazer a melhor escolha em investimentos no Bradesco.
Sobre qual tipo de investimento você deseja informações?
Fale em poucas palavras." 

  Desse modo, o usuário terá um tratamento mais "humanizado" ao interagir com a assistente virtual.
  <br><br><br>

\*OBS.: _o presente projeto tem por finalidade única o aprendizado e uso básico das ferramentas (tecnologias) utilizadas para realizá-lo. Em nenhum momento o projeto tem a pretensão de criar uma assistente virtual financeira de uso real._






