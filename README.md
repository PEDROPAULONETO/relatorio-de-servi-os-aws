# Relatório de Implementação de Serviços ![Logo](https://www.mcmtelecom.com/hubfs/AWS_logo_New.png)

Data: 02/08/2025

Empresa: Abstergo Industries

Responsável: Pedro Paulo da Silva Neto

## Introdução

  Este relatório apresenta o processo de Implementação de ferramentas na empresa Abstergo Industries, realizado por Pedro Paulo da Silva Neto.
O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos.

## Descrição do Projeto

  O projeto de implementação do projeto foi dividido em 3 etapas, cada uma com seus objetivos específicos.
A seguir serão descritas as etapas do projeto:

### Etapa 1:

- Amazon S3 (Simple Storage Service):
- Ideal para substituir o armazenamento on-premise caro (servidores físicos, manutenção, refrigeração) por um serviço de armazenamento de objetos escalável, durável e de baixo custo. Permite a otimização do armazenamento através de classes (Standard, Infrequent Access, Glacier) que se adequam à frequência de acesso aos dados, resultando em economias substanciais.
- Utilizar ferramentas como AWS CLI, SDKs ou AWS DataSync para migrar os dados identificados para os buckets S3, aplicando as classes de armazenamento apropriadas.
Dados legados ou de baixa frequência de acesso armazenados de forma mais econômica no S3, desativando ou redimensionando o armazenamento on-premise correspondente. Redução imediata nos custos de hardware e manutenção de armazenamento.

### Etapa 2:

- Amazon EC2 (Elastic Compute Cloud) com Instâncias Spot:
- A utilização de instâncias Spot EC2 oferece uma maneira de economizar significativamente em custos de computação para cargas de trabalho flexíveis e tolerantes a interrupções. Estas instâncias permitem que você "dê lances" por capacidade de computação não utilizada da AWS, pagando um preço muito mais baixo do que as instâncias On-Demand.
- Configurar Auto Scaling Groups ou instâncias avulsas usando instâncias Spot para as cargas de trabalho selecionadas. Implementar mecanismos de resiliência caso as instâncias Spot sejam interrompidas (ex: ponto de verificação, fila de mensagens).
Aplicações ou processos executando em instâncias Spot com um custo de computação significativamente menor em comparação com instâncias On-Demand ou servidores físicos.

### Etapa 3:

- AWS Cost Explorer:
- Embora não seja um serviço de "redução de custo" direto no sentido de substituir uma despesa existente, o Cost Explorer é crucial para identificar e otimizar gastos. Ele fornece uma interface visual para analisar seus custos e uso da AWS ao longo do tempo, permitindo identificar áreas de desperdício e tomar decisões informadas para otimização contínua. Sem visibilidade, é impossível otimizar eficazmente.
- Acompanhar diariamente os gastos na conta AWS através do Cost Explorer, identificando as fontes de custo e verificando as economias geradas pelas ações anteriores. Criar relatórios personalizados.
Visibilidade em tempo real sobre os gastos, permitindo ajustes rápidos e validação das reduções de custo alcançadas.

## Conclusão

  A implementação desses três serviços AWS (Amazon S3, Amazon EC2 com Instâncias Spot e AWS Cost Explorer) na empresa Abstergo Industries tem como esperado se implementado de forma estruturada nas três etapas propostas, permitirá à empresa obter uma redução de custos imediata e sustentar essa otimização ao longo do tempo. O foco inicial na migração de armazenamento e computação flexível, aliado à visibilidade granular dos custos, são os pilares para uma estratégia eficaz de economia. o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da ultilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais processos da empresa.

## Anexos

 - [Documentação Oficial AWS](https://docs.aws.amazon.com/pt_br/)

Assinatura do Responsável pelo Projeto:

Pedro Paulo da Silva Neto

[![github](https://img.shields.io/badge/github-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PEDROPAULONETO/k8s-projeto1-app-base/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-paulo-da-silva-neto-8b8a20368/)
