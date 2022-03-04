# Passo a passo para criação do repositório no Git

### 1° Passo foi acessar a minha conta no github e criar um novo diretório público deixando marcada a opção para criar o readme.md

### 2º Selecione o diretório no seu computador que deseja clonar o seu projeto
git clone: https://github.com/batistapab/dio-desafio-github.git

### 3º Acesse o diretório e crie um novo usando o comando abaixo:
mkdir "introdução ao git e ao github" && cd '.\introdução ao git e ao github\'

### 4º Crie um novo arquivo txt com as anotações que serão utilizadas para realizar o desafio:
echo "Anotações do desafio" > anotacoes.txt

Mas existe outras opções para criação do arquivo vazio via cmd como:
 fsutil file createnew test.txt. 
 wsl touch test1.txt. 
 type > test2.txt.
 
 ### 5° Acesse diretório anterior e verifique o status do projeto
 cd ../
 git status 
 
 ### 6° Mapei as modificações, o modelo utilizado foi bem simples, em muitos projetos você precisar especificar exatamente os arquivos que deseja subir e usar o .gitignore para ignorar diretórios ou pastas que não deseja enviar ao repositório.
 
  git add .
  
 ### 7º Efetive as modificações 
 
 git commit -m "Inclusão das anotações do curso de git/github"
 
 ### 8º Finalize enviando os arquivos alterados para o servidor e  não esqueça de informar o branch
 git push origin main
