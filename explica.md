## Backend (`api_server/`):

  * Aplicação FastAPI com autenticação JWT e RBAC.
  * Modelos de banco de dados : Usuários, Planos, Assinaturas, Disciplinas, Questões, Exames.
  * Pontos de extremidade da API : Autenticação (login/cadastro) e gerenciamento de usuários.
  * Scripts : start_backend.shpara inicializar o banco de dados e executar o servidor.

## Front-end (`frontend/`):

 * Aplicação React + Vite com Tailwind CSS.
 * Páginas : Login, Painel de Controle (Usuário), Painel Administrativo.
 * Integração : Conectado à API de backend via proxy.
 * Scripts : start_frontend.shpara instalar dependências e executar o servidor de desenvolvimento.

Agora você pode executar o projeto localmente usando os scripts fornecidos. 
O backend será executado na porta 8000 e 
o frontend na porta 5173. 
O usuário administrador inicial é admin@example.comcom senha admin.
