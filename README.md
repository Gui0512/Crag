exercicio:
  titulo: "Exercício GitHub – Projeto Web Básico"
  objetivo: "Criar um repositório no GitHub contendo 5 arquivos obrigatórios (HTML, CSS, JS e dois arquivos de texto), respeitando nomes exatos e versionamento com Git."
  estrutura_obrigatoria:
    - index.html
    - style.css
    - script.js
    - texto1.txt
    - texto2.txt
  observacoes:
    - "Os nomes dos arquivos devem ser exatamente os informados"
    - "Todos os arquivos devem ficar na raiz do repositório"
    - "Repositório deve ser público"
  arquivos:
    index.html: |
      <!DOCTYPE html>
      <html lang="pt-BR">
      <head>
        <meta charset="UTF-8">
        <title>Projeto GitHub</title>
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <h1>Projeto GitHub</h1>
        <p>Este projeto foi criado como exercício de Git e GitHub.</p>
        <script src="script.js"></script>
      </body>
      </html>
    style.css: |
      h1 {
        color: blue;
      }

      p {
        font-size: 18px;
      }
    script.js: |
      // Arquivo responsável pela lógica JavaScript do projeto
      console.log("Projeto iniciado");
    texto1.txt: |
      Este é o primeiro bloco de texto do projeto.
    texto2.txt: |
      Este é o segundo bloco de texto do projeto.
  git:
    passos: |
      git init
      git add .
      git commit -m "Criação da estrutura inicial do projeto"
      git commit -am "Ajustes no conteúdo dos arquivos"
      git branch -M main
      git remote add origin URL_DO_REPOSITORIO
      git push -u origin main
  criterios_avaliacao:
    - "Todos os arquivos existem"
    - "Nomes corretos dos arquivos"
    - "HTML importando CSS e JS"
    - "Conteúdo mínimo presente"
    - "Pelo menos dois commits"
    - "Repositório público no GitHub"
