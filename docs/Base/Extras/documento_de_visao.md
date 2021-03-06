## Histórico de Versão

| Data       | Versão | Descrição                                                 | Autor(es)      |
| ---------- | ------ | --------------------------------------------------------- | ------------ |
| 30/01/2022 | 1.0    | Criação do documento                                      | Caio Gabriel |
| 31/01/2022 | 1.1    | Detalhamento                                              | Caio Gabriel |
| 01/02/2022 | 1.2    | Revisão do Documento                                      | Caio Gabriel |
| 03/02/2022 | 1.3    | Atualização dos Requisitos Funcionais/Adição N Funcionais | Caio Gabriel |
| 04/02/2022 | 1.4    | Atualização dos Requisitos Funcionais/Adição N Funcionais | Caio Gabriel |
| 21/02/2022 | 1.5    | Revisão | Jaime Juan |

# Documento de Visão

## 1. Introdução

### 1.1. Objetivo

O objetivo deste documento é apresentar a aplicação PartyRental e determinar a sua real utilidade e funcionalidade. Tendo em mente esse objetivo, será realizado uma análise detalhada do projeto, com o intuito de deixar claro as inovações e funcionalidades ofertadas pela aplicação. Desse modo, isso irá ocorrer através de tópicos relativos à descrição do problema, oportunidade de negócios, descrição dos envolvidos, restrições do projeto, dentre outros.

### 1.2. Escopo

_“Imagine uma pequena empresa, que aluga kits para festas, tais como mesas, cadeiras, móveis específicos, talheres, vasos e outros materiais tipicamente utilizados em aniversários, casamentos, formaturas... Todo o processo de aluguel é feito de forma bem tradicional, via ligação de celular, telefone ou pessoalmente. Por que não pensar em uma aplicação web simples, que permita facilitar esse processo de aluguel?”_</br>
Tendo como base a proposta inicial do projeto, pressupõe-se que geralmente o aluguel de equipamentos de trabalho e lazer ocorrem de maneira convencional como mencionado acima na proposta do tema. Materiais para festas e eventos também não fogem desse quesito, pois sabe-se, que para realizar tal atividade, qualquer indivíduo geralmente se dirige a loja física e faz a seleção do seu material com o vendedor. Com o intuito de mitigar essa etapa, e melhorar o conforto do usuário que provavelmente estará sobrecarregado com a organização de sua festa, a aplicação consegue fornecer um serviço útil e ágil para que consumidor final possa descentralizar melhor sua preocupação em relação a esta burocracia.

### 1.3. Definições, acrônimos e abreviações

-   FGA - Faculdade do Gama
-   UnB - Universidade de Brasília

### 1.4. Visão Geral

A organização do documento tem como objetivo possibilitar uma melhor visualização das informações e intenções levantadas pela equipe. Tendo esse ponto como foco, será apresentado inicialmente a motivação por trás da implementação, que resultou no desenvolvimento dessa proposta. Em seguida, serão expostos os envolvidos no projeto, explicitando como a equipe está organizada. Logo após, o documento evidenciará todas as funcionalidades do sistema e demais requisitos fundamentais.

## 2. Posicionamento

### 2.1. Oportunidade de Negócio

Normalmente, nota-se que o aluguel de kits para festas, sendo esses kits de qualquer natureza, é necessário tempo e locomoção para adquirir esses produtos. É perceptível também que o consumidor desses produtos estão preocupados não somente com os kits, mas com toda a burocracia encontrada na realização de um evento. Vendo essa necessidade de desburocratização e economia de tempo, a aplicação disponibilizará vários produtos para festas que podem ser alugados em poucos minutos via aplicação web.

### 2.2. Instrução do Problema

| O problema de                      | haver deslocamento e gasto de tempo para alugar kits/itens de festas.       |
| ---------------------------------- | --------------------------------------------------------------------------- |
| Afeta                              | Todos que organizam eventos/festas periodicamente.                          |
| O impacto do problema é            | Aflição pela burocracia e perda de tempo útil                               |
| Uma solução bem sucedida incluiria | Aluguel de kits para festas e eventos por meio de uma aplicação web online. |

### 2.3. Instrução de Posição do Produto

| Para o        | organizador de eventos doméstico ou comercial                                                             |
| ------------- | --------------------------------------------------------------------------------------------------------- |
| Quem          | _Promoter_ e pessoa física que precisa alugar kits para festas e eventos                                  |
| O             | Aluguel de Kit’s de Festas                                                                                |
| que           | Gera um lista com itens categoricamente separados de eventos/festas que poderão ser alugados pelo usuário |
| De outro modo | ****\*****                                                                                                |
| nosso produto | Disponibilizará de maneira inteiramente online, o aluguel de itens para festas/eventos.                   |

## 3. Descrição das Partes Interessadas

### 3.1. Resumo da das Partes Interessadas

| Nome                      | Descrição                                                                             | Responsabilidade                                                  |
| ------------------------- | ------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Equipe de Desenvolvimento | Estudantes da disciplina de Arquitetura e Desenho de Software ministrada na FGA, UnB. | Documentar, gerenciar, desenvolver, testar e implantar o produto. |
| Consumidor                | Indivíduo que precisa alugar itens de festa para seu evento.                          | --------                                                          |

### 3.2. Perfil das Partes Interessadas

#### 3.2.1. Desenvolvedores

| Desenvolvedores                          |
| ---------------------------------------- |
| Caio Gabriel Araujo Medeiros             |
| Flavio Vieira Leao                       |
| Jaime Juan de Castro Feliciano Damasceno |
| João Victor Max Bisinotti de Oliveira    |
| Luis Gustavo Avelino de Lima Jacinto     |
| Luis Gustavo Ferreira Marques            |
| Marcos Gabriel Tavares                   |
| Mateus Brandão Teixeira                  |
| Matheus Clemente Caravalho de Azevedo    |
| Victor Rayan Ferreira                    |

| Descrição dos Desenvolvedores |                                                                                             |
| ----------------------------- | ------------------------------------------------------------------------------------------- |
| Tipo                          | Estudantes da disciplina de Arquitetura e Desenho de Software ministrada na FGA, UnB.       |
| Responsabilidades             | Documentar, gerenciar, desenvolver, testar e implantar o software descrito nesse documento. |
| Critérios de sucesso          | Entregar os artefatos e funcionalidades solicitados dentro do prazo.                        |
| Envolvimento                  | Alto                                                                                        |
| Problemas/Comentários         | Gerenciamento de tempo/humano                                                               |

#### 3.2.1. Usuários

| Descrição do Usuário  |                                                                    |
| --------------------- | ------------------------------------------------------------------ |
| Representantes        | Consumidor                                                         |
| Tipo                  | Consumidor que precisa de itens específicos para eventos e festas. |
| Responsabilidades     | Manter o cadastro sempre atualizado.                               |
| Critérios de sucesso  | Economia de tempo e de custo por deslocamento                      |
| Envolvimento          | Alto                                                               |
| Problemas/Comentários | --------                                                           |

### 3.3. Ambiente do Usuário/Consumidor

A aplicação poderá ser utilizada em qualquer dispositivo que possuir navegador com acesso a internet.

-   Google Chrome
-   Mozilla Firefox
-   Microsoft

### 3.4. Principais Necessidades do Usuário/Consumidor

#### 3.4.1. Tempo

A forma com que os consumidores realizam este tipo de operação demanda muito tempo de deslocamento até o estabelecimento que realiza o aluguel dos itens/kits. Mesmo quando o aluguel ocorre por telefone, o consumidor em algum momento terá que se locomover até o estabelecimento, acarretando até em maior perda de tempo.

#### 3.4.2. Deslocamento

Para o aluguel de itens/kits de festas é necessário, como mencionado no item anterior, se locomover até o estabelecimento. Isso, dependendo da distância, pode gerar alto custo de locomoção.

### 3.5. Alternativas e Concorrência¶

-   https://www.partyrent.com/
-   https://www.lokdecore.com.br/
-   https://www.rentalfesta.com.br/
-   https://www.aluguelmaterialfesta.com.br/

## 4. Visão Geral do Produto

### 4.1. Perspectiva do produto

O sistema terá como principal objetivo, mitigar a burocracia de deslocamento para aluguel de kits de festas, fornecendo uma listagem de itens/kits de festa que podem ser organizados em “carrinhos” e pagos previamente na própria aplicação, que posteriormente, se alugados, serão entregues no local designado pelo consumidor.

### 4.2. Resumo dos recursos

| Benefício para o Cliente                          | Recursos de suporte                                                                                       |
| ------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| Visualização de produtos separados por categorias | Informações sobre o preço de aluguel de um item e tempo de disponibilização para aluguel                  |
| Carrinho com uma lista de itens pré alugados      | Lista de itens que transparece as informações do aluguel de todos os itens selecionados                   |
| Histórico de aluguel                              | Informações detalhadas de todas as operações realizadas pelo usuário/consumidor                           |
| Avaliação do Usuário                              | Espaço reservado para que o usuário possa avaliar a qualidade do produto e do serviço de aluguel prestado |

### 4.3. Recursos Principais do Produto

-   Pesquisar item ou kit desejado
-   Visualizar lista de itens ou kits
-   Visualizar histórico de pesquisas
-   Visualizar historico de contratos de aluguel
-   Visualizar itens mais alugados
-   Criar lista/carrinho de itens para serem alugados
-   Pagamento facilitado, rápido e inteiramente online

### 4.4. Restrições do Produto

Para a utilização do produto descrito, o usuário deverá ter acesso aos dados do sistema que são disponibilizados pelo prestador de serviço,, implicando assim em certas limitações, tais como:

-   O usuário deve escolher somente entre os itens disponíveis
-   O usuário deve dispor de acesso a internet
-   O usuário deve dispor de um navegador

## 5. Faixa de Qualidade

### 5.1. Restrições de Implementação

O sistema deverá consumir uma API externa para realizar as operações de pagamento do usuário.

### 5.2. Requisitos do Sistema

### 5.2.1. Usabilidade

**RU01 - Tempo mínimo para a execução de uma operação**
É preciso que o tempo de execução das atividades não ultrapassem o tempo de 60 segundos. Caso aconteça, a plataforma deve apresentar uma mensagem de _Timeout_

**RU02 - Número de erros na execução de uma tarefa**
Espera-se que o sistema apresente um número máximo de 2 erros por operação realizada pelo usuário.

**RU03 - Número de operações para realização de uma operação**
Deve ser necessário o máximo de 10 tarefas para conseguir iniciar e finalizar uma operação no sistema web. Com isso, o sistema acaba ficando mais interativo e menos complexo.

**RU04 - Facilidade de Uso**
Espera-se que o sistema seja de fácil uso ao usuário e intuitivo, de modo que, não seja preciso uso de documentação externa para utilização do fluxo principal do sistema.

### 5.2.2. Confiabilidade

**RC01 - Segurança**
É preciso que o sistema se recupere de falhas em operações críticas do sistema e também que a aplicação seja implementada a fim de combater as seguintes atividades maliciosas :

-   SQL Injection.
-   Autenticação e gerenciamento de sessão.
-   Configuração incorreta de segurança.
-   Armazenamento inseguro (criptografia).

**RC02 - Disponibilidade**
O sistema deve permanecer disponível 24 horas/7 dias. Para isso, o servidor deve ficar em um ambiente preparado para tal, afim de evitar possíveis contra tempos. A manutenção deve ser feita em um período fora do horário de pico, pela madrugada.
Opção para configuração do servidor:

-   Web Server (Linux-based virtual machine - droplet)

**RC03 - Tempo Médio entre Falhas (MTBF)**
O tempo médio entre falhas do sistema é de uma semana.

**RC04 - Tempo Médio para Reparo (MTTR)**
O tempo médio de reparo de ser de um dia.

**RC05 - Taxa/Nivelamento de erros ou defeitos**

-   **Pouca importância** ex: Sistema com resposta lenta
-   **Média importância** ex: Queda momentânea do sistema.
-   **Muita importância** ex: Perca/vazamento de dados de persistência

### 5.2.3. Desempenho

**RD01 - Tempo de processamento**
O sistema não deve ultrapassar 30 segundos para processar a requisição de uma tarefa.

**RD02 - Tempo de resposta**
O tempo de resposta de uma pesquisa no sistema não deve ultrapassar o prazo máximo de 1 minuto.(**_Query Performance_**)

### 5.2.4. Funcionais

| RF        | Descrição                                                                                                                 |
| --------- | ------------------------------------------------------------------------------------------------------------------------- | 
| **RF01**  | O cliente deve ser capaz de reservar produtos para aluguel                                                                |
| **RF02**  | O cliente deve informar seu nome, endereço e telefone ao realizar uma reserva                                             |
| **RF03**  | O admnistrador deve ser capaz de cadastrar produtos na plataforma                                                         |
| **RF04**  | O sistema deve fazer controle de estoque                                                                                  |
| **RF05**  | O sistema deve permitir editar a reserva                                                                                  |
| **RF06**  | O usuário deve ser capaz de pesquisar produtos                                                                            |
| **RF07**  | O sistema deve permitir o dono altere os itens disponíveis como parte do kit festa.                                       |
| **RF08**  | O sistema deve emitir um código que representa a reserva realizada pelo cliente                                           |                                                                                                        
| **RF09**  | O usuário deve realizar cadastro no sistema                                                                               |
| **RF10**  | O sistema deve permitir cancelar a reserva                                                                                |
| **RF11**  | O sistema deve manter o registro do que foi alugado e quando estará disponível novamente                                  |
| **RF12**  | O sistema devem informar fotos e dimensões dos produtos                                                                   |
| **RF13**  | O sistema deve  emitir um e-mail contenta os dados dos itens que foram reservados                                         |
| **RF14**  | O sistema deve  enviar e-mail ao usuário contendo os dados de sua reserva                                                 |
| **RF15**  | O sistema deve permitir o admnistrador deve ser capaz de de cancelar a reserva                                            |
| **RF16**  | O usuário deve ser capaz de adicionar produtos separadamente ou em conjunto na reseva                                     |

### 5.2.4. Não Funcionais  

| RF     | Descrição                                                            |
| ------ | -------------------------------------------------------------------- | 
| RNF01  | O sistema deve suportar os principais navegadores web.               | 
| RNF02  | O sistema deve seguir boas práticas de usabilidade e acessibilidade. |
| RNF03  | O sistema deve ser responsivo                                        |

## Referências

> IBM. Documento de Visão. Disponível em: https://www.ibm.com/support/knowledgecenter/pt-br/SSWMEQ_4.0.6/com.ibm.rational.rrm.help.doc/topics/r_vision_doc.html. Acesso em: 16 de setembro de 2018.
> Falko. Documento de Visão. Disponível em: https://github.com/fga-eps-mds/Falko-2017.2-BackEnd/wiki/Documento-de-Visão. Acesso em 31 de janeiro de 2022.
