# 📦 Apps Gratuitos da XInstala

Esta pasta contém os **aplicativos gratuitos** disponíveis na **XInstala**, a loja de instalação em 1 clique do **XPanel**.

Todos os apps são **open source**, compatíveis com Docker e projetados para instalação rápida, segura e com suporte a:
- Subdomínio automático
- SSL via Let's Encrypt
- Firewall básico (UFW)
- Backup de dados persistente

---

## 🎯 Objetivo

Oferecer uma experiência brasileira de instalação de aplicações web, com:
- ✅ 100% em **português brasileiro**
- ✅ Instalação em **1 clique**
- ✅ Apps gratuitos e pagos (esta pasta é apenas para os gratuitos)
- ✅ Foco em simplicidade, segurança e performance

---

## 🧩 Apps Disponíveis (MVP)

Abaixo está a lista de aplicativos já integrados ao XPanel. Cada um possui:
- `app.json` → metadados (nome, descrição, preço, categoria)
- `data.yml` → configuração Docker (Traefik, volumes, redes)
- `icon.png` → ícone 128x128
- `README.md` → documentação em PT-BR

| App | Categoria | Descrição |
|-----|---------|-----------|
| [WordPress](wordpress/) | Sites e Blogs | CMS mais usado do mundo para sites, blogs e lojas |
| [N8N](n8n/) | Automação | Plataforma de automação de workflows com interface visual |
| [Portainer](portainer/) | DevOps | Interface visual para gerenciar Docker e containers |
| [MinIO](minio/) | Armazenamento | Solução S3 compatível para armazenamento de arquivos |
| [Ollama](ollama/) | IA | Execute modelos de IA localmente (Llama 3, Gemma, Phi, etc) |
| [Typebot](typebot/) | IA | Crie chatbots inteligentes com fluxo visual |
| [Flowise AI](flowise-ai/) | IA | Interface visual para LangChain e agentes de IA |
| [Langflow](langflow/) | IA | Ferramenta para construir apps com IA generativa |
| [Appsmith](appsmith/) | Ferramentas de Dev | Plataforma low-code para painéis internos |
| [NocoDB](nocodb/) | Banco de Dados | Transforme qualquer banco de dados em uma planilha inteligente |
| [NocoBase](nocobase/) | Banco de Dados | Plataforma low-code para criação de backends |
| [Directus](directus/) | Ferramentas de Dev | CMS headless + banco de dados moderno |
| [Cal.com](cal-com/) | Utilidades | Agendamento de reuniões com suporte a múltiplos provedores |
| [Mautic](mautic/) | Marketing | Automação de marketing open source |
| [Vaultwarden](vaultwarden/) | Segurança | Servidor leve do Bitwarden (gerenciador de senhas) |
| [Uptime Kuma](uptime-kuma/) | Monitoramento | Monitore seus serviços e receba alertas em tempo real |
| [RabbitMQ](rabbitmq/) | DevOps | Broker de mensagens para sistemas distribuídos |
| [Halo](halo/) | Sites e Blogs | Plataforma moderna de blog escrito em Java/Spring |
| [WoofeedCRM](woofeedcrm/) | Negócios | CRM simples e eficaz para pequenas empresas |
| [Evolution API](evolution-api/) | Comunicação | API para integração com WhatsApp (uso avançado) |

---

## 🛠️ Como Contribuir

Você pode:
- 🔧 Adicionar novos apps gratuitos
- 🌐 Melhorar traduções para PT-BR
- 🐞 Relatar bugs ou sugerir melhorias
- 🧪 Testar instalações em VPS reais

👉 Veja o guia completo em: [CONTRIBUTING.md](../../CONTRIBUTING.md)

---

## 📁 Estrutura de um App

Cada aplicativo deve conter:
nome-do-app/
├── app.json → metadados (nome, preço, categoria, licença)
├── data.yml → configuração Docker (services, networks, labels)
├── icon.png → ícone 128x128 px
└── README.md → documentação em PT-BR
---

## 🇧🇷 Feito no Brasil, para o mundo

A **XInstala** é parte do ecossistema **XPanel** — um painel de controle moderno, feito por brasileiros, para quem quer simplicidade e poder.

🔗 Site: [https://xpanel.dev](https://xpanel.dev)  
🐙 Repositório: [https://github.com/SxConnect/xinstala](https://github.com/SxConnect/xinstala)  
💬 Comunidade: [@xpanelbr no Telegram](https://t.me/xpanelbr)