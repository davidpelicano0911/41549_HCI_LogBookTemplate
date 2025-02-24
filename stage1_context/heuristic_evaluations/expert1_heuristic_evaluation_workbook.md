<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: David Poeta Pelicano
**Date**: [24-02-2025]
**Product**: [YourHero]

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

-----------------------------------------------------------------------------


Não foram identificados problemas para o tópico #1, uma vez que, ao concluir a candidatura, o site fornece um feedback claro e imediato. Após o envio da candidatura, o utilizador recebe uma mensagem de sucesso visível na tela, confirmando que o processo foi concluído com êxito. Além disso, o sistema envia um e-mail de confirmação com os detalhes da candidatura, garantindo que o utilizador tenha uma confirmação adicional da ação realizada. Este feedback eficaz assegura que o utilizador esteja sempre ciente do que aconteceu e qual o próximo passo, proporcionando uma boa experiência e evitando incertezas.


-----------------------------------------------------------------------------


# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**                                               | **Severity** | **Recommendation**                                                                            |
| ------------------------------------------------------- | ------------ | -------------------------------------------------------------------------------------------- |
| As descrições de vagas como "Marketing Specialist" ou "Sales Executive" podem ser genéricas e não refletem diretamente a cultura ou o foco específico da empresa. | 2            | Especificar melhor as funções nas descrições de cargos e associá-los aos valores da empresa. Por exemplo: "Especialista em Marketing de Performance" ou "Executivo de Vendas e crescimento em equipa". |
| O uso de expressões como KPIs e NPS pode ser confuso para um público que não esteja familiarizado com termos técnicos ou de avaliação de desempenho. | 3            | Explicar essas métricas de forma acessível, como "medidas de sucesso" ou "avaliação da satisfação dos clientes", para garantir que todos os utilizadores compreendam facilmente o impacto dessas medições no serviço oferecido. |

                  

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**                                           | **Severity**     |            Recommendation                                  |
| ---------------                                     | ------------     |            --------------                                  |
| O design não permite fácil reversão de ações ou     |                  | Adicionar um botão de "Voltar" ou "Cancelar",visível       |
| saída do processo sem complicação.                  |       3          | durante todo o processo, para permitir que o utilizador    |
|                                                     |                  | saia facilmente sem ter que passar por etapas adicionais   |
|-------------------------------------------------------------------------------------------------------------------------------------|
| Falta de uma opção de "Desfazer" ou "Refazer" em    |                  | Implementar uma funcionalidade de "Desfazer" e "Refazer"   |
| ações que podem ser corrigidas facilmente.          |      4           | para ações,especialmente em áreas de                           
|                                                     |                  | personalização ou edição de  
|                                                     |                  | dados                                                          
                                                      


# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**                                           | **Severity**     |            Recommendation                                |
| ---------------                                     | ------------     |            --------------                                |
| Diferentes padrões para a exibição de erros em      |                  | Adotar um sistema unificado para feedback de erros,      |
| campos: Algumas mensagens de erro aparecem em       |       1          | garantindo que todas as mensagens sejam exibidas no mesmo|
| vermelho abaixo dos campos, equanto outras aparecem |                  | formato e local, de acordo com as melhores práticas      |
| como pop-ups ou em locais diferentes na tela.       |                  |                                                          |




# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

-----------------------------------------------------------------------------

Para o tópico 5, não foram identificados problemas significativos no site de candidatura da YourHero. O design implementa boas práticas para evitar erros, como a exigência de campos obrigatórios e a apresentação de mensagens de erro quando necessário. Além disso, o fluxo de candidatura é claro e direto, minimizando a possibilidade de enganos por parte dos utilizadores.

-----------------------------------------------------------------------------


# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

-----------------------------------------------------------------------------


Não foram identificados problemas para o tópico #6, uma vez que, ao concluir a candidatura, o site exibe uma mensagem de sucesso e envia um e-mail de confirmação ao candidato. Estas medidas garantem que o utilizador não precise de memorizar o estado da sua candidatura, oferecendo feedback claro e imediato.

-----------------------------------------------------------------------------

# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?


| **Issue**                                           | **Severity**     |            Recommendation                                |
| ---------------                                     | ------------     |            --------------                                |
| Falta de atalhos para facilitar a navegação rápida  |                  |Implementar atalhos de teclado ou gestos táteis para ações|
| para utilizadores inexperientes.                    |       3          |frequentes, como preencher rapidamente formulários ou     |
|                                                     |                  |navegar entre secções.                                    |
|-----------------------------------------------------------------------------------------------------------------------------------|
| Ausência de personalização na experiência do        |                  |Permitir que os utilizadores guardem preferências, filtrem|
| utilizador                                          |      3           |oportunidades de trabalho de acordo com critérios         |
|                                                     |                  |específicos e recebam recomendações personalizadas        |






# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?


| **Issue**                                           | **Severity**     |            Recommendation                                |
| ---------------                                     | ------------     |            --------------                                |
| Excesso de texto em algumas páginas como por exemplo|                  | Resumir o conteúdo, destacando as informações principais |
| na Overview que têm descrições, requisitos          |       3          | e fornecendo links ou botões "Ler mais" para detalhes    |
| e benefícios muito grandes, entre outros.           |                  | adicionais.                                              |






# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

-----------------------------------------------------------------------------


No caso do tópico #9 , não foram identificados problemas, pois o site já implementa boas práticas em relação ao feedback de erros. As mensagens de erro são expressas de forma clara, sem o uso de códigos de erro, e são apresentadas de maneira que os usuários possam entender facilmente o que deu errado. Além disso, as soluções para resolver o erro são fornecidas imediatamente, permitindo que o utilizador recupere rapidamente a situação. Essas abordagens estão em conformidade com as melhores práticas de design e devem ser mantidas, pois garantem uma experiência de utilizador mais eficiente e agradável.

-----------------------------------------------------------------------------


# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**                                           | **Severity**     |            Recommendation                                |
| ---------------                                     | ------------     |            --------------                                |
| A secção de ajuda existe, mas não é facilmente      |                  |  Tornar a seccção de ajuda mais visível e acessível      |
| acessível para o utilizador, porque não aparece na  |       3          |  diretamente no site, com links ou ícones em áreas chave.|
| página principal e só aparece na página do "Join Us"|                  |                                                          |
| , contudo só aparece no final da página em pequeno. |                  |                                                          |
