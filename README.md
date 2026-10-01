# 🤖 DeepSeek Chat

Chat inteligente desenvolvido em Python utilizando o modelo DeepSeek-R1 executado localmente através do Ollama.

## 🚀 Tecnologias

- Python
- Streamlit
- LangChain
- Ollama
- DeepSeek-R1 1.5B

## 💡 Sobre o projeto

Aplicação de chat utilizando um Large Language Model (LLM) executado localmente.

O projeto utiliza o LangChain para integração com o modelo DeepSeek-R1 através do Ollama e Streamlit para criação da interface web.

## ⚙️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/deepseek-chat.git
cd deepseek-chat

2. Crie o ambiente virtual
python -m venv .venv

3. Ative o ambiente virtual
Windows:

.venv\Scripts\activate

4. Instale as dependências
pip install -r requirements.txt

5. Instale o Ollama
Instale o Ollama e baixe o modelo:

ollama pull deepseek-r1:1.5b

6. Execute o projeto
streamlit run app.py

A aplicação será aberta no navegador.

🧠 Arquitetura
Usuário
   ↓
Streamlit
   ↓
LangChain
   ↓
Ollama
   ↓
DeepSeek-R1 1.5B
   ↓
Resposta


📌 Objetivo

Projeto desenvolvido para praticar integração de LLMs locais com Python, LangChain e Streamlit.