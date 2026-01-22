# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 22/01/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Thálik Andrade Parente

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Thálik Andrade Parente. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar a transição para a nuvem focando na diminuição de custos operacionais imediatos e no aumento da escalabilidade.

## Descrição do Projeto
A estratégia de migração para a nuvem da Abstergo Industries visa substituir a infraestrutura local (On-premise) — onde a empresa arca sozinha com todos os custos de hardware e manutenção — por um modelo de pagamento conforme o uso (Pay-as-you-go). O projeto foi dividido em 3 etapas fundamentais:

### Etapa 1: Otimização de Processamento e Custo Variável
- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud).
- **Foco da ferramenta:** Fornecer capacidade computacional (servidores virtuais) redimensionável e segura.
- **Descrição de caso de uso:** A Abstergo pode substituir seus servidores físicos por instâncias EC2. Para o setor financeiro, o ganho principal é a redução de gastos com capital (CapEx), eliminando a necessidade de comprar hardware caro. Através do Auto Scaling, a empresa paga apenas pelo processamento que realmente utiliza, aumentando o número de servidores em picos de demanda e reduzindo-os em momentos de ociosidade.

### Etapa 2: Eficiência em Armazenamento e Intercâmbio de Dados
- **Nome da ferramenta:** Amazon S3 (Simple Storage Service).
- **Foco da ferramenta:** Armazenamento de objetos escalável, com alta disponibilidade e baixo custo.
- **Descrição de caso de uso:** Sendo uma indústria farmacêutica que se comunica com diversas empresas, a Abstergo pode utilizar o S3 para centralizar o intercâmbio de documentos regulatórios e pesquisas de forma segura. A redução de custo ocorre pela eliminação de sistemas de armazenamento físico (Storage) e custos de backup manual, já que o S3 oferece durabilidade e redundância automática por um custo por GB muito inferior ao armazenamento local.

### Etapa 3: Gestão de Banco de Dados de Alta Performance
- **Nome da ferramenta:** Amazon DynamoDB.
- **Foco da ferramenta:** Banco de dados NoSQL totalmente gerenciado, do tipo chave-valor, com performance em escala.
- **Descrição de caso de uso:** Ideal para o rastreamento de lotes de medicamentos e gestão de sessões em portais de parceiros. Por ser um serviço Serverless (sem servidor), não há custo de manutenção de servidor de banco de dados nem necessidade de contratar DBAs para gerenciar a infraestrutura física. O foco é a escalabilidade horizontal e a alta disponibilidade sem investimentos iniciais pesados.

## Conclusão
A implementação de ferramentas AWS na Abstergo Industries tem como esperado a redução de custos operacionais (OpEx) e a eliminação de grandes investimentos iniciais em hardware. Além da economia direta, a empresa ganhará agilidade para se conectar com parceiros externos e escalabilidade para crescer conforme a demanda do mercado farmacêutico. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias, como o AWS Lambda, para otimizar ainda mais os processos através de computação sem servidor.  
Essas decisões seguem o princípio do AWS Well-Architected Framework, especialmente no pilar de otimização de custos.

## Anexos
- [Manual de Boas Práticas AWS](https://aws.amazon.com/pt/architecture/well-architected/)
- [Calculadora de Preços AWS (Estimativa)](https://calculator.aws/#/)
- [Guia de Segurança IAM](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/introduction.html)

**Assinatura do Responsável pelo Projeto:** Thálik Andrade Parente  
Thálik Andrade Parente
