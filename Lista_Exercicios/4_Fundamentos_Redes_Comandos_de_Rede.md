# Lista 4 - EXERCICIO PRÁTICO DE REVISÃO :notebook:



### 1) Crie um arquivo de aularedes.txt

_touch aularedes.txt_



### 2) Exiba o número de IP da rede no terminal

_hostname -I_



### 3) Adicione a saída do comando anterior ao arquivo aula redes.txt

_echo -e "---INFORMACAO DE IP---" >> aularedes.txt_

_hostname -I >> aularedes.txt_



### 4) Exiba o número de IP Loopback no terminal

_hostname -i_



### 5) Adicione a saída do comando anterior ao arquivo aularedes.txt

_echo -e "---INFORMACAO DE ENDEREÇO (Loopback)---\n" >> aularedes.txt_

_hostname -i >> aularedes.txt_



### 6) Exiba Informações DNS sobre o host www.pudim.com.br

_dig www.pudim.com.br_



### 7) Adicione a saída do comando anterior ao arquivo aularedes.txt

_echo -e "\n---INFORMACAO DE DNS HOST (wwww.pudim.com.br)---" >> aularedes.txt_

_dig www.pudim.com.br >> aularedes.txt_



### 8) Exiba Informações do Usuário logado na rede

_w_



### 9) Adicione a saída do comando anterior ao arquivo aularedes.txt

_echo -e "\n---INFORMACAO DE USUARIO LOGADO NA REDE---" >> aularedes.txt_

_w >> aularedes.txt_



### 10) Execute um teste no host www.pudim.com.br com 6 pacotes

_ping www.pudim.com.br -w 6_



### 11) Adicione a saída do comando anterior ao arquivo aula redes.txt

_echo -e "\n---INFORMACAO DE TESTE DO HOST (www.pudim.com.br)---" >> aularedes.txt_

_ping www.pudim.com.br -w 6 >> aularedes.txt_



### 12) Trace a Rota do seu computador até o host www.pudim.com.br

_traceroute www.pudim.com.br_



### 13) Adicione a saída do comando anterior ao arquivo aula redes.txt

_echo -e "\n---INFORMACAO DE ROTA (www.pudim.com.br)---" >> aularedes.txt_

_traceroute www.pudim.com.br >> aularedes.txt_



### 14) Exiba Informações sobre Interfaces de Rede e Endereços IP no terminal

_ifconfig_



### 15) Adicione a saída do comando anterior ao arquivo aula redes.txt

_echo -e "\n---INFORMACOES INTERFACES DE REDE E ENDERECOS IP---" >> aularedes.txt_

_ifconfig >> aularedes.txt_



### 16) Limpe o terminal

_clear_ 

ou 

_CTRL + L_



### 17) Imprima o arquivo aularedes.txt com paginação no terminal

_cat aularedes.txt | more_



