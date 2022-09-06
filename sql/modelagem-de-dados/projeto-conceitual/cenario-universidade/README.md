# Bootcamp Database Experience - DIO

## Desafio do projeto


### Objetivo:
Criar esquema conceitual para o contexto de universidade com base na narrativa fornecida.


### Narrativa:
* A universidade possui diversos alunos que podem estar matriculados em mais de um curso (graduação).
* Os alunos podem fazer cursos extras fornecidos externa e internamente (universidade) para contar como horas complementares.
* Não há restrição quanto ao número de matérias puxadas se não houver sobreposição de horário.
* Os alunos são submetidos a duas provas por semestre para cada disciplina. 
* Eventuais trabalhos devem ser tratados pelo professor para compor a nota da prova.
* Cada disciplina é fornecida por um professor. Restrição: apenas por este professor.
* Algumas disciplinas possuem pré-requisitos, um mesmo pré requisito pode ser associado a mais de uma disciplina.
* As disciplinas podem ser comuns a cursos distintos. Ex: Cálculo 1 para computação e engenharia
* O ciclo de vida da disciplina é semestral
* Os professores que ministram as disciplinas estão associados as coordenações de seus respectivos cursos. Ex: Computação, Física, Engenharia.

### Desenvolvimento:
MySQL Wokbench

### Arquivos:
* Universidade_V1.mwb - versão inicial
* Universidade_V2.mwb - versão com refinamentos do esquema
* Universidade_V3.mwb - versão final com alterações visuais
* Diagrama_Universidade.png - Imagem do diagrama