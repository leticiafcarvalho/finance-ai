# Finance AI
Finance AI é uma plataforma SaaS de gerenciamento financeiro que permite aos usuários adicionar e controlar transações, incluindo depósitos, despesas e investimentos. O sistema oferece funcionalidades de gestão financeira, geração de relatórios (somente para usuários assinantes) e visualização de dados financeiros no dashboard.


## Funcionalidades
Adicionar Transações: Permite adicionar transações de depósito, despesas e investimentos.
Edição e Exclusão de Transações: Os usuários podem editar ou excluir transações existentes.
Dashboard: Painel de controle para visualizar transações e gerar relatórios financeiros.
Relatórios de IS: Disponível apenas para usuários com assinatura paga.
Login de Usuário: Apenas usuários logados podem acessar e gerenciar suas transações.

## Planos de Assinatura
Versão Gratuita: Acesso básico ao sistema com funcionalidades limitadas.
Versão Paga: Acesso completo, incluindo a geração de relatórios de IS e outras funcionalidades avançadas.

## Tecnologias Utilizadas
Frontend: React, Next.js, Tailwind CSS
Backend: Node.js, Prisma (para banco de dados)
Banco de Dados: PostgreSQL

## Como Rodar Localmente

1-Clone o repositório:
git clone https://github.com/seu-usuario/nome-do-repositorio.git

2- Instale as dependências:
npm install

3- Configure as credenciais do banco de dados no arquivo .env.

4- Rode as migrações do Prisma:
npx prisma migrate dev

5- Inicie o servidor:
npm run dev

6- Acesse no navegador: http://localhost:3000
