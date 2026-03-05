# Pré-Requisitos

Antes de iniciar, certifique-se de configurar seu ambiente local e remoto:

1. **IDE Eclipse com plugin ADT**: 
   * Baixe o Eclipse IDE e adicione o ABAP Development Tools (ADT) Plugin.
   * [Guia de Instalação Oficial](https://developers.sap.com/tutorials/abap-install-adt.html).

   1.1.	No Eclipse, vá ao menu Help (Ajuda) > Install New Software... (Instalar Novo Software);
   
   1.2.	Clique em Add... (Adicionar).
   
   1.3.	No campo URL, insira: https://tools.hana.ondemand.com/latest.
   
   1.4.	Pressione Enter, selecione ABAP Development Tools e clique em Next.
  
<br></br>
3. **Repositório no GitHub**:
   * Crie um novo repositório para hospedar seu código [cite: 23].
   * [Documentação do GitHub](https://docs.github.com/pt/repositories/creating-and-managing-repositories/creating-a-new-repository) .

Passo a Passo Detalhado:

Acesse as Configurações: No canto superior direito do GitHub, clique na sua foto de perfil e selecione Settings (Configurações).

Developer Settings: Na barra lateral esquerda, role até o fim e clique em <> Developer settings.

Fine-grained tokens: Clique em Personal access tokens e selecione Fine-grained tokens.

Gerar Novo Token: Clique no botão Generate new token.

Configurar o Token:

Token name: Dê um nome claro.

Expiration: Escolha uma data de expiração (recomendado).

Resource owner: Selecione seu usuário.

Repository access: Escolha "All repositories" ou "Only select repositories" (recomendado para segurança).

Permissions: Defina as permissões específicas (read/write) que o token terá, como em Contents ou Issues.

<br></br>
<br></br>
Continuar para: [**Configuração da Infraestrutura**: Preparando o BTP Cockpit](../02-infraestrutura-btp-cockpit/README.md)
