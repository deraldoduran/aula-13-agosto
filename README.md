# aula-13-agosto
select * from empregado
update empregado set matricula = 99 where nome = 'francisco'; -- matícula é chave primaria e não pode mudar

create table if not exists log_empregado(
  usuario varchar(60) not null,
  data timestamp not null,
  
  
