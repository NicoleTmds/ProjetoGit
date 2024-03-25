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

Criando uma nova branch (Cria outra linha cronologica dentro do seu projeto):
    git checkout -b "<nome da nova branch>"

Restaurando arquivos apagados (No repositório local)
    git checkout HEAD "<nome do arquivo apagado>"

#Caso você tenha realizado o commit:
    git reset --hard HEAD~1
    git checkout HEAD "<nome do arquivo apagado>"

#Para casos diferentes acesso em: https://recoverit.wondershare.com.br/file-recovery/recover-files-from-local-repository-git.html#:~:text=Para%20recuperar%20este%20arquivo%2C%20voc%C3%AA,no%20arquivo%20ap%C3%B3s%20o%20commit.