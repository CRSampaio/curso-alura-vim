# Curso VIM Alura

## Todos os modos

## Modo de edição (INSERT) 

## Modo de seleção

Este modo é ativo através do modo de navegação, pressionando V

## Modo de seleção de linhas

Este modo é ativo através do modo de navegação, pressionando Shift+c

## Modo de seleção de bloco

Este modo é ativo através do modo de blocos (colunas, basicamente), pressionando Ctrl+v

## Modo de navegação/comando 

- K = Sobe uma linha 
- J = Desce uma linha 
- H = Volta um caracter
- L = Avança um caracter
  - Para cada um dos comandos acimas, caso seja digitado um número antes, será avançado/retornado a quantidade de linhas que foi digitado

- X = Corta um caracter
- U = Undo. Desfaz o ultímo comando executado
- Ctrl + R = Redo. Refaz o ultímo comando desfeito
- D = Deleta um caracter 
- Y duas vezes = Copia uma linha inteira para área de transferência
- P = Cola o que estiver na área de transferência para o arquivo

- : = Irá abrir o bash e também as opções de comando do VIM

  - :%s = É o comando para substituir texto dentro do VIM, sua sintaxe ficará da seguinte forma:
		- :%s/{textoAtual}/{textoPrevisto}/opcoesDeSubstituicao
      - As opções de substituicao que temos, podem ser
		    - g = Significa global e irá substituir todas as ocorrências nos arquivos
				- c = Significa choose. Irá perguntar ocorrência por ocorrência, qual será substituida ou não
Juntos com esse comando, podemos digitar números antes e o VIM irá entender isso como o número de linhas/caracteres que ele irá avançar
  - / = É o Ctrl+F do VIM basicamente, que funciona nativamente com expressões regulares. Digita-se /{textoProcurado} e após isso se pressiona ENTER. O cursor será leva para o resultado mais próxima daonde seu cursor está. Para achar a próxima ocorrência, apertar N e voltar para que você passou, aperte Shift+N.
O = Insere uma nova linha no arquivo e entra no modo de edição
