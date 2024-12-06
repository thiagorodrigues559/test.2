**Git** e um sistema de controle, que permite com os usuarios gerencien e controlen as alterações no codigo fonte de seus projetos.
possui o hitorico de todas as alterações feitas no codigo;
com ele a o usuario consegue pegar uma parte do codigo modificar, validar as alterações feitas, e depois integrar ao codigo principal
**GitHub** é uma plataforma baseada na web que utiliza o Git para hospedar repositórios.
Os repositorios estão todos armazenados na nuvem qur facilita o acesso a eles 
com o **github** podemos participar de projetos de outros desenvolvedores, que faz a comunidade acabe crescendo
**Passos para Postar seu Projeto Online no GitHub**
o primeiro passo e criar uma conta no **Github**;
depois instalar o git; git-scm.com.
Configurar o Git: Abra o terminal e configure seu nome de usuário e email:
git config --global user.name "Seu Nome"
git config --global user.email "seu-email@example.com"
Dentro do seu editor de codigo, inicialize um terminal e insira esses comandos;
**git init ** - para inicializar o git
**git add .** - para adcionar os arquivos dentro do repositorio
git commit -m "Primeiro commit" - o commit serve para salvar as alterações
depois você vai conectar o seu editor ao repositorio
git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git
depois de conectar você vai mandar o projeto para o Github
git push -u origin master
feito isso seu projeto esta upado no github

