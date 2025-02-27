**Evaluator**: Martina Duque  
**Date**: 24-02-2025  
**Product**: StarOfService  

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]  
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)  

# 1 Visibility of System Status

> The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time.  
> 
> - Does the design clearly communicate its state?  
> - Is feedback presented quickly after user actions?  

# 2 Match Between System and The Real World

> The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order.  
> 
> - Will user be familiar with the terminology used in the design?  
> - Do the design’s controls follow real-world conventions?  

| **Issue**                                                                                                                             | **Severity** | **Recommendation**                                                                                               |
| ------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ---------------------------------------------------------------------------------------------------------------- |
| O nome do serviço necessita de ser sempre válido, o que pode ser confuso para utilizadores que designam o serviço de forma diferente. | 3            | Implementar sugestões automáticas e um sistema de reconhecimento de sinónimos.                                   |
| O icon da bandeira apenas aparece para o idioma selecionado, podendo ser problemático para pessoas de outros idiomas.                 | 2            | Mostrar todas as opções de idioma e adicionar bandeiras para facilitar a identificação visual.                   |
| As designações usadas por vezes não são as melhores.                                                                                  | 3            | Rever e melhorar os termos utilizados para serem mais intuitivos e alinhados com o vocabulário dos utilizadores. |

# 3 User Control and Freedom

> Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process.  
> 
> - Does the design allow users to go back a step in the process?  
> - Are exit links easily discoverable?  
> - Can users easily cancel an action?  
> - Is Undo and Redo supported?  

| **Issue**                                                            | **Severity** | **Recommendation**                                    |
| -------------------------------------------------------------------- | ------------ | ----------------------------------------------------- |
| Em diversas páginas é difícil retornar à página inicial de pesquisa. | 4            | Adicionar um botão claro de retorno à página inicial. |

# 4 Consistency and Standards

> Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions.  
> 
> - Does the design follow industry conventions?  
> - Are visual treatments used consistently throughout the design?  

| **Issue**                                                                                                     | **Severity** | **Recommendation**                                                             |
| ------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------ |
| A barra de contratar serviço e procurar por um é diferente, mas isso não está indicado na página.             | 3            | Especificar claramente a diferença entre ambas as barras.                      |
| O site é um pouco confuso de navegar demorando para o utilizar entender como tem de fazer aquilo que pertende | 3            | Usar uma estrutura de pesquisa mais comum, para tornar a pesquisa mais simples |

# 5 Error Prevention

> Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action.  
> 
> - Does the design prevent slips by using helpful constraints?  
> - Does the design warn users before they perform risky actions?  

| **Issue**                                                                              | **Severity** | **Recommendation**                             |
| -------------------------------------------------------------------------------------- | ------------ | ---------------------------------------------- |
| As opções do questionário por vezes não cobrem todas as necessidades dos utilizadores. | 3            | Permitir a adição de respostas personalizadas. |

# 6 Recognition Rather than Recall

> Minimize the user's memory load by making elements, actions, and options visible.  
> 
> - Does the design keep important information visible, so that users do not have to memorize it?  
> - Does the design offer help in-context?  



# 7 Flexibility and Efficiency of Use

> Shortcuts — hidden from novice users — may speed up the interaction for the expert user.  
> 
> - Does the design provide accelerators like keyboard shortcuts and touch gestures?  
> - Is content and functionality personalized or customized for individual users?  

| **Issue**                                                                                                         | **Severity** | **Recommendation**                               |
| ----------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------ |
| O site, quando inicia a pesquisa, aparece sempre o mesmo pop-up, o que não é ideal para utilizadores experientes. | 2            | Permitir desativar o pop-up após o primeiro uso. |

# 8 Aesthetic and Minimalist Design

> Interfaces should not contain information that is irrelevant or rarely needed.  
> 
> - Is the visual design and content focused on the essentials?  
> - Have all distracting, unnecessary elements been removed?  

| **Issue**                                                | **Severity** | **Recommendation**                                      |
| -------------------------------------------------------- | ------------ | ------------------------------------------------------- |
| O site é difícil de navegar e exige alguma aprendizagem. | 3            | Melhorar a estrutura de navegação para facilitar o uso. |

# 9 Help Users Recognize, Diagnose, and Recover from Errors

> Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution.  
> 
> - Does the design use traditional error message visuals?  
> - Does the design offer a solution that solves the error immediately?  

| **Issue**                                  | **Severity** | **Recommendation**                      |
| ------------------------------------------ | ------------ | --------------------------------------- |
| Durante a navegação houve um server error. | 2            | Melhorar a gestão de erros do servidor. |

# 10 Help and Documentation

> It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks.  
> 
> - Is help documentation easy to search?  
> - Is help provided in context right at the moment when the user requires it?  

