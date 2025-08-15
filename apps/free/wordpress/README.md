# WordPress

O CMS mais popular do mundo. Ideal para criar sites, blogs, portfólios e lojas virtuais.

## 🚀 Recursos
- Instalação em 1 clique via XPanel
- Subdomínio automático (ex: `wordpress.seusite.com`)
- SSL via Let's Encrypt (automático)
- Banco de dados integrado (MariaDB)
- Backup de dados persistente
- Suporte a temas e plugins

## 📦 Requisitos
- Docker e Docker Compose
- Domínio configurado (opcional)
- 512MB de RAM (mínimo)

## 🧩 Personalização
Após a instalação, acesse:
- Painel de administração: `https://seu-dominio.com/wp-admin`
- Arquivos do site: `/opt/xpanel/data/wordpress`

## 🔧 Configuração Técnica
- Imagem: `wordpress:latest`
- Banco de dados: `mariadb:10.11`
- Rede: `xpanel-network`
- Labels Traefik: automaticamente gerados pelo XPanel

## 🌐 Documentação Oficial
[https://wordpress.org](https://wordpress.org)

## 💬 Sobre o App
Este app foi criado pela comunidade XPanel para ser instalado em 1 clique, com segurança, SSL e subdomínio automático. É parte da **XInstala**, a loja oficial de apps do XPanel.