```markdown
# 🤝 Contribua com a XInstala

A **XInstala** é um projeto open source construído pela comunidade, para a comunidade.  
Se você quer ajudar a trazer mais apps, melhorar traduções ou tornar a instalação ainda mais fácil, este é o seu lugar!

Seja bem-vindo(a) — desenvolvedores, tradutores, testadores e entusiastas são todos essenciais para o crescimento da loja de apps do **XPanel**.

---

## 📌 Como Contribuir

Você pode contribuir de várias formas:

### 1. 🔧 Adicionar um Novo App (Gratuito ou Pago)
Ajude a aumentar o número de aplicativos disponíveis com instalação em 1 clique.

**Passos:**
1. Crie uma pasta em `/apps/free/` (gratuito) ou `/apps/paid/` (pago).
2. Adicione os arquivos:
   - `app.json` → metadados do app (nome, descrição, versão, preço, etc)
   - `install.sh` → script de instalação (Docker + Traefik + SSL)
   - `icon.png` (128x128) → ícone do app
3. Abra um **Pull Request** com sua contribuição.

📌 Veja o modelo: [`/templates/app.json`](#) e [`/templates/install.sh`](#)

---

### 2. 🌐 Traduzir ou Melhorar Textos em PT-BR
Nosso foco é 100% em **português brasileiro**. Ajude a corrigir nomes, descrições ou mensagens de erro.

**Onde ajudar:**
- Arquivos `app.json` (nome, descrição, tags)
- Scripts de instalação (`install.sh`)
- Interface da AppStore (futuro: painel XPanel)

💡 Dica: Evite anglicismos como "setup", "dashboard", "store". Use "configuração", "painel", "loja de apps".

---

### 3. 🐞 Testar e Reportar Bugs
Teste instalações em VPS reais (DigitalOcean, AWS, etc) e nos ajude a identificar falhas.

**Como reportar:**
1. Abra uma **Issue** no GitHub.
2. Descreva:
   - App testado
   - Sistema operacional
   - Erro encontrado
   - Logs (se possível)

---

### 4. 💡 Sugerir Melhorias
Tem uma ideia para:
- Novas categorias
- Melhorias de segurança
- UX da instalação
- Automação de subdomínios

Abra uma **Discussion** ou **Issue** com a tag `[sugestão]`.

---

## 🧱 Estrutura de um App

### Exemplo: `app.json` (App Gratuito)
```json
{
  "id": "wordpress",
  "name": "WordPress",
  "description": "Crie sites e blogs com o CMS mais usado do mundo.",
  "version": "6.6",
  "category": "cms",
  "price_brl": 0,
  "license_required": false,
  "tags": ["blog", "site", "cms"],
  "author": "Comunidade XPanel",
  "website": "https://wordpress.org"
}
Exemplo: (App Pago)app.json
json
{
  "id": "crm-pro-br",
  "name": "CRM Pro BR",
  "description": "Sistema completo de gestão de clientes com suporte a Pix e automação.",
  "version": "1.2",
  "category": "negocios",
  "price_brl": 49.9,
  "license_required": true,
  "tags": ["vendas", "clientes", "automacao"],
  "author": "Dev Parceiro",
  "website": "https://meusite.com"
}
🛠️ Requisitos parainstall.sh
Seu script deve:

Usar Docker e Docker Compose
Configurar subdomínio automático (ex: )app.seudominio.com
Integrar com Traefik para SSL (Let's Encrypt)
Criar volumes persistentes
Aplicar regras básicas de firewall (UFW)
Mostrar mensagens claras em PT-BR
📌 Exemplo de modelo:/scripts/install-template.sh

📂 Estrutura de Pastas
/apps/
├── /free/     → Apps gratuitos
└── /paid/     → Apps pagos
/categories/   → Categorias oficiais
/scripts/      → Templates de instalação
/icons/        → Ícones dos apps
/templates/    → Modelos para app.json e install.sh
📄 Regras de Contribuição
Use português brasileiro em todos os textos.
Evite aplicativos duplicados ou obsoletos.
Teste seu script antes de enviar.
Seja respeitoso nas discussões.
🚀 Como Enviar Sua Contribuição
Faça um fork do repositório: https://github.com/SxConnect/xinstala
Crie uma filial:git checkout -b app/nome-do-app
Adicione seus arquivos e faça o commit:
festança


1
2
git add .
git commit -m "Adiciona [Nome do App] à XInstala"
Envie para o GitHub:
festança


1
git push origin app/nome-do-app
Abra um Pull Request com o título:
Adiciona [Nome do App] (Gratuito/Pago)
💼 Programa de Desenvolvedores Parceiros
Se você cria aplicativos pagos, pode se tornar um Desenvolvedor Parceiro e:

Ganhar com as vendas
Ter seu aplicativo destacado no XInstala
Receber suporte técnico para integração
📩 Envie um email para: parcerias@xpanel.dev

🙌 Agradecemos Sua Contribuição!
Juntos, estamos construindo a melhor loja de aplicativos em 1 clique do Brasil — simples, rápida e feita para quem fala nossa língua.

🔗 XPanel: https://xpanel.dev 💬 Comunidade: @xpanelbr no Telegram

