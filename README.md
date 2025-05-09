# 🤖 Chatbot Integrado ao WhatsApp com Inteligência Artificial

Este projeto é um **chatbot inteligente** desenvolvido em **Python**, que utiliza **modelos de linguagem (LLMs)** para interpretar mensagens e responder de forma automatizada via **WhatsApp**. A aplicação é ideal para automatizar atendimentos, realizar triagens iniciais e oferecer suporte personalizado.

## 📌 Objetivo

Desenvolver um sistema robusto e escalável que:
- Receba mensagens enviadas ao WhatsApp por meio de uma API oficial
- Gere respostas com base em um modelo de linguagem (como OpenAI/GPT)
- Envie as respostas automaticamente ao remetente
- Gerencie múltiplas conversas simultâneas

## ⚙️ Tecnologias utilizadas

- **Python 3.10+**
- **FastAPI** — estrutura leve para criação de APIs
- **OpenAI API** — para geração de respostas com LLMs
- **Uvicorn** — servidor ASGI para rodar a aplicação
- **ngrok** — tunelamento local (para testes com webhooks)
- **WhatsApp Cloud API (Meta)** — integração com WhatsApp

## 📁 Estrutura do projeto
ChatBot-Integrado-ao-WhatsApp/
│<br>
├── app/<br>
│ ├── main.py    # Arquivo principal, define os endpoints<br>
│ ├── whatsapp.py    # Funções de integração com a API do WhatsApp<br>
│ ├── llm.py    # Lógica de chamadas ao modelo de linguagem<br>
│ ├── session.py    # Gerenciamento de contexto de conversas<br>
│ └── config.py    # Variáveis de ambiente e chaves de API<br>
│<br>
├── requirements.txt    # Dependências do projeto<br>
├── .env    # Variáveis de ambiente (não versionado)<br>
├── README.md    # Este arquivo<br>
└── .gitignore<br>

## 👨‍💻 Desenvolvedores

**Thalles Oliveira**  [![GitHub](https://img.shields.io/badge/-000000?style=flat-square&logo=github)](https://github.com/thallescunhadeoliveira) [![LinkedIn](https://img.shields.io/badge/-in-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thalles-cunha-de-oliveira/)

