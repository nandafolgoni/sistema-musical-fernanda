🎵 Sistema Musical — Interface Web

Um sistema web responsivo e moderno para gerenciamento de catálogo musical, cadastro de artistas e controle de acervo de músicas. O projeto foi desenvolvido com HTML5 e CSS3, estruturado em módulos e preparado para futura integração com back-end em PHP e banco de dados.

🚀 Funcionalidades

🔒 Autenticação de Usuário (login.html)

Tela de login centralizada com suporte a autocompletar e validação de campos obrigatórios.

Exibição de credenciais de demonstração/teste.

📌 Menu Principal / Dashboard (index.html)

Painel de navegação limpo em grade (grid layout) para acesso rápido a todas as áreas do sistema.

Opção de encerrar sessão (logout).

🎤 Cadastro de Artistas (cadastro_artista.html)

Formuário com layout em grade com suporte a upload de imagem de perfil (multipart/form-data).

Validação visual de campos obrigatórios (marcação com $*$ em destaque).

🎵 Cadastro de Músicas (cadastro_musica.html)

Associação de música ao artista cadastrado via seletor dinâmico (<select>).

Suporte a links de vídeos no YouTube, envio de capa de álbum e inserção de letra da música.

Tabela de cadastro rápido integrada na própria página.

🎼 Biblioteca Musical (listagem_musicas.html)

Consulta de acervo com campos de busca por palavra-chave, filtro por artista e por gênero musical.

Tabela organizada com atalhos diretos para assistir ao vídeo no YouTube, editar registros ou excluir.

📂 Estrutura de Arquivos

.
├── index.html              # Menu principal de navegação do sistema
├── login.html              # Tela de autenticação de usuário
├── cadastro_artista.html   # Formulário para cadastrar novos artistas
├── cadastro_musica.html    # Formulário de cadastro de músicas e prévia
├── listagem_musicas.html   # Biblioteca geral com filtros e tabela de dados
└── styles.css              # Folha de estilos unificada (CSS3 + Responsividade)


🛠️ Tecnologias Utilizadas

HTML5: Marcação semântica (<form>, <table>, <head>, <select>, <textarea>).

CSS3 Moderno:

CSS Variables (:root): Padronização da identidade visual, facilitando a troca global de temas e cores.

Flexbox & CSS Grid: Layouts responsivos e adaptáveis para telas de qualquer tamanho.

Media Queries (@media (max-width: 768px)): Adaptação total para dispositivos móveis (tabelas com rolagem horizontal, botões responsivos, formulários em coluna única).

Design System Leve: Componentes de botões (.btn-primary, .btn-edit, .btn-delete, .btn-youtube), cards e formulários customizados.

💻 Como Executar o Projeto

Faça o download ou clone este repositório.

Abra qualquer um dos arquivos .html diretamente em seu navegador web (ex: Chrome, Firefox, Edge).

Recomendamos iniciar abrindo o arquivo login.html ou index.html.

Nota: Por se tratar de uma interface estática (front-end), o envio dos formulários e o funcionamento dos filtros simulados serão totalmente ativados após a integração com a camada de servidor.

🔮 Próximos Passos (Integração Back-end — Sprint 2)

[ ] Implementar script de autenticação e controle de sessões em PHP (session_start(), logout.php).

[ ] Criar banco de dados relacional (MySQL/PostgreSQL) com tabelas de usuarios, artistas e musicas.

[ ] Tratar uploads de arquivos de imagens (capas e fotos de artistas) salvando os diretórios no servidor.

[ ] Ativar listagem dinâmica via consultas SQL com suporte a busca e filtros reais.
