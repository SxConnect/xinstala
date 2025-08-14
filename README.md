instalação de Apps do XPanel (XInstala)README.md
# XInstala – para instalar Apps em 1 Clique do XPanel

🚀 **XInstala** é a loja oficial de aplicativos do **XPanel**, projetada para quem busca **simplicidade, velocidade e apps em português**.  
Instale +200 aplicações open source com **um único clique** — tudo integrado diretamente ao seu painel.

> ✅ Open Source | 💸 Apps Pagos (BRL + Pix) | 🌐 100% em PT-BR | 🔐 SSL Automático

---

## 🎯 Objetivo

Oferecer uma experiência brasileira de instalação de aplicações web, com:
- **Instalação em 1 clique** (Docker + Traefik + SSL)
- Suporte a **subdomínios automáticos**
- **Apps gratuitos e pagos** 
- Totalmente em **português brasileiro**

---

## 🧩 Funcionalidades

- ✅ +200 apps open source (WordPress, Ollama, N8N, Nextcloud, etc)
- 💰 Modelos para apps pagos (com licença e validação)
- 🌍 Tradução completa para **PT-BR** (nomes, descrições, tooltips)
- 🔒 SSL automático via Let's Encrypt (DNS-01)
- 🛠️ Firewall básico integrado (UFW)
- 🔄 Integração direta com o **XPanel** (futuro: instalação sem sair do painel)

---

## 📁 Estrutura do Projeto

. ├── /apps/ │ 
    ├── /free/ → Apps gratuitos 
      ├── /categories/ → Arquivos de categorias (IA, CRM, Automação, etc) ├── /scripts/ → Templates de instalação (install.sh, Docker Compose) 
     ├── /paid/ → Apps pagos (com licença) 
  └── README.md → Este arquivo

---

## 🛠️ Como Contribuir

Você pode:
- 🔧 Enviar apps novos (com `app.json` e script de instalação)
- 🌐 Traduzir ou melhorar textos em PT-BR
- 💡 Sugerir melhorias na segurança ou UX
- 🧪 Testar instalações em diferentes VPS

👉 Veja nosso [guia de contribuição](CONTRIBUTING.md) para começar.

---

## 🚀 Como Usar (Manualmente)

1. Clone este repositório:
   ```bash
   git clone https://github.com/SxConnect/xinstala.git
Acesse a pasta de um aplicativo, por exemplo WordPress:
festança


1
cd apps/free/wordpress
Execute o script de instalação:
festança


1
2
chmod +x install.sh
./install.sh
Em breve: tudo diretamente no painel XPanel, com interface integrada. 

💼 Programa de Desenvolvedores Parceiros
Crie apps para o XInstala e ganhe 85% das vendas ! Aceitamos aplicativos pagos com:

Preço em BRL
Pagamento via Pix, boleto ou cartão (Mercado Pago)
Validação de licença por UUID
📩 Envie sua proposta: parcerias@xpanel.dev

📄 Licença
Este projeto é open source e está sob licença MIT .

🇧🇷 Feito no Brasil, para o mundo
XInstala é parte do ecossistema XPanel — um painel de controle moderno, feito por brasileiros, para quem quer simplicidade e poder.

🔗 Site: https://xpanel.dev (em construção) 🐙 Repositório: https://github.com/SxConnect/xinstala 💬 Comunidade: @xpanelbr no Telegram
