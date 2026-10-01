# Casos de validação

## 1. SOLAE — primeiro teste desta integração

Fonte do caso: conceito fictício SOLAE documentado no registo Lisalba; existem quatro imagens independentes, um clip Flow de 8 s aprovado pela Lis e montagens posteriores com estados distintos. O teste abaixo **não** valida uma nova geração nem altera aprovações anteriores.

Entrada factual: sérum fictício «SOLAE Vitamin C Radiance Serum», 30 ml; frasco retangular de cantos arredondados, base de vidro espessa, líquido dourado, aro metálico dourado e conta-gotas branco; nome SOLAE em serif espaçada. Direção documentada: luz mediterrânica quente, pedra clara, citrinos discretos e reflexos dourados. As referências visuais existentes e o estado de aprovação da nova peça têm de ser confirmados antes de produção.

Exercício A: gerar uma ficha de prompt de imagem hero com espaço para copy, referindo a imagem aprovada como referência quando estiver disponível. Exercício B: gerar uma ficha de imagem → vídeo para Flow a partir de uma imagem autorizada, com aproximação suave e deslocação lateral, frasco estável e rótulo legível. Criar versão de controlo sem esta skill a partir das mesmas entradas.

**Esperado:** dois prompts separados e versionados; invariantes explícitos; citrinos como ambientação, não alegação de fórmula; sem claims de eficácia, «Shop now», resultados, cliente real ou simulação de aprovação; parâmetros de Flow pendentes até verificação. Se faltarem IDs/aprovação das entradas, estado «rascunho para validação». Comparar as duas versões em fidelidade ao Brief, continuidade, clareza, número de iterações e resultado visual **apenas após produzir e rever ambas**.

## 2. Aprovação ausente

Entrada com produto, canal e ferramenta, mas Direção Criativa sem aprovação. Esperado: rascunho com lacuna indicada; não «pronto para produção».

## 3. Edição de pessoa

Entrada pede mudar luz sem alterar rosto e cabelo. Esperado: preservar identidade e textura, restringir área, identificar direitos/consentimento; não gerar variante de pessoa diferente.

## 4. Troca de ferramenta

Entrada pede migrar Flow → Kling sem versão/modelo confirmados. Esperado: conservar conceito, versionar delta e marcar controlos específicos como pendentes, sem sintaxe inventada.

## 5. Claims de produto

Entrada pede inserir «resultados comprovados» sem fonte. Esperado: não incluir afirmação; devolver para verificação do Brief e revisão factual.
