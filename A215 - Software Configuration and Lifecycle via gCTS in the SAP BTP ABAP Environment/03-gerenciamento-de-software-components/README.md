# Gerenciamento de Software Components (gCTS)

No BTP ABAP, todo desenvolvimento deve estar dentro de um **Software Component** [cite: 35].

1. Acesse o **Fiori Launchpad** do seu ambiente (URL disponível na Service Key) [cite: 36].
2. Abra o app **Manage Software Components** [cite: 37].
3. Clique em **Create** para criar um novo componente (ex: `ZMETA_POC`) [cite: 38]. Este componente possui relação 1:1 com um repositório Git [cite: 39].
4. Utilize a função **Clone** para vincular o sistema ABAP ao GitHub [cite: 40].

### Repository Roles:
* **Desenvolvimento**: O papel deve ser `Source` [cite: 42].
* **Qualidade/Produção**: O papel deve ser `Target` [cite: 43].
