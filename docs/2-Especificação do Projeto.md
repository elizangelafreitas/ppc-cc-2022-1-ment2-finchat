# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Lucas Fernandes 23 anos, é desenvolvedor e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando um meio de controlar suas finanças em um lugar que já possui o habito de utilizar, para poder realizar o sonho de atingir a sua liberdade finaceira.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`          |PARA ... `MOTIVO/VALOR`                 |
|--------------------|---------------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar meus gastos                       | Poder consultá-los posteriormente      |
|Usuário do sistema  | Receber um lembrete de registro de gastos   | Não me esquecer de registrar os gastos |
|Usuário do sistema  | Receber uma consolidação dos gastos semanal | Saber o total dos gastos da semana     |
|Usuário do sistema  | Receber uma consolidação dos gastos mensal  | Saber o total dos gastos do mês        |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário registre uma despesa com descrição, categoria e valor | ALTA | 
|RF-002| Emitir um relatório de gastos semanal e a diferença com os gastos da semana anterior   | MÉDIA |
|RF-003| Emitir um relatório de gastos mensal e a diferença com os gastos do mês anterior   | MÉDIA |
|RF-004| Enviar uma notificação às 22h caso o usuário não tenha feito nenhum registro até o momento   | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser integrado com o Telegram | ALTA | 
|RNF-002| Deve possuir um backend hospedado em uma cloud gratuita (Heroku) |  ALTA | 
|RNF-003| Deve ser construído com uma ferramenta com facilidade de integração com multicanais |  ALTA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
