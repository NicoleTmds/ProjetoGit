Aqui você escreve tudo o que deve saber sobre o projeto...
Primeira alteração;
Alteração teste;

Criando o primeiro Repositório:
    git init (Inicializa um repositório local vazio);
    git add "nome do arquivo" (Manda os arquivos para a área de standing/Espera);
    git status (Verifica o atual status dos arquivos);
    git commit -m "<Titulo do commit>" (Atualiza as novas versões do arquivo);
    git status (Verifica o atual status dos arquivos);
    git branch -M "main" (Renomeia a linha cronologica principal para -main- . Nome padrão de projeto);
    git remote add origin "Url do Repositório do github.com"
        ex: git remote add origin https://github.com/NicoleTmds/Projetogit.git;
    git push -u origin main (Puxa/empurra seu código para o github);

Atualizando o github:
    git add . (Adiciona todas as alterações)
    git status (Verifica o atual status dos arquivos)
    git commit -m "<Titulo do commit>" (Posta as alterações/novas versões do projeto)
    git push origin main (Envia essas alterações )

Criando uma nova brach (Cria outra linha cronologica dentro do seu projeto):
    git checkout -b "<nome da nova branch>"