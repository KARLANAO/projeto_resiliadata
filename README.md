<h1>--> Projeto Resilia Módulo 2 - Sistema RESILIADATA</h1>

## 📌 Descrição do Projeto

➔ O sistema irá auxiliar na avaliação de quais são as tecnologias que as empresas parceiras
estão utilizando e quem são seus colaboradores;

➔ Vamos ter o cadastro de empresas parceiras, cadastro de tecnologias com a opção de
selecionar a área (webdev, dados, marketing, etc.), uma tabela para registrar quais
tecnologias as empresas estão utilizando e uma tabela para cadastro de colaboradores.

## 📌 Modelo Lógico

![image](https://github.com/KARLANAO/projeto_resiliadata/assets/112179212/60c2a356-2027-4202-a13c-45a0fa376146)
Ferramenta de Modelagem - StarUML

## Perguntas sobre o Modelo

## 1. Quais são as entidades necessárias?
As entidades necessárias são: Empresa parceira, Tecnologia e Colaborador.

## 2. Quais são os principais campos e seus respectivos tipos?
Os principais campos e seus tipos são:

+ Empresa Parceira:
ID (Inteiro)
Nome (Texto)
Localização (Texto)
Email (Texto)

+ Tecnologia:
ID (Inteiro)
Nome (Texto)
Area (Texto)

+ Colaborador:
ID (Inteiro)
Nome (Texto)
Cargo (Texto)
ID empresa (Inteiro)



## 3. Como essas entidades estão relacionadas?
As relações ocorrem da seguinte forma: 

+ Cada Colaborador está associado a uma Empresa.
+ Uma Empresa pode utilizar várias Tecnologias.

## 4. Simule 2 registros para cada entidade.

empresa_parceira

|         empresas_parceiras        |      Coluna 1      |      Coluna 2      |      Coluna 3      |
| :------------------------------: | :----------------: | :----------------: | :----------------: |
|        Left-aligned text         |    Center-aligned text    |    Right-aligned text   |    Fourth column    |
|        Left-aligned text         |    Center-aligned text    |    Right-aligned text   |    Fourth column    |

tecnologia 

|      empresas_parceiras      |      Coluna 1      |      Coluna 2      |
| :--------------------------: | :----------------: | :----------------: |
|      Left-aligned text       |  Center-aligned text  |  Right-aligned text |
|      Left-aligned text       |  Center-aligned text  |  Right-aligned text |


empresa_tecnologia

|      empresas_parceiras      |      Coluna 1      |
| :--------------------------: | :----------------: |
|      Left-aligned text       |  Center-aligned text  |
|      Left-aligned text       |  Center-aligned text  |

colaborador
|         empresas_parceiras        |      Coluna 1      |      Coluna 2      |      Coluna 3      |
| :------------------------------: | :----------------: | :----------------: | :----------------: |
|        Left-aligned text         |    Center-aligned text    |    Right-aligned text   |    Fourth column    |
|        Left-aligned text         |    Center-aligned text    |    Right-aligned text   |    Fourth column    |


