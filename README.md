# Curso VIM Alura

## Todos os modos

## Modo de edição (INSERT) 

## Modo de navegação/comando 
- U = Undo. Desfaz o ultímo comando executado
- R = Redo. Refaz o ultímo comando desfeito

- K = Sobe uma linha 
- J = Desce uma linha 
- H = Volta um caracter
- L = Avança um caracter
  - Para cada um dos comandos acimas, caso seja digitado um número antes, será avançado/retornado a quantidade de linhas que foi digitado

- : = Irá abrir o bash e também as opções de comando do VIM

- :%s = É o comando para substituir texto dentro do VIM, sua sintaxe ficará da seguinte forma:
    - :%s/{textoAtual}/{textoPrevisto}/opcoesDeSubstituicao
      - As opções de substituicao que temos, podem ser
		    - g = Significa global e irá substituir todas as ocorrências nos arquivos
				- c = Significa choose. Irá perguntar ocorrência por ocorrência, qual será substituida ou não
Juntos com esse comando, podemos digitar números antes e o VIM irá entender isso como o número de linhas/caracteres que ele irá avançar

O = Insere uma nova linha no arquivo e entra no modo de edição
