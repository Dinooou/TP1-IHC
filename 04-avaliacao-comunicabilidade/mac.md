# Avaliação de Comunicabilidade (MAC)

Esta avaliação aplica o Método de Avaliação de Comunicabilidade (MAC) ao Simulador de Votação na Urna Eletrônica do TSE. O MAC analisa como a interface comunica ao usuário a lógica do designer e identifica as rupturas de comunicação que acontecem durante o uso, por meio da etiquetagem de sessões gravadas com expressões de comunicabilidade.

## 1. Planejamento

### Objetivo
Identificar onde e por que a interface do simulador deixa de comunicar ao usuário o que ele precisa fazer, avaliando a clareza das mensagens, dos controles e das transições de estado do sistema.

### Participantes
A avaliação contou com 2 participantes externos à equipe e que não participaram do Teste de Usabilidade, selecionados com perfis distintos e identificados por código para preservar sua identidade. Antes do início das sessões, ambos leram e assinaram o Termo de Consentimento Livre e Esclarecido (TCLE).

| Código | Perfil resumido |
| :--- | :--- |
| U1 | 18 a 24 anos, Ensino Médio completo, com experiência prévia de voto. |
| U2 | 25 a 34 anos, Ensino Superior completo, com experiência prévia de voto. |

### Cenário e tarefas

#### Cenário 1: Eleições Gerais

1. **Tarefa 1:** Na tela inicial do simulador, encontre e inicie o cenário de votação para "Eleições Gerais no Brasil".
2. **Tarefa 2:** O primeiro cargo a aparecer é o de Deputado Federal. Faça um voto de legenda (votar apenas no partido) utilizando o número 91 e confirme.
3. **Tarefa 3:** Para o cargo de Deputado Estadual, digite o número 93222, mas não confirme o voto ainda.
4. **Tarefa 4:** Você mudou de ideia. Utilize a tecla correta para apagar o número digitado na tarefa anterior, vote em Branco para Deputado Estadual e confirme.
5. **Tarefa 5:** Para o cargo de Senador, vote no candidato de número 912 e confirme.
6. **Tarefa 6:** No cargo de Governador, simule um voto nulo digitando um número de partido que não existe (por exemplo, 99) e confirme a anulação.
7. **Tarefa 7:** Para Presidente, digite o número 93. Antes de confirmar, identifique na tela qual é o nome do candidato a Vice-Presidente e, em seguida, confirme o voto.
8. **Tarefa 8:** Após ouvir o som prolongado e ver a tela de "FIM", encontre o botão ou link necessário para retornar à página inicial (Nova Simulação).

#### Cenário 2: Eleições Municipais

9. **Tarefa 9:** De volta à tela inicial, ative a opção de áudio para pessoas com deficiência visual e inicie um novo cenário de votação escolhendo as "Eleições Municipais".
10. **Tarefa 10:** Conclua este cenário votando no candidato 91111 para Vereador e no candidato 91 para Prefeito, finalizando a simulação com sucesso.

### Coleta de dados
Os testes foram realizados presencialmente na plataforma web oficial do TSE e gravados pela câmera de um celular enquanto os usuários interagiam com o sistema em um laptop, garantindo a ocultação de quaisquer dados pessoais.

## 2. Evidências: vídeos das sessões

Os vídeos das sessões de interação foram publicados no YouTube como "não listados" e podem ser acessados pelos links abaixo.

| Participante | Vídeo da sessão | Duração |
| :--- | :--- | :--- |
| U1 | [Vídeo do participante U1](https://youtu.be/I4FwFOVdxrg) | 3:44 |
| U2 | [Vídeo do participante U2](https://youtu.be/pC-yMRykwHQ) | 6:19 |

## 3. Etiquetagem

A etiquetagem consiste em assistir às gravações das sessões e associar, a cada ruptura de comunicação observada, a expressão oficial do método que melhor representa o comportamento ou a fala do usuário ("colocando palavras na boca do usuário").

### 3.1 Expressões de comunicabilidade

| Expressão | Quando é usada |
| :--- | :--- |
| Cadê? | O usuário sabe o que quer fazer, mas não encontra o elemento da interface |
| E agora? | O usuário não sabe qual é o próximo passo |
| O que é isto? | O usuário não entende um elemento, termo ou mensagem |
| Epa! | O usuário faz uma ação sem querer e tenta desfazê-la |
| Onde estou? | O usuário age como se estivesse em outra parte ou contexto da interface |
| Por que não funciona? | O usuário faz o que acha certo e não obtém o resultado esperado |
| Assim não dá | O usuário percebe que o caminho escolhido não leva ao objetivo |
| Ué, o que houve? | A resposta do sistema é diferente da esperada |
| Para mim está bom | O usuário acha que concluiu a tarefa, mas não concluiu |
| Desisto | O usuário abandona a tarefa |
| Vai de outro jeito | O usuário tenta outra estratégia para o mesmo objetivo |
| Não, obrigado | O usuário recusa o caminho previsto pelo designer e segue por outro |
| Socorro! | O usuário procura ajuda ou recorre à ajuda do sistema |

### 3.2 Etiquetagem do participante U1

A tabela a seguir apresenta as rupturas de comunicação identificadas durante a sessão do participante U1, com os links diretos para o exato momento do vídeo em que ocorreram.

| Tarefa | Momento | Tela/Elemento | O que o usuário fez ou disse | Tipo de falha | Etiqueta | Problema de comunicabilidade / Observação |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Tarefa 2 | [00:20](https://youtu.be/I4FwFOVdxrg?t=20) | Visor da urna (Voto de Legenda) | "Não está funcionando" | Temporária | Ué, o que houve? | Não entendeu a resposta exibida pelo site ao digitar apenas os dois dígitos do partido, mas prosseguiu |
| Tarefa 6 | [01:35](https://youtu.be/I4FwFOVdxrg?t=95) | Visor da urna (Governador / Voto Nulo) | ... | Temporária | Cadê? | O usuário expressa dúvida e procura por algo na interface para validar o voto nulo, mas não verbaliza nada |
| Tarefa 7 | [02:46](https://youtu.be/I4FwFOVdxrg?t=166) | Visor da urna (Presidente / Vice-Presidente) | ... | Temporária | Cadê? | O usuário expressa dúvida e procura visualmente pela informação do Vice-Presidente na interface, mas não verbaliza nada |

### 3.3 Etiquetagem do participante U2

A tabela a seguir apresenta as rupturas de comunicação identificadas durante a sessão do participante U2, com os respectivos links para o momento do vídeo.

| Tarefa | Momento | Tela/Elemento | O que o usuário fez ou disse | Tipo de falha | Etiqueta | Problema de comunicabilidade / Observação |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Tarefa 6 | [01:40](https://youtu.be/pC-yMRykwHQ?t=100) | Visor da urna (Governador / Voto Nulo) | "O quê?" | Temporária | O que é isto? | O usuário não entende a mensagem de número errado/voto nulo devolvida pelo site, o que causa um pequeno atraso |
| Tarefa 9 | [05:04](https://youtu.be/pC-yMRykwHQ?t=304) | Controles de áudio / Seleção de cenário | ... | Temporária | E agora? | O usuário fica travado por um tempo após ativar o áudio e não saber como prosseguir para a votação, mas não verbaliza |

## 4. Interpretação

### 4.1 Consolidação e frequência das etiquetas

A tabela abaixo consolida a contagem das etiquetas atribuídas aos participantes U1 e U2 e indica as tarefas mais afetadas por cada tipo de ruptura.

**Quadro 1 - Consolidação das etiquetas por participante**

| Expressão | Ocorrências (U1) | Ocorrências (U2) | Total | Tarefas mais afetadas |
| :--- | :---: | :---: | :---: | :--- |
| Cadê? | 2 | 0 | 2 | Tarefa 6, Tarefa 7 |
| E agora? | 0 | 1 | 1 | Tarefa 9 |
| O que é isto? | 0 | 1 | 1 | Tarefa 6 |
| Ué, o que houve? | 1 | 0 | 1 | Tarefa 2 |
| Epa! | 0 | 0 | 0 | — |
| Onde estou? | 0 | 0 | 0 | — |
| Por que não funciona? | 0 | 0 | 0 | — |
| Assim não dá | 0 | 0 | 0 | — |
| Para mim está bom | 0 | 0 | 0 | — |
| Desisto | 0 | 0 | 0 | — |
| Vai de outro jeito | 0 | 0 | 0 | — |
| Não, obrigado | 0 | 0 | 0 | — |
| Socorro! | 0 | 0 | 0 | — |

A análise de frequência registrou 5 rupturas de comunicação no total, tendo a expressão **"Cadê?"** como a mais recorrente (2 ocorrências), seguida por **"E agora?"**, **"O que é isto?"** e **"Ué, o que houve?"** (1 ocorrência cada). A maior incidência de **"Cadê?"** indica falhas de visibilidade e destaque visual nas informações exibidas na interface, evidenciando que o usuário compreende a tarefa solicitada, mas encontra dificuldade para localizar elementos ou avisos específicos na tela. Por sua vez, as demais etiquetas revelam momentos pontuais de hesitação diante das mensagens e transições de estado do simulador (como no voto de legenda na Tarefa 2, na confirmação de voto nulo na Tarefa 6 e no retorno ao fluxo após ativar o áudio na Tarefa 9), nos quais o sistema não comunicou de imediato o que havia acontecido ou qual deveria ser o próximo passo. Vale ressaltar que os participantes verbalizaram pouco durante a interação, fazendo com que a coleta desses dados dependesse fortemente da observação das hesitações e ações na tela.

### 4.2 Rupturas de comunicação por tarefa

**Quadro 2 - Principais rupturas identificadas**

| Tarefa / elemento da interface | Etiquetas associadas | Participantes | O que a interface não comunicou |
| :--- | :--- | :---: | :--- |
| **Tarefa 2 (Voto de legenda para Deputado Federal)** | *Ué, o que houve?* | U1 | Não deixou evidente de imediato que digitar apenas os dois números do partido já é suficiente para habilitar o voto de legenda, fazendo U1 achar que as demais casas numéricas estavam travadas. |
| **Tarefa 6 (Simulação de voto nulo para Governador)** | *Cadê?*, *O que é isto?* | U1, U2 | Falhou em evidenciar na interface a informação que o usuário procurava (U1) e exibiu uma mensagem de retorno ("Número Errado / Voto Nulo") pouco intuitiva no visor da urna, gerando estranhamento e atraso na leitura (U2). |
| **Tarefa 7 (Identificação de Vice-Presidente e confirmação)** | *Cadê?* | U1 | Apresentou o nome e a foto do Vice-Presidente com pouco destaque visual no visor, exigindo busca visual pela interface antes da confirmação do voto. |
| **Tarefa 9 (Ativação de áudio e início das Eleições Municipais)** | *E agora?* | U2 | Não indicou claramente como prosseguir para a seleção do cenário de votação após a interação com o controle de áudio, deixando U2 temporariamente travado na tela. |

As rupturas identificadas pelo MAC dialogam diretamente com os resultados obtidos no Teste de Usabilidade. Na **Tarefa 9**, a etiqueta *"E agora?"* (U2) ajuda a explicar por que a missão relacionada ao recurso de áudio apresentou a menor Taxa de Sucesso (TSR de 25%) nos testes quantitativos: mesmo quando o usuário interage com a opção, o sistema não orienta claramente a continuidade do fluxo de votação. Já na **Tarefa 6**, a ocorrência simultânea das etiquetas *"Cadê?"* (U1) e *"O que é isto?"* (U2) reflete a hesitação observada no teste de usabilidade durante a etapa de Governador (Voto Nulo), comprovando que os avisos exibidos na tela da urna e a disposição das informações no visor (como também observado nas **Tarefas 2 e 7**) geram dúvidas momentâneas antes da confirmação do voto.

## 5. Perfil semiótico

O perfil semiótico reconstrói a mensagem que o designer comunica ao usuário por meio da interface, no formato da metacomunicação:

> *"Este é o meu entendimento de quem você é, do que aprendi que você quer ou precisa fazer, de que maneiras prefere fazer e por quê. Este é, portanto, o sistema que projetei para você, e esta é a forma como você pode ou deve usá-lo para alcançar uma gama de objetivos que se encaixam nesta visão."*

Aplicada ao simulador:

- **Quem é o usuário, segundo o designer:** Eleitores brasileiros de diferentes faixas etárias e níveis de letramento digital que já conhecem (ou desejam conhecer) o formato físico da urna eletrônica e buscam um ambiente seguro na web para treinar o processo de votação antes do dia da eleição.
- **O que o usuário quer ou precisa fazer:** Simular o fluxo completo de votação para todos os cargos em disputa, testando votos nominais, de legenda, em branco, nulos e correções, além de utilizar recursos de apoio (como a "colinha" virtual e o guia em áudio).
- **Como o designer espera que o usuário faça:** Espera que o usuário escolha o tipo de eleição na tela inicial, configure previamente os recursos auxiliares na página web (áudio e colinha) e, em seguida, utilize o mouse para clicar nas teclas numéricas da urna virtual, lendo as mensagens do visor e pressionando "Branco", "Corrige" ou "Confirma" conforme a ordem dos cargos.
- **Onde a mensagem falha na comunicação:** A metacomunicação falha principalmente na separação entre os **controles da página web** e a **metáfora da urna física**. Elementos externos à urna (como a ativação de áudio) possuem baixa visibilidade e não informam claramente como iniciar ou retornar ao fluxo de votação após acionados, provocando rupturas como *"E agora?"*. Já no visor da urna, a interface assume que o eleitor compreenderá de imediato avisos textuais discretos sobre regras eleitorais (como o funcionamento do voto de legenda, a mensagem de número inexistente/voto nulo ou a disposição secundária do Vice-Presidente), gerando hesitação e rupturas dos tipos *"Ué, o que houve?"*, *"Cadê?"* e *"O que é isto?"*.

## 6. Considerações

A aplicação do Método de Avaliação de Comunicabilidade (MAC) revelou que a metáfora central da urna eletrônica (teclado numérico e botões Branco, Corrige e Confirma) é bem compreendida pelos usuários na etapa final de votação, mas a camada web que envolve o simulador e os feedbacks visuais no visor da urna apresentam falhas importantes de comunicação. As rupturas que merecem maior atenção concentram-se na orientação de fluxo após o acionamento do recurso de áudio (Tarefa 9) e na clareza das mensagens e hierarquia visual exibidas no visor durante situações específicas, como o voto de legenda (Tarefa 2), a validação do voto nulo (Tarefa 6) e a visualização do Vice-Presidente (Tarefa 7). Como sugestões de melhoria, recomenda-se: (1) posicionar o botão de áudio em local de maior destaque visual com indicador claro de ativação e instrução direta para início da votação; (2) destacar melhor a hierarquia das informações dos candidatos e suplentes/vices no visor; e (3) tornar os avisos de "Voto de Legenda" e "Voto Nulo / Número Errado" mais explicativos quanto à ação esperada do eleitor.
