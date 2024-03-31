# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 31/03/2024
Empresa: Capsule Corp
Responsável: Jeanderson Soares da Silva

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Capsule Corp, realizado por Jeanderson Soares da Silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- S3
- Prover armazenamento de objetos (arquivos) com baixo custo, através de diferentes classes de armazenamento.
- Grande parte dos arquivos que hoje são armazendos em tecnologias mais caras e que precisam de atualização/manutenção periodicas, como HDs e SSDs, podem ser transferidos para o S3 que tem um politica de cobrança por uso, e além disso, para os arquivos com acessos menos frequentes, pode-se utilizar classes de armazenamento cuja cobrança é ainda menor.

Etapa 2: 
- EC2 Auto Scaling
- Escalar recursos computacionais horizontalmente de forma automatica.
- A capacidade de recursos disponíveis para a aplicação poderá ser ajustada dinamicamente, de forma que não haverá desperdício quando a demanda for baixa, nem haverá escasses de recursos quando a demanda atingir níveis maiores. Como a cobrança dos recursos de EC2 é feita por uso, haverá economia principalmente nos momentos em que a demanda for baixa.

Etapa 3: 
- Snapshots EBS
- Criação de backups de EBS
- Os snapshots funcionam de forma incremental, ou seja, são copiadas apenas a diferença de dados entre cada backup, havendo economia no uso de dados utlizados e portanto, tendo menor cobrança.

## Conclusão
A implementação de ferramentas na empresa Capsule Corp tem como esperado economia e agilidade na utilização de recursos, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[lista de anexos, como manuais, documentos, planilhas, entre outros]
- https://aws.amazon.com/pt/s3/
- https://aws.amazon.com/pt/ec2/autoscaling/
- https://aws.amazon.com/pt/ebs/snapshots/
- https://calculator.aws/

Assinatura do Responsável pelo Projeto:

Jeanderson Soares da Silva
