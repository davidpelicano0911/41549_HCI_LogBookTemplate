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

A avaliação heurística foi realizada tendo por base no método de **Nielsen**, utilizando um conjunto de heurísticas predefinidas para avaliar a usabilidade da plataforma **StarOfService**. O processo seguiu os seguintes passos:

### 1. Seleção das Heurísticas  
Foram utilizadas as 10 heurísticas de usabilidade de Jakob Nielsen.

### 2. Procedimento de Avaliação  
- Cada um dos elementos do grupo avaliou a plataforma de forma independente, identificando problemas de usabilidade com base nas heurísticas selecionadas. 
- Foi utilizada uma escala de gravidade para classificar os problemas encontrados, escala este previamente atribuida pelos docentes da cadeira

### 3. Número de Especialistas  
- A avaliação foi conduzida pelos alunos **113261**, **113391** e **113939**. 

### 4. Escala de Gravidade  
- **0**: Não é um problema de usabilidade 
- **1**: Problema cosmético (pode ser corrigido se houver tempo) 
- **2**: Pequeno problema de usabilidade (correção desejável, mas não essencial) 
- **3**: Problema de usabilidade importante (deve ser corrigido) 
- **4**: Problema crítico (deve ser corrigido com urgência) 

### 5. Processo de Consenso  
- Após a análise individual, reuni-mos para discutir os problemas identificados. 
- Nos casos em que um problema foi identificado por apenas um especialista, os outros foram convidados a reavaliá-lo para determinar se deveria ser incluído na lista final. 
- Os problemas foram classificados por gravidade e recomendações de melhoria foram propostas.


#### Individual Evaluations

- [113261_heuristic_evaluation_workbook](heuristic_evaluations/113261_heuristic_evaluation_workbook.md)

- [113939_heuristic_evaluation_workbook](heuristic_evaluations/113939_heuristic_evaluation_workbook.md)

- [113391_heuristic_evaluation_workbook](heuristic_evaluations/113391_heuristic_evaluation_workbook.md)

#### Consensus

>    After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**                                                                                                                                                                                                                                                          | **Expert 1 -  113261** | **Expert 2 -  113391** | **Expert 3 -  113939** | Recommendations                                                                                                                                                                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------- | ---------------------- | ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| O nome do serviço necessita de ser sempre válido, o que pode ser confuso para utilizadores que designam o serviço de forma diferente.                                                                                                                              | 3                      | X                      | X                      | Implementar sugestões automáticas e um sistema de reconhecimento de sinónimos.                                                                                                                                                                             |
| O icone da bandeira apenas aparece para o idioma selecionado, o que pode ser problemático para pessoas de outros idiomas.                                                                                                                                          | 2                      | X                      | X                      | Mostrar todas as opções de idioma e adicionar bandeiras para facilitar a identificação visual.                                                                                                                                                             |
| As designações usadas por vezes não são as melhores.                                                                                                                                                                                                               | 3                      | X                      | 2                      | Rever e melhorar os termos utilizados para serem mais intuitivos e alinhados com o vocabulário dos utilizadores.                                                                                                                                           |
| O fluxo de navegação é confuso, dificultando a solicitação de serviços ou candidaturas como prestador. A falta de distinção entre ações para clientes e profissionais causa frustração.                                                                            | X                      | 3                      | X                      | Reestruturar o site para diferenciar claramente clientes e profissionais. Incluir botões e seções específicas, como “Solicitar um serviço” e “Torne-se um prestador”. Melhorar a navegação com mensagens guiadas e onboarding interativo.                  |
| Em diversas páginas é difícil retornar à página inicial de pesquisa.                                                                                                                                                                                               | 4                      | 4                      | 4                      | Adicionar um botão claro de retorno à página inicial.                                                                                                                                                                                                      |
| Ausência de botões de "Cancelar" ou "Sair" em processos multi-etapas. Os utilizadores dependem de um pequeno ícone de "X", pouco visível, dificultando a interrupção do fluxo. Isso pode levá-los a concluir o processo involuntariamente ou a fechar o navegador. | X                      | 3                      | X                      | Adicionar botões de "Cancelar" e "Sair" visíveis e acessíveis em todas as etapas, com texto claro e tamanho adequado para facilitar a interrupção do processo.                                                                                             |
| A barra de contratar serviço e procurar por um é diferente, mas isso não está indicado na página.                                                                                                                                                                  | 3                      | X                      | X                      | Especificar claramente a diferença entre ambas as barras.                                                                                                                                                                                                  |
| O layout muda significativamente entre os modos Cliente e Prestador, causando confusão na navegação e adaptação. Isso dificulta a experiência dos utilizadores ao alternar entre os perfis.                                                                        | X                      | 2                      | X                      | Padronizar o layout entre os modos Cliente e Prestador, garantindo consistência visual e estrutural. Se houver diferenciação, manter as mudanças sutis e intuitivas, destacando apenas elementos essenciais sem comprometer a familiaridade do utilizador. |
| As opções do questionário por vezes não cobrem todas as necessidades dos utilizadores.                                                                                                                                                                             | 3                      | X                      | X                      | Permitir a adição de respostas personalizadas.                                                                                                                                                                                                             |
| Ao fechar um serviço solicitado, não há opção de confirmação nem possibilidade de retroceder, podendo levar a encerramentos acidentais sem reversão.                                                                                                               | X                      | X                      | 4                      | Adicionar confirmação em operações sensíveis, como: **"Tem a certeza que pretende excluir o serviço?"**, permitindo ao utilizador cancelar ou confirmar a ação antes de prosseguir.                                                                        |
| Ausência de confirmações antes de ações críticas, como marcar um pedido como "Não interessado". Isso pode levar a decisões acidentais ou impulsivas, dificultando a reversão da ação.                                                                              | X                      | 3                      | X                      | Adicionar diálogos de confirmação antes de ações críticas, como marcar desinteresse em um pedido. A mensagem deve alertar sobre as consequências e, se possível, permitir reversão dentro de um curto período.                                             |
| O site, quando inicia a pesquisa, aparece sempre o mesmo pop-up, o que não é ideal para utilizadores experientes.                                                                                                                                                  | 2                      | X                      | 1                      | Ocultar mensagens repetitivas para clientes que já realizaram a operação anteriormente, evitando redundância e tornando a experiência mais fluida.                                                                                                         |
| O site é difícil de navegar e exige alguma aprendizagem.                                                                                                                                                                                                           | 3                      | X                      | X                      | Melhorar a estrutura de navegação para facilitar o uso.                                                                                                                                                                                                    |
| O excesso de informação nas páginas de projetos torna a visualização confusa, dificultando a identificação dos detalhes mais relevantes.                                                                                                                           | X                      | X                      | 3                      | Organizar a informação de uma forma mais clara.                                                                                                                                                                                                            |
| Durante a navegação houve um server error.                                                                                                                                                                                                                         | 2                      | X                      | X                      | Melhorar a gestão de erros do servidor.                                                                                                                                                                                                                    |

---

### - Cognitive Walkthrough

#### Method

[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]


#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]

| Task                              | Subtasks                                                                                 |
| --------------------------------- | ---------------------------------------------------------------------------------------- |
| **1. Contratar serviço(cliente)** | Pesquisar pelo serviço desejado                                                          |
|                                   | Preencher os campos que o cliente deseja                                                 |
|                                   | Escolher entre os profissionais sugeridos ou só esperar pelo contacto de um profissional |
|                                   |                                                                                          |

| Task                    | Subtasks                                                                         |
| ----------------------- | -------------------------------------------------------------------------------- |
| **2. Prestar Serviços** | Ir para o separador "Oportunidades"                                              |
|                         | Escolher entre as oportunidades que fazem match com preferências do profissional |
|                         | Escolher a opção "Contactar Cliente"                                             |
|                         | Escolher a opção "Comprar o lead" para entrar em contacto com o cliente          |
|                         | Entrar em contacto com o cliente                                                 |
 Results

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
