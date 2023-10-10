// Comando para criar as pastas
´´´
mkdir
´´´

// Comando para abrir o VScode
´´´
code .
´´´

// Comando usado para criar arquivos
´´´
touch
´´´

// Comando usado para baixar as dependencias
´´´
npm init -y
´´´
![image](https://github.com/HenriqueSENAC/projetoBackend/assets/117770107/0daff42b-cff5-4692-bf25-e1d2ea581a89)

// Comando instalador do pacote express
´´´
npm i express nodemon dotenv
´´´

// Comando para criar o .gitignore
´´´
nano .gitignore
´´´
![image](https://github.com/HenriqueSENAC/projetoBackend/assets/117770107/ae2f44ba-171c-4b07-aa54-ca1fd25224a0)
Para adcionar no nano .gitignore "node_modules" 

// Criar arquivos e pastas na seguinte ordem
´´´
mkdir src
touch src/app.js
touch src/server.js
mkdir src/config
mkdir src/controllers
mkdir src/routes
´´´

// Iniciar o gerenciador do github
´´´
git init
´´´

// Comandos para informar E-mail e Nome
´´´
git config --global user.name "[NOME AQUI]"
´´´
´´´
git config --global user.email "[EMAIL AQUI]"
´´´

// Verificar os arquivos a serem enviados
´´´
git status
´´´

// Adcionar arquivos ao versionamento (?)
´´´
git add .
´´´

// Salvar projeto
´´´
git commit -m "estrutura do projeto"
´´´

// Voltar ao main
´´´
git branch -M main
´´´

// Adcionar url do repositorio
´´´
git remote add origin [URL AQUI]
´´´

// Caso erre o URL usar esse para remover o URL errado
´´´
git remote rm origin
´´´

// Comando para enviar arquivos ao github
´´´
git push -u origin main
´´´

// Atualizar a pagina dos arquivos
´´´
cd ..
´´´

// Remover pastas do computador (-r = recursive: apaga as pastas de forma recursiva) (-f = force: não pede confirmações)
´´´
rm -rf [NOME DA PASTA]
´´´

