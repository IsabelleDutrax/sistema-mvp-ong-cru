SIte: https://isabelledutrax.github.io/sistema-mvp-ong-cru/
💰 **MVP Doações - Sistema de Gestão de Doações**
=================================================

Um simples sistema de gestão de doações voltado para ONGs, desenvolvido utilizando HTML, CSS, SCSS, JavaScript e a plataforma Supabase. Este projeto permite que organizações gerenciem doadores, doações e interações em um só lugar.

📝 **Sumário**
--------------

*   Descrição
    
*   Funcionalidades
    
*   Tecnologias Utilizadas
    
*   Instalação
    
*   Uso
    
*   Como Contribuir
    
*   Licença
    

🖥️ **Descrição**
-----------------

O **MVP Doações** é um sistema que ajuda ONGs a gerenciarem:

*   Doadores (criação, atualização e remoção de registros).
    
*   Doações realizadas por doadores, incluindo consulta e controle.
    
*   Interações realizadas com os doadores, para acompanhar o histórico de contato.
    

O sistema inclui uma interface simples e intuitiva com botões estilizados e ícones responsivos.

🛠️ **Funcionalidades**
-----------------------

*   **Autenticação** de usuários (login e logout).
    
*   Gerenciamento de **doadores**:
    
    *   Adicionar novos doadores.
        
    *   Editar ou excluir informações de doadores.
        
*   Controle de **doações**:
    
    *   Registrar novas doações.
        
    *   Visualizar histórico de doações.
        
*   Registro de **interações** com doadores:
    
    *   Adicionar observações e histórico de contato realizado.
        
    *   Editar ou deletar essas interações.
        
*   Design responsivo para melhor experiência em dispositivos móveis e desktops.
    

⚙️ **Tecnologias Utilizadas**
-----------------------------

**TecnologiaDescriçãoHTML**Estruturação da aplicação.**CSS/SCSS**Estilização aprimorada com o uso de mixins, variáveis e estrutura modular do SCSS.**JavaScript**Lógica e interação do cliente (frontend).**Supabase**Backend como serviço para banco de dados, autenticação e APIs.**Flaticon**Ícones responsivos e minimalistas para melhorar a interface do usuário.**SweetAlert2**Alertas estilizados e responsivos nas interações do sistema.

🚀 **Instalação**
-----------------

Siga os passos abaixo para rodar o projeto localmente:

### Pré-requisitos

1.  Certifique-se de que você possui o [**nodejs.org**](https://nodejs.org/) instalado (para instalação do Sass, se necessário).
    
2.  Conhecimento básico de **Supabase** e uma conta criada.
    

### Passos

1.  bashCopiargit clone https://github.com/seu-usuario/seu-repositorio.git
    
2.  bashCopiarcd mvp-doacoes
    
3.  Configure as variáveis do Supabase no arquivo principal de JavaScript:
    
    *   Substitua os valores das constantes SUPABASE\_URL e SUPABASE\_KEY pelas informações do seu projeto no Supabase.
        
4.  bashCopiarnpm install -g sass
    
    *   bashCopiarsass --watch scss/main.scss:style.css
        
5.  (Opcional) Utilize um servidor para rodar a aplicação localmente:
    
    *   bashCopiarpython -m http.server
        

📖 **Uso**
----------

1.  Acesse a interface pelo seu navegador, usando o endereço local (http://127.0.0.1:8000) ou pela sua hospedagem.
    
2.  **Login** ou **cadastro**:
    
    *   Use os e-mails padrão cadastrados no Supabase (ou crie novos diretamente pela interface).
        
3.  Comece a gerenciar doadores, doações e interações diretamente pelo painel do sistema.
    

🌐 **Estrutura do Projeto**
---------------------------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   project/  │  ├── index.html          # Página principal  ├── style.css           # Estilo gerado pelo SCSS  ├── scss/               # Arquivos SCSS (estilo modular)  │   ├── main.scss       # SCSS principal  │   ├── _variables.scss # Variáveis reutilizáveis (cores, espaçamento, etc.)  │   ├── _base.scss      # Estilos básicos/reset  │   ├── _components.scss# Estilos de botões e tabelas  │   └── _mixins.scss    # Mixins reutilizáveis  ├── scripts.js          # Lógica principal do frontend  └── README.md           # Documentação do projeto   `

🤝 **Como Contribuir**
----------------------

Contribuições são bem-vindas! Aqui está como você pode ajudar:

1.  Faça um fork do repositório.
    
2.  bashCopiargit checkout -b minha-feature
    
3.  Faça suas alterações e salve seus commits.
    
4.  bashCopiargit push origin minha-feature
    
5.  Crie um Pull Request explicando sua contribuição.