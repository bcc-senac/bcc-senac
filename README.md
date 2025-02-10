# bcc-senac

## Público-alvo
- Alunos e ex-alunos de graduações voltados á tecnologia
- Pessoas interessadas em começar na área de tecnologia

## Requisitos Funcionais
- Autenticação
- Solicitação para postagem de projeto, incluindo: colaboradores, mídias, titulo, descrição, categoria, tecnologias, data e curso
- Feed de projetos, exibindo: mídias, titulo, descrição, tecnologias, categoria, data e curso
- Barra de pesquisa (busca por projetos, turmas ou grupos)
- Sistema de filtragem (data de postagem, tecnologias, curso e categoria)
- Opção de favoritar projetos para acesso rápido depois
  
  ### Usuários administradores
- Painel de administração
- Lista de projetos para aprovar (como professor/administração)
- Adições de novos cursos e categorias
- Gestão de professores
  
## Requisitos não-funcionais
- Autenticação em dois fatores (2FA) e JWT para aumentar a segurança dos usuários.  
- Proteção contra ataques de injeção SQL e XSS.  
- Criptografia de senhas e dados sensíveis usando padrões seguros (bcrypt).
- Interface responsiva e adaptável para dispositivos móveis e desktops.
