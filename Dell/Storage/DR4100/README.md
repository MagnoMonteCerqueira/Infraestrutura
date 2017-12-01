


![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/banner-dell.jpg)

##                                     Procedimento de Reimage do equipamento de backup em disco Dell DR4100!


## Introdução.

Com as empresas que operam 24/7, os departamentos de TI estão sob intensa pressão para garantir disponibilidade de dados e
integridade enquanto ainda conhece a capacidade e as restrições da janela de backup. O dispositivo de backup de disco Dell DR4100
com tecnologia de duplicação e compressão integrada pode ajudar a superar esses desafios, reduzindo a
quantidade de dados que precisa ser armazenada e replicada. Ao remover dados redundantes do trabalho de backup
O DR4100 pode reduzir drasticamente a pegada de armazenamento, permitir que os dados de backup permaneçam no disco e
mais on-line, fornecem restaurações mais rápidas e confiáveis e reduzem a complexidade do gerenciamento de fitas


## Requisitos:

DR4100.


## Reimage.

###### 1) Vamos acessar o DR4100 via web (idrac):

![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-01.PNG)

```sh
# Usuario: root
# Senha: calvin
```
##
###### 2) Para iniciar o procedimento sera solicitado a troca da senha:
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-02.PNG)


##
###### 3) Dentro da Idrac, vamos clicar em launch e executar o aplicativo java para acesso via console:
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-03.PNG)

##
###### 4) Apos executar o console via java , vamos acessar via CLI o DR4100:
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-04-1.PNG)

```sh
# Usuario: administrator
# Senha: St0r@ge!
```

##
###### 5) Vamos reiniciar o equipamento:
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-05.PNG)

##
###### 6) Apos reiniciar o DR4100, vamos precionar F2 para acessar o System Setup e configurar para boot via usb:
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-06.PNG)

##
###### 7) Configurando o Zabbix Proxy para conexao ao banco de dados:
OBS: Vamos selecionar, System Bios => Boot Settings => Bios Boot Settings => Hard-Disck Drive Seguence, e selecionar o pendrive como boot primario, clique em OK 
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-07.PNG)

##
###### 8) Na tela de Restore Manager, vamos selecionar Factory Reset, e fomatar o equipamento:
OBS: sera solicitado a senha para seguir com o procedimento, a mesma se encontra abaixo da tela do Restore Manager
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-08.PNG)
```sh
# Senha: resetmyappliance
```

##
###### 9) Sera iniciado o restore do equipamento:
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-09.PNG)

##
###### 10) Sera iniciado o diagnostico do equipamento, clique em next:
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-10-1.PNG)

##
###### 11) Aguarde os testes:
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-11.PNG)

##
###### 12) Testes concluidos, vamos reiniciar o DR4100:
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-12-1.PNG)

##
###### 13) Ao reiniciar o equipamento , sera iniciado a restauração do software do equipamento, vamos aguardar:
![Alt Text](https://raw.githubusercontent.com/MagnoMonteCerqueira/Infraestrutura/master/src/img/Dell/DR4100/dr4100-13-1.PNG)


##

## Contatos:


* Telegram: @Magnopeem
* Skype: magnopeem_rj@hotmail.com
* E-mail: magnopeem@gmail.com
* Linkedin: https://br.linkedin.com/in/magno-monte-cerqueira-976b1587
