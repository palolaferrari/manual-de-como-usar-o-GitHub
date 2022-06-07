# manual-de-como-usar-o-GitHub
Manual de como fazer um repositório do zero

JOÃO GUILHERME CARAMÊS

GUSTAVO BENETI

DANIELLE CHAGAS

PAOLA FERRARI

## Passo 1 - Criar a conta

## Passo 2 - Criar um novo repositório

### Passo 2.A  (BOAS PRÁTICAS) 
  
  - Escolher se será público (toda a comunidade terá acesso)ou privado (somente você poderá ver); 
  - Selecionar o README file (descrição do seu projeto);
  - Gitignore : o próprio Git já exclui os seus checkpoints, para ter só o arquivo final;
  - Licença: é um copilado de 'regras' para o uso do repositório, caso você escolha 'NONE' se alguém quiser usar o seu código, terá que pedir para você como ele poderá trabalhar com as informações.
 
### PASSO 2.B (DICAS)
  - 'commits' mostra tudo que você fez e as setinhas na lateral 'viajam no tempo': vão para a configuração que o repositório estava no momento em que aquela alteração foi feita
  - para poder editar uma pasta, basta clicar no lápis, após fazer a modificação é importante dizer o que foi feito de diferente e dar um COMMIT

## Passo 3 - usar o GitHub no computador
  - criar uma pasta em qualquer lugar do explore;
  - com o botão direito, clique Git Bash Here (uma tela preta vai abrir);
  - na página, na internet, copiar o CODE (botão verde) de https, na tela preta: *git clone + link*;
  - escrever: *cd + nome do repositório*, para abrir a pasta; **cd serve para mudar o diretório, e significa change director**
  - os arquivos, do computador, vão aparecer nessa pasta.

## Passo 4 - alterando arquivos e salvando no servidor
  - para alterar um arquivo no computador (txt, pyton), fazemos a alteração;
  - se dermos um *git status* vai mostrar que existêm arquivos modificados, mas não salvos,
  - para fazer as alterações serem salvas damos um *git add + nome do arquivo* (para arquivos específicos) ou um *git add .* (para adicionar todos os arquivos modificados);
  - para salvar: *git commit -m “ descrição do que foi feito”* e depois *git push* - comando final para mandar pro servidor a alteração.
  - para mandarmos para o computador alterações feitas no servidor damos um *git pull* **DICA: todas as vezes que formos usar o Git na máquina, damos um git pull, para que não haja conflitos de versões e usar o último arquivo proposto salvo**
 
## Passo 5 - usando o main (universo paralelo)
Podemos abrir um 'universo paralelo' para que possamos mudar sem salvar o nosso arquivo, e assim, quando tivermos mudanças relevantes podemos 'juntar' os universos.

Quando abrimos o **MAIN** damos um novo nome e ele faz um cópia de todos os arquivos no MAIN PRINCIPAL e as alterações são feitas nele. Caso quisermos fazer na máquina, damos um *cd + nome do main novo*, e as alterações são feitas nele. 

Depois de terminar suas atualizações para juntar (merge) os ramos, devemos:
  - clicar em *Pull Requests* , *new pull request*, arrumar as bases (**prestar atenção no sentido das setas**) e completar, caso for possível. 

## Passo 6 - usando o fork (modificação de um repositório alheio)
Para isso temos que encontrar com arquivo de interesse, clicar em FORK 
  - Após modificar o arquivo de interesse, pedimos se podemos fazer um MERGE PULL REQUEST, o dono vai avaliar e deixar ou não a modificação existir no arquivo orginal; 
  - se você fez as modificações na sua máquina, precisamos de um *git pull* e depois de modificado um *git push*;
  - caso hajam mais modificações no mesmo arquivo, devemos escolher uma que prevalecerá
