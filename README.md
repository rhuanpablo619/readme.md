# readme.md
<div align="center">
💼 Currículo Interativo — Rhuan Pablo

🧠 Projeto completo que une interface, servidor e banco de dados em uma aplicação CRUD funcional.

🔰 Status do Projeto






🔧 Tecnologias Principais








</div>
🧩 Visão Geral

O projeto apresenta um currículo interativo, que pode ser criado, editado, visualizado e excluído por meio de uma interface gráfica simples e funcional.
Ele foi desenvolvido com foco em organização de código, separação de camadas e integração completa entre servidor e banco de dados local.

🧱 Estrutura do Projeto
curriculo-interativo-rhuan/
├── backend/
│   ├── server.js
│   ├── models/
│   ├── controllers/
│   ├── routes/
│   ├── seed.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── App.js
│   │   ├── api.js
│   │   ├── index.js
│   │   ├── styles.css
│   │   └── components/
│   │       ├── CurriculoCard.js
│   │       ├── CurriculoForm.js
│   │       └── CurriculoList.js
│   └── package.json
│
└── README.md


📂 Backend: contém toda a lógica do servidor e comunicação com o banco.
🖥️ Frontend: interface gráfica para interação com os dados.
💾 Banco de Dados: armazenamento local das informações.

💡 Funcionalidades
✅ Função	💬 Descrição
Adicionar	Cadastrar novas informações no currículo
Listar	Exibir todos os registros salvos
Editar	Atualizar dados diretamente na interface
Excluir	Remover informações do banco
Integração completa	Comunicação entre interface, servidor e banco local
💾 Estrutura dos Dados
Campo	Descrição
id	Identificador único
nome	Nome completo
email	Endereço eletrônico
telefone	Contato telefônico
nascimento	Data de nascimento
cidade	Cidade e estado
estadoCivil	Estado civil
formacao	Formação acadêmica
experiencias	Histórico profissional
informacoesComplementares	Habilidades e observações
informatica	Competências técnicas
⚙️ Como Executar Localmente
1️⃣ Clonar o repositório
git clone https://github.com/SEU_USUARIO/curriculo-interativo-rhuan.git
cd curriculo-interativo-rhuan

2️⃣ Iniciar o servidor
cd backend
npm install
npm run seed   # Cria e preenche o banco
npm start      # Inicia o servidor local


O servidor será iniciado (porta padrão: 3001).

3️⃣ Iniciar a interface
cd ../frontend
npm install
npm start


A interface abrirá automaticamente no navegador, permitindo interação total com os dados.

🌐 Publicação Online

A aplicação foi configurada para funcionar em ambientes gratuitos de hospedagem.
O processo de publicação envolve:

Enviar o servidor para uma hospedagem online.

Publicar a interface em um serviço gratuito de páginas web.

Definir variáveis de ambiente para conectar as duas partes.

Após isso, o sistema poderá ser acessado por URLs públicas.

📡 Rotas do Servidor
Método	Caminho	Descrição
GET	/api/curriculo	Lista todos os registros
GET	/api/curriculo/:id	Retorna um registro específico
POST	/api/curriculo	Cria um novo registro
PUT	/api/curriculo/:id	Atualiza um registro existente
DELETE	/api/curriculo/:id	Remove um registro
🎨 Interface do Projeto

🖊️ Formulário de Cadastro e Edição
Permite inserir e modificar informações do currículo.

📋 Lista de Currículos
Mostra todos os dados cadastrados de forma clara.

⚙️ Ações Rápidas
Botões de edição e exclusão em cada item da lista.

⚠️ Observações Importantes

⚙️ O banco local é ideal para testes e apresentações.
Para ambientes permanentes, é recomendada a integração com um serviço de banco remoto.

🔁 Em ambientes gratuitos, os dados podem ser recriados a cada atualização do projeto.

🌍 As variáveis de ambiente controlam o endereço da interface e do servidor para garantir a comunicação correta.

🚀 Melhorias Futuras

🧠 Implementar sistema de autenticação e login.
📸 Adicionar campo de foto de perfil.
🔍 Criar busca e filtros de registros.
📄 Modo de visualização pública (sem edição).
💾 Migrar o banco local para um ambiente remoto.

👤 Autor

Rhuan Pablo Ferreira Cordeiro
📍 Arniqueiras - DF
📧 rhuanpablo619@gmail.com

🧾 Licença

📜 Este projeto é livre para uso acadêmico e de portfólio.
Pode ser copiado e adaptado para estudos e demonstrações.

<div align="center">
✅ Projeto Finalizado e Funcional

Pronto para uso local e publicação gratuita online.

✨ Aplicação que integra interface, servidor e banco de dados em um sistema completo e intuitivo.

</div>
