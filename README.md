# seguranca_AWS
Desafio de Projeto AWS - A Importância da Segurança

# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 03/04/2024
Empresa: Abstergo Industries 
Responsável: Viviane Gomes

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Viviane Gomes. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: IAM - Identity and Access Management

-  O IAM permite que você gerencie o acesso dos usuários aos recursos da AWS de forma granular, concedendo permissões apenas para as ações necessárias.

Processo de Implantação:
Identifique os usuários e grupos que precisam de acesso aos recursos da AWS.
Crie políticas de acesso personalizadas que definam as permissões necessárias para cada usuário ou grupo.
Associe as políticas aos usuários ou grupos relevantes.
Implemente a autenticação multifatorial (MFA) para reforçar a segurança das contas de usuário.
Regularmente, revise e atualize as permissões conforme necessário para garantir o princípio do menor privilégio.

Medida 2: CloudTrail e CloudWatch

- O CloudTrail registra todas as atividades realizadas nas contas da AWS, enquanto o CloudWatch monitora e fornece alertas sobre métricas e logs.

Processo de Implantação:
Ative o CloudTrail para registrar todas as atividades na sua conta da AWS.
Configure notificações e alertas no CloudWatch para monitorar métricas importantes e logs de eventos.
Defina alarmes para alertar sobre atividades suspeitas ou anomalias de segurança.
Analise regularmente os logs e as métricas para detectar padrões incomuns ou possíveis violações de segurança.
Implemente automação para responder rapidamente a incidentes de segurança, como desativação de credenciais comprometidas.

Medida 3: VPC - Virtual Private Cloud
- A VPC permite que você crie uma rede virtual isolada na AWS, na qual você pode controlar com precisão o tráfego de entrada e saída.

Processo de Implantação:
Projetar e configurar uma VPC adequada às necessidades de segurança da sua empresa.
Defina sub-redes públicas e privadas para separar os recursos de forma apropriada.
Configure grupos de segurança para controlar o tráfego de entrada e saída para as instâncias da AWS.
Utilize listas de controle de acesso (ACLs) para filtrar o tráfego de rede na camada de sub-rede.
Considere o uso de serviços como AWS WAF (Web Application Firewall) e AWS Shield para proteger contra ataques DDoS e ataques na camada de aplicação.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado garantir a segurança e controle de acessos, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

É importante lembrar que a segurança na AWS é um esforço contínuo e deve ser revisada e atualizada regularmente para se adaptar às novas ameaças e necessidades da empresa. Além disso, a implementação dessas medidas deve ser feita em conformidade com as melhores práticas de segurança e considerando as políticas e regulamentações específicas da empresa.

Assinatura do Responsável pelo Projeto:

Viviane Gomes
