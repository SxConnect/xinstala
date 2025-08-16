# Vaultwarden

Servidor leve do Bitwarden para auto-hospedagem de senhas e autenticação de dois fatores.

## 🚀 Recursos
- 100% compatível com apps, extensões e APIs do Bitwarden
- Interface web limpa e segura
- Subdomínio automático (ex: `senha.seusite.com`)
- SSL via Let's Encrypt
- Dados persistentes em volume Docker
- Painel de administração (com token)

## 📦 Requisitos
- Docker e Docker Compose
- 512MB de RAM (mínimo)
- 2GB de armazenamento

## 🧩 Personalização
Após a instalação, acesse:
- Painel: `https://seu-dominio.com`
- Admin: `https://seu-dominio.com/admin` (use o token gerado)
- Dados persistentes: `/opt/xpanel/data/vaultwarden`

## 🔐 Primeiro Acesso
Crie uma conta normal. O painel de admin é protegido por token.

## 🌐 Documentação Oficial
[https://github.com/dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden)

## 💬 Sobre o App
Este app foi integrado pela comunidade XPanel para funcionar em 1 clique, com SSL, subdomínio automático e configuração completa. É parte da **XInstala**, a loja oficial de apps do XPanel.