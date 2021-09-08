

# Lista 2 - EXERCICIO PRÁTICO DE REVISÃO :notebook:



### 1) Crie uma pasta de nome Exercícios e Acesse a mesma

_mkdir Exercicios && cd Exercicios_



### 2) Crie um arquivo vazio de nome lista_nomes.txt

_touch lista_nomes.txt_



### 3) Abra este arquivo com o Editor Nano
_nano lista_nomes.txt_



### 4) Digite 20 nomes de pessoas incluindo o seu, pulando de linha para cada nome inserido

nome1

nome1

...

nome20



### 5) Salve o arquivo e saia do mesmo

_CTRL + O (Aparecerá uma confirmação para salvar os documento editado, só apertar "ENTER" para salvar)_

_CTRL + X (Sairá do editor)_



### 6) Exiba os 10 primeiros nomes da lista

_head lista_nomes.txt_



### 7) Exiba os 10 últimos nomes da lista

_tail lista_nomes.txt_



### 8) Procure no texto o seu nome

_cat lista_nomes.txt | grep "nome"_



### 9) Crie um arquivo chamado setembro.txt com a saída do comando cal

_cal september 2020 > setembro.txt_



### 10) Adicione o conteúdo do arquivo setembro.txt ao arquivo lista_nomes.txt

_cat setembro.txt >> lista_nomes.txt_



### 11) Exiba o arquivo lista_nomes.txt com paginação

_cat lista_nomes.txt | more_



### 12) Exiba o caminho do arquivo setembro.txt

_find ~ -name setembro.txt_



### 13) Exiba o tipo do arquivo lista_nomes.txt

_file setembro.txt_



### 14) Exiba a explicação do comando ls

_ls --help_



### 15) Renomeie o Arquivo lista_nomes.txt para arquivo.txt

_mv lista_nomes.txt arquivo.txt_



### 16) Limpando o terminal

_CTRL + L_



### 17) Saindo do Terminal 

_exit_

