# GIT COMMANDS TIPS 

Antes de mais nada, o git serve basicamente para criar pontos na história do nosso projeto, que chamamos de commits, ou seja, utilizamos para fazer versionamento de código.

### Outras funcionalidades:
  - Restaurar algum trecho de código utilizado antigamente;
  - Acompanhar linha de atualizações e como elas ocorreram;
  - Saber quem trabalhou em cada funcionalidade;
  - Facilitar o trabalho em time no mesmo projeto;
  - Trabalhar com as mudanças provenientes desse time;
  - Organização.
  
## => `git init`
Inicia o git no projeto.

## => `git add .`
Adiciona todos os arquivos alterados na fila para criar ponto na história.

## => `git status`
Mostra informações como novos arquivos que ainda não foram adicionados ao git.

## => `git commit -m "sua mensagem"`
Cria o ponto na história com os arquivos adicionados.

> Referente a mensagem do commit, este é um dos pontos mais importantes, a mensagem tem que dizer em poucas palavras o que aquele trecho de código adicionado faz, por exemplo: "Adiciona CRUD de Users", assim, fica fácil saber exatamente o que aquele ponto faz. É interessante também, utilizar algum padrão, como por exemplo escrever a mensagem em inglês, ou ate mesmo usar algum prefixo junto com a mensagem, irei citar os que mais uso:

  - CHORE -> Usamos quando realizamos alguma alteração em um arquivo que já existe, exceto quando envolve uma alteração nos arquivos de testes ou alguma nova funcionalidade. o Chore pode ser usado no primeiro commit do projeto: "CHORE: Commit inicial";
  - FEAT -> Uma nova funcionalidade e/ou novo arquivo;
  - FIX -> Mostra que o commit resolve algum bug;
  - REVERT -> Indica uma reversão para um commit anterior;
  - DOCS -> Adiciona ou alteração nos arquivos de docs;
  - REFACTOR -> Refatora o código sem adicionar novas features ou correção de bug, apenas uma mudança em código ja existente. 
  - PERF -> Utilizado principalmente quando há a mudança de algum componente para melhorar a performance;
  - TEST -> Adiciona arquivos de test ou altera algum existente.

## => `git push`
Envia o código adicionado e commitado para o git hub.

## => `git checkout -b nome-da-nova-ramificacao`
Muda a ramificação (caso ela exista) ou cria uma nova.

