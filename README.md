# Bitbucket-monitoring

<img width="850" alt="image" src="https://github.com/DreadPirateRobertt/Bitbucket-monitoring/assets/82410029/c1b27714-9c04-422b-b6bf-072e483d3e3c">


Este script tem o intuito de monitorar Criação de novos repositório dentro da organização de forma global, além de de coletar dados como: Projetos criados recentemente, Projetos sem update com filtro de data personalizado, Projetos que nunca foram atualizados e Projetos que estão recebendo commits com filtro de data personalizado.

o Bitbucket, que é uma plataforma de hospedagem de repositórios de código Git, ele não possui uma função nativa que envie alertas automáticos quando novos repositórios são criados. O Bitbucket fornece recursos para notificar membros do repositório sobre atividades específicas, como push de código, pull requests e outros eventos, mas não possui uma funcionalidade nativa para notificar sobre a criação de novos repositórios em toda a instância.

No entanto, você pode criar um fluxo personalizado para receber notificações sobre a criação de novos repositórios usando outras ferramentas e integrações disponíveis. Aqui estão algumas maneiras de fazer isso:

**1.	Webhooks Personalizados:** Você pode configurar webhooks personalizados em sua instância do Bitbucket para monitorar eventos de criação de repositório. Quando um novo repositório é criado, o webhook pode ser acionado e enviar uma notificação para o sistema de mensagens ou serviço de alerta de sua escolha.

**2.	API do Bitbucket:** Você pode usar a API do Bitbucket para criar um script ou aplicativo que verifica periodicamente a lista de repositórios em sua instância Bitbucket e detecta novos repositórios. Quando um novo repositório é detectado, o script pode enviar notificações para os interessados.

**3.	Integrações de Terceiros:** Algumas ferramentas de integração de terceiros, como Zapier ou IFTTT, podem ser usadas para criar fluxos personalizados de notificação com base em eventos do Bitbucket, incluindo a criação de repositórios.

# Por que utilizar API's ?

Com o uso das API's conseguimos escrever códigos altamente customizaveis e também podemos adaptar a logica que será aplicada exatamente ao nosso cenário atual.
Por exemplo..

Digamos que você quer monitorar apenas repoistórios de uma BU (Business Unit) ou Squad Especifica.

Então devemos setar a lista de `projetos` em que essa squad ou BU trabalha.

A ideia deste script é facilitar a vida do time de Application Security na hora de fazer o monitoramento e avaliação de cobertura dentro dos repositórios da empresa.
