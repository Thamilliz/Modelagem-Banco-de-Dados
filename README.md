# Modelagem-Banco-de-Dados 

O projeto tem como objetivo criar um banco de dados para um novo Sistema de Acompanhamento! 
Criando novas entidades tais como: Curso, Turma e Aluno. 


Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem
e responder algumas perguntas com nosso modelo:
⇨ Existem outras entidades além dessas três? 
⇨ Quais são os principais campos e tipos?
⇨ Como essas entidades estão relacionadas?


1-Sim. Entidade Professor!

2- Os principais campos são: Nome do tipo Varchar, Cod do tipo INT, Data de inicio do tipo date e cep do tipo INT. 

3- As entidades estão relacionadas da seguinte forma: Por exemplo, a entidade curso está relacionada a Turma como muito para muitos (N:N), porque um curso pode ter mais de uma turma, assim como uma turma pode ter mais de um aluno. Porém um aluno só pode ter uma turma. 
E uma turma pode ter vários professores, assim um professor pode ter vários alunos. 
