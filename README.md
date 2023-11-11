# banco_funcionarios

nessa atividade desenvolvemos algumas ações em um banco de dados de funcionarios de uma empresa
usamos os seguintes comandos para fazer algumas alterações:

use momento;

select * from funcionarios;
 
select * from departamentos;
  
select * from paises;
  
select * from escritorios;
    
select * from ocupacoes;

select * from dependentes;


  
  INSERT INTO funcionarios (primeiro_nome, sobrenome, email, telefone, data_contratacao, ocupacao_id, salario, gerente_id, departamento_id) VALUES 
('Breno', 'Maia', 'maiabre5533zmail.org', '77.95533-33575', '2024-05-01', 5, 57000.00, 100, 6 );


  INSERT INTO funcionarios (primeiro_nome, sobrenome, email, telefone, data_contratacao, ocupacao_id, salario, gerente_id, departamento_id) VALUES 
('Everton', 'Megatokio', 'megatokiozmail.org', '11.99888-88000', '2024-02-08', 5, 200000.00, 100, 6 );


  INSERT INTO funcionarios (primeiro_nome, sobrenome, email, telefone, data_contratacao, ocupacao_id, salario, gerente_id, departamento_id) VALUES 
('Henry', 'BuenDJ', 'melhordjzmail.org', '199.900033-3355', '2024-01-24', 5, 199850.00, 100, 6 );


  INSERT INTO funcionarios (primeiro_nome, sobrenome, email, telefone, data_contratacao, ocupacao_id, salario, gerente_id, departamento_id) VALUES 
('Xerox', 'Silva', 'Xerox06533zail.org', '010.970533-3355', '2025-11-01', 5, 1000.00, 100, 5 );



SELECT COUNT(*) AS funcionario_id
FROM funcionarios
where departamento_id = 10;


 INSERT INTO funcionarios (primeiro_nome, sobrenome, email, telefone, data_contratacao, ocupacao_id, salario, gerente_id, departamento_id) VALUES 
('Willian', 'Ferreira', 'will2k22gmail.org', '010.970003-3355', '2028-10-01', 9, 3000.00, 100, 12 );


 INSERT INTO funcionarios (primeiro_nome, sobrenome, email, telefone, data_contratacao, ocupacao_id, salario, gerente_id, departamento_id) VALUES 
('Fernanda', 'Lima', 'felima03gmail.org', '010.933332-3355', '2028-11-01', 9, 3000.00, 100, 12 );


 INSERT INTO funcionarios (primeiro_nome, sobrenome, email, telefone, data_contratacao, ocupacao_id, salario, gerente_id, departamento_id) VALUES 
('Sumaia', 'Azevedo', 'maiasu00gmail.org', '010.973332-9955', '2028-11-03', 20, 3000.00, 100, 12 );


SELECT COUNT(*) AS funcionario_id
FROM funcionarios;


SELECT AVG(salario) AS salario
FROM funcionarios;


SELECT AVG(salario) AS salario
FROM funcionarios
where departamento_id = 5;


insert into departamentos ( departamento_nome, escritorio_id) values
( 'inovações', 5400 );


insert into ocupacoes ( ocupacao_nome, min_salario, max_salario) values 
( 'Gerente de inovações', 2400.00, 18300.00 );


SELECT AVG(salario) AS salario
FROM funcionarios
where departamento_id = 1 and 10;
