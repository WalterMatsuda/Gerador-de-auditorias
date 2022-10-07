# Gerador-de-auditorias
1 - Execute a função dentro do database que deseja auditar , 

2 - Execute a função informando o nome do schema que será auditado =>SELECT gerar_rules(NOME_DO_SCHEMA);

3 - Copie o retorna da função, execute este script no banco.



O Schema informado gerará as tabelas no schema auditoria e as rules que irão inserir um log dentro da tabela correspondente em auditorias para auditar o banco.
