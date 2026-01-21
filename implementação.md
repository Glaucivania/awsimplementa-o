# RELATORIO DE IMPLEMENTAÇÃO DE SERVIÇOS  AWS

Data: [19/01/2026]
Empresa: Computer Industries
Responsavel: Glaucivania Vieira Gomes

## Introdução
Este relatorio apresenta o processo de implementação de ferramentas na empresa Computer Indusries, realizado por Glaucivania Vieira Gomes. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especificações. A seguir, serão descritas as etapas do projeto:

Etapa 1: Otimização de Instâncias
- AWS Compute Optimizer
- Redução de custos através de Rightsizing (dimensionamento correto)
- A ferramenta analisou o histórico de utilização das instâncias EC2 da Abstergo e identificou que 40% dos servidores estavam superdimensionados (ociosos). Com as recomendações, foi possível migrar para famílias de instâncias mais baratas e modernas, reduzindo a fatura mensal sem perda de performance.

Etapa 2: Gerenciamento de Ciclo de Vida de Dados
- Amazon S3 Lifecycle Policies
- Automação de armazenamento de baixo custo
- Implementação de regras automáticas para mover arquivos que não são acessados há mais de 30 dias da classe S3 Standard para S3 Intelligent-Tiering ou S3 Glacier. Isso eliminou o custo de manter dados "frios" em camadas de armazenamento de alta disponibilidade e alto custo.

Etapa 3: Governança e Alertas Financeiros
- AWS Budgets
- Controle preventivo de gastos e previsibilidade
- Configuração de alertas automáticos via e-mail para os gestores caso o gasto mensal atinja 80% do teto estipulado. Isso evita surpresas na fatura ao final do mês e permite a interrupção imediata de serviços de teste que foram esquecidos ligados.



## Conclusão
A implementação de ferramentas na empresa Computer Industries tem como esperado a redução direta de até 30% nos custos fixos de nuvem, maior visibilidade sobre o desperdício de recursos e a automação da economia de dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

