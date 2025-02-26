<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: [David Poeta Pelicano]
**Date**: [26-02-2025]
**Product**: [StarOfService]

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status

>    The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
> 
> - Does the design clearly communicate its state?
> - Is feedback presented quickly after user actions?


# 2 Match Between System and The Real World

>    The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
> 
> - Will user be familiar with the terminology used in the design? 
> - Do the design’s controls follow real-world conventions?

| **Issue**                                                                                                                                                                                                                                                           | **Severity** | Recommendation                                                                                                                                                                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Fluxo de navegação não intuitivo: Existe dificuldade em entender onde devem solicitar um serviço ou candidatar-se como prestadores, tornando a experiência confusa. Não há distinção clara entre as ações para clientes e profissionais, resultando em frustração.| 3            | Reformular a estrutura do site para tornar mais evidente a distinção entre clientes e profissionais. Incluir botões e seções bem sinalizadas para cada público, como “Solicitar um serviço” e “Torne-se um prestador”. Melhorar a orientação dentro da plataforma com mensagens guiadas e onboarding interativo. |

# 3 User Control and Freedom

>    Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
> 
> - Does the design allow users to go back a step in the process? 
> - Are exit links easily discoverable? 
> - Can users easily cancel an action? 
> - Is Undo and Redo supported?

| **Issue**                                                                                                                                                                                                                                                                                                                                                                                                                                          | **Severity** | Recommendation                                                                                                                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Falta de botões de "Cancelar" ou "Sair" em processos multi-etapas: Durante processos que envolvem múltiplas etapas, como ao solicitar um serviço, os utilizadores não encontram opções claras para cancelar ou sair do fluxo facilmente. O único meio disponível é um pequeno ícone de "X", que é pouco visível e pode passar despercebido, levando os utilizadores a concluir o processo involuntariamente ou forçando-os a fechar o navegador. | 3            | Tornar os botões de "Cancelar" e "Sair" mais evidentes e acessíveis em todas as etapas do processo, utilizando texto claro e botões de tamanho adequado.                                                                     |
| Dificuldade em retornar à página inicial a partir do painel de controlo do cliente: Atualmente, não há uma maneira clara e intuitiva de voltar à página inicial a partir do painel de controlo do cliente. O utilizador é forçado a alterar manualmente o link na barra de endereços, o que não é uma solução prática nem esperada.                                                                                                                | 4            | Adicionar um botão ou link visível no painel de controlo que permita retornar facilmente à página inicial. Esse botão pode estar no menu principal, no cabeçalho ou como um ícone de "Início" acessível em todas as páginas. |

# 4 Consistency and Standards

>    Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
> 
> - Does the design follow industry conventions? 
> - Are visual treatments used consistently throughout the design?

| **Issue**                                                                                                                                                                                                                                                                                                                                                                      | **Severity** | Recommendation                                                                                                                                                                                                                                                                                                |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Inconsistência no layout entre os modos Cliente e Prestador de Serviço: Quando os utilizadores alternam entre o perfil de Cliente (para solicitar serviços) e o de Prestador (para oferecer serviços), o layout e a organização da interface sofrem mudanças perceptíveis. Essas variações podem causar confusão, dificultando a adaptação e a navegação entre os dois modos. | 2            | Padronizar o layout entre os dois modos, mantendo a consistência visual e estrutural. Se for necessário diferenciar as interfaces, garantir que as mudanças sejam sutis e intuitivas, destacando apenas os elementos essenciais para cada perfil sem comprometer a familiaridade do utilizador com o sistema. |

# 5 Error Prevention

>    Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
> 
> - Does the design prevent slips by using helpful constraints? 
> - Does the design warn users before they perform risky actions?

| **Issue**                                                                                                                                                                                                                                                                                               | **Severity** | Recommendation                                                                                                                                                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Falta de confirmações antes de ações críticas: Utilizadores podem realizar ações significativas, como marcar um pedido como "Não interessado" enquanto profissionais, sem uma confirmação prévia. Isso pode levar a decisões impulsivas ou acidentais, dificultando a reversão da ação posteriormente. | 3            | Implementar diálogos de confirmação antes de ações críticas, como marcar desinteresse em um pedido. A confirmação deve incluir um aviso sobre as consequências da ação e, se possível, oferecer a opção de reverter dentro de um curto período de tempo. |

# 6 Recognition Rather than Recall

>    Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
> 
> - Does the design keep important information visible, so that users do not have to memorize it? 
> - Does the design offer help in-context?



# 7 Flexibility and Efficiency of Use

>    Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
> 
> - Does the design provide accelerators like keyboard shortcuts and touch gestures? 
> - Is content and funtionality personalized or customized for individual users?

# 8 Aesthetic and Minimalist Design

>    Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
> 
> - Is the visual design and content focused on the essentials? 
> - Have all distracting, unnescessary elements been removed?

# 9 Help Users Recognize, Diagnose, and Recover from Errors

>    Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
> 
> - Does the design use traditional error message visuals, like bold, red text? 
> - Does the design offer a solution that solves the error immediately?

# 10 Help and Documentation

>    It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
> 
> - Is help documentation easy to search? 
> - Is help provided in context right at the moment when the user requires it?

