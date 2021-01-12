
# Planilha de características do modelo

É provável que um modelo seja descrito por uma série de características diferentes. Revise a lista abaixo e escolha qual se aplica ao contexto no qual você está trabalhando ou pense em suas próprias características.

| Trait | Heurística |
| --- | --- |
| Modelo de especificação | Produz um documento que descreve um trabalho / solicitação que precisa ser executado. Exemplo: Construtor de campanha publicitária |
| Modelo de execução | Executa ou rastreia um trabalho. Exemplo: Motor de campanha publicitária |
| Modelo de auditoria | Monitora a execução. Exemplo: Analisador de campanha publicitária |
| Aprovador | Recebe solicitações e determina se devem avançar para a próxima etapa do processo. Exemplo: verificação de fraude |
| Enforcer | Garante que outros contextos realizem certas operações. Exemplo: Contexto GDPR (garante que outros contextos excluam todos os dados de um usuário) |
| Octopus Enforcer | Garante que vários / todos os contextos no sistema cumpram uma regra padrão. Exemplo: Contexto GDPR (como acima) |
| Interchanger | Traduz entre vários idiomas onipresentes. |
| Gateway | Senta-se na extremidade de um sistema e gerencia a comunicação de entrada e / ou saída. Exemplo: gateway de mensagens IoT |
| Gateway Interchange | A combinação de um gateway e um intercâmbio. |
| Contexto Dogfood | Simula a experiência do cliente ao usar os contextos principais limitados. Exemplo: loja de música Whitelabel |
| Contexto da bolha | Situa-se na frente de contextos legados, fornecendo um modelo novo e mais limpo, enquanto os contextos legados estão sendo substituídos. |
| Bolha autônoma | Contexto de bolha que tem seu próprio armazenamento de dados e sincroniza dados de forma assíncrona com os contextos legados. |
| Contexto do cérebro (provável anti-padrão) | Contém um grande número de regras importantes e muitos outros contextos dependem dele. Exemplo: mecanismo de regras contendo todas as regras do domínio |
| Contexto do funil | Recebe documentos de vários contextos upstream e os passa para um único contexto downstream em um formato padrão (após aplicar suas próprias regras). |
| Contexto de engajamento | Oferece os principais recursos que atraem os usuários a continuar usando o produto. Exemplo: Contexto de aconselhamento financeiro gratuito |
