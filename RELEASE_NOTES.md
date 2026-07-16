# Release Notes — MVP Doações

Histórico de mudanças do projeto, organizado por commit/entrega. Formato inspirado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/).

## [Não lançado] — em andamento (working tree)
### Adicionado
- Tela de Login/Cadastro redesenhada: card centralizado vertical e horizontalmente na tela, com círculo de logo acima do título.
- Barra compacta pós-login ("Logado como ...") que substitui o formulário de login enquanto o usuário está autenticado.
- Layout responsivo do login (breakpoint para telas pequenas).
### Alterado
- Credenciais do Supabase (`SUPABASE_URL`/`SUPABASE_KEY`) atualizadas para o novo projeto (formato de chave `sb_publishable_...`).

## [1b442ee] — 2025-12-16 — mudei caminho style
### Corrigido
- Caminho de referência do `style.css` no `index.html`.

## [cde66de] — 2025-12-16 — Correção lógica de funcionalidades + validação + estilos + README
### Adicionado
- CRUD completo (criar, editar, excluir) para Doadores, Doações e Interações via Supabase.
- Autenticação (login/logout) com verificação de nível de acesso administrador (tabela `doador`, campo `nivel_acesso`).
- Validação de existência do doador antes de registrar uma doação ou interação.
- Alertas estilizados com SweetAlert2, substituindo `alert()`/`confirm()` nativos do navegador.
- Ícones do Flaticon nos botões de ação (editar/excluir/sair).
- Estrutura SCSS modular (`_variables`, `_mixins`, `_base`, `_components`) compilada para `style.css`.
- README detalhado com descrição, funcionalidades, tecnologias utilizadas e instruções de instalação.
### Alterado
- Reorganização e indentação do HTML/JS para maior legibilidade.

## [beb4144] — 2025-12-15 — Add site link to README
### Adicionado
- Link do site publicado (GitHub Pages) no README.

## [f8f52e7] — 2025-12-15 — Add initial HTML structure for MVP Doações
### Adicionado
- Estrutura HTML inicial do sistema, com seções de Login, Doadores, Doações e Interações.

---
*Elaborado com suporte de IA — Revisado por [Nome do Responsável]*
