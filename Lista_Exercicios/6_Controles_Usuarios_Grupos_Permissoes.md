# Lista 6 - EXERCICIO PRÁTICO DE REVISÃO :notebook:



### 1) Crie um usuário chamado teste

_sudo adduser teste_

![image-20210907223752244](C:\Users\Tiago\AppData\Roaming\Typora\typora-user-images\image-20210907223752244.png)



### 2) Crie um grupo chamado, grupoteste

_sudo addgroup grupoteste_



### 3) Adicione o usuário teste ao grupo teste
_sudo adduser teste grupoteste_



### 4) Troque a senha do usuario teste

_sudo passwd teste_



### 5) Troque o usuário atual para o usuário teste

_su teste_



### 6) Exiba os grupos de usuários teste

_cat /etc/group | more_



### 7) Exiba todos os usuários do sistema

_cat /etc/passwd | more_



### 8) Exiba todos os grupos do sistema

_cat /etc/group | more_



### 9) Delete o usuário teste

su "usuário principal"

_sudo userdel -r teste_

##### Feche o terminal e abra novamente

_sudo userdel -r teste_



### 10) Delete o Grupo grupoteste

_sudo groupdel grupoteste_



### 11) Troque para o usuário root

_sudo su_



### 12) Crie um arquivo de nome teste.txt

_touch teste.txt_



### 13) Edite o arquivo teste.txt com o nome desse curso 

_nano teste.txt_

![image-20210907225649971](C:\Users\Tiago\AppData\Roaming\Typora\typora-user-images\image-20210907225649971.png)





### 14) Mude as permissões do arquivo teste.txt para 111

_chmod 111 teste.txt_



### 15) Saia do usuário root para seu computador

_su "user"_



### 16) Tente exibir o arquivo teste.txt no terminal

_cat teste.txt_



### 17) Desligue o computador pelo terminal

_shutdown -h now_

