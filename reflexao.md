# Reflexão sobre o conflito de merge

## O que causou o conflito?

Nós dois alteramos a primeira linha do `README.md` em nossas cópias locais. Mateus enviou seu commit primeiro, e Gabriela tentou enviar o dela sem antes receber essa alteração. Ao fazer `git pull`, o Git encontrou mudanças diferentes na mesma linha e pediu uma decisão manual.

## Como decidimos qual versão manter?

Conversamos e decidimos manter as duas versões. Gabriela usou a opção "Accept Both Changes" no editor, deixando os dois títulos no arquivo, removeu os marcadores de conflito e fez o commit de resolução.

## O que faríamos diferente em um projeto maior?

Faríamos `git pull` antes de começar a editar e combinaríamos quem vai alterar cada parte do arquivo. Também dividiríamos as mudanças em commits menores e avisaríamos a equipe antes de mexer em uma linha compartilhada.
