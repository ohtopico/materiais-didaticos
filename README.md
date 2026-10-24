# Materiais didáticos interativos

Atividades em HTML para usar em sala de aula: cada material é **um único arquivo** que abre direto no navegador, funciona **sem internet** e **não coleta nenhum dado** dos alunos.

Os materiais acompanham a página [IA pra Prof](https://ohtopico.com.br/ia-pra-prof/), que ensina professores a criar atividades como estas com inteligência artificial.

## Materiais

| Arquivo | O que é | Conteúdo |
| --- | --- | --- |
| [`calculadora-bhaskara.html`](calculadora-bhaskara.html) | Calculadora que resolve a equação do 2º grau mostrando cada passo, do Δ até a conferência das raízes | Equação do 2º grau (9º ano) |
| [`jogotriangulo.html`](jogotriangulo.html) | *Detetive de Triângulos*: o aluno arrasta os vértices para cumprir missões e depois treina o ângulo que falta | Classificação de triângulos e soma dos ângulos internos |
| [`mapa do tesouro matemático.html`](mapa%20do%20tesouro%20matem%C3%A1tico.html) | Jogo de mapa com seis missões; a caverna do tesouro só abre depois das cinco primeiras | Soma, frações, porcentagem, área, equações e expressões |
| [`criador de prompts.html`](criador%20de%20prompts.html) | Montador de prompts pelo método **P.A.C.T.O.** (Papel, Alvo, Comando, Tom e formato, Observações) | Ferramenta para o professor usar com IA |

## Como usar

1. Clique no arquivo desejado e depois em **Download raw file** (ícone de download).
2. Abra o arquivo baixado no navegador (Chrome, Edge, Firefox ou o navegador do celular).
3. Para usar com a turma, envie o arquivo por WhatsApp, Drive ou pendrive. Ele funciona offline.

Para adaptar uma atividade, abra o arquivo num editor de texto. As questões, missões e dicas ficam reunidas em listas no começo do `<script>` (por exemplo, `MISSOES` no mapa do tesouro e no jogo dos triângulos), então dá para trocar o conteúdo sem mexer no resto do código.

## Como o código está organizado

- Tudo em um arquivo: HTML, CSS e JavaScript, sem bibliotecas externas.
- Nomes em português que dizem o que cada parte faz (`montarPassos`, `analisarTriangulo`, `conferirResposta`).
- Funções pequenas, cada uma com uma tarefa só, e números importantes guardados em constantes com nome (`TOLERANCIA_ANGULO_RETO`, `PERGUNTAS_POR_RODADA`).
- Cores com bom contraste, modo escuro automático, navegação por teclado e textos lidos por leitores de tela.

## Autora

Júlia Roberta Quoos Alves, professora de computação e formadora de professores em IA.
[ohtopico.com.br](https://ohtopico.com.br) · [LinkedIn](https://www.linkedin.com/in/ohtopico)
