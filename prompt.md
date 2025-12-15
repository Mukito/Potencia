# PROMPT – GERAÇÃO DE SAAS PROFISSIONAL DE PLATAFORMA DE ESTUDOS

>Atue como um Arquiteto de Software Sênior e Desenvolvedor Full Stack, especializado em SaaS escaláveis, seguros e profissionais.
>Gere um projeto completo, bem documentado, pronto para rodar localmente em ambiente de desenvolvimento, seguindo boas práticas de mercado.

## 🎯 OBJETIVO DO PROJETO

Criar um SaaS profissional de Plataforma de Estudos e Simulados, com autenticação, controle de acesso, planos de assinatura, área administrativa e banco de dados relacional.

## 🧱 ARQUITETURA OBRIGATÓRIA

Explique e gere o projeto com:

 * Backend: API REST (preferencialmente FastAPI ou Node.js/NestJS)
 * Frontend: SPA moderna (React, Next.js ou Vue)
 * Banco de Dados: PostgreSQL ou MySQL
 * ORM: SQLAlchemy / Prisma / TypeORM
 * Autenticação: JWT + Refresh Token
 * Controle de Acesso (RBAC):
    * USER
    * ADMIN
 * Migrações de banco
 * Estrutura de pastas organizada
 * Variáveis de ambiente (.env)
 * Documentação de como rodar localmente

## 🔐 AUTENTICAÇÃO E USUÁRIOS

Implementar:
 * Cadastro de usuário
 * Login
 * Logout
 * Recuperação de senha
 * Hash de senha seguro (bcrypt ou similar)
 * Middleware de autenticação
 * Middleware de autorização por perfil

## 👤 TIPOS DE USUÁRIOS
 * Usuário comum
 * Administrador (ADM)

## 🛠️ ÁREA ADMINISTRATIVA (OBRIGATÓRIA)
Criar uma página de ADMIN, protegida por permissão, com:
 * Listagem de usuários
 * Editar usuário
 * Deletar usuário
 * Alterar tipo de plano (Free, Pago, PRO)
 * Ativar / desativar usuário

## 📚 FUNCIONALIDADE PRINCIPAL – PLATAFORMA DE ESTUDOS
Criar um sistema de questões e simulados para as matérias:
 * Português
 * Matemática
 * Inglês

Cada matéria deve conter questões separadas por nível de dificuldade:
 * Fácil
 * Médio
 * Difícil

Funcionalidades:
 * Banco de questões
 * Simulados por matéria
 * Simulados por nível
 * Correção automática
 * Exibição de resultado ao final

## 💳 PLANOS E ASSINATURA
Implementar 3 níveis de acesso:

### 🟢 FREE
 * Cadastro gratuito
 * Acesso limitado
 * Algumas questões
 * Sem simulados completos

### 🔵 PAGO
 * Assinatura MENSAL
 * Acesso completo a uma parte das matérias
 * Simulados liberados apenas enquanto a assinatura estiver ativa

### 🟣 PRO
 * Assinatura ANUAL
 * Acesso total:
   * Todas as matérias
   * Todos os níveis
   * Todos os simulados
> Implementar lógica de expiração de plano e bloqueio automático quando vencido.

## 💰 PAGAMENTO
 * Estrutura preparada para gateway de pagamento (ex: Stripe, Mercado Pago)
 * Tabela de assinaturas no banco
 * Status:
   * ativa
   * expirada
   * cancelada
 * Data de início e data de vencimento (ANUAL)
*(Não é necessário integrar o gateway real, mas a estrutura deve estar pronta)*

## 🗄️ MODELAGEM DE DADOS (OBRIGATÓRIA)
Criar e explicar tabelas como:
 * users
 * roles
 * plans
 * subscriptions
 * subjects
 * questions
 * exams (simulados)
 * exam_results
Com relacionamentos claros (FKs).

## 🖥️ FRONTEND
Criar telas:
 * Login
 * Cadastro
 * Dashboard do usuário
 * Lista de matérias
 * Simulados
 * Resultado de simulados
 * Página ADMIN
 * Página de planos e assinatura

## 📦 ENTREGA FINAL
Ao final, apresente:
 1. Estrutura de pastas do projeto
 2. Explicação da arquitetura
 3. Scripts para rodar localmente:
   * Backend
   * Frontend
   * Banco de dados

 4. Exemplo de .env
 5. Comandos para iniciar o projeto
 6. Boas práticas de segurança aplicadas

## ⚠️ REQUISITOS DE QUALIDADE
 * Código limpo
 * Comentários explicativos
 * Padrões REST
 * Separação clara de responsabilidades
 * Projeto pronto para evoluir para produção



-----------------------------------------

próximo passo eu posso:
 * Adaptar esse prompt especificamente para FastAPI + React
 * Adaptar para NestJS + Next.js
 * Criar somente o backend
 * Criar somente o banco de dados
 * Ou transformar isso em um roadmap de desenvolvimento passo a passo
