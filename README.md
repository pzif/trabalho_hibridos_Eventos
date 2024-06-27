# Programa de Controle de Eventos

Ferramenta para o controle de eventos.

## Funcionalidades Principais

- **Autenticação (CRUD) com Clerk:** Gerenciamento seguro de usuários.
  
- **Eventos (CRUD):** Criação, leitura, atualização e exclusão de eventos.

- **Organização de Eventos:** Exibição estruturada de eventos criados pelos usuários.

- **Busca & Filtro:** Sistema robusto para encontrar eventos.

- **Pagamento com Stripe:** Transações seguras de pagamento.

## Início Rápido

### Pré-requisitos

- Git
- Node.js
- npm (Node Package Manager)

### Clonando e Instalando

```bash
git clone https://github.com/your-username/your-project.git
cd your-project
npm install


#Configuração
#Crie um arquivo .env na raiz do projeto com suas variáveis de ambiente:

# NEXT
NEXT_PUBLIC_SERVER_URL=http://localhost:3000

# CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_CLERK_WEBHOOK_SECRET=your_clerk_webhook_secret

# MONGODB
MONGODB_URI=your_mongodb_uri

# UPLOADTHING
UPLOADTHING_SECRET=your_uploadthing_secret
UPLOADTHING_APP_ID=your_uploadthing_app_id

# STRIPE
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key

#Executando o Projeto

npm start

#Abra http://localhost:3000 no navegador para ver o projeto.