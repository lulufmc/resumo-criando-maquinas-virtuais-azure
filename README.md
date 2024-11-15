# resumo-criando-maquinas-virtuais-azure
Este repositório contém o resumo das lições aprendidas durante o módulo "Criando máquinas Virtuais na Azure"

Desde o último "desafio de projeto", a professora passou uma visão mais ampla dos beneficios da computação em nuvem, focando mais na plataforma da Azure, falou um pouco mais sobre Acordos de Nível de Serviço(SLA's), usando alguns serviços da plataforma para dar exemplos e exemplificar situações. 

# Benefícios

- Alta disponibilidade: refere-se aos serviços estarem disponíveis o máximo de tempo possível, garantidos pelas SLA's e pela própria Microsoft.

- Escalabilidade: Você pode começar com um recurso simples e pequeno e aumentar para algo muito maior conforme cresce a demanda pelo seu site ou aplicativo. E como a computação em nuvem, é baseada em consumo, ouseja, você só paga pelo que usar.

- Elasticidade: significa que os recursos de TI (como servidores, armazenamento e processamento) podem ser ajustados dinamicamente para atender à demanda de maneira instantânea e automática. Em outras palavras, você pode aumentar ou diminuir os recursos que está usando de acordo com a necessidade do momento. Scale Up, quando a demanda aumenta, o sistema aloca mais recursos para lidar com o tráfego ou processamento adicional. Scale down, quando a demanda diminui, os recursos são reduzidos, evitando custos desnecessários.

- Redução de Custos: Como não há investimento inicial em servidores, empresas de todos os tamanhos conseguem criar sistemas robustos sem gastar muito.

- Segurança: a plataforma oferece ferramentas de segurança para atender as necessidades dos clientes, mas *é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.

- Confiabilidade: Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutra confiável e resiliente. Como os servidores estão espalhados pelo mundo, seus usuários podem acessar seu aplicativo de qualquer lugar e ainda assim ter uma boa experiência. É necessário ressaltar também que, os provedores de nuvem, como a Microsoft, oferecem segurança de ponta, e se um servidor falhar, há outros prontos para entrar em ação, garantindo que seu serviço permaneça online.

- Previsibilidade: permite que avance com confiança, seja no desempenho ou no custo. A nuvem oferece ferramentas que permitem estimar custos antes mesmo de usar os serviços, então permite empresas planejem melhor seus custos, recursos e desempenho.

- Governança: refere-se às ferramentas e práticas que ajudam as empresas a monitorar, gerenciar e controlar os recursos e serviços que estão usando na nuvem. Isso garante que os sistemas sejam utilizados de maneira eficiente, segura e dentro das políticas e regulações necessárias. Monitoramento de Recursos, Controle de Custos, Gerenciamento de Acessos e Conformidade com Regras e Políticas.

# Acordos de nível de serviço ou Service Level Agreement(SLA)

É como um contrato entre o cliente e o provedor de serviços. Serve para definir o nível de serviço que será entregue, incluindo disponibilidade, desempenho e o que acontece se o provedor não cumprir com o prometido. Nesse contrato então, defini-se a disponibilidade, porcentagem do tempo que o serviço estará funcionando, por exemplo “99,9% de disponibilidade mensal”. O desempenho, garantias de velocidade ou capacidade. Consequências por falhas, o que o provedor faz se não cumprir o prometido, geralmente inclui reembolso parcial ou créditos na conta.

