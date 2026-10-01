---
name: jm-image-video-prompt-assistant
description: Preparar, adaptar e versionar fichas de prompts de imagem, edição e vídeo para a Lisalba Studio a partir de um Brief e uma Direção Criativa aprovados. Usar no papel Prompt Builder entre direção e produção, incluindo testes SOLAE e passagem para Revisão Lisalba; não executar a produção nem aprovar resultados.
---

# JM Image & Video Prompt Assistant — Lisalba Studio

Transformar decisões criativas aprovadas em instruções técnicas verificáveis para a ferramenta escolhida. Operar no fluxo **Brief aprovado → Direção criativa aprovada → Prompt Assistant → Produção Lisalba → Revisão Lisalba**. O Coordinator mantém o estado e as aprovações; esta skill apenas prepara a passagem à produção.

## Antes de escrever

1. Ler [ROUTING.md](references/ROUTING.md) para escolher a operação e o destino. Ler [SOURCE_STATUS.md](references/SOURCE_STATUS.md) quando forem mencionados o GPT JM, os sete PDFs ou especificações de ferramentas.
2. Confirmar identificador e versão do Brief e da Direção Criativa, estado de aprovação por pessoa autorizada, objetivo, público, peça, canal, formato, ferramenta, referências autorizadas, invariantes, alterações permitidas e critérios de aceitação. Não inferir aprovações a partir da existência de um documento ou imagem.
3. Se faltar aprovação ou um invariante material, produzir **rascunho para validação**, apontar a lacuna e suspender a etiqueta «pronto para produção». Se a ferramenta não estiver definida, criar um prompt agnóstico e marcar parâmetros específicos como pendentes.
4. Distinguir factos de fonte, decisões aprovadas e sugestões técnicas. Não acrescentar claims, resultados, clientes, licenças ou características de produto. Não copiar materiais confidenciais para repositórios públicos.

## Preparar a Ficha de Prompt Lisalba

Usar [PROMPT_CARD.md](references/PROMPT_CARD.md). Descrever sujeito/produto, cenário, ação, enquadramento, luz, cor e materialidade em termos observáveis. Fixar identidade, embalagem, rótulo, geometria e relações espaciais antes de variar estilo. Para edição, referir explicitamente a imagem de origem e separar «preservar» de «alterar». Para vídeo, definir fotograma/referência inicial, movimento de câmara e objetos, continuidade, fim do plano, duração e proporção, sem atribuir suporte técnico não confirmado ao modelo.

Escrever em português de Portugal ou inglês conforme a ferramenta e o projeto; preservar texto de marca exatamente como aprovado. A indicação histórica de 20–50 palavras é apenas uma opção para modelos/tarefas adequados: usar o comprimento necessário para restrições e continuidade. Não substituir uma versão aprovada sem registar o delta.

Entregar prompt principal, exclusões relevantes, referências, parâmetros confirmados e pendentes, critérios de inspeção, estado e nome `PROJETO_OPERACAO_FERRAMENTA_PROMPT_vNN`. Evitar listas de negativos que contradigam o objetivo. Se for útil, criar variantes controladas que mudem uma variável de cada vez.

## Passagem e revisão

Entregar a ficha à Produção Lisalba, sem gerar nem publicar automaticamente. Registar ferramenta/modelo e parâmetros efetivamente usados, custo/tentativas se conhecidos, ficheiro de saída e diferenças observadas. A Revisão Lisalba inspeciona a imagem ampliada ou fotogramas e decide aceitar, devolver ao Prompt Assistant/Direção ou rejeitar. Rever em especial rótulos, anatomia, materiais, reflexos, contacto, flicker, legibilidade, formato, direitos e claims. A publicação ou entrega externa exige autorização humana específica.

Para verificar o comportamento da skill, executar os casos de [TEST_CASES.md](tests/TEST_CASES.md). SOLAE é o primeiro caso de **validação desta integração**; já existem imagens e um clip anteriores. Não chamar a um prompt estrutural um teste de geração nem afirmar que o GPT externo ou os PDFs foram reproduzidos.
