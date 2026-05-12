# NutriX — Landing Page

Página de vendas do NutriX, CRM para nutricionistas.

## Estrutura

```
nutrix-landing/
├── index.html      # Página principal
├── vercel.json     # Configuração do Vercel
└── README.md       # Este arquivo
```

## Como fazer o deploy no Vercel

### Opção 1 — Via GitHub (recomendado)

1. Crie um repositório no GitHub chamado `nutrix-landing`
2. Faça upload dos arquivos desta pasta
3. Acesse vercel.com e clique em **Add New Project**
4. Conecte o repositório `nutrix-landing`
5. Clique em **Deploy** — sem configurar nada, o Vercel detecta automaticamente
6. Pronto! Sua landing page estará no ar

### Opção 2 — Via Vercel CLI

```bash
# Instalar o Vercel CLI
npm install -g vercel

# Dentro da pasta nutrix-landing
vercel

# Seguir as instruções no terminal
# Quando perguntar o projeto, criar um novo chamado nutrix-landing
```

### Opção 3 — Upload direto no Vercel (mais simples)

1. Acesse vercel.com
2. Clique em **Add New Project**
3. Clique em **Upload** (opção de arrastar pasta)
4. Arraste a pasta `nutrix-landing` inteira
5. Clique em **Deploy**

## Domínio personalizado

Após o deploy, para apontar seu domínio (ex: nutrix.com.br):

1. No painel do Vercel, acesse o projeto
2. Vá em **Settings > Domains**
3. Adicione seu domínio
4. Configure os DNS conforme instruções do Vercel

## Atualizar a página

Para atualizar qualquer conteúdo, basta editar o `index.html` e fazer um novo push no GitHub — o Vercel faz o deploy automaticamente.
