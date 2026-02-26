# 3d2026
Links
<h2>Laboratório de Software</h2>
<p>
  Projeto de Software<br>
  https://www.monitoratec.com.br/blog/projeto-de-software/
</p>
<p>
   Fases de desenvolvimento de projeto<br>
  https://drive.google.com/file/d/1rTqW02ieh7PfYugO6fweb-oUQYHOA8mB/view
</p>
<p>
  Conhecendo o projeto a ser desenvolvido<br>
  https://drive.google.com/file/d/12OOQRXyfQ7H8AZ0au15pE1VEpcbYYkiQ/view
</p>
<p>
  biblioteca.sql<br>
 CREATE TABLE editora( 
 id INT PRIMARY KEY AUTO_INCREMENT,  
 nome VARCHAR(50) NOT NULL,  
 email VARCHAR(50) NOT NULL,  
 telefone VARCHAR(50) NOT NULL  
); 

CREATE TABLE autor 
( 
 id INT PRIMARY KEY AUTO_INCREMENT,  
 nome VARCHAR(50) NOT NULL  
); 

CREATE TABLE obra 
( 
 id INT PRIMARY KEY AUTO_INCREMENT,  
 titulo VARCHAR(50) NOT NULL,  
 id_genero INT  
); 

CREATE TABLE genero 
( 
 id INT PRIMARY KEY AUTO_INCREMENT,  
 nome VARCHAR(50) NOT NULL  
); 

CREATE TABLE livro 
( 
 id INT PRIMARY KEY AUTO_INCREMENT,  
 isbn INT,  
 paginas INT NOT NULL,  
 ano INT NOT NULL,  
 id_obra INT NOT NULL,  
 id_editora INT NOT NULL   
); 

CREATE TABLE usuario 
( 
 cpf VARCHAR(50) PRIMARY KEY,  
 nome VARCHAR(50) NOT NULL,  
 email VARCHAR(50) NOT NULL,  
 telefone VARCHAR(50) NOT NULL,  
 endereco VARCHAR(50) NOT NULL,  
 numero INT NOT NULL,  
 bairro VARCHAR(50) NOT NULL,  
 cidade VARCHAR(50) NOT NULL,  
 uf VARCHAR(50) NOT NULL,  
 data_nascimento DATE NOT NULL,  
 id_tipo_usuario INT  
); 

CREATE TABLE tipo_usuario 
( 
 id INT PRIMARY KEY AUTO_INCREMENT,  
 nome VARCHAR(50) NOT NULL  
); 

CREATE TABLE emprestimo 
( 
 id INT PRIMARY KEY AUTO_INCREMENT,  
 data_inicio DATE NOT NULL,  
 data_fim DATE,  
 id_livro INT,  
 id_usuario INT,  
 id_bibliotecario INT NOT NULL  
); 

CREATE TABLE autor_obra 
( 
 id INT PRIMARY KEY AUTO_INCREMENT,  
 id_autor INT,  
 id_obra INT  
); 
</p>
<hr>
<h2>Gestão de Startup III</h2>
<p>
  Identificando dores do consumidor<br>
  https://professormurara.wordpress.com/2012/10/09/empreendedorismo-necessidade-desejo-e-demanda/
</p>
<p>
  Persona e Mapa e Empatia<br>
  https://pingback.com/br/resources/personas/<br>
  https://docs.google.com/presentation/d/1aNDBSRrqZSwz3Uw6BQQ0tPVadh3bM2SCNw2SNVb_LX4/edit
</p>
