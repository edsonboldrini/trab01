# TRABALHO 01
Trabalho desenvolvido durante a disciplina de BD

#Sumário

###1	COMPONENTES<br>
Edson Simões Boldrini e Everson Delmaschio<br>

###2	INTRODUÇÃO E MOTIVAÇAO<br>
Este documento contém a especificação do projeto do banco de dados <nome do projeto> e motivação da escolha realizada. <br>

###3	MINI-MUNDO<br>
O SUS quer um sistema de realocação de médicos sejam elas por motivos emergenciais ou motivos de remanejamento apenas. 
Esse sistema funcionará como. Um cadastro de todos os médicos disponíveis. Nesse cadastro, deverão ser informados dados como: Nome, data de nascimento, Registro militar(se houver), local onde mora, especialidade, doenças tratadas etc. 
Depois de feito esse cadastro, os técnicos do SUS que irão trabalhar nesse sistema farão os remanejamentos de acordo com a necessidade de cada região. Se em determinada região há um número excessivo de médicos de uma determinada especialidade, ele também pode ser remanejado para outro lugar. 
Nesse sistema, também será possível visualizar as consultas e as doenças que determinado médico fez durante um período de tempo, podendo assim visualizar como e com o que ele trabalhou em um determinado período de tempo.<br>

###4	RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>

![Alt text](https://github.com/edsonsb96/trab01/blob/master/Tela%20Inicial.png)
![Alt text](https://github.com/edsonsb96/trab01/blob/master/Tela%20de%20%20solcita%C3%A7%C3%A3o.png)
![Alt text](https://github.com/edsonsb96/trab01/blob/master/Tela%20de%20Cadastro%20emergencia.png)
![Alt text](https://github.com/edsonsb96/trab01/blob/master/Tela%20de%20Consulta.png)
![Alt text](https://github.com/edsonsb96/trab01/blob/master/Tela%20de%20Graficos.png)
![Alt text](https://github.com/edsonsb96/trab01/blob/master/Tela%20de%20Login.png)
![Alt text](https://github.com/edsonsb96/trab01/blob/master/Tela%20de%20Relatorios.png)
![Alt text](https://github.com/edsonsb96/trab01/blob/master/Tela%20de%20cadastro%20vaga.png)


###5	MODELO CONCEITUAL<br>
    5.1 NOTACAO ENTIDADE RELACIONAMENTO
![Alt text](https://github.com/edsonsb96/trab01/blob/master/BD_SUS.jpg "Modelo Conceitual")
    
    5.2 NOTACAO UML (Caso esteja fazendo a disciplina de analise)

####5.1 Validação do Modelo Conceitual
    [Grupo01]: [Nomes dos que participaram na avaliação]
    [Grupo02]: [Nomes dos que participaram na avaliação]

####5.2 DECISÕES DE PROJETO
    [atributo]: [descrição da decisão]
    
    EXEMPLO:
    a) Campo endereço: em nosso projeto optamos por um campo multivalorado e composto, pois a empresa 
    pode possuir para cada departamento mais de uma localização... 
    b) justifique!

####5.3 DESCRIÇÃO DOS DADOS 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>


###6	MODELO LÓGICO<br>
###7	MODELO FÍSICO<br>
###8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
####8.1 DETALHAMENTO DAS INFORMAÇÕES
        Detalhamento sobre as informações e processo de obtenção ou geração dos dados.
        Referenciar todas as fontes referentes a :
        a) obtenção dos dados
        b) obtenção de códigos reutilizados
        c) fontes de estudo para desenvolvimento do projeto
        
####8.2 INCLUSÃO DO SCRIPT PARA CRIAÇÃO DE TABELA E INSERÇÃO DOS DADOS
        a) inclusão das instruções para criação das tabelas e estruturas de amazenamento do BD
        b) inclusão das instruções de inserção dos dados nas referidas tabelas
        c) inclusão das instruções para execução de outros procedimentos necessários

###9	TABELAS E PRINCIPAIS CONSULTAS<br>
####9.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS<br>
####9.2	CONSULTAS DAS TABELAS COM FILTROS WHERE<br>
####9.3	CONSULTAS QUE USAM OPERADORES LÓGICOS, ARITMÉTICOS E CAMPOS RENOMEADOS<br>
####9.4	CONSULTAS QUE USAM OPERADORES LIKE<br>
####9.5	ATUALIZAÇÃO E EXCLUSÃO DE DADOS<br>
####9.6	CONSULTAS COM JUNÇÃO<br>
####9.7	CONSULTAS COM GROUP BY<br>
####9.8	CONSULTAS COM LEFT E RIGHT JOIN<br>
####9.9	CONSULTAS COM SELF JOIN E VIEW<br>
####9.10	SUBCONSULTAS<br>
###10	ATUALIZAÇÃO DA DOCUMENTAÇÃO DOS SLIDES<br>
###11	DIFICULDADES ENCONTRADAS PELO GRUPO<br>
###12  FORMATACAO NO GIT: https://help.github.com/articles/basic-writing-and-formatting-syntax/
