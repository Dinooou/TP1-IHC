# Teste de Usabilidade

## 1. Planejamento
### Objetivo do teste
O principal objetivo deste teste é avaliar a usabilidade e identificar possíveis barreiras de interação no Simulador de Urna Eletrônica do TSE. Pretende-se observar como os usuários navegam pela interface web para realizar ações comuns — como inserir números, corrigir escolhas e submeter votos em branco ou nulos —, avaliando a eficácia e a satisfação durante a simulação do fluxo eleitoral.

### Tarefas
Para simular o fluxo real de uma eleição, os participantes foram orientados a completar um percurso focado nas seguintes missões:
1. Iniciar a simulação no cenário de Eleições Gerais.
2. Ativar o recurso de acessibilidade de áudio do site.
3. Abrir a subpágina e preencher a colinha eleitoral.
4. Realizar um voto direto em um candidato ou voto de legenda.
5. Digitar um número incorreto propositadamente e utilizar a tecla "Corrige".
6. Registrar um voto em "Branco" para um dos cargos.
7. Simular um voto nulo (inserir um número de partido inexistente) e confirmar.
8. Concluir todo o fluxo de votação até visualizar a tela final ("FIM").

### Instrumentos utilizados
O teste foi conduzido de forma remota, contando com a colaboração de 8 participantes. Todo o processo foi executado diretamente no ambiente web, recorrendo à seguinte estrutura de ferramentas:
* **Simulador da Urna Eletrônica (TSE):** O sistema alvo onde as tarefas foram efetivamente realizadas.
* **Maze:** Plataforma principal para a estruturação das tarefas e coleta de métricas comportamentais não moderadas.
* **Google Meet:** Utilizado para a condução das sessões remotas, permitindo o compartilhamento de tela, a observação do percurso e a comunicação em tempo real.
* **Google Forms:** Ferramenta escolhida para a aplicação do questionário de caracterização do perfil (pré-teste) e para o formulário de satisfação (pós-teste).

## 2. Teste Piloto
### Ajustes realizados
Foi ajustado o passo a passo dentro do Maze, adicionando mais alguns passos contextuais, pra ajudar na interpretação. Além disso foi elaborada uma mensagem personalizada para passar os links para o voluntário. 

## 3. Execução
### Evidências
![Participante realizando o teste](../imagens/Teste_P01.png)
*Figura 1 - Participante durante a realização do teste.*

## 4. Análise dos Resultados

**Legenda dos resultados**

| Símbolo | Significado |
| :--- | :--- |
| ✓ | O usuário conseguiu completar a tarefa |
| ! | O usuário completou a tarefa, mas com dificuldade |
| X | O usuário não conseguiu completar a tarefa |

**Erros:** quantidade de ações incorretas registradas durante a tarefa (por exemplo, cliques em lugares errados ou tentativas sem sucesso).

### Resultados por participante

As tabelas abaixo detalham o desempenho individual de cada um dos 8 participantes nas tarefas propostas, incluindo o tempo de execução e os erros cometidos.

**Participante P01**

| Tarefa | Tempo (em segundos) | Resultado da tarefa | Erros | Observações |
| :--- | :--- | :--- | :--- | :--- |
| M1: Iniciar simulação | 10 | ! | 1 | O usuário iniciou clicando em um lugar errado, mas percebeu e voltou atrás |
| M2: Ativar áudio | 15 | X | 3 | O usuário não conseguiu ativar o áudio e não achou a opção |
| M3: Abrir colinha | 34 | ! | 2 | O usuário demorou pra entender a colinha |
| M4: Votar Dep. Federal | 82 | ! | 2 | O usuário teve uma breve confusão sobre o cargo, mas rapidamente sanada |
| M5: Corrigir Dep. Estadual | 32 | ! | 1 | O usuário sentiu dificuldade em corrigir |
| M6: Votar em Branco (Senador) | 50 | ! | 3 | O usuário sentiu dificuldade com a relação de ter de votar em dois senadores, pois o sistema evidencia pouco |
| M7: Votar Nulo (Governador) | 56 | ! | 1 | O usuário sentiu dificuldade em entender que o voto registrado pelo número seria nulo |
| M8: Votar Presidente e Fim | 14 | ✓ | 0 | O usuário teve êxito |

**Participante P02**

| Tarefa | Tempo (em segundos) | Resultado da tarefa | Erros | Observações |
| :--- | :--- | :--- | :--- | :--- |
| M1: Iniciar simulação | 10 | X | 1 | O usuário iniciou a simulação errada por erro de especificação do site |
| M2: Ativar áudio | 88 | ! | 0 | O usuário teve um pouco de demora, mas resolveu sem nenhum erro |
| M3: Abrir colinha | 83 | ! | 0 | O usuário abriu e preencheu sua colinha |
| M4: Votar Dep. Federal | 56 | X | 1 | Usuário ficou perdido devido ao tipo de votação escolhida não constar Deputado Federal, após perceber, prosseguiu |
| M5: Corrigir Dep. Estadual | 20 | X |  1 | O usuário pulou a etapa pois não constava Deputado Estadual no tipo de eleição escolhido |
| M6: Votar em Branco (Senador) | 7 | X | 1 | O usuário pulou a etapa pois não constava Senador no tipo de eleição escolhido |
| M7: Votar Nulo (Governador) | 18 | ✓ | 0 | O usuário entendeu o voto nulo, e prosseguiu |
| M8: Votar Presidente e Fim | 17 | ✓ | 0 | Concluiu com êxito |

**Participante P03**

| Tarefa | Tempo (em segundos) | Resultado da tarefa | Erros | Observações |
| :--- | :--- | :--- | :--- | :--- |
| M1: Iniciar simulação | 66 | ! | 3 | Usuário vagou pelas opções erradas por que o site não especificava bem qual ele deveria ir |
| M2: Ativar áudio | 10 | X | 1 | Não achou a opção de ativar o áudio e não sabia que existia |
| M3: Abrir colinha | 43 | ! | 3 | demorou pra entender como a colinha funcionava |
| M4: Votar Dep. Federal | 23 | ! | 1 | Demorou pra entender que tinha começado |
| M5: Corrigir Dep. Estadual | 15 | X | 1 | Saiu sem corrigir |
| M6: Votar em Branco (Senador) | 47| ! | 1 | Demorou pra entender que eram dois senadores |
| M7: Votar Nulo (Governador) | 31 | ! | 0 | Demorou pra entender que o número inserido votaria nulo |
| M8: Votar Presidente e Fim | 10 | ✓ | 0 | Concluiu a etapa com êxito |

**Participante P04**

| Tarefa | Tempo (em segundos) | Resultado da tarefa | Erros | Observações |
| :--- | :--- | :--- | :--- | :--- |
| M1: Iniciar simulação | 8 | ✓ | 0 | Entendeu rápido aonde clicar |
| M2: Ativar áudio | 7 | X | 1 | Não achou aonde |
| M3: Abrir colinha | 98 | ! | 3 | Conseguiu com muita dificuldade devido a confusão causada dentro do site |
| M4: Votar Dep. Federal | 142 | ! | 2 | Demorou devido ao carregamento do site |
| M5: Corrigir Dep. Estadual | 87 | ! | 2 | Conseguiu com dificuldades pois não sabia exatamente aonde clicar |
| M6: Votar em Branco (Senador) | 53 | ! | 0 | Conseguiu realizar a atividade porem se confundiu com as duas vagas |
| M7: Votar Nulo (Governador) | 46 | ! | 1 | Demorou pra entender que o número digitado votaria nulo e tentou corrigir |
| M8: Votar Presidente e Fim | 21 | ✓ | 0 | Teve êxito na etapa |

**Participante P05**

| Tarefa | Tempo (em segundos) | Resultado da tarefa | Erros | Observações |
| :--- | :--- | :--- | :--- | :--- |
| M1: Iniciar simulação | 80 |  ! | 1 | Teve dificuldade de saber aonde clicar, e o site demorou pra carregar |
| M2: Ativar áudio | 8 | X | 1 | Não encontrou o botão de ativar áudio, e nem sabia da funcionalidade |
| M3: Abrir colinha | 146 | ! | 4 | Teve muita dificuldade com a colinha, pois não sabia como corrigir somente um erro e além disso não entendeu o sistema de colinha |
| M4: Votar Dep. Federal | 63 | ✓ | 0 | Demorou devido carregamento do site |
| M5: Corrigir Dep. Estadual | 14 | X | 1 | Não corrigiu e seguiu adiante |
| M6: Votar em Branco (Senador) | 22 | X | 2 | Não conseguiu votar em branco pois não entendeu o sistema |
| M7: Votar Nulo (Governador) | 41 | ! | 1 | Não entendeu como iria registrar o voto nulo, mas no fim conseguiu |
| M8: Votar Presidente e Fim | 21 | ✓ | 1 | Teve êxito na etapa |

**Participante P06**

| Tarefa | Tempo (em segundos) | Resultado da tarefa | Erros | Observações |
| :--- | :--- | :--- | :--- | :--- |
| M1: Iniciar simulação | 24 | ! | 1 | Teve dificuldade de encontrar aonde clicar, e clicou no lugar errado, porém conseguiu retornar |
| M2: Ativar áudio | 5 | X | 1 | Não encontrou o botão de ativar áudio, e nem sabia da funcionalidade |
| M3: Abrir colinha | 86 | ! | 5 | Teve dificuldades em corrigir números errados |
| M4: Votar Dep. Federal | 32 | ✓ | 0 | Percorreu tranquilamente |
| M5: Corrigir Dep. Estadual | 31 | ! | 1 | Teve dificuldades com corrigir o número |
| M6: Votar em Branco (Senador) | 26 | ! | 1 | Demorou pra entender que eram dois senadores |
| M7: Votar Nulo (Governador) | 30 | ! | 1 | Não conseguiu entender que o voto seria nulo, mas o fez mesmo assim |
| M8: Votar Presidente e Fim | 9 | ✓ | 0 | Concluiu com êxito |

**Participante P07**

| Tarefa | Tempo (em segundos) | Resultado da tarefa | Erros | Observações |
| :--- | :--- | :--- | :--- | :--- |
| M1: Iniciar simulação | 8 | ✓ | 0 | O usuário conseguiu iniciar sem erros |
| M2: Ativar áudio | 41 | ! | 2 | O usuário teve certa dificuldade para ativar o áudio, mas conseguiu no fim |
| M3: Abrir colinha | 37 | ✓ | 0 | O usuário abriu a colinha e a preencheu sem dificuldades |
| M4: Votar Dep. Federal | 43 | ✓ | 0 | O usuário não teve dificuldades porem o site demorou pra carregar |
| M5: Corrigir Dep. Estadual | 26 | ! | 1 | O usuário teve um pouco de dificuldade com a correção, mas concluiu |
| M6: Votar em Branco (Senador) | 12 | ✓ | 0 | O usuário conseguiu sem problemas |
| M7: Votar Nulo (Governador) | 15 | ✓ | 0 | Entendeu rápido e registrou o voto |
| M8: Votar Presidente e Fim | 12 | ✓ | 0 | Concluiu com êxito |

**Participante P08**

| Tarefa | Tempo (em segundos) | Resultado da tarefa | Erros | Observações |
| :--- | :--- | :--- | :--- | :--- |
| M1: Iniciar simulação | 13 | ✓ | 0 | Iniciou sem erros |
| M2: Ativar áudio | 56 | X | 4 | O usuário procurou e tentou ativar, porem não conseguiu e prosseguiu sem |
| M3: Abrir colinha | 16 | ! | 1 | Usuário abriu a colinha, porém não a preencheu |
| M4: Votar Dep. Federal | 24 | ✓ | 0 | O usuário votou sem problemas |
| M5: Corrigir Dep. Estadual | 28 | ! | 0 | Usuário demorou um pouco pra entender aonde corrigia, mas conseguiu |
| M6: Votar em Branco (Senador) | 18 | ✓ | 0 | Votou tranquilamente em branco |
| M7: Votar Nulo (Governador) | 14 | ✓ | 0 | Entendeu rapidamente a mensangem e registrou |
| M8: Votar Presidente e Fim | 13 | ✓ | 0 | Registrou o voto sem problemas |

---

### Resumo por participante

Esta tabela consolida o desempenho geral de todos os usuários que realizaram o teste, somando os sucessos, dificuldades, falhas, tempo total e total de erros de cada um.

| Participante | Sucesso ✓ | Com dificuldade ! | Insucesso X | Tempo total (s) | Total de erros |
| :--- | :--- | :--- | :--- | :--- | :--- |
| P01 | 1 | 6 | 1 | 293 | 13 |
| P02 | 2 | 2 | 4 | 299 | 4 |
| P03 | 1 | 5 | 2 | 245 | 10 |
| P04 | 2 | 5 | 1 | 462 | 9 |
| P05 | 2 | 3 | 3 | 395 | 11 |
| P06 | 2 | 5 | 1 | 243 | 10 |
| P07 | 6 | 2 | 0 | 194 | 3 |
| P08 | 5 | 2 | 1 | 182 | 5 |

---

### Consolidação por tarefa

A tabela seguinte apresenta a taxa de sucesso e o tempo médio gasto em cada missão, permitindo identificar quais as etapas do simulador que geraram mais atrito geral.

| Tarefa | TSR - Taxa de Sucesso (%) | TTR - Tempo médio da tarefa (s) |
| :--- | :--- | :--- |
| M1: Iniciar simulação | 87,5% | 27,4 |
| M2: Ativar áudio | 25,0% | 28,8 |
| M3: Abrir colinha | 100,0% | 67,9 |
| M4: Votar Dep. Federal | 87,5% | 58,1 |
| M5: Corrigir Dep. Estadual | 62,5% | 31,6 |
| M6: Votar em Branco (Senador) | 75,0% | 29,4 |
| M7: Votar Nulo (Governador) | 100,0% | 31,4 |
| M8: Votar Presidente e Fim | 100,0% | 14,6 |

---

### Respostas abertas e fatores de usabilidade

[Insira aqui as respostas abertas recolhidas no questionário pós-teste e explique brevemente os padrões encontrados.]

### Considerações sobre o Teste de Usabilidade

[Apresente a conclusão final da equipa sobre a experiência de uso da urna baseada nos dados quantitativos acima e nos principais bloqueios observados.]
