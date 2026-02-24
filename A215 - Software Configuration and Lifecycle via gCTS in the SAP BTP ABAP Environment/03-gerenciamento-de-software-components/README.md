# Gerenciamento de Software Components (gCTS)

No BTP ABAP, todo desenvolvimento deve estar dentro de um **Software Component** .

1. Acesse o **Fiori Launchpad** do seu ambiente (URL disponível na Service Key) .
2. Abra o app **Manage Software Components** .
3. Clique em **Create** para criar um novo componente (ex: `ZMETA_POC`) . Este componente possui relação 1:1 com um repositório Git .
4. Utilize a função **Clone** para vincular o sistema ABAP ao GitHub .

### Repository Roles:
* **Desenvolvimento**: O papel deve ser `Source` .
* **Qualidade/Produção**: O papel deve ser `Target` .

<br></br>
Continuar para: [**Ambiente de Desenvolvimento**: Prática com ADT (Eclipse)](../04-desenvolvimento-e-ciclo-de-vida-adt/README.md)
