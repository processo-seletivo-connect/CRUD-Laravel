Criar um CRUD em laravel9
-> Baixar o Laravel 9 (composer)
-> Utilizar o Jetstream (biblioteca oficial do laravel p/ login, registration, email verification, etc)
-> Utilizar o Mysql
-> Implementar um CRUD para gestao de Funcionários, com as seguintes telas:
	->Cadastro de funcionário
	->Editar funcionário
	->Pesquisar funcionários
	->Excluir funcionário	  	
	
	obs: criar uma migration e uma Model de Funcionários com os seguintes campos: id (usar padrao do laravel p/ ids), nome (VARCHAR255), email(VARCHAR255), data de nascimento (DATE), data de admissao (DATE), data de demissao (DATE), salario (Decimal 11,2), 
        CPF  (VARCHAR255).




Jetstream utiliza tailwind como biblioteca CSS.
Eh permitido utilizar javascript puro ou alguma lib de JS para melhorar interacao/usabilidade das telas.



Regras/Acoes necessários:

	- email deve ser email válido e único. CPF deve ser um CPF válido e único.
	- Salário deve ser maior que  1300.00	

	- Na tela de pesquisa adicionar filtros por nome, email, data de nascimento, data de admissao data de demissao, salario e CPF
	- Disponibilizar todos campos da tabela funcionarios como colunas da grid da tela de pesquisa
	- Disponibilizar paginacao (15 itens por página)
	- Criar um Seeder para popular a tabela funcionarios
	





Prazo: 3 dias a partir da entrega do teste.
