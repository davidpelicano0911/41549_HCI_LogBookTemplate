[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements

# Personas

## Persona: Miguel Ferreira
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Persona Name\|100](personas/miguel.jpeg)    |
| **Name**         | Miguel Ferreira                               |
| **Age**          | 38                                            |
| **Occupation**   | Faz-Tudo em Serviços de Jardinagem            |
| **Location**     | Porto, Portugal                               |
| **Goals**        | Expandir a carteira de clientes, encontrar trabalhos próximos e gerir orçamentos de forma eficiente.         |
| **Pain Points**  | Dificuldade em alcançar novos clientes, concorrência com grandes empresas e falta de tempo para divulgar serviços.              |
| **Motivation**   | Quero que mais pessoas conheçam o meu trabalho sem gastar fortunas em publicidade."               |
| **Full Profile** | [📄 Read More](personas/persona1_Miguel.md)   |

---
## Persona: [Persona Name] 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Persona Name](path/to/photo.jpg)            |
| **Name**         | [Persona Name]                                |
| **Age**          | [Persona Age]                                 |
| **Occupation**   | [Job Title or Role]                           |
| **Location**     | [City, Country]                               |
| **Goals**        | [Brief summary of their main goals]           |
| **Pain Points**  | [Key frustrations or challenges]              |
| **Motivation**   | [One-line motivation or quote]                |
| **Full Profile** | [📄 Read More](personas/persona2_template.md) |

---





# Scenarios

## Scenario 1: Miguel Consegue um Novo Cliente pela Plataforma

Miguel sempre teve talento e paixão por transformar espaços verdes, mas encontrar novos clientes nem sempre era fácil. Para expandir a sua clientela e otimizar o seu tempo, decidiu experimentar uma plataforma de serviços freelance.

Ao criar o seu perfil, Miguel adicionou fotografias dos seus melhores trabalhos e detalhou os serviços que oferecia. Para facilitar a pesquisa dos clientes, decidiu ainda incluir os preços que cobra por hora para diferentes tipos de serviço no seu perfil. Estes valores serviam apenas como referência, sendo o preço final ajustado na troca de mensagens, tendo em conta o tamanho do terreno, a complexidade do serviço e a estimativa do tempo necessário.

Pouco tempo depois de ativar o seu perfil, Miguel recebeu uma notificação sobre um pedido próximo. Com base nessas informações e necessidades do cliente, Miguel analisou o trabalho e enviou uma mensagem personalizada, sugerindo uma estimativa de tempo para a execução e ajustando o orçamento de acordo com a dimensão do serviço. Combinou também que o pagamento seria realizado diretamente através da aplicação depois do serviço concluído. No mesmo momento, definiram o horário para o serviço ser realizado, em que cliente estaria em casa para lhe abrir a porta.

No dia do serviço, Miguel chegou ao local conforme combinado e tirou uma fotografia do jardim antes de começar, registando o seu estado inicial. Após concluir o serviço notificou o cliente descrevendo as atividades que realizou, fotografias do resultado final e uma confirmação com a duração do serviço conforme a estimativa combinada. Também incluiu o valor final a pagar, de acordo com o que foi previamente acordado.




## Scenario 2: Ana Encontra um Dog Walker Confiável para o Max


Ana sempre se preocupou com o bem-estar do Max, mas a sua rotina intensa de trabalho tornava difícil garantir que ele tivesse passeios regulares. Durante semanas, tentou organizar melhor o seu tempo, mas percebeu que precisava de ajuda. Foi então que decidiu procurar um serviço fiável de **dog walkers**.  

Ao pesquisar online, encontrou uma plataforma especializada na contratação de profissionais para serviços diários, incluindo passeios para cães. Curiosa, criou um perfil e preencheu as preferências do Max: cão de grande porte, energético, gosta de correr no parque. O sistema sugeriu vários **dog walkers certificados**, com avaliações detalhadas e informações sobre a sua experiência.  

Ana gostou especialmente de um profissional chamado João, que tinha excelentes recomendações de outros donos de cães grandes. A plataforma permitia **agendar um primeiro passeio-teste** e acompanhar o percurso em direto. No dia seguinte, enquanto estava numa reunião, Ana recebeu uma notificação informando que João tinha chegado para buscar o Max. Através do **seguimento do percurso em tempo real**, viu que ele seguiu a rota combinada e até enviou uma foto do Max feliz no parque.  

Satisfeita com a experiência, Ana decidiu contratar João para passeios regulares, ajustando os horários conforme a sua agenda. Agora, sempre que está ocupada com o trabalho, sabe que o Max está bem cuidado e a fazer exercício. Isso trouxe-lhe tranquilidade e eliminou a culpa que sentia por não conseguir passear com ele todos os dias.
---


# Requirements


## C.1. Functional requirements

1. **Gestão de Perfis**
   - Os freelancers podem criar e editar perfis com nome, serviços oferecidos, localização e avaliações e preços.
   - Os clientes podem criar perfis para entrar em contacto com freelancers e deixar avaliações.

2. **Publicação e Procura de Serviços**
   - Os clientes podem pesquisar por serviços, especificando categoria, descrição, localização e prazo.
   - O sistema deve sugerir freelancers relevantes com base nas preferências do cliente.

3. **Sistema de Mensagens entre o Cliente e o Freelancer**
   - Os clientes podem enviar mensagens diretas aos freelancers através da plataforma para definirem seja o que for.  
   - Os freelancers recebem notificações quando um cliente os contacta.  

4. **Avaliações e Feedback**
   - Os clientes podem avaliar e comentar os serviços prestados.
   - As avaliações são exibidas nos perfis dos freelancers para maior credibilidade.

5. **Gestão de Pagamentos**
   - Suporte para pagamentos online através da plataforma.

6. **Filtros de Pesquisa e Geolocalização**
   - Os clientes podem filtrar profissionais por localização, preço e tipo de serviço
   - Os freelancers podem definir um raio de atuação para receber pedidos dentro de uma área específica. (ver se vamos aplicar)

---


## C.2. Non-functional requirements

1. **Escalabilidade**
   - O sistema deve suportar um número crescente de utilizadores sem comprometer o desempenho.

2. **Segurança**
   - Proteção dos dados dos utilizadores através de autenticação segura e encriptação de informações pessoais.
   - Principalmente os pagamentos na plataforma, devem ser processados de forma segura.

3. **Disponibilidade**
   - A plataforma deve estar acessível **24/7**, garantindo um tempo de inatividade mínimo.

4. **Usabilidade e Acessibilidade**
   - Interface simples e de fácil compreensão, mesmo para utilizadores com pouca experiência digital.
   - Design responsivo garantindo uma navegação fluída e eficiente.

5. **Tempo de Resposta**
   - O sistema deve responder rapidamente às pesquisas, mensagens e interações.

6. **Compatibilidade**
   - Deve ser adaptado para diferentes tamanhos de ecrã.

---
[Back to main Logbook Page](hci_logbook.md)