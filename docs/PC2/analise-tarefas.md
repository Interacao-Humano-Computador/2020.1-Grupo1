# Análise de Tarefas:
A análise de tarefas é utilizada para se ter um entendimento sobre qual é o trabalho dos usuários, a forma como eles o realizam e a finalidade. Nela, o trabalho é definido em termos dos objetivos que os usuários querem ou precisam atingir.[1]
Em IHC, esse tipo de análise pode ser utilizado nas três atividades habituais: para análise da situação atual, para o design de um sistema computacional ou para a avaliação do resultado de uma intervenção que inclua a introdução de um sistema computacional. Se seu objetivo é avaliar um sistema computacional existente, a análise de tarefas pode ser bem definida, descrevendo o comportamento de forma detalhada. Já numa situação de design, a análise de tarefas geralmente será realizada num nível maior de abstração, pois diversos pontos ainda não terão sido definidos no início da atividade de design.[1]

<br>
<br>


## HTA 01 - Marcar Presença

![Presença - HTA](../images/analises-tarefas/Presença_HTA.png)

| Objetivos/Operações           | Problemas e recomendações                                    |
| ----------------------------- | ------------------------------------------------------------ |
| 0. Marcar Presença<br>1 > 2 | Plano: Entrar no sistema, informando a turma **e depois** clicar no indicativo de presença.<br>Feedback: Indicativo de presença ou ausência na aula. |
| 1. Entrar no Sistema<br> 1 > 2 | Input: Login e senha do aluno, código da turma, disciplina e semestre<br>Plano: Além de entrar com seu login e sua senha, o aluno deve informar código da turma, disciplina e semestre **e depois** selecionar a turma para poder marcar a presença. |
| 1.1 Informar código da turma, disciplina e semestre |                                                              |
| 1.2 Selecionar turma |                                                              |
| 2. Clicar no Indicativo de presença | Ação: Presença deve ser marcada em determinado hora |

<br>
<br>

## HTA 02 - Fazer Prova

![Prova - HTA](../images/analises-tarefas/Presença_HTA.png)

| Objetivos/Operações                                 | Problemas e recomendações                                    |
| --------------------------------------------------- | ------------------------------------------------------------ |
| 0. Fazer Prova<br> 1 > 2                            | Plano: Entrar no sistema, informando a turma **e depois,** com o código fornecido pelo professor, realizar a prova.Feedback: Indicativo de conclusão da prova. |
| 1. Entrar no sistema<br> 1 > 2 > 3                  | Input: Login e senha do aluno, código da turma, disciplina e semestre, senha fornecida pelo professor para fazer a prova.<br>Plano: Além de entrar com seu login e sua senha, o aluno deve informar código da turma, disciplina e semestre **e depois** selecionar a turma para poder marcar a presença **e depois** acessar a prova com a senha fornecida pelo professor. |
| 1.1 Informar código da turma, disciplina e semestre |                                                              |
| 1.2 Selecionar Turma                                |                                                              |
| 1.3 Entrar com a senha fornecida pelo professor.    | Input: Senha fornecida.                                      |
| 1.3.1 Responder as questões                         |                                                              |
| 2. Enviar a prova respondida                        | Ação: Enviar as respostas da prova.                          |

<br>
<br>

## Referências:

[1] BARBOSA, Simone Diniz Junqueira; DA SILVA, Bruno Santana. Interação humano-computador. Capítulo 6 - Organização do Espaço de Problema. Elsevier, 2010. Disponibilizado no material de apoio da turma.

<br>
<br>

## Versionamento:

| Data:      | Versão: | Descrição:           | Autor:                       |
|------------|---------|----------------------|------------------------------|
| 05/10/2020 | 0.1     | Criação da Análise de Tarefas | Rafael Ribeiro |
| 08/10/2020 | 1.0     | Criação da Página com as Análises de Tarefas | Gabriel Paiva, Murilo Gomes e Rafael Ribeiro |
