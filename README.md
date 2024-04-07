# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: A definir

Empresa: Abstergo Industries 

Responsável: Genival José de Moura Neto

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Genival José de Moura Neto. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 (Simple Storage Service)
- Armazenamento
- É inegável que já há muito tempo dados são a mina de diamantes da era moderna, podendo servir para diferentes tipos de processamento analíticos que venham a ajudar nas tomadas de decisões estratégicas para a saúde financeira da empresa. Não só isso pois também existem as questões burocráticas, pois no Brasil as distribuidoras farmacêuticas devem manter registros e históricos de dados para fins de auditoria e conformidade regulatória (ver mais nos anexos). Nesse cenário, a empresa pode reduzir os custos de armazenamento de dados farmacêuticos, documentos de distribuição e registros de transações, mantendo a acessibilidade e a durabilidade dos dados. Para tal, o Amazon S3 oferece diferentes classes de armazenamento, como S3 Standard, S3 Intelligent-Tiering, S3 Standard-IA e S3 Glacier, cada uma com seus próprios preços e características. A utilização inteligente dessas classes de armazenamento pode resultar em uma redução significativa nos custos de armazenamento, especialmente para dados menos acessados como os utilizados para conformidade regulatória.

Etapa 2: 
- Amazon EC2 (Elastic Compute Cloud) Spot Instances
- Computação
- Também é necessário ter um cuidado especial na executação de cargas de trabalho não críticas, como processamento em lote, análises de dados ou tarefas de computação intensiva, pois apesar de entregarem as valiosas informações que poderão servir para a tomada de decisão baseada em dados em vez de especulações, poderão representar um custo significativo. Nesse cenário, as Spot Instances permitem o aproveitamento da capacidade de computação não utilizada da AWS, oferecendo descontos muito interessantes em comparação com as instâncias sob demanda convencionais, podendo chegar a 90%. A partir disso, será possível executar as cargas de trabalho tolerantes a falhas ou intermitentes, aproveitando os preços variáveis a um custo muito mais baixo, maximizando o valor dos recursos computacionais da AWS.

Etapa 3: 
- Amazon CloudWatch
- Monitoramento e observabilidade
- Ao manter uma visão abrangente do ambiente da AWS e das métricas de desempenho, será possível identificar oportunidades de otimização, melhorar a eficiência operacional e reduzir os custos de infraestrutura. Para isso, o Amazon CloudWatch fornece monitoramento e observabilidade para recursos da AWS, permitindo que a empresa identifique e resolva ineficiências operacionais que possam resultar em custos desnecessários. Monitorando o uso de recursos em tempo real, será possível ajustar dinamicamente a capacidade e otimizar os recursos para evitar gastos excessivos.



## Conclusão
A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado **o cumprimento de exigências para conformidade regulatória, melhoria na utilização dos recursos computacionais e redução de custos**, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- [Resolução da Diretoria Colegiada (RDC) nº 17/2010 da Agência Nacional de Vigilância Sanitária (ANVISA)](https://bvsms.saude.gov.br/bvs/saudelegis/anvisa/2010/res0017_16_04_2010.html)

- [Lei nº 13.709/2018 - Lei Geral de Proteção de Dados (LGPD)](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)

- [What is Amazon S3?](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)

- [Amazon S3 Storage Classes](https://aws.amazon.com/s3/storage-classes/)

- [Amazon EC2 Spot Instances](https://aws.amazon.com/ec2/spot/)

- [Cost Optimization with EC2 Spot Instances](https://www.workfall.com/learning/blog/how-to-run-fault-tolerant-workloads-for-up-to-90-off-using-amazon-ec2-spot-instances/)

- [Amazon CloudWatch](https://aws.amazon.com/cloudwatch/)

Assinatura do Responsável pelo Projeto:

Genival José de Moura Neto
