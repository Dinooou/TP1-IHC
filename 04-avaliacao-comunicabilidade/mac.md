# Avaliação de Comunicabilidade (MAC)

<!--
NOTAS PARA QUEM PREENCHE (apagar antes de entregar):
- Os vídeos estão como "não listados" no YouTube. O link de cada vídeo precisa estar escrito neste arquivo.
- Para apontar um momento do vídeo, use o formato https://youtu.be/ID_DO_VIDEO?t=SEGUNDOS (por exemplo, 1min15s = ?t=75).
- Identifique os participantes só por código (U1, U2). Não escreva nome, e-mail nem outros dados pessoais.
- Procure por [PREENCHER] antes de entregar: não pode sobrar nenhum.
-->

Esta avaliação aplica o Método de Avaliação de Comunicabilidade (MAC) ao Simulador de Votação na Urna Eletrônica do TSE. O MAC analisa como a interface comunica ao usuário a lógica do designer e identifica as rupturas de comunicação que acontecem durante o uso, por meio da etiquetagem de sessões gravadas com expressões de comunicabilidade.

## 1. Planejamento

### Objetivo
Identificar onde e por que a interface do simulador deixa de comunicar ao usuário o que ele precisa fazer.

### Participantes
A avaliação contou com 2 participantes, identificados por código para preservar sua identidade.

| Código | Perfil resumido |
| :--- | :--- |
| U1 | 18 a 24 anos, com experiência prévia de voto. |
| U2 | 18 a 24 anos, com experiência prévia de voto. |

### Cenário e tarefas

####Cenário 1: Eleições Gerais

Tarefa 1: Na tela inicial do simulador, encontre e inicie o cenário de votação para "Eleições Gerais no Brasil".

Tarefa 2: O primeiro cargo a aparecer é o de Deputado Federal. Faça um voto de legenda (votar apenas no partido) utilizando o número 91 e confirme.

Tarefa 3: Para o cargo de Deputado Estadual, digite o número 93222, mas não confirme o voto ainda.

Tarefa 4: Você mudou de ideia. Utilize a tecla correta para apagar o número digitado na tarefa anterior, vote em Branco para Deputado Estadual e confirme.

Tarefa 5: Para o cargo de Senador, vote no candidato de número 912 e confirme.

Tarefa 6: No cargo de Governador, simule um voto nulo digitando um número de partido que não existe (por exemplo, 99) e confirme a anulação.

Tarefa 7: Para Presidente, digite o número 93. Antes de confirmar, identifique na tela qual é o nome do candidato a Vice-Presidente e, em seguida, confirme o voto.

Tarefa 8: Após ouvir o som prolongado e ver a tela de "FIM", encontre o botão ou link necessário para retornar à página inicial (Nova Simulação).

####Cenário 2: Eleições Municipais

9. Tarefa 9: De volta à tela inicial, inicie um novo cenário de votação, desta vez escolhendo as "Eleições Municipais" (se houver a opção de ativar o áudio para deficientes visuais nesta tela inicial, peça para ativá-lo antes de entrar).
    
10. Tarefa 10: Conclua este cenário votando no candidato 91111 para Vereador e no candidato 91 para Prefeito, finalizando a simulação com sucesso.

### Coleta de dados
Os testes foram feitos na plataforma web oficial do TJE, gravados pela câmera de um celular enquanto os usuário testavam a plataforma em um laptop

## 2. Evidências: vídeos das sessões

Os vídeos foram publicados no YouTube como "não listados" e podem ser acessados pelos links abaixo.

| Participante | Vídeo da sessão | Duração |
| :--- | :--- | :--- |
| U1 | [link do vídeo de U1](https://youtu.be/I4FwFOVdxrg) | 3:44 |
| U2 | [link do vídeo de U2](https://youtu.be/pC-yMRykwHQ) | 6:19 |

## 3. Etiquetagem

A etiquetagem consiste em assistir às sessões e marcar, em cada ruptura de comunicação, a expressão que melhor representa o que o usuário disse ou fez.

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

Em "Momento", escreva o tempo no formato `[mm:ss](https://youtu.be/ID_DO_VIDEO?t=SEGUNDOS)` para que o link leve direto ao trecho do vídeo.

| Tarefa | Momento | O que o usuário fez ou disse | Etiqueta | Observação |
| :--- | :--- | :--- | :--- | :--- |
| tarefa 2 | [00:20](https://youtu.be/I4FwFOVdxrg?t=20) | Não está funcionando |  Ué, o que houve? | Não entendeu a resposta dada pelo site, mas prosseguiu |
| tarefa 6 | [01:35](https://youtu.be/I4FwFOVdxrg?t=95) | ... | Cadê? | O usuário expressa dúvida e procura por algo na interface, mas não verbaliza nada |
| tarefa 7 | [2:46](https://youtu.be/I4FwFOVdxrg?t=166) | ... | Cadê? | O usuário expressa dúvida e procura por algo na interface, mas não verbaliza nada |

### 3.3 Etiquetagem do participante U2

| Tarefa | Momento | O que o usuário fez ou disse | Etiqueta | Observação |
| :--- | :--- | :--- | :--- | :--- |
| Tarefa 6 | [01:40](https://youtu.be/I4FwFOVdxrg?t=100) | O que? | O que é isso? | O usuário não entende a mensagem devolvida pelo site, o que causa um pequeno atraso |
| Tarefa 9 | [05:04](https://youtu.be/I4FwFOVdxrg?t=304) | ... |  E agora? | O usuário fica travado por um tempo após ativar o áudio e não saber como prosseguir, mas não verbaliza |

## 4. Interpretação

### 4.1 Frequência das etiquetas

**Quadro 1 - Etiquetas por participante**

| Expressão | U1 | U2 | Total |
| :--- | :--- | :--- | :--- |
| Cadê? | 2 | 0 | 2 |
| E agora? | 0 | 1 | 1 |
| O que é isto? | 0 | 1 | 1 |
| Epa! | 0 | 0 | 0 |
| Onde estou? | 0 | 0 | 0 |
| Por que não funciona? | 0 | 0 | 0 |
| Assim não dá | 0 | 0 | 0 |
| Ué, o que houve? | 1 | 0 | 1 |
| Para mim está bom | 0 | 0 | 0 |
| Desisto | 0 | 0 | 0 |
| Vai de outro jeito | 0 | 0 | 0 |
| Não, obrigado | 0 | 0 | 0 |
| Socorro! | 0 | 0 | 0 |

A análise de frequência registrou 5 rupturas de comunicação no total, tendo a expressão **"Cadê?"** como a mais recorrente (2 ocorrências), seguida por **"E agora?"**, **"O que é isto?"** e **"Ué, o que houve?"** (1 ocorrência cada). A maior incidência de **"Cadê?"** indica falhas de visibilidade na interface web, evidenciando que o usuário compreende a tarefa solicitada, mas encontra dificuldade para localizar elementos específicos na tela (como controles de áudio ou recursos auxiliares). Por sua vez, as demais etiquetas revelam momentos pontuais de hesitação diante das mensagens e transições de estado do simulador (como na cobrança do segundo voto para Senador ou na confirmação de voto nulo), nos quais o sistema não comunicou de imediato o que havia acontecido ou qual deveria ser o próximo passo. Vale ressaltar que, os participantes não se mobilizaram muito a seguir o Thinkaloud, fazendo com que a coleção desses dados tenha sido mais dificultada.

### 4.2 Rupturas de comunicação por tarefa

**Quadro 2 - Principais rupturas identificadas**

| Tarefa / elemento da interface | Etiquetas associadas | Participantes | O que a interface não comunicou |
| :--- | :--- | :---: | :--- |
| **Tarefa 2 (Ativação de áudio e feedback do sistema)** | *Ué, o que houve?*, *E agora?* | U1, U2 | Não deixou claro o feedback após a ação (fazendo U1 achar que o recurso não estava funcionando) nem indicou como prosseguir para a votação após ativar o áudio (deixando U2 travado na tela). |
| **Tarefa 6 (Mensagens e transição na tela da urna)** | *Cadê?*, *O que é isto?* | U1, U2 | Falhou em evidenciar na interface a informação que o usuário procurava (U1) e exibiu uma mensagem de retorno pouco intuitiva no visor da urna, gerando estranhamento e atraso na leitura (U2). |
| **Tarefa 7 (Localização de elementos e confirmação)** | *Cadê?* | U1 | Não destacou visualmente os elementos ou informações esperadas pelo usuário para validar a etapa, exigindo busca visual pela interface antes de avançar. |

As rupturas identificadas pelo MAC dialogam diretamente com os resultados obtidos no Teste de Usabilidade. Na **Tarefa 2**, as etiquetas *"Ué, o que houve?"* (U1) e *"E agora?"* (U2) explicam por que a missão de ativar o áudio apresentou a menor Taxa de Sucesso (TSR de 25%) nos testes quantitativos: mesmo quando o usuário interage com a opção, o sistema não oferece um retorno claro de funcionamento nem orienta o retorno ao fluxo de votação. Já nas **Tarefas 6 e 7**, a recorrência das etiquetas *"Cadê?"* e *"O que é isto?"* reflete a hesitação observada no teste de usabilidade durante as etapas de Senador e Governador (Voto em Branco e Nulo), comprovando que os avisos exibidos na tela da urna e a disposição das informações geram dúvidas momentâneas antes da confirmação do voto.

## 5. Perfil semiótico

O perfil semiótico reconstrói a mensagem que o designer comunica ao usuário por meio da interface, no formato da metacomunicação:

> *"Este é o meu entendimento de quem você é, do que aprendi que você quer ou precisa fazer, de que maneiras prefere fazer e por quê. Este é, portanto, o sistema que projetei para você, e esta é a forma como você pode ou deve usá-lo para alcançar uma gama de objetivos que se encaixam nesta visão."*

Aplicada ao simulador:

- **Quem é o usuário, segundo o designer:** Eleitores brasileiros de diferentes faixas etárias e níveis de letramento digital que já conhecem (ou desejam conhecer) o formato físico da urna eletrônica e buscam um ambiente seguro na web para treinar o processo de votação antes do dia da eleição.
- **O que o usuário quer ou precisa fazer:** Simular o fluxo completo de votação para todos os cargos em disputa, testando votos nominais, de legenda, em branco, nulos e correções, além de utilizar recursos de apoio (como a "colinha" virtual e o guia em áudio).
- **Como o designer espera que o usuário faça:** Espera que o usuário escolha o tipo de eleição na tela inicial, configure previamente os recursos auxiliares na página web (áudio e colinha) e, em seguida, utilize o mouse para clicar nas teclas numéricas da urna virtual, lendo as mensagens do visor e pressionando "Branco", "Corrige" ou "Confirma" conforme a ordem dos cargos.
- **Onde a mensagem falha na comunicação:** A metacomunicação falha principalmente na separação entre os **controles da página web** e a **metáfora da urna física**. Elementos externos à urna (como a ativação de áudio) possuem baixa visibilidade e não informam claramente como retornar ao fluxo de votação após acionados, provocando rupturas como *"Cadê?"*, *"Ué, o que houve?"* e *"E agora?"*. Já no visor da urna, a interface assume que o eleitor compreenderá de imediato avisos textuais discretos sobre regras eleitorais (como a transição para o segundo voto de Senador ou a mensagem de número inexistente/voto nulo), gerando hesitação e rupturas do tipo *"O que é isto?"*.

## 6. Considerações

A aplicação do Método de Avaliação de Comunicabilidade (MAC) revelou que a metáfora central da urna eletrônica (teclado numérico e botões Branco, Corrige e Confirma) é bem compreendida pelos usuários na etapa final de votação, mas a camada web que envolve o simulador e os feedbacks visuais de transição entre cargos apresentam falhas importantes de comunicação. As rupturas que merecem maior atenção concentram-se na localização e no retorno de estado do recurso de áudio (Tarefa 2) e na clareza das mensagens exibidas no visor durante situações específicas, como a dupla votação para Senador e a validação do voto nulo (Tarefas 6 e 7). Como sugestões de melhoria, recomenda-se: (1) posicionar o botão de áudio em local de maior destaque visual com indicador claro de ativação e retorno imediato para a urna; (2) destacar visualmente no visor a transição entre a 1ª e a 2ª vaga de Senador; e (3) tornar os avisos de "Voto Nulo / Número Errado" mais explicativos quanto à ação esperada do eleitor.

**Limitações:** A avaliação contou com uma amostra reduzida de apenas 2 participantes (U1 e U2), foi conduzida em sessões remotas e teve o processo de etiquetagem realizado diretamente pelos membros da equipe, além de os usuários apresentarem baixa verbalização espontânea durante os momentos de dúvida.
