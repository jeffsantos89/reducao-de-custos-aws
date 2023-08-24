# reducao-de-custos-aws
contem proposta de projeto para redução de custos e anexos
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 24/08/2023
Empresa: Abstergo Industries 
Responsável:Jeferson da silva dos santos

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Jeferson da silva dos santos. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: Otimização de Recursos de Computação

Ferramenta: Amazon EC2 Auto Scaling

Foco da Ferramenta:
O Amazon EC2 Auto Scaling é uma ferramenta que permite ajustar automaticamente o número de instâncias EC2 (servidores virtuais) de acordo com a carga de trabalho, garantindo que a capacidade de computação esteja adequada à demanda, resultando em custos mais baixos e melhor desempenho.

Descrição de Caso de Uso:
Na Etapa 1, o Amazon EC2 Auto Scaling foi implementado para ajustar dinamicamente o número de instâncias EC2 com base na carga de trabalho. Durante picos de atividade, novas instâncias são automaticamente iniciadas para lidar com o aumento de tráfego, enquanto nos períodos de baixa demanda, instâncias extras são automaticamente encerradas para economizar recursos e reduzir custos operacionais.

Etapa 2: Otimização de Armazenamento de Dados

Ferramenta: Amazon S3 (Simple Storage Service)

Foco da Ferramenta:
O Amazon S3 é um serviço de armazenamento de objetos altamente escalável e durável, projetado para armazenar e recuperar grandes quantidades de dados de forma eficiente e econômica.

Descrição de Caso de Uso:
Nesta etapa, parte dos dados da empresa foi migrada para o Amazon S3, aproveitando sua escalabilidade e baixo custo de armazenamento. Além disso, estratégias de gerenciamento de ciclo de vida de dados foram implementadas para mover automaticamente dados menos acessados para classes de armazenamento mais econômicas, contribuindo para redução dos custos de armazenamento.

Etapa 3: Gestão de Cargas de Trabalho

Ferramenta: AWS Lambda

Foco da Ferramenta:
AWS Lambda é um serviço de computação sem servidor que permite executar código em resposta a eventos, como requisições HTTP, uploads de arquivos, entre outros, sem a necessidade de gerenciar a infraestrutura subjacente.

Descrição de Caso de Uso:
Na terceira etapa, a empresa implementou AWS Lambda para automatizar a alocação de recursos em resposta a diferentes cargas de trabalho. Por exemplo, em horários de alta demanda, Lambda pode ser configurado para aumentar a capacidade de recursos temporariamente, e em horários de baixa demanda, diminuir a capacidade para economizar recursos. Isso garante que apenas os recursos necessários sejam utilizados, resultando em redução de custos.





## Conclusão
A implementação das ferramentas propostas na empresa Abstergo Industries demonstrou um progresso significativo em termos de otimização de recursos e redução de custos. Através da estratégia de utilizar o Amazon EC2 Auto Scaling, a empresa foi capaz de ajustar dinamicamente sua capacidade computacional de acordo com a demanda, evitando recursos ociosos e resultando em economia imediata. A migração de parte dos dados para o Amazon S3, aliada ao uso de estratégias de gerenciamento de ciclo de vida, também proporcionou uma redução considerável nos custos de armazenamento, mantendo a acessibilidade dos dados. A adoção do AWS Lambda para a gestão de cargas de trabalho permitiu uma alocação eficiente de recursos, contribuindo para um uso mais consciente e econômico.

Essas implementações alinham-se perfeitamente com os objetivos iniciais do projeto, que visava a redução dos custos operacionais da Abstergo Industries. Os benefícios tangíveis já observados nas três etapas refletem o comprometimento da empresa em otimizar seus processos e recursos.

## Anexos
1.Documento de Planejamento do Projeto
2.Planilhas de Monitoramento de Custos e Desempenho
3.Manuais de Configuração das Ferramentas
4.Relatórios de Testes de Performance
5.Logs de Implementação e Configuração
6.Assinatura do Responsável pelo Projeto:

Jeferson da Silva dos Santos

Este relatório documenta de forma abrangente a implementação das ferramentas AWS e sua influência na redução de custos na Abstergo Industries. Os anexos fornecem detalhes técnicos e suporte ao progresso do projeto. Recomenda-se a revisão constante das estratégias adotadas e a exploração de novas oportunidades de otimização, mantendo a empresa no caminho de maior eficiência e competitividade.
