# Backlog dos Requisitos Priorizados

## User Stories do Host do Projeto Social (Anna)

### Cadastrar de Host
- **Como** Host, **quero** cadastrar meus dados básicos e realizar login para acessar as funcionalidades do aplicativo.

  **Critérios de Aceitação:**
  - O cadastro deve ser concluído com sucesso ao fornecer todas as informações necessárias.
  - O usuário deve receber uma confirmação de cadastro via e-mail.

  **Restrições:**
  - Todos os campos são obrigatórios.
  - O e-mail deve ser único no sistema.

### Editar Perfil de Host
- **Como** Host, **quero** poder editar minha foto de perfil e atualizar meus dados pessoais.

  **Critérios de Aceitação:**
  - O host deve poder atualizar qualquer informação do perfil, exceto o e-mail.
  - As alterações devem ser salvas imediatamente e refletidas no perfil.

  **Restrições:**
  - O e-mail não pode ser alterado.

### Cadastrar de Projetos Sociais
- **Como** Host, **quero** cadastrar um novo projeto social com todos os dados necessários para compartilhar minha iniciativa.

  **Critérios de Aceitação:**
  - O projeto deve ser registrado com todos os detalhes fornecidos.
  - O host deve poder visualizar o projeto cadastrado na lista de projetos.

  **Restrições:**
  - Todos os detalhes do projeto são obrigatórios.

### Editar e Excluir de Projetos Sociais
- **Como** Host, **quero** ter a possibilidade de alterar e excluir projetos sociais que eu criei.

  **Critérios de Aceitação:**
  - O host deve poder editar qualquer detalhe do projeto.
  - O host deve poder excluir o projeto, e esta ação deve ser confirmada antes da exclusão.

  **Restrições:**
  - A exclusão de um projeto é irreversível.

### Convidar Voluntários
- **Como** Host, **quero** convidar voluntários por e-mail ou WhatsApp para se juntarem aos meus projetos.

  **Critérios de Aceitação:**
  - Convites devem ser enviados com sucesso para o e-mail ou WhatsApp fornecido.
  - Voluntários devem receber todas as informações necessárias sobre o projeto no convite.

  **Restrições:**
  - O host deve ter um projeto ativo para enviar convites.

### Gerenciar Eventos
- **Como** Host, **quero** inserir eventos em projetos ativos e gerenciar detalhes e voluntários associados.

  **Critérios de Aceitação:**
  - Eventos dentro de projetos ativos podem ser criados, editados e excluídos.
  - Voluntários associados devem ser notificados sobre novos eventos ou alterações.

  **Restrições:**
  - Eventos só podem ser associados a projetos ativos.

### Registrar Fotográfico de Eventos
- **Como** Host, **quero** inserir fotos dos eventos para criar um portfólio dos projetos.

  **Critérios de Aceitação:**
  - Fotos devem ser carregadas e associadas ao evento correspondente.
  - O host deve poder visualizar e excluir fotos postadas.

  **Restrições:**
  - Limitação no tamanho e formato das fotos.

### Comunicar com Voluntários
- **Como** Host, **quero** enviar mensagens aos voluntários do projeto para facilitar a comunicação.

  **Critérios de Aceitação:**
  - Mensagens devem ser enviadas e recebidas entre o host e os voluntários.
  - Deve haver um registro de todas as mensagens trocadas.

  **Restrições:**
  - A comunicação é restrita aos participantes do projeto.

## User Stories do Voluntário do Projeto Social (Sandra)

### Cadastrar Voluntário
- **Como** Voluntária, **quero** realizar meu cadastro e acessar o aplicativo para encontrar projetos.

  **Critérios de Aceitação:**
  - O cadastro deve ser simples e intuitivo, exigindo informações básicas.
  - O voluntário deve receber uma confirmação de cadastro.

  **Restrições:**
  - O e-mail deve ser único.

### Receber Convites
- **Como** Voluntária, **quero** receber convites para projetos sociais por e-mail ou WhatsApp e decidir se quero participar.

  **Critérios de Aceitação:**
  - O voluntário deve receber convites claros e completos, com informações sobre o projeto.
  - Deve haver uma opção clara para aceitar ou recusar o convite.

  **Restrições:**
  - Convites expiram após um determinado período.

### Visualizar Projetos
- **Como** Voluntária, **quero** visualizar um painel com todos os projetos dos quais estou participando.

  **Critérios de Aceitação:**
  - O voluntário deve ter uma visão geral clara dos projetos em que está envolvido.
  - Detalhes adicionais devem estar disponíveis ao selecionar um projeto específico.

  **Restrições:**
  - Apenas projetos aceitos são exibidos.

### Notificar Eventos
- **Como** Voluntária, **quero** receber notificações sobre os eventos dos quais fui escalada.

  **Critérios de Aceitação:**
  - O voluntário deve receber notificações oportunas sobre eventos dos quais participará.
  - Deve haver detalhes claros sobre o evento na notificação.

  **Restrições:**
  - Notificações devem ser enviadas com antecedência adequada.

### Comunicar e Feedback
- **Como** Voluntária, **quero** enviar mensagens e deixar comentários nos projetos, além de avaliá-los.

  **Critérios de Aceitação:**
  - O voluntário deve poder enviar mensagens e feedback de forma fácil e intuitiva.
  - O feedback deve ser visível para o host e, se aplicável, para outros voluntários.

  **Restrições:**
  - Feedback deve ser construtivo e respeitoso.

## User Stories da ONG (Terra)

### Cadastrar ONG
- **Como** ONG, **quero** cadastrar os dados básicos e realizar login para divulgar nossas atividades.

  **Critérios de Aceitação:**
  - O cadastro da ONG deve ser completo, incluindo todas as informações necessárias.
  - A ONG deve receber uma confirmação de cadastro.

  **Restrições:**
  - Informações como nome e e-mail devem ser únicas.

### Editar Perfil de ONG
- **Como** ONG, **quero** editar a foto de perfil e atualizar informações para atrair voluntários.

  **Critérios de Aceitação:**
  - A ONG deve poder atualizar seu perfil, incluindo foto e informações.
  - As alterações devem ser refletidas imediatamente.

  **Restrições:**
  - Algumas informações, como e-mail, não podem ser alteradas.

### Divulgar Atividades e Vagas
- **Como** ONG, **quero** ter uma página para divulgar nossas atividades, eventos e vagas de voluntariado.

  **Critérios de Aceitação:**
  - A ONG deve poder postar e gerenciar anúncios de atividades e vagas de voluntariado.
  - Os anúncios devem ser visíveis para voluntários potenciais.

  **Restrições:**
  - Anúncios devem seguir diretrizes de clareza e completude.

### Comunicar com Voluntários
- **Como** ONG, **quero** receber e enviar mensagens para possíveis voluntários pelo aplicativo.

  **Critérios de Aceitação:**
  - Deve haver um canal de comunicação eficaz entre a ONG e os voluntários.
  - Mensagens devem ser trocadas de forma segura e privada.

  **Restrições:**
  - A comunicação deve ser profissional e respeitar a privacidade dos voluntários.
