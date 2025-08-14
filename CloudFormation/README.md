# AWS CloudFormation

O AWS CloudFormation é um serviço da Amazon Web Services (AWS) que permite aos usuários definir e provisionar recursos de infraestrutura AWS como código, usando arquivos de modelo JSON ou YAML. 

Ele permite automatizar a criação, atualização e exclusão de recursos da AWS de forma previsível e repetível, agrupados em "pilhas". 

Em resumo: CloudFormation é uma ferramenta de Infraestrutura como Código (IaC) para a AWS, que permite gerenciar a infraestrutura da nuvem por meio de código. 

<h1>Como funciona:</h1>

1. Modelo:
Você cria um arquivo de modelo (em JSON ou YAML) que descreve a infraestrutura desejada, incluindo os tipos de recursos AWS (como instâncias EC2, bancos de dados, etc.) e suas configurações. 

2. Pilha:
Você usa o modelo para criar uma "pilha" no CloudFormation. A pilha é um conjunto de recursos que são gerenciados como uma única unidade. 

3. Provisionamento:
O CloudFormation interpreta o modelo e provisiona automaticamente todos os recursos definidos na pilha, garantindo que a infraestrutura corresponda à descrição no modelo. 

4. Gerenciamento:
O CloudFormation permite atualizar e gerenciar a infraestrutura provisionada, aplicando alterações ao modelo e atualizando a pilha de acordo. 

<b>Benefícios:</b>

1 - Automação: Automatiza o provisionamento e gerenciamento da infraestrutura, economizando tempo e esforço.

2 - Consistência: Garante que a infraestrutura seja consistente e replicável em diferentes ambientes. 

3 - Infraestrutura como Código: Permite tratar a infraestrutura como código, facilitando o versionamento, compartilhamento e reutilização. 

4 - Escalabilidade: Facilita a expansão e redução da infraestrutura conforme a necessidade. 

5 - Custo-efetividade: Permite otimizar o uso dos recursos e evitar custos desnecessários. 

6 - Em outras palavras: O AWS CloudFormation é uma ferramenta poderosa que permite aos desenvolvedores e administradores de sistemas definirem e gerenciarem a infraestrutura da AWS de forma automatizada, consistente e escalável, usando o conceito de "Infraestrutura como Código". 
