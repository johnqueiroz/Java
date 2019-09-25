# Java
Atividade Java

	@query="select count(p.StatusPedidos) from Pedidos p WHERE p.StatusPedidos in ('RESPONDIDO', 'BLOQUEADO')"
	@query="select p.StatusPedidos from Pedidos p WHERE p.StatusPedidos in ('BLOQUEADO') LIKE '%ANTONIO%'"
