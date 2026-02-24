# Desenvolvimento no ADT (Eclipse)

### Conexão e Projetos
Crie um novo **ABAP Cloud Project** utilizando os dados da sua **Service Key** [cite: 46].

![Novo Projeto ABAP Cloud](../images/04_adt_connection.png)

### Organização de Pacotes
Localize o pacote gerado automaticamente com o nome do seu Software Component [cite: 47]. Todos os objetos devem ser criados sob este pacote ou sub-pacotes [cite: 48].

![Estrutura de Pacotes e Classes](../images/05_adt_packages.png)

### Transport Requests (TRs)
Ao criar objetos, o sistema solicitará uma TR [cite: 49]. No BTP, as TRs são locais, servindo para agrupar as mudanças que serão "comitadas" no Git [cite: 50].
