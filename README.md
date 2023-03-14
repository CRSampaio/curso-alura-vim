# Curso VIM Alura

## Modos

### Modo de edição (INSERT) 

### Modo de seleção

Este modo é ativo através do modo de navegação, pressionando V

### Modo de seleção de linhas

Este modo é ativo através do modo de navegação, pressionando Shift+c

### Modo de seleção de bloco

Este modo é ativo através do modo de blocos (colunas, basicamente), pressionando Ctrl+v

### Modo de navegação/comando 
- Q + Qualquer outra tecla = Inicia o modo de gravação. Neste modo, todos os comandos que você executou são gravados, até você entrar no modo de navegação novamente e apertar q para finalizar a gravação. Após isso, toda essa gravação de comandos ficará salva na tecla que você pressionou após ter apertado Q no inicio. Esses comandos podem ser repetidos se você pressionar @ e depois a tecla aonde foi gravado 
- K = Sobe uma linha 
- J = Desce uma linha 
- H = Volta um caracter
- L = Avança um caracter
- O = Insere uma nova linha no arquivo e entra no modo de edição
- D duas vezes = Deleta uma linha
- X = Corta um caracter
- U = Undo. Desfaz o ultímo comando executado
- Ctrl + R = Redo. Refaz o ultímo comando desfeito
- D = Deleta um caracter 
- P = Cola o que estiver na área de transferência para o arquivo
  - Para cada um dos comandos acimas, caso seja digitado um número antes, será avançado/retornado a quantidade de linhas que foi digitado

- R = Replace. Irá subsituir o texto selecionado, pela proxima letra que você digitar
- Y duas vezes = Copia uma linha inteira para área de transferência
- G duas vezes = Volta a primeira linha do arquivo 
- Shift+G = Vai até a ultíma linha do arquivo
- close / Ctrl+W e C = Fecha a janela aberta
- Ctrl+W e depois seta pro lado direito / Ctrl+W e depois L = Vai para a tela da direita
- Ctrl+W e depois seta pro lado esquerdo / Ctrl+W e depois H = Vai para a tela da esquerda
- Ctrl+W e depois seta pra baixo / Ctrl+W e depois J = Vai para a tela de baixo
- Ctrl+W e depois seta pra cima / Ctrl+W e depois K = Vai para a tela de cima

- : = Irá abrir o bash e também as opções de comando do VIM
  - %s = É o comando para substituir texto dentro do VIM, sua sintaxe ficará da seguinte forma:
	- %s/{textoAtual}/{textoPrevisto}/opcoesDeSubstituicao
    - As opções de substituicao que temos, podem ser
		  - g = Significa global e irá substituir todas as ocorrências nos arquivos
			- c = Significa choose. Irá perguntar ocorrência por ocorrência, qual será substituida ou não
  - vs {nomeArquivo} / Ctrl+W (split no mesmo arquivo) e V = Irá executar o split vertical
  - sp {nomeArquivo} / Ctrl+W (split no mesmo arquivo) e S = Irá executar o split horizontal
  - find (algum texto) = É o comando que irá procurar arquivos, dentro do diretório que você abriu o VIM
	- q = Comando para sair do VIM
  - w = Comando para escrever/salvar as mudanças que você fez no arquivo
  - x = Comando para escrever/salvar as mudanças e fechar o arquivo que está aberto
  - / = É o Ctrl+F do VIM basicamente, que funciona nativamente com expressões regulares. Digita-se /{textoProcurado} e após isso se pressiona ENTER. O cursor será leva para o resultado mais próxima daonde seu cursor está. Para achar a próxima ocorrência, apertar N e voltar para que você passou, aperte Shift+N.
