# 	AlmoxControl

## Equipe
* Gabriel Ramos
* Giovani Petri

## 1. Visão 
O problema de falta de atenção, afeta os almoxarifes já que a falta de organização do 
patrimônio de uma empresa pode resultar em dias de prejuízo para a empresa. 
Neste contexto, uma solução de sucesso resultaria em um controle maior sobre dos 
os materiais da empresa, gerando agilidade nos processos, e também 
análises para economia na hora da compra e venda dos serviços.

## 2. Envolvidos

| Nome                      | Descrição     |
| -------------             |:-------------:|
| Almoxarife  | Este usuário será responsável pelo controle de todos os materiais da empresa, realizando a compra e distribuição para os empregados. |
| Empregado   | Este usuário é o responsável pela criação da requisição de materiais para o almoxarife. |

## 3. Product Backlog
_O product backlog é basicamente uma lista priorizada de requisitos, estórias, features ou restrições. Coisas que o cliente ou usuário deseja descritas utilizando a terminologia do ambiente de negócios cliente ou usuário. Ele deverá conter no mínimo dez (20) estórias  de valor priorizadas pela sua importância._ 

| No. | Nome do requisito      | Importância | Estória   | Critérios de Aceitação | Link para o Protótipo de Baixa Fidelidade  |
| ----|:---------------------: |:----------: | :-------: | :--------------------: | :----------------------------------------: |
| I   | Tela para Login        |    1        | O usuário deve ter uma tela de login para diferenciar o tipo de conta que está acessando o sistema, se é um empregado ou almoxerife          | 1-) Somente pode ser feito Login quem estiver cadastrado no sistema. 2-)Irá definir o tipo de acesso que o usuário vai ter no sistema conforme o nível de permissão do usuário                        |   [Acessar protótipo ](https://github.com/gabrielsramosss/Almox/blob/625c3c582de88c309767486879fd14a03f0cad1a/docs/prototipos/baixa/Telalogin.PNG)|
| II  | Tela para solicitar produto | 1 | Como empregado, gostaria de realizar pedidos de materiais para o almoxarifado de forma que não tenha que preencher papel e ficar esperando a separação | 1-) Deverá ter o nome e quantidade de todos os materiais requisistados 2-) Apresentar o data do pedido, nome da pessoa que está requisitando os materiais | [Acessar protótipo](https://github.com/gabrielsramosss/Almox/blob/ff9d57fda17ee0d096c66ec157aa180ba4065009/docs/prototipos/baixa/TelaRequisicao.PNG)|
| III | Tela de requisições | 1 | Como almoxarife, gostaria de visualizar todas as requisições pendentes para ter o controle do que ainda precisa ser separado | 1-) Deverá listar todas as requisições pendentes com sua data de pedido para que possa separar os materiais | [Acessar protótipo](https://github.com/gabrielsramosss/Almox/blob/ff9d57fda17ee0d096c66ec157aa180ba4065009/docs/prototipos/baixa/Reqpendentes.PNG )| 
| IV  | Tela para cadastrar fornecedores | 2 | Como almoxarife, gostaria de deixar registrado todos os fornecedores | 1-) Deverá ter campos de cadastro como CNPJ, nome fantasia, endereço, e-mail, telefone | [Acessar protótipo](https://github.com/gabrielsramosss/Almox/blob/aa938689871f1024fb6a419ad0c6d95ffbe25359/docs/prototipos/baixa/Cadastrodefornecedores.PNG) |
| V   | Tela para listar todos os fornecedores | 2 | Como almoxarife, gostaria de ter acesso ao catálogo de fornecedores | 1-) Irá listar todos os fornecedores com seus respectivos dados |[Acessar protótipo](https://github.com/gabrielsramosss/Almox/blob/aa938689871f1024fb6a419ad0c6d95ffbe25359/docs/prototipos/baixa/perfilfornecedor.PNG) |
| VI  | API do google maps | 4 | Como almoxarife gostaria de ter acesso a localização do fornecedor | 1-) Irá ter um mapa onde é possível visualizar todos os endereços dos fornecedores |[Acessar protótipo]() |	
| VII | Tela para listar histórico de compras | 2 | Como almoxarife, gostaria de saber todas as compras feitas no sistema | 1-) Deverá ter a data da compra, o almoxarife que fez a compra, o produto da compra com a quantidade e valor, fornecedor. | [Acessar protótipo]()|
| VIII| Tela para cadastrar todo equipamento | 5 | Como almoxarife, gostaria de ter controle de todos os equipamentos da empresa | 1-) Essa tela deverá cadastrar um número de patrimônio para cada equipamento |[Acessar protótipo]() |
| IX  | Tela para gerar relatórios | 3 | Como almoxarife, gostaria de criar relatórios para o sistema | 1-) Nessa tela o almoxarife irá selecionar que tipo de relatório ele deseja, de material, requisição, fornecedor, etc. 2-) Depois de escolher qual relatório, o almoxarife vai escolher os filtros disponível para o relatório escolhido. |[Acessar protótipo]() |
| X   | Tela para exportação de relatório | 4 | Como o almoxarife, gostaria de gerar dashboards com os dados gerados pelo gerador de relatórios | 1-) Após gerar o relatório, essa tela irá exportar o relatório como planilha para ser importada no Power BI. |[Acessar protótipo]() |
| XI  | Tela para parametrizar o sistema | 2 |  Como almoxarife gostaria de ter uma tela de configuração de diversas opções | 1-) Ao iniciar a aplicação, terá uma tela para configurar o e-mail de alertas como exemplo, quando o estoque chegar na determinada quantidade estabelecida como mínima. | [Acessar protótipo]()|
| XII | Tela de fale conosco | 3 | Como empregado, gostaria de entrar em contato ou enviar alguma sugestão para a equipe do almoxarifado | 1-) Deverá ter uma tela de fale conosco onde é preenchido os campos para enviar a mensagem para a equipe. |[Acessar protótipo]() |
| XIII| Tela de devolução de material | 1 | Como empregado, gostaria de ter a opção de devolver material | 1-) Deverá ter uma tela onde o empregado da mesma forma que ele abre para requisitar, ele vai ter a tela de devolução. |[Acessar protótipo]() |
| XIV | Tela para cadastra o material | 1 | Como almoxarife, gostaria de registrar o material | 1-) Deverá ter uma tela onde cadastra o material com uma ID de identificação, nome e imagem|[Acessar protótipo]() |
| XV  | Tela para listar e consultar os materiais | 1 | Como almoxarife e empregado, gostaria de ter acesso a todos os equipamentos na empresa | 1-) A tela deverá ter um menu de pesquisa por nome de material, onde apresenta a imagem, ID e quantidade em estoque |[Acessar protótipo]() |
| XVI | Tela para cotação | 3 | Como almoxarife, gostaria de ter uma tela onde pudesse solicitar cotação para os fornecedores | 1-) A tela deverá ter um botão para enviar um arquivo para os fornecedores com os materiais para cotação |[Acessar protótipo]() |
| XVII| Tela de cadastro de funcionário| 1 | Como almoxarife, iremos cadastrar os empregados para conseguir controlar a situação do empregado dentro da empresa | 1-) A tela deverá ter um cadastro do funcionário com o número do empregado (ID), nome completo, E-mail, CPF, setor, status.|[Acessar protótipo]() |
|XVIII|Log out| 1 | Como usuário ou almoxarife, gostaria de poder sair do sistema | 1-) O user conectado deverá clicar na opção 'Sair' para fazer log out do sistema | [Acessar protótipo]()|
| XIX | Remover equipamento | 2| Como almoxarife, gostaria de poder remover um equipamento cadastrado | 1-) O almoxarife só poderar excluir o material caso não tenha nenhum lançamento no material cadastrado.|[Acessar protótipo]() |
| XX  | Tela para listar todos os empregados | 2 | Como almoxarife, gostaria de saber o status do funcionário em relação a empresa | 1-) Irá listar os funcionários com seus dados, número do empregado (ID), nome completo, E-mail, CPF, setor, status. |[Acessar protótipo]() |