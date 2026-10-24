# Avaliação de Acessibilidade

A avaliação de acessibilidade teve como objetivo identificar barreiras de interação no simulador da urna eletrônica do Tribunal Superior Eleitoral (TSE), tomando como base os princípios e diretrizes da Web Content Accessibility Guidelines (WCAG 2.2) nos níveis A e AA. A análise contemplou tanto verificações manuais de navegação quanto o uso de tecnologias assistivas.

## Escopo da avaliação
Foram selecionadas as seguintes telas e componentes para inspeção:
* Tela de instruções e seleção do turno/eleição
* Interface do teclado virtual da urna eletrônica (teclas numéricas e teclas Branco, Corrige, Confirma)
* Tela de exibição dos dados e foto dos candidatos
* Mensagens de instrução e rodapé de navegação

## Processo utilizado
O processo foi organizado em três etapas sequenciais:
1. **Detecção:** Realização dos testes práticos no simulador divididos em quatro técnicas: navegação exclusiva por teclado (Tab/Shift+Tab/Enter), utilização do software leitor de tela (NVDA) para verificação do retorno sonoro das teclas virtuais, análise do tamanho de fontes e espaçamento de leitura, e teste de taxa de contraste de cores nos botões de comando.
2. **Coleção:** Agrupamento de todas as inconsistências mapeadas em uma lista consolidada.
3. **Discriminação:** Análise de cada ocorrência para classificar a gravidade, descartar falsos positivos e associar cada defeito ao critério correspondente da WCAG 2.2.

## Resultados da inspeção

Abaixo estão apresentados os problemas encontrados e o detalhamento das diretrizes violadas.

### Síntese dos problemas encontrados
A tabela a seguir resume as principais barreiras de acessibilidade identificadas durante os testes práticos na interface do simulador, acompanhadas do respectivo critério da WCAG e frequência de ocorrência.

| Problema | Critério WCAG | Tela/Página | Frequência |
| :--- | :--- | :--- | :--- |
| Botões do teclado virtual sem rótulo textual adequado para leitor de tela | 1.1.1 Conteúdo não textual | Teclado da Urna | 13 |
| Contraste insuficiente entre o texto do botão "Branco" e o fundo do botão | 1.4.3 Contraste mínimo | Teclado da Urna | 1 |
| Impossibilidade de acionar teclas da urna exclusivamente via teclado físico | 2.1.1 Teclado | Interface de Votação | 1 |
| Indicador de foco visual ausente ou imperceptível ao navegar por Tab | 2.4.7 Foco visível | Todas as telas | 4 |

### Critérios WCAG violados
A tabela a seguir classifica as violações mapeadas de acordo com os princípios, diretrizes e níveis de conformidade da WCAG 2.2.

| Princípio | Diretriz | Critério violado | Nível |
| :--- | :--- | :--- | :--- |
| Perceptível | 1.1 Alternativas em texto | 1.1.1 Conteúdo não textual | A |
| Perceptível | 1.4 Distinguível | 1.4.3 Contraste mínimo | AA |
| Operável | 2.1 Acessível por teclado | 2.1.1 Teclado | A |
| Operável | 2.4 Navegável | 2.4.7 Foco visível | AA |

## Considerações sobre os resultados
A inspeção revelou que a interface do simulador web do TSE apresenta forte dependência do mouse para simular a interação física da urna. A ausência de suporte completo à navegação por teclado e a falta de rótulos acessíveis em parte dos botões numéricos criam barreiras severas para usuários que utilizam leitores de tela. Para mitigar esses problemas, recomenda-se a implementação imediata de atributos `aria-label` nos componentes da urna virtual, a definição de estilos explícitos de foco via CSS (`:focus`) e o ajuste no contraste dos botões de ação especial.
```[cite: 19, 20]
