# Evolution API 2.0

API poderosa para integração com WhatsApp, usada por empresas e desenvolvedores no Brasil.

## 🚀 Recursos
- Conexão com WhatsApp via QR Code
- Armazenamento de mídias no MinIO (S3 compatível)
- Filas com RabbitMQ
- Banco de dados Postgres para persistência
- Cache com Redis
- Subdomínios automáticos (API, MinIO, RabbitMQ)
- SSL via Let's Encrypt

## 📦 Requisitos
- Docker e Docker Compose
- 2GB de RAM (recomendado)
- 10GB de armazenamento

## 🧩 Personalização
Após a instalação, acesse:
- API: `https://api.seusite.com`
- Painel MinIO: `https://storage.seusite.com`
- Painel RabbitMQ: `https://rabbitmq.seusite.com`
- Dados persistentes: `/opt/xpanel/data/evolution-api`

## 🔐 Primeiro Acesso
Na primeira execução, use a API Key gerada pelo XPanel para criar instâncias.

## 🌐 Documentação Oficial
[https://docs.evolution-api.com](https://docs.evolution-api.com)

## 💬 Sobre o App
Este app foi integrado pela comunidade XPanel para funcionar em 1 clique, com SSL, subdomínio automático e configuração completa. É parte da **XInstala**, a loja oficial de apps do XPanel.