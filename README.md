# DesafioMD02_CarteiraDigital
API REST desenvolvida para simular uma carteira digital (CRUD), seguindo os padrões REST utilizando Javascript e bibliotecas do NodeJS.

💰 Back-end - API REST: Carteira Digital
GitHub language count Repository size GitHub last commit Feito por Stephanie Feliciano

🚧 API de Finanças (CRUD) 🚧 
Status Concluído

📝 Sobre o Projeto
Este projeto consiste em uma RESTful API desenvolvida para atender às necessidades de gerenciamento de usuários, categorias e transações.

📋 Funcionalidades
Com esta API, os usuários podem realizar as seguintes ações:

1. Gerenciamento de Usuários
Cadastrar Usuário: Os usuários podem se registrar na plataforma, fornecendo informações básicas;
Fazer Login: Usuários registrados podem fazer login para acessar suas contas;
Detalhar Perfil do Usuário Logado: Os usuários podem visualizar informações detalhadas de seu próprio perfil;
Editar Perfil do Usuário Logado: Usuários têm a capacidade de atualizar suas informações de perfil.

2. Gerenciamento de Categorias
Listar Categorias: A API permite listar todas as categorias disponíveis.

3. Gerenciamento de Transações
Listar Transações: Os usuários podem visualizar uma lista de todas as transações;
Detalhar Transação: Detalhes específicos de uma transação podem ser acessados;
Cadastrar Transação: Usuários podem criar novas transações;
Editar Transação: Transações existentes podem ser atualizadas;
Remover Transação: Exclusão de transações, se necessário;
Obter Extrato de Transações: Os usuários podem gerar um extrato de suas transações;
Filtrar Transações por Categoria (Extra): Os usuários têm a opção de filtrar transações com base em categorias específicas;

▶️ Como executar o projeto

🛠️ Pré-requisitos
Possuir um editor de código-fonte, por exemplo VSCode ou Vim;
Possuir o Git ou qualquer outro programa de versionamento;
Possuir o Node.js (versão 18.16.0 ou superior);
Possuir o Insomnia instalado;
Possuir o Beekeeper instalado para criar e acessar o banco de dados (versão 3.9.20 ou superior).

⚙️ Instalação
1. Clone este repositório em sua máquina local:
2. Navegue até o diretório do projeto:
cd nome_da_pasta
3. Instale as dependências através do comando:
npm install
4. Para executa-lo digite no terminal do seu editor de código:
npm run dev
5. No terminal, aparecerá a seguinte mensagem: O Servidor está sendo executado na porta 3000.;
6. Após exibir a mensagem acima, é necessário configurar o Beekeeper para gerenciar o banco de dados. Siga as configurações do arquivo conexao.js, localizado na pasta src, para configurar corretamente o Beekeeper;
7. Logo depois de configurar o Beekeeper, execute o Insomnia e configure um novo ambiente para testar as rotas da API. É possível fazer os testes importando o arquivo insomnia.

🚀 Tecnologias Utilizadas
1. Node.js (versão 18.16.0);

2. Bibliotecas:

Express (versão 4.18.2);
Nodemon (versão 3.0.1);
Date-fns (versão 2.30.0);
Bcrypt (versão 5. 1. 1);
jsonwebtoken (versão 9. 0. 2);
pg ou node-postgres (versão 8. 11. 3);
Linguagem de programação:
JavaScript.

🎲 Demonstração da Aplicação

🤝 Contribuição
Contribuições são bem-vindas! Se você quiser melhorar ou adicionar novos recursos a esta API, siga as etapas abaixo:

1. Crie um Fork deste repositório;
2. Crie uma branch para suas alterações: git checkout -b my-feature;
3. Commit suas alterações: git commit -m 'Adicionar nova funcionalidade';
4. Faça push para a branch: git push origin my-feature;
5. Abra um pull request.

🧙‍♂️ Autora
Projeto Back-end desenvolvido por Stephanie Feliciano, como desafio do modulo 3 do curso de Desenvolvimento de Software - Foco em Back-end da Cubos Academy ✨

📝 Licença
Feito por Stephanie Feliciano 👋🏽 Entre em contato!

Divirta-se explorando a API! 🌟

tags: back-end nodeJS PostgreSQL API REST bcrypt SQL .
