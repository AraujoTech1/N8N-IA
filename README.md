<h1 align="center">🤖 Chatbot para WhatsApp 🤖</h1>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-FF6D6D?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
</p>


## Descrição 

Chatbot para WhatsApp utilizando automação via n8n, integração com a WhatsApp HTTP API (WAHA) e geração de respostas com OpenAI ou Azure OpenAI. Com capacidade de respostas inteligentes baseada em IA. O fluxo automatizado é orquestrado visualmente através da plataforma **n8n**, que interage com o WhatsApp via **WAHA (WhatsApp HTTP API)**. As respostas são geradas com **GPT-3.5-turbo** da OpenAI ou Azure OpenAI, e o histórico pode ser armazenado no **Redis** para contexto de conversas.

Tudo roda em containers Docker, facilitando a instalação local ou em nuvem.

---

## Funcionalidades 

- Recebe mensagens do WhatsApp via Webhook.
- Envia mensagens automatizadas usando inteligência artificial (IA).
- Integração com OpenAI (ou Azure OpenAI) para gerar respostas dinâmicas.
- Armazena contexto da conversa usando Redis.
- Fluxo visual gerenciável via n8n.
- Totalmente containerizado com Docker Compose.

---

## Testes de Software

**Tipos de testes realizados:**

-  **Teste de funcionamento**: envio e recebimento de mensagens via WAHA.
-  **Teste de integração**: conexão com API da OpenAI/Azure, retorno de respostas.
-  **Teste de segurança**:
  - Uso de senhas em `.env`
  - Autenticação básica no n8n (`BASIC_AUTH`)
-  **Teste de depuração**:
  - Monitoramento de execuções no painel do n8n.
  - Logs nos containers com `docker logs`.

**Exemplo de teste**:
- Enviado: "Olá, o que você pode fazer?"
- Resposta esperada: "Olá! Eu sou um assistente de IA e posso responder suas perguntas."

---

## Tecnologias


<img src="https://img.shields.io/badge/n8n-FF6D6D?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
<img src="https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white" alt="JSON" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure" />
<img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows" />

---

## Bibliotecas e Frameworks

- [WAHA (WhatsApp HTTP API)](https://github.com/diego3g/whatsapp-http-api)
- [OpenAI API](https://platform.openai.com/docs) ou [Azure OpenAI](https://learn.microsoft.com/azure/cognitive-services/openai/)
- [Redis](https://redis.io)
- [PostgreSQL](https://www.postgresql.org)

---

## Pré-requisitos e Instalações

- Docker Desktop instalado ou Cloud da Azure 
- Conta na OpenAI ou Azure OpenAI com chave de API ativa
- Conta no WAHA (ou rodar localmente para pareamento com QR code)

---

## Instruções de Uso

1. Clone o repositório:
- git clone https://github.com/seuusuario/n8n-waha-bot.git

2. Passo a Passo completo no artigo que criei:
- Artigo: [Como automatizar tarefas com n8n e IA](https://web.dio.me/articles/como-automatizar-tarefas-com-n8n-e-ia-utilizando-chatgpt-gemini-e-azure-ai-bed520ef0cda)

---
## ⚖️ Licença ⚖️

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](./LICENSE) para mais detalhes.


---

<p align="center">Desenvolvido com ☕+++</p>
