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
| **Photo**        | ![Persona Name\|100](personas/miguel.jpg)                                                                          |
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

## Scenario:

Miguel é experiente em cuidados de jardim e, ao criar conta na plataforma, cria um perfil, adicionando fotografias dos seus trabalhos anteriores, descrevendo os serviços que oferece e os preços, com o objetivo de encontrar clientes que necessitem de soluções práticas e de qualidade para a manutenção de espaços verdes.

Do outro lado, a Ana precisa de alguém para lhe podar as árvores e cortar o relvado. Ao criar conta na mesma plataforma, adiciona também a sua localização e o serviço que pretende. De imediato, recebe uma lista de profissionais disponíveis. Entre as várias opções, o perfil do Miguel chama-lhe a atenção: as fotografias de antes e depois de cada trabalho, as avaliações positivas de outros clientes e os preços detalhados dão-lhe a confiança que procurava.

Depois de conversarem pelo chat da plataforma e agendarem uma visita para avaliar o jardim pessoalmente, o Miguel analisa o espaço e apresenta um orçamento, incluindo a estimativa de tempo e custo. A Ana aprova a proposta e confirma o pagamento diretamente através da aplicação, já organizando a data do serviço.

No dia combinado, o Miguel chega, tira fotografias do estado atual do jardim e inicia as tarefas. No final, regista novas imagens a mostrar o resultado, descreve as etapas realizadas e o tempo gasto, comprovando a qualidade do seu trabalho. Satisfeita com o serviço, a Ana confirma tudo na plataforma, deixa uma avaliação positiva, atribui ao Miguel a pontuação máxima e ainda o adiciona à lista de profissionais favoritos para futuras manutenções.

# Requirements

## C.1. Functional requirements

1. **Gestão de Perfis**
   
   - Os freelancers podem criar e editar perfis com nome, serviços oferecidos, localização e avaliações e preços.
   - Os clientes podem criar perfis para entrar em contacto com freelancers e deixar avaliações.

2. **Procura de Serviços e Profissionais**
   
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

---

## C.2. Non-functional requirements

1. **Escalabilidade**
   
   - O sistema deve suportar um número crescente de utilizadores sem comprometer o desempenho.

2. **Segurança**
   
   - Proteção dos dados dos utilizadores através de autenticação segura e encriptação de informações pessoais.
   - Principalmente os pagamentos na plataforma, devem ser processados de forma segura.

4. **Usabilidade**
   
   - Interface simples e de fácil compreensão, mesmo para utilizadores com pouca experiência digital.

5. **Performance**
   
   - O sistema deve responder rapidamente às pesquisas, mensagens e interações.
   - Design responsivo garantindo uma navegação fluída e eficiente.

6. **Compatibilidade**
   
   - Deve ser adaptado para diferentes tamanhos de ecrã.

---

[Back to main Logbook Page](hci_logbook.md)