CREATE DATABASE SIS2402;

USE SIS2402;

CREATE TABLE CLIENTES
(
	`ID_number` INT auto_increment,
	`nome` VARCHAR(50) NOT NULL,
    `email` VARCHAR(50) NOT NULL,
    `nascimento` DATE NOT NULL,
    `rua` VARCHAR(50) NOT NULL,
    `numero` INT,
    `bairro` VARCHAR(50) NOT NULL,
    `cidade` 	VARCHAR(50) NOT NULL,
    `uf` VARCHAR(2) NOT NULL,
    `pais` VARCHAR(50) NOT NULL,
    
    PRIMARY KEY (`ID_NUMBER`)
);
