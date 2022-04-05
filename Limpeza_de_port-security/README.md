#  <center>Limpeza de Port-security</center>

## Detalhes

A função desse script é facilitar a tarefa de limpeza de MAC Address presos na porta do switch, por conta do port-security habilitado.  

Invés de logar no switch e ficarmos procurando de uma forma manual o MAC Address da máquina anterior que estava vinculado naquela interface, o script faz esse processo automatico, limpando todas as interfaces de uma única vez e por fim roda o comando para desabilitar e habilitar as interfaces deixando todas disponiveis para uso. 