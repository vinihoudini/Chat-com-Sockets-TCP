# Chat-com-Sockets-TCP
Prática 1 (Extra)

Bate-Papo desenvolvido para a disciplina de Sistemas Distribuídoss na Universidade Federal da Paraiba. Funciona em rede local com o uso de sockets, o trabalho foi implementado na estrutura cliente-servidor. O código foi desenvolvido na linguagem Python, versão 3.

Funcionamento do servidor: O servidor é responsável por receber as mensagens dos clientes e a partir disso verificar se ela é um comando (bloquear, desbloquear, enviar mensagem privada, lista de onlines, lista de bloqueados, sair). Além disso, o servidor deve manter o correto funcionamento do bate-papo, executando o comando que é pedido pelo cliente ou enviando mensagem de um deles para todos os outros.

Funcionamento do cliente: Quando o cliente se conecta ao servidor, ele deve informar seu nome/apelido, sendo que este não pode ser igual ao nome/apelido de nenhum dos usuários que estão conectados no momento. O cliente pode mandar tanto mensagens públicas quanto mensagens privadas. Além disso, ele pode bloquear e desbloquear usuários, ver lista de clientes conectados no bate-papo no presente momento e visualizar a lista de usuários que estão bloqueados.

#Comandos que podem ser usados pelo cliente:

/tchau 
	O comando /tchau é usado pelo cliente quando este quer se retirar do bate-papo. Caso o cliente dê um Ctrl + C no terminal, ele também é desconectado corretamente do bate-papo pois envia, por default, o /tchau para o servidor. 
	
/bloquear usuario
	O comando /bloquear é usado para bloquear um usuário, no lugar de 'usuário' deve-se colocar o nome do usuário que será bloqueado. O usuário que foi bloqueado recebe mensagem de aviso sobre isso.

/desbloquear usuario
	O comando /desbloquear é usado para desbloquear um usuário, no lugar de 'usuário' deve-se colocar o nome do usuário que será desbloqueado. O usuário que foi desbloqueado recebe mensagem de aviso sobre isso.

/lista_bloqueados
	O comando /lista_bloqueados é usado para ver a lista de usuários que foram bloqueados pelo próprio cliente na sessão corrente.

/lista_online
	O comando /lista_online é usado para ter acesso a lista de usuários que estão conectados no bate-papo no presente momento.

/apelido
	O comando /apelido é usado para enviar mensagem privada, no lugar de apelido deve-se escrever o nome/
