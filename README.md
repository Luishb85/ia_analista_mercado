
# 🤖 Agente de IA para Análise de Mercado com CrewAI + ChatGPT

Este projeto demonstra o uso de **agentes autônomos de inteligência artificial** para realizar **análises econômicas e identificar oportunidades de investimento** com base em linguagem natural. Utilizei a biblioteca [CrewAI](https://github.com/joaomdmoura/crewai) integrada à API da **OpenAI (ChatGPT)**, criando um verdadeiro **analista virtual** com capacidade de raciocínio estratégico.

---

## 🚀 Tecnologias Utilizadas

- 🧠 [OpenAI / ChatGPT](https://platform.openai.com/) – modelo de linguagem principal
- 🤖 [CrewAI](https://github.com/joaomdmoura/crewai) – estrutura para agentes com propósito e autonomia
- ⚡ [LiteLLM](https://docs.litellm.ai/) – ponte leve entre Python e múltiplas LLMs
- 🌐 [OpenRouter API](https://openrouter.ai) – acesso à LLM via token externo
- 🐍 Python – linguagem base
- 🔐 Dotenv – para gerenciamento de chaves de API

---

## 🧩 O que este agente faz?

- Assume o papel de **Analista de Mercado Econômico**
- Utiliza linguagem natural para **avaliar o cenário atual**
- Identifica **setores com alto potencial de crescimento**
- Gera respostas contextuais, detalhadas e alinhadas com o objetivo

---

## 📦 Estrutura do Projeto

```bash
├── .env                  # Contém a chave da OpenAI ou do OpenRouter
├── agente.ipynb          # Notebook com a definição e execução do agente
├── llm_config.py         # Configuração do modelo e integração via LiteLLM
├── main.py               # Script principal executável
├── requirements.txt      # Dependências do projeto
```

---

## 🧪 Como usar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repo.git
cd seu-repo
```

2. Crie e ative um ambiente virtual:

```bash
python -m venv .venv
.\.venv\Scriptsctivate
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Configure sua chave no arquivo `.env`:

```env
OPENROUTER_API_KEY=coloque_sua_chave_aqui
```

5. Execute:

```bash
python main.py
```

Ou abra o notebook `agente.ipynb` para explorar.

---

## 💡 Ideias Futuras

- Permitir múltiplos agentes (ex: consultor de investimentos, gestor de risco, etc.)
- Exportar relatórios de análise em PDF/HTML
- Conectar com APIs financeiras para dados em tempo real

---

## 📬 Contato

Quer saber como adaptar essa ideia ao seu projeto ou empresa?  
Me chama aqui no GitHub ou no [LinkedIn](https://linkedin.com/in/luishb85) — bora conversar!

---

## ⭐️ Curtiu o projeto?

Deixe uma ⭐ para apoiar e acompanhar novas aplicações com IA autônoma!
