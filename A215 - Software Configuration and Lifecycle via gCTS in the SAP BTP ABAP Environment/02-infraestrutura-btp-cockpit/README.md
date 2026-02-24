# Configuração da Infraestrutura no BTP Cockpit

A preparação da Subaccount deve ocorrer antes de abrir o ADT].

### 1. Entitlements
Garanta que sua Subaccount tenha cotas para o serviço **SAP BTP ABAP Environment** (plano standard ou free-tier).

![Atribuição de Serviços](../images/01_entitlements.png)

### 2. Service Instance e Service Key
* No **Service Marketplace**, crie uma instância do serviço ABAP.
* Durante a criação, utilize um arquivo JSON para definir o administrador inicial.

![Criação da Instância](../images/02_service_marketplace.png)

* Gere uma **Service Key** após criar a instância. Ela contém as URLs e credenciais para o ADT.

![Service Keys Geradas](../images/03_service_keys.png)

### 3. Role Collections
Atribua as funções necessárias ao seu usuário, como `SAP_BR_DEVELOPER` e `SAP_BR_ADMINISTRATOR`.


<br>
<br>
Continuar para: [**Software Components**: O papel do gCTS e integração com Git](03-gerenciamento-de-software-components/README.md)
