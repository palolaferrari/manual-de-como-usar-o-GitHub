DRC: ficou muito bom com bastante imagens!

# manual-de-como-usar-o-GitHub
Manual de como fazer um repositório do zero

JOÃO GUILHERME CARAMÊS

GUSTAVO BENETI

DANIELLE CHAGAS

PAOLA FERRARI

## Passo 1 - Criar a conta


## Passo 2 - Criar um novo repositório
![Capturar](https://user-images.githubusercontent.com/106709314/173057767-eed445db-dcb2-4259-9c14-47c45068f880.PNG)

### Passo 2.A  (BOAS PRÁTICAS) 
  
  - Escolher se será público (toda a comunidade terá acesso)ou privado (somente você poderá ver); 
  - Selecionar o README file (descrição do seu projeto);
  - Gitignore : o próprio Git já exclui os seus checkpoints, para ter só o arquivo final;
  - Licença: é um copilado de 'regras' para o uso do repositório, caso você escolha 'NONE' se alguém quiser usar o seu código, terá que pedir para você como ele poderá trabalhar com as informações
  ![Capturar PNG0](https://user-images.githubusercontent.com/106709314/173057814-3963a736-b46b-4379-ac32-9c2719d608b8.PNG)
es.
 
### PASSO 2.B (DICAS)
  - 'commits' mostra tudo que você fez e as setinhas na lateral 'viajam no tempo': vão para a configuração que o repositório estava no momento em que aquela alteração foi feita
  ![Commits](https://user-images.githubusercontent.com/106709314/173057939-2c8714e0-9737-4ee6-b8ac-e61827c579dc.PNG)
a
![lista de commits](https://user-images.githubusercontent.com/106709314/173058103-1079724b-6d55-49a4-a72d-16be12b790a5.PNG)

  - para poder editar uma pasta, basta clicar no lápis, após fazer a modificação é importante dizer o que foi feito de diferente e dar um COMMIT
  
  DRC: seria interessante contar um pouco mais sobre o que é o conceito de commit para git.
  ![Editar](https://user-images.githubusercontent.com/106709314/173058188-ef56be69-e0c3-47f5-8aa8-0c548bdd537d.PNG)
  <img width="541" alt="commit" src="https://user-images.githubusercontent.com/106709314/173058264-12490316-ba69-48f7-84c1-8d0f4a7173b2.PNG">

## Passo 3 - usar o GitHub no computador
  - criar uma pasta em qualquer lugar do explore;
  - com o botão direito, clique Git Bash Here (uma tela preta vai abrir);
  ![GitBashHere](https://user-images.githubusercontent.com/106709314/173058970-633a9118-b695-4358-9c84-b3e4f056e63d.png)
  - na página, na internet, copiar o CODE (botão verde) de https, na tela preta: *git clone + link*;
  -![https(gitbash)](https://user-images.githubusercontent.com/106709314/173168070-2a3bc185-263b-4659-9c23-5d52d8a82e55.PNG)
  - escrever: *cd + nome do repositório*, para abrir a pasta; **cd serve para mudar o diretório, e significa change directory**
  - os arquivos, do computador, vão aparecer nessa pasta.
  
  <img width="442" alt="Capturar PNG1" src="https://user-images.githubusercontent.com/106709314/173168144-09018bac-2c53-4d5e-9265-13b5db959f69.PNG">

## Passo 4 - alterando arquivos e salvando no servidor

DRC: aqui seria especialmente interessante ter uma imagem mostrando o git status.

  - para alterar um arquivo no computador (txt, pyton), fazemos a alteração;
  - se dermos um *git status* vai mostrar que existêm arquivos modificados, mas não salvos,
  - para fazer as alterações serem salvas damos um *git add + nome do arquivo* (para arquivos específicos) ou um *git add .* (para adicionar todos os arquivos modificados);
  - para salvar: *git commit -m “ descrição do que foi feito”* e depois *git push* - comando final para mandar pro servidor a alteração.
  - para mandarmos para o computador alterações feitas no servidor damos um *git pull* **DICA: todas as vezes que formos usar o Git na máquina, damos um git pull, para que não haja conflitos de versões e usar o último arquivo proposto salvo**
 
## Passo 5 - usando o main (universo paralelo)

DRC: senti que a partir daqui o texto ficou menos explicativo.

DRC: aqui nesse primeiro parágrafo faltou comentar que os universos paralelos se chamam ramos ou branches

Podemos abrir um 'universo paralelo' para que possamos mudar sem salvar o nosso arquivo, e assim, quando tivermos mudanças relevantes podemos 'juntar' os universos.

DRC: para trocar de branch usamos o comando "checkout nome_da_branch" e não "cd". Chamamos as branchs pelo nome, não de "0main novo"

Quando abrimos o **MAIN** damos um novo nome e ele faz um cópia de todos os arquivos no MAIN PRINCIPAL e as alterações são feitas nele. Caso quisermos fazer na máquina, damos um *cd + nome do main novo*, e as alterações são feitas nele. 

![main](https://user-images.githubusercontent.com/106709314/173168235-ddf96006-41aa-4e2d-856e-4f8aab886b58.png)

Depois de terminar suas atualizações para juntar (merge) os ramos, devemos:
  - clicar em *Pull Requests* , *new pull request*, arrumar as bases (**prestar atenção no sentido das setas**) e completar, caso for possível. 
  ![tempsnip](https://user-images.githubusercontent.com/106709314/173168320-a5f19b18-13f2-417b-b966-c6c44fbc4153.png)


## Passo 6 - usando o fork (modificação de um repositório alheio)
Para isso temos que encontrar com arquivo de interesse, clicar em FORK 
  - Após modificar o arquivo de interesse, pedimos se podemos fazer um MERGE PULL REQUEST, o dono vai avaliar e deixar ou não a modificação existir no arquivo orginal; 
  - se você fez as modificações na sua máquina, precisamos de um *git pull* e depois de modificado um *git push*;
  - caso hajam mais modificações no mesmo arquivo, devemos escolher uma que prevalecerá
  ![image15](https://user-images.githubusercontent.com/106709314/173168494-d65c7416-881a-4db8-9b24-24ee62002cc4.png)
![image7](https://user-images.githubusercontent.com/106709314/173168497-913ecdf4-b822-4a6e-9d20-87e224ed73b0.png)

