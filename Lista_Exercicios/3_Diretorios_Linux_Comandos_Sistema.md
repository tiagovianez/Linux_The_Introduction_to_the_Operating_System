# Lista 3 - EXERCICIO PRÁTICO DE REVISÃO :notebook:



### 1) Criando o arquivo 

_touch minhamaquina.txt_



### 2) Inserindo título de informações sobre o Hardware no arquivo minhamaquina.txt

_echo -e "---INFORMAÇOES DE HARDWARE---n\" > minhamaquina.txt_



### 3) Exiba todos os hardwares que existem na máquina com paginação

_lshw | more_



### 4) Salve a saída do comando anterior no arquivo minhamaquina.txt

_lshw >> minhamaquina.txt_



### 5) Exiba informações sobre a memória física e virtual na sua máquina

_free_



### 6) Adicione a saída do comando anterior ao arquivo minhamaquina.txt 

_echo -e "\n---INFORMACOES SOBRE MEMORIA---" >> minhamaquina.txt_

_free >> minhamaquina.txt_



### 7) Exiba todas as placas PCI conectadas

_lspci_



### 8) Adicione a saída do comando anterior ao arquivo minhamaquina.txt

_echo -e "\n---INFORMACOES SOBRE PLACAS CONECTADAS---" >> minhamaquina.txt_

_lspci >> minhamaquina.txt_



### 9) Exiba todos dispositivos USB conectados

_lsusb_



### 10) Adicione a saída do comando anterior ao arquivo minhamaquina.txt

_echo -e "\n---INFORMACOES SOBRE USB---" >> minhamaquina.txt_

_lsusb >> minhamaquina.txt_



### 11) Exiba as informações sobre processador

_lscpu_



### 12) Adicione a saída do comando anterior ao arquivo minhamaquina.txt 

_echo -e "\n---INFORMACOES DE CPU (PROCESSADOR)---" >> minhamaquina.txt_

_lscpu >> minhamaquina.txt_



### 13) Exiba o nome do kernel

_uname_



### 14) Adicione a saída do comando anterior ao arquivo minhamaquina.txt

_echo -e "\n---INFORMACOES DO KERNEL (NOME)---" >> minhamaquina.txt_

_uname >> minhamaquina.txt_



### 15) Exiba a versão do Kernel

_uname -r_



### 16) Adicione a saída do comando anterior ao arquivo minhamaquina.txt

_echo -e "\n---INFORMACOES DA VERSÃO DO KERNEL---" >> minhamaquina.txt_

_uname -r >> minhamaquina.txt_



### 17) Exiba a arquitetura do Kernel e adicione a saida desse comando ao arquivo minhamaquina.txt

_uname -m_ 

_echo -e "\n---INFORMACOES DE ARQUITETURA---" >> minhamaquina.txt_

_uname -m >> minhamaquina.txt_



### 18) Reinicie a máquina

_reboot_



### 19) Abra o arquivo minhamaquina.txt

Pela própria pasta do sistema Linux



### 20) Desligue a maquina

_init0_

