RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 04/02/2026
Empresa: Abstergo Industries
Responsável: Paulo Vargas

Introdução

Este relatório apresenta o processo de implementação de ferramentas em nuvem na empresa Abstergo Industries, realizado por Paulo Vargas.
O objetivo do projeto foi selecionar e aplicar 3 serviços da AWS com foco na redução imediata de custos operacionais no contexto de uma rede de farmácias, otimizando infraestrutura, armazenamento e processamento de dados.

Descrição do Projeto

O projeto de implementação foi dividido em 3 etapas, cada uma voltada à otimização de um ponto crítico de custos da operação.

Etapa 1

Ferramenta: Amazon EC2 (Elastic Compute Cloud)

Foco: Redução de custos com infraestrutura de servidores

Caso de uso:
A empresa utilizava servidores físicos locais para hospedar seus sistemas de gestão, controle de estoque e vendas. Com a migração para instâncias EC2, foi possível pagar apenas pelos recursos utilizados, além de ajustar automaticamente a capacidade conforme a demanda (por exemplo, maior uso em horários comerciais).
Isso eliminou gastos com manutenção de hardware, energia elétrica e infraestrutura física.

Etapa 2

Ferramenta: Amazon S3 (Simple Storage Service)

Foco: Armazenamento de dados com menor custo e maior escalabilidade

Caso de uso:
Notas fiscais, relatórios, backups e históricos de vendas passaram a ser armazenados no Amazon S3.
O serviço permite armazenamento seguro, durável e de baixo custo, além da possibilidade de utilizar camadas como o S3 Glacier para arquivos antigos, reduzindo ainda mais os custos com dados que não precisam de acesso frequente.

Etapa 3

Ferramenta: AWS Lambda

Foco: Execução de código sem necessidade de servidores ativos

Caso de uso:
Processos como geração de relatórios, validação de dados e integração entre sistemas foram implementados usando AWS Lambda.
Com isso, a empresa deixou de manter servidores ligados continuamente para tarefas pontuais, pagando apenas pelo tempo real de execução do código, o que trouxe economia significativa em processamento.

Conclusão

A implementação dos serviços Amazon EC2, Amazon S3 e AWS Lambda na empresa Abstergo Industries tem como resultado esperado a redução de custos operacionais, maior escalabilidade, segurança e eficiência nos processos internos.
Essas soluções permitem que a empresa foque no seu core business, reduzindo despesas com infraestrutura e aumentando a produtividade.
Recomenda-se a continuidade do uso dos serviços AWS e a avaliação constante de novas tecnologias em nuvem para otimização contínua dos custos.

Anexos

Documentação dos serviços AWS utilizados

Diagramas de arquitetura em nuvem

Planilha comparativa de custos (antes e depois da migração)

Assinatura do Responsável pelo Projeto:

Paulo Vargas
