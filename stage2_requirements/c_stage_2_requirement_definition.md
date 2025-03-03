[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements

# Personas

## Persona: [Persona Name] 
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

Miguel sempre teve talento e gosta em transformar espaços verdes, mas encontrar novos clientes nem sempre era fácil. Ele dependia muito de indicações e redes sociais, o que consumia tempo que poderia estar a usar para trabalhar. Hoje, ele decidiu experimentar um sistema de serviços freelance para expandir a sua clientela.

Assim que criou o perfil, Miguel adicionou fotos dos seus melhores trabalhos, descreveu os serviços que oferece e definiu a sua área de atendimento. O sistema, percebendo sua experiência e localização, sugeriu que ele ativasse um recurso de orçamentos automáticos, permitindo que potenciais clientes recebessem estimativas iniciais sem precisar trocar muitas mensagens.

Pouco tempo depois, Miguel recebeu uma notificação: um cliente próximo precisava de poda e manutenção de um jardim. O pedido incluía fotos e uma breve descrição. Com poucos cliques, Miguel enviou uma resposta personalizada e um orçamento inicial. O cliente, impressionado com as avaliações positivas de Miguel e com a sua resposta rápida, aceitou a proposta e agendou o serviço diretamente pela plataforma.

No dia do serviço, Miguel chegou ao local e realizou o trabalho com dedicação. Ao finalizar, notificou o cliente para indicar que o serviço estava concluído e anexou algumas fotos do resultado. O cliente, satisfeito, deixou uma avaliação positiva e uma recomendação, aumentando a visibilidade do perfil de Miguel para futuros clientes.

Animado com a facilidade do processo, Miguel decidiu explorar mais recursos da plataforma. Ativou alertas para novos pedidos na sua área e começou a usar a funcionalidade de promoções personalizadas, oferecendo descontos para serviços recorrentes. Em poucos dias, percebeu um aumento nas solicitações, permitindo-lhe organizar melhor a sua agenda e reduzir o tempo gasto na procura por novos clientes.



## Scenario 2: Maria goes on a Museum Tour

[Maria had always loved modern art, but she often found museum visits overwhelming—so many exhibits, so much information, and little guidance on where to start. Today, she was visiting a contemporary art museum that had recently introduced an **interactive guide**.  ]

[As she entered the museum, Maria received a notification on her phone, reminding her to launch the app. She opened it and was greeted with a personalized welcome screen. The system, aware of her general interests in **digital media and abstract art**, suggested a self-guided tour tailored to her preferences.  ]

[Curious, Maria followed the suggested path. As she approached the first painting, the guide vibrated slightly—a prompt that additional content was available. Holding up the guide, she saw an **overlay** appear on the screen, revealing a time-lapse animation of the artist creating the piece. A small **audio clip** played, explaining the artist’s thought process and influences. Maria found this fascinating; it was as if the artwork was coming to life in front of her.  ]

[As she continued her tour, Maria **bookmarked** her favorite pieces, leaving notes about what she found intriguing. The system, recognizing her engagement, suggested another exhibit nearby featuring similar themes. Midway through her visit, she received a pop-up asking if she’d like a **short quiz** on the artworks she had explored, offering an interactive way to reflect on what she had learned.  ]

---


# Requirements


## C.1. Functional requirements

1. **Gestão de Perfis**
   - Os freelancers podem criar e editar perfis com nome, serviços oferecidos, localização e avaliações.
   - Os clientes podem criar perfis para entrar em contacto com freelancers e deixar avaliações.

2. **Publicação e Procura de Serviços**
   - Os clientes podem pesquisar por serviços, especificando categoria, descrição, localização e prazo.
   - O sistema deve sugerir freelancers relevantes com base nas preferências do cliente.

3. **Sistema de Orçamentos**
   - Os freelancers podem definir **preços base** para os seus serviços.
   - Os clientes podem solicitar orçamentos personalizados diretamente pelo perfil do freelancer.
   - Os freelancers podem ativar a funcionalidade de **orçamentos automáticos**, permitindo que os clientes recebam uma estimativa com base nas informações que inserem. (ver se vamos aplicar)

4. **Sistema de Mensagens entre o Cliente e o Freelancer**
   - Os clientes podem enviar mensagens diretas aos freelancers através da plataforma.  
   - Os freelancers recebem notificações quando um cliente os contacta.  

5. **Avaliações e Feedback**
   - Os clientes podem avaliar e comentar os serviços prestados.
   - As avaliações são exibidas nos perfis dos freelancers para maior credibilidade.

6. **Gestão de Pagamentos**
   - Suporte para pagamentos online através da plataforma.

7. **Filtros de Pesquisa e Geolocalização**
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
   - Deve ser compatível com as versões mais recentes do **Android** e **iOS**.
   - Deve ser adaptado para diferentes tamanhos de ecrã.

---
[Back to main Logbook Page](hci_logbook.md)