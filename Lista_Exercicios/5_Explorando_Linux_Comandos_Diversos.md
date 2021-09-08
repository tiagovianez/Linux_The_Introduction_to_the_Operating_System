# Lista 5 - REVISÃO DO CONTEÚDO COM JSLinux (Fedora):notebook:



### 1) Primeiramente acesse o site: https://bellard.org/jslinux/



### 2) Acesse em seguida o Fedora 33 (Linux) com a interface Console 

![image-20210907214518970](C:\Users\Tiago\AppData\Roaming\Typora\typora-user-images\image-20210907214518970.png)

##### Fique tranquilo (a), não há necessidade de instalar esse sistema em máquina virtual nenhuma, ele roda todo no próprio navegador mesmo.



### 3) Imprima no terminal do Fedora uma sequência de 1 a 10.

_seq 1 10_



### 4) Calcule o tempo de rota pelo Fedora para o site (www.pudim.com.br)
_time traceroute www.pudim.com.br_



### 5) Calcule o tempo de resposta do Fedora em processar uma sequencia de 1 a 10

_time seq 1 10_



### 6) Crie um arquivo e acesse-o através do editor de texto do fedora (vi)

_vi texto.txt_



### 7) Escreva no editor "Olá Mundo"

##### Para ativar o modo insert no vi, é preciso eu pressionar o qualquer teclado do teclado 2x, para entrar em modo insert.

Após inserir o texto "Olá Mundo", aperte a tecla "ESC", em seguida digite ":wq! + ENTER"



### 8) Imprima no terminal Fedora 33 "Olá Mundo"

_cat texto.txt_



### 9) Imprima no terminal a quantidade de linhas do texto

_wc -l texto.txt_



### 10) Imprima no terminal a quantidade de palavras do texto

_wc -w texto.txt_



### 10) Imprima no terminal a quantidade de bytes

_wc -c texto.txt_



### 11) Crie um arquivo "vazio.txt" e faça a comparação com o "texto.txt"

_touch vazio.txt_

_cmp vazio.txt texto.txt_



### 12) Edite o arquivo vazio.txt com o vi (escreva uma sequencia de números aleatórios com quebras de linhas)

_vi vazio.txt_

Após o preenchimento, aperte a tecla "ESC", insira ":wq!" + "Enter"



### 13) Organize esses valores aleatórios do arquivo vazio.txt em ordem numérica 

_sort -n vazio.txt_



### 14) Desligue a máquina por comando

_init 0_

ou

_telinit 0_

ou

_halt_



### 15) Imprima no terminal Fedora as informações de reinicialização

_last reboot_



### 15) Utilize o comando elias, criando apelido para o "history"

_alias hh='history'_

_hh_

![image-20210907222316358](C:\Users\Tiago\AppData\Roaming\Typora\typora-user-images\image-20210907222316358.png)



### 16) Utilize o comando para saber onde está o programa "ls"

_whereis ls_



### 17) Por fim, utilize o comando para sair do local host (Agora é só dar F5 no navegador) 

_logout_
