# Cheat Sheet de Git 
**Autor:** Rayan Oliveira

Este é um guia rápido para iniciantes com os principais comandos do Git para o dia a dia de desenvolvimento.

## git init
**O que faz:** Transforma uma pasta comum do seu computador em um repositório Git.
**Explicação simples:** É como dizer ao Git: *"Ei, comece a vigiar e gravar tudo o que acontece dentro desta pasta a partir de agora"*. Você só usa esse comando uma vez por projeto, logo no início.

## git clone
**O que faz:** Copia um projeto que já existe na internet (como no GitHub) para o seu computador.
**Explicação simples:** É o famoso "baixar o código". Se o time já tem um projeto pronto, você usa o clone para puxar uma cópia idêntica para a sua máquina e começar a trabalhar.

## git status
**O que faz:** Mostra o estado atual dos seus arquivos.
**Explicação simples:** É a sua bússola. Ele diz quais arquivos você modificou, quais foram adicionados e quais estão prontos para serem salvos. Sempre que estiver perdido e não souber o que fazer em seguida, digite `git status`.

## git add .
**O que faz:** Adiciona todas as suas modificações recentes a uma "área de preparação" (chamada de *staging*).
**Explicação simples:** Imagine que você está empacotando uma caixa de mudanças. O `git add .` (com esse ponto no final) pega todos os arquivos que você alterou e coloca dentro da caixa, deixando tudo pronto para ser fechado.

## git commit -m "mensagem"
**O que faz:** Salva definitivamente as alterações que você preparou com o `git add`, criando um ponto na história do projeto.
**Explicação simples:** É o ato de fechar a caixa com fita adesiva e colar uma etiqueta nela. O `-m` significa *message* (mensagem), e o texto entre aspas é a sua etiqueta explicando o que você fez (ex: `git commit -m "Cria tela de login"`).

## git pull
**O que faz:** Atualiza o código do seu computador com as mudanças mais recentes que estão no servidor.
**Explicação simples:** Se outro desenvolvedor do time fez uma alteração e salvou lá no GitHub, o `git pull` "puxa" essas novidades para a sua máquina, garantindo que você não está trabalhando com código desatualizado.

## git branch
**O que faz:** Lista, cria ou exclui ramificações (branches) no projeto.
**Explicação simples:** Imagine o código principal como o tronco de uma árvore. Uma *branch* é um galho que você cria para trabalhar em uma nova funcionalidade sem o risco de quebrar o tronco principal. Quando tudo estiver perfeito no seu galho, você pode juntá-lo ao tronco depois.

---

## Tabela de Resumo

| Comando | Para que serve de forma resumida? |
| :--- | :--- |
| `git init` | Começa a rastrear uma pasta nova. |
| `git clone` | Baixa um projeto existente da internet. |
| `git status` | Mostra o que foi modificado no momento. |
| `git add .` | Prepara todos os arquivos alterados para o salvamento. |
| `git commit -m` | Salva o pacote de alterações com uma mensagem explicativa. |
| `git pull` | Puxa as atualizações mais recentes do time para a sua máquina. |
| `git branch` | Cria ou mostra caminhos paralelos para trabalhar com segurança. |
