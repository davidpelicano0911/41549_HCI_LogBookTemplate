[Back to main Logbook Page](../hci_logbook.md)

---

# B. Stage 1 - Context Definition

# B.1. Competitor Identification

>    The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative.

## B.1a. Competitors

| **Competitor**                                                         | **Description**                                            | Information repository                                                                        |
| ---------------------------------------------------------------------- | ---------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| [Fixando](competitors/Competitor%20Analysis%20Fixando.md)              | Plataforma de contratação de serviços com +1200 categorias | [📄 Competitor Analysis Fixando](competitors/Competitor%20Analysis%20Fixando.md)              |
| [StarOfService](competitors/Competitor%20Analysis%20StartOfService.md) | Marketplace de serviços com sistema de matching automático | [📄 Competitor Analysis StarOfService](competitors/Competitor%20Analysis%20StartOfService.md) |
| [YourHero](competitors/Competitor%20Analysis%20YourHero.md)            | Plataforma para serviços domésticos e empresariais         | [📄 Competitor Analysis YourHero](competitors/Competitor%20Analysis%20YourHero.md)            |

## B.1b. Detailed Competitor Analysis

>    Choose the most notable competitor and do a more thorough analysis of their interactive solution

Para uma análise mais aprofundada, escolhemos o StarofService como principal concorrente devido à sua proximidade com o conceito do nosso projeto. Esta plataforma destaca-se por conectar profissionais de diversos setores a clientes que necessitam de serviços específicos, simplificando o processo de contratação. O StarofService apresenta uma interface simplificada o que facilita a utilização do website tanto para profissionais quanto para clientes. O fluxo de interação é direto, permitindo que os utilizadores encontrem rapidamente os serviços que desejam.

### - Heuristic Evaluation

#### Method

[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]

#### Individual Evaluations

- [113261_heuristic_evaluation_workbook](heuristic_evaluations/113261_heuristic_evaluation_workbook.md)

- [113939_heuristic_evaluation_workbook](heuristic_evaluations/113939_heuristic_evaluation_workbook.md)

- [113391_heuristic_evaluation_workbook](heuristic_evaluations/113391_heuristic_evaluation_workbook.md)

#### Consensus

>    After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**                                                                                                                                                                                                                                                                                                                                                                                                                                          | **Expert 1 -  113261** | Expert 2 - 113391 | Expert 3 - 113939 | Recommendations                                                                                                                                                                                                                                                                                                  |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- | ----------------- | ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| O nome do serviço necessita de ser sempre válido, o que pode ser confuso para utilizadores que designam o serviço de forma diferente.                                                                                                                                                                                                                                                                                                              | 3                      | X                 | X                 | Implementar sugestões automáticas e um sistema de reconhecimento de sinónimos.                                                                                                                                                                                                                                   |
| O icone da bandeira apenas aparece para o idioma selecionado, podendo ser problemático para pessoas de outros idiomas.                                                                                                                                                                                                                                                                                                                             | 2                      | X                 | X                 | Mostrar todas as opções de idioma e adicionar bandeiras para facilitar a identificação visual.                                                                                                                                                                                                                   |
| As designações usadas por vezes não são as melhores.                                                                                                                                                                                                                                                                                                                                                                                               | 3                      | X                 | 2                 | Rever e melhorar os termos utilizados para serem mais intuitivos e alinhados com o vocabulário dos utilizadores.                                                                                                                                                                                                 |
| Fluxo de navegação não intuitivo: Existe dificuldade em entender onde devem solicitar um serviço ou candidatar-se como prestadores, tornando a experiência confusa. Não há distinção clara entre as ações para clientes e profissionais, resultando em frustração.                                                                                                                                                                                 | X                      | 3                 | X                 | Reformular a estrutura do site para tornar mais evidente a distinção entre clientes e profissionais. Incluir botões e seções bem sinalizadas para cada público, como “Solicitar um serviço” e “Torne-se um prestador”. Melhorar a orientação dentro da plataforma com mensagens guiadas e onboarding interativo. |
| Em diversas páginas é difícil retornar à página inicial de pesquisa.                                                                                                                                                                                                                                                                                                                                                                               | 4                      | 4                 | 4                 | Adicionar um botão claro de retorno à página inicial.                                                                                                                                                                                                                                                            |
| Falta de botões de "Cancelar" ou "Sair" em processos multi-etapas: Durante processos que envolvem múltiplas etapas, como ao solicitar um serviço, os utilizadores não encontram opções claras para cancelar ou sair do fluxo facilmente. O único meio disponível é um pequeno ícone de "X", que é pouco visível e pode passar despercebido, levando os utilizadores a concluir o processo involuntariamente ou forçando-os a fechar o navegador. | X                      | 3                 | X                 | Tornar os botões de "Cancelar" e "Sair" mais evidentes e acessíveis em todas as etapas do processo, utilizando texto claro e botões de tamanho adequado.                                                                                                                                                         |
| A barra de contratar serviço e procurar por um é diferente, mas isso não está indicado na página.                                                                                                                                                                                                                                                                                                                                                  | 3                      | X                 | X                 | Especificar claramente a diferença entre ambas as barras.                                                                                                                                                                                                                                                        |
| Inconsistência no layout entre os modos Cliente e Prestador de Serviço: Quando os utilizadores alternam entre o perfil de Cliente (para solicitar serviços) e o de Prestador (para oferecer serviços), o layout e a organização da interface sofrem mudanças perceptíveis. Essas variações podem causar confusão, dificultando a adaptação e a navegação entre os dois modos.                                                                     | X                      | 2                 | X                 | Padronizar o layout entre os dois modos, mantendo a consistência visual e estrutural. Se for necessário diferenciar as interfaces, garantir que as mudanças sejam sutis e intuitivas, destacando apenas os elementos essenciais para cada perfil sem comprometer a familiaridade do utilizador com o sistema.    |
| As opções do questionário por vezes não cobrem todas as necessidades dos utilizadores.                                                                                                                                                                                                                                                                                                                                                             | 3                      | X                 | X                 | Permitir a adição de respostas personalizadas.                                                                                                                                                                                                                                                                   |
| Quando fecho um serviço que tinha pedido não aparece nenhuma opção<br/>para confirmar se quero mesmo realizar esta operação nem é possível retroceder                                                                                                                                                                                                                                                                                              | X                      | X                 | 4                 | Colocar pré-condições em operações sensíveis, por exemplo:<br/>"Tem a certeza que pretende excluir o serviço?"                                                                                                                                                                                                   |
| Falta de confirmações antes de ações críticas: Utilizadores podem realizar ações significativas, como marcar um pedido como "Não interessado" enquanto profissionais, sem uma confirmação prévia. Isso pode levar a decisões impulsivas ou acidentais, dificultando a reversão da ação posteriormente.                                                                                                                                            | X                      | 3                 | X                 | Implementar diálogos de confirmação antes de ações críticas, como marcar desinteresse em um pedido. A confirmação deve incluir um aviso sobre as consequências da ação e, se possível, oferecer a opção de reverter dentro de um curto período de tempo.                                                         |
| O site, quando inicia a pesquisa, aparece sempre o mesmo pop-up, o que não é ideal para utilizadores experientes.                                                                                                                                                                                                                                                                                                                                  | 2                      | X                 | 1                 | Quando o cliente já realizou uma operação anteriormente,<br/>não é necessário exibir essa mensagem.                                                                                                                                                                                                              |
| O site é difícil de navegar e exige alguma aprendizagem.                                                                                                                                                                                                                                                                                                                                                                                           | 3                      | X                 | X                 | Melhorar a estrutura de navegação para facilitar o uso.                                                                                                                                                                                                                                                          |
| Nas informações específicas de um projeto, existe muita informação,<br/>tornando-se tudo muito confuso.                                                                                                                                                                                                                                                                                                                                            | X                      | X                 | 3                 | Organizar a informação de uma forma mais clara.                                                                                                                                                                                                                                                                  |
| Durante a navegação houve um server error.                                                                                                                                                                                                                                                                                                                                                                                                         | 2                      | X                 | X                 | Melhorar a gestão de erros do servidor.                                                                                                                                                                                                                                                                          |

---

### - Cognitive Walkthrough

#### Method

[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]

| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Buyng a grammar book** | Search for available grammar books     |
|                             | Identify a specific book from the list |
|                             | Add the selected book to the cart      |
|                             | Proceeed to checkout                   |

| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **1. Booking a train ticket** | Select departure and destination cities |
|                               | Choose travel date and time             |
|                               | Pick a seat (if applicable)             |
|                               | Confirm booking and make payment        |

#### Results

Task: [This is the task]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | [Step 1 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | [Step 2 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | [Step 3 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| ...    | [Further steps]        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |

---

# B.2. Users

>    For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...

## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]

## B.2b. Results

>    This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List

| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 03-09-2000 | Bob / student      | Does most things on paper and would require a complete solution | [📄 Notes](interview-Bob.md) |     |
| ...        |                    |                                                                 |                              |     |

### Common Themes & Patterns

- **Recurring Problems:** 
  - Issue 1
  - Issue 2
- **Frequently Used Tools:** 
  - Tool 1
  - Tool 2
- **Desired Features / Solutions:** 
  - Feature 1
  - Feature 2

- --- 

---

[Back to main Logbook Page](../hci_logbook.md)

---
