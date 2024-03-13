##  bd diagram 
isso não vai fazer a tabela é só uma explicação logica com outros exemplos, e sintaxe
# table clientes{ id uuid [primary key,unique,not null] ... nome text [not null] cpf text [not null]
## REGRAS
# 1 toda tabela tem um id PK (primary key) id uuid < uuid é o valor encrypitado sem ordem como int (não tenho certeza to fazendo isso de ultima hora ) quando queremos definir informações como obrigatorias ou não nulas utilizamos  [not null,....     ]  toda informação depois de not null ou oque for tem que ter uma virgula
# temos ,not null : unique :primary key dentre outros que você pode achar em docs do dbdiagram ou até mesmo em outras como postgres
# porque usamos text em cpf??? ou em numeros de telefone isso acontece por que int ou decimal,double ou smallint oque for exclui qualquer tipo de zero que não tenha um numero na sua frente
# quebrando a formatação de um cpf por exemplo que existe .

