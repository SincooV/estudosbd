##   Sintaxe SQL 

##  table_name é o nome dado a sua tabela
 `valores: text ,uuid,smallint`
# criar tabela : 
`create table table_name(id uuid, nome text....);` 
##  //dentre outras colunas
# colocar nova coluna em uma table :
` alter table table_name peso smallint;` 
# nome da nova coluna é peso!
# excluir colunas específicas em uma table : 
  `alter table table_name drop column peso`.
##    adicionar Dados A uma Tabela  : 
   `inser into  table_name(coluna1,coluna2,coluna3......) VALUES ("valor,valor2,valo3");`
   
## VALORES A COLOCAR NA COLUNA TEM QUE ESTAR COM " " 
///////   ENTRE ASPAS