[Back to main Logbook Page](../hci_logbook.md)

---

# C. Requirement Definition

>    Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
> 
> - summarize the user characteristics, context, and motivations using Personas
> - explain your vision for a novel solution that will target user motivations using Scenarios
> - identify requirements

# Personas

## Persona: Miguel Ferreira

### Summary

| Attribute        | Details                                                                                                            |
| ---------------- | ------------------------------------------------------------------------------------------------------------------ |
| **Photo**        | ![Persona Name\|100](personas/miguel.jpeg)                                                                         |
| **Name**         | Miguel Ferreira                                                                                                    |
| **Age**          | 38                                                                                                                 |
| **Occupation**   | Faz-Tudo em Serviços de Jardinagem                                                                                 |
| **Location**     | Porto, Portugal                                                                                                    |
| **Goals**        | Expandir a carteira de clientes, encontrar trabalhos próximos e gerir orçamentos de forma eficiente.               |
| **Pain Points**  | Dificuldade em alcançar novos clientes, concorrência com grandes empresas e falta de tempo para divulgar serviços. |
| **Motivation**   | Quero que mais pessoas conheçam o meu trabalho sem gastar fortunas em publicidade."                                |
| **Full Profile** | [📄 Read More](personas/persona1_Miguel.md)                                                                        |

---

## Persona: Ana Silva

### Summary

| Attribute        | Details                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Photo**        | ![Persona Name](personas/ana.webp)                                                                                               |
| **Name**         | Ana Silva                                                                                                                        |
| **Age**          | 42 anos                                                                                                                          |
| **Occupation**   | Gestora de Recursos Humanos                                                                                                      |
| **Location**     | Braga, Portugal                                                                                                                  |
| **Goals**        | Encontrar um profissional de jardinagem fiável e acessível. Ter um jardim bem cuidado sem investir muito tempo.                  |
| **Pain Points**  | Falta de tempo para procurar prestadores de serviços, dificuldade em avaliar a qualidade do serviço, preços pouco transparentes. |
| **Motivation**   | Quero um jardim bonito e bem cuidado sem preocupações.                                                                           |
| **Full Profile** | [📄 Read More](personas/persona2_Ana.md)                                                                                         |

---

# Scenarios

## Scenario 1: Miguel Consegue um Novo Cliente pela Plataforma

Miguel sempre teve talento e paixão por transformar espaços verdes, mas encontrar novos clientes nem sempre era fácil. Para expandir a sua clientela e otimizar o seu tempo, decidiu experimentar uma plataforma de serviços freelance.

Ao criar o seu perfil, Miguel adicionou fotografias dos seus melhores trabalhos e detalhou os serviços que oferecia. Para facilitar a pesquisa dos clientes, decidiu ainda incluir os preços que cobra por hora para diferentes tipos de serviço no seu perfil. Estes valores serviam apenas como referência, sendo o preço final ajustado na troca de mensagens, tendo em conta o tamanho do terreno, a complexidade do serviço e a estimativa do tempo necessário.

Pouco tempo depois de ativar o seu perfil, Miguel recebeu uma notificação sobre um pedido próximo. Com base nessas informações e necessidades do cliente, Miguel analisou o trabalho e enviou uma mensagem personalizada, sugerindo uma estimativa de tempo para a execução e ajustando o orçamento de acordo com a dimensão do serviço. Combinou também que o pagamento seria realizado diretamente através da aplicação depois do serviço concluído. No mesmo momento, definiram o horário para o serviço ser realizado, em que cliente estaria em casa para lhe abrir a porta.

No dia do serviço, Miguel chegou ao local conforme combinado e tirou uma fotografia do jardim antes de começar, registando o seu estado inicial. Após concluir o serviço notificou o cliente descrevendo as atividades que realizou, fotografias do resultado final e uma confirmação com a duração do serviço conforme a estimativa combinada. Também incluiu o valor final a pagar, de acordo com o que foi previamente acordado.

## Scenario 2: Ana Encontra o Profissional Certo Sem Perder Tempo

Ana Silva sempre quis um jardim bonito e bem cuidado, mas a falta de tempo tornava difícil encontrar um profissional de confiança. Já tinha tido experiências frustrantes com jardineiros que não respondiam rapidamente ou não apareciam à hora combinada. Decidida a resolver o problema de forma mais prática, resolveu experimentar uma plataforma de serviços freelance.

Ao aceder à plataforma, Ana inseriu a sua localização e descreveu brevemente o que precisava: poda de árvores, corte da relva e manutenção geral. Em poucos minutos, recebeu sugestões de profissionais próximos, incluindo Miguel Ferreira, que tinha excelentes avaliações e um portefólio com fotografias de trabalhos anteriores.

Gostando do que viu, Ana enviou uma mensagem direta ao Miguel através da plataforma, perguntando sobre disponibilidade e valores. O Miguel respondeu rapidamente, explicando os serviços que podia oferecer e sugerindo uma visita rápida para avaliar o espaço antes de definir o orçamento final.

No dia seguinte, o Miguel passou pela casa da Ana, avaliou o jardim e explicou-lhe detalhadamente o que poderia ser feito. Com um orçamento claro e um plano de manutenção ajustado às necessidades da Ana, ela aceitou a proposta e marcou a primeira sessão de trabalho.

Depois do serviço concluído, o Miguel enviou fotografias do antes e depois através da plataforma, e a Ana ficou impressionada com o resultado. Como estava satisfeita, decidiu deixar uma avaliação positiva e adicioná-lo à sua lista de profissionais favoritos para futuras manutenções. Agora, sempre que precisar de jardinagem, sabe que pode contar com um profissional de confiança sem perder tempo à procura.

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