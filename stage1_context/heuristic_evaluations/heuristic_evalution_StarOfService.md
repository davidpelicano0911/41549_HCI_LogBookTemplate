<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Tomás Oliveira
**Date**: [24-02-2025]
**Product**: [StarOfService]

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?





# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**                                           | **Severity** | Recommendation                                                                  |
| ---------------                                     | ------------ | --------------                                                                  |
| Existem expressões no site português (.pt) com      | 2            |  Recomendo a adaptação de expressões brasileiras para equivalentes portugueses  |
| expressões brasileiras que certos utilizadores      |              |  de forma a tornar o conteúdo mais acessível                                    |               
| podem não compreender



# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**                                        | **Severity**    | Recommendation                                                        |
| ---------------                                  | ------------    |--------------                                                         |
| Não existe a opção de retroceder em praticamente | 4               | Adicionar a funcionalidade/opção de retroceder em cada ação executada |
| todas as operações que eu queira executar        |                 | pelo utilizador



# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?



# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**                                                 | **Severity** | Recommendation                                                                      
| Quando fecho um serviço que tinha pedido não aparece      | 4            | Colocar pré-condições em operaçõoes sensíveis por exemplo "Tem a certeza que  |         
| nenhuma opção para confirmar se quero mesmo realizar esta |              | pretende excluir o serviço?"                                                  |
| operação nem é possível retroceder                        |              |                                                                               |


# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?




# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**                                               | **Severity** | Recommendation                                                    |
| Não existe quaisquer distinção entre utilizadores       |  1           | Quando já não é a primeira vez que o cliente realiza uma operação |
| experientes e não experientes tanto que sempre que      |              | não é necessário aparecer essa mensagem                           |
| crio um serviço é me apresentada uma confirmação que    |              |                                                                   |
| irão aparecer perguntas de forma a recomendar           |              |                                                                   |
| profissionais                                           |              |                                                                   |



# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**                                             | **Severity** | Recommendation                                |
| Nas informações especificas de um projeto existe      | 3            | Organizar informação de uma forma mais clara  |
| muita informação tornando-se tudo muito confuso       |              |                                               |



# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?





# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

