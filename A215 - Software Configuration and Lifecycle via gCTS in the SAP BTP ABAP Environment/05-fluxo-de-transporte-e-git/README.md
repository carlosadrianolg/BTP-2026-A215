# Fluxo de Transporte via gCTS

O transporte é o ato de levar o código do Git para outro sistema .

### No Ambiente de Desenvolvimento (Push)
1. **Release**: No ADT, libere as tarefas e a Transport Request no **Transport Organizer** .

![Transport Organizer - Release](../images/06_transport_organizer.png)

2. **Push**: Após a liberação, a mudança fica disponível no app **Manage Software Components** .

![Lista de Componentes](../images/07_software_components_list.png)
<br></br>
![Detalhes do Componente e History](../images/08_component_details.png)

3. **Review**: Realize o processo de revisão e Pull Request no GitHub .

![Repositório GitHub](../images/09_github_repo.png)

### No Ambiente de Destino (QA/Prod)
1. Abra o app **Manage Software Components** no sistema de destino .
2. Selecione o componente e clique em **Pull** [cite: 60]. Isso baixará a versão mais recente do Git para o sistema local .

![Pull no Sistema de Destino](../images/10_target_pull.png)

O código será então transportado para o ambiente de destino .
