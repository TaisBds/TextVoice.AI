# 🎙️ VoiceAI Assistant

## 📌 Descrição

O **VoiceAI Assistant** é uma aplicação de Inteligência Artificial capaz de compreender e responder perguntas por meio da voz, utilizando tecnologias modernas de **Speech-to-Text**, **Processamento de Linguagem Natural** e **Text-to-Speech**.

O sistema permite interações naturais e inteligentes em múltiplos idiomas, oferecendo uma experiência fluida de comunicação entre humano e máquina.

---

## 🚀 Tecnologias Utilizadas

- **Python**
- **Whisper (OpenAI)** – Conversão de fala em texto (Speech-to-Text)
- **ChatGPT (OpenAI API)** – Processamento de linguagem natural
- **Google Text-to-Speech (gTTS)** – Conversão de texto em voz

---

## ⚙️ Funcionamento do Sistema

O fluxo da aplicação ocorre da seguinte forma:

1. 🎤 O usuário envia um áudio com uma pergunta  
2. 🧠 O modelo **Whisper** converte o áudio em texto  
3. 💬 O texto é enviado para o **ChatGPT**, que gera uma resposta inteligente  
4. 🔊 A resposta é convertida em áudio utilizando **gTTS**  
5. 🎧 O usuário recebe a resposta em formato de voz  

---

## 🌍 Diferenciais

- Suporte a múltiplos idiomas  
- Comunicação totalmente por voz  
- Integração de múltiplas APIs de Inteligência Artificial  
- Aplicação prática de IA generativa  
- Base para sistemas acessíveis e inclusivos  

---

## 📚 Contexto do Projeto

Este projeto foi desenvolvido durante o bootcamp:

**GenIA e Dados**  
Parceria entre **Bradesco** e **DIO**

Durante o desenvolvimento, foram aplicados conhecimentos em:

- Inteligência Artificial Generativa  
- Processamento de Linguagem Natural (NLP)  
- Integração de APIs  
- Python  


---

## 👩‍💻 Autora

**Tais Barbosa dos Santos**  

---

## ▶️ Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/voice-ai-assistant.git
```

### 2. Instale as dependências

```bash
pip install -r requirements.txt
```

### 3. Configure sua API Key (IMPORTANTE 🔒)

Por segurança, a chave da OpenAI não está incluída no projeto.

No Google Colab ou no seu ambiente local, configure:

```python
import os

os.environ["OPENAI_API_KEY"] = "SUA_API_KEY_AQUI"
```

Ou utilize variável de ambiente:

```bash
export OPENAI_API_KEY=sua_chave_aqui
```

### 4. Execute o projeto

```bash
python main.py
```

---

## 🔒 Boas Práticas de Segurança

- Nunca exponha sua API Key em repositórios públicos  
- Utilize variáveis de ambiente  
- Utilize arquivos `.env` (não versionados)  
- Revogue imediatamente qualquer chave exposta  



## 🔮 Melhorias Futuras

- Deploy em nuvem  
- Integração com banco de dados em tempo real  
- Reconhecimento de comandos avançados  

