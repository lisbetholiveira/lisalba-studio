# SOLAE — ensaio estrutural do Prompt Assistant, 01-10-2026

**Estado:** prompts preparados em rascunho; sem geração, comparação visual ou nova aprovação. SOLAE já tinha quatro imagens e um clip Flow de 8 segundos aprovado. As montagens seguintes possuem estados de revisão próprios.

**Fontes de entrada:** conceito documentado em `Documento_Mestre_Lisalba_Studio_Atualizado.docx` e `SOLAE_Case_Study_v1.docx`. A aprovação específica do Brief/Direção para estas duas novas peças e os ficheiros de referência autorizados não constam deste ensaio. Confirmar antes de Produção.

## A — `SOLAE_TEXT_TO_IMAGE_FERRAMENTA_PENDENTE_PROMPT_v01`

- Operação: texto → imagem hero; ferramenta, proporção e canal finais por confirmar.
- Invariantes documentados: frasco retangular de cantos arredondados, base de vidro espessa, líquido dourado, aro metálico dourado, conta-gotas branco; rótulo «SOLAE», «Vitamin C Radiance Serum», «30 ml». Confirmar grafismo exato na imagem de referência autorizada.
- Variáveis propostas: disposição da pedra e citrinos; manter leitura do frasco e área livre para copy.
- Prompt (PT-PT, agnóstico): «Fotografia editorial de produto para um conceito fictício de skincare. Frasco SOLAE sobre pedra clara, com luz mediterrânica quente, sombras suaves e reflexos dourados no vidro. Preserva a forma retangular de cantos arredondados, a base espessa, o líquido dourado, o aro metálico dourado e o conta-gotas branco da referência autorizada. Mantém legíveis SOLAE, Vitamin C Radiance Serum e 30 ml. Citrinos discretos no cenário; composição com espaço limpo para texto acrescentado em montagem gráfica posterior.»
- Excluir: alteração do frasco/rótulo, texto adicional, claims de eficácia, pessoas e cenário apresentado como local real documentado.
- Aceitação: comparar geometria e texto ampliados com a referência; verificar luz, reflexos, hierarquia e espaço para montagem; revisão humana obrigatória.
- Pendentes: Brief/Direção aprovados para esta peça; imagem de referência e permissão; ferramenta; canal/proporção. **Rascunho para validação.**

## B — `SOLAE_IMAGE_TO_VIDEO_FLOW_PROMPT_v01`

- Operação: imagem → vídeo, destino Flow; modelo, duração, proporção, áudio e custo por confirmar na interface.
- Entrada: imagem SOLAE autorizada, ainda por identificar; não usar o clip anterior como aprovação automática desta nova peça.
- Prompt (inglês descritivo para Flow): “Use the authorised SOLAE product image as the first-frame reference. A gentle camera push-in with a slight lateral move across pale stone in warm Mediterranean light. Keep the rectangular rounded-corner glass bottle, thick base, golden serum, gold collar, white dropper and exact visible label stable throughout. Subtle light and shadow movement; citrus remains background styling. End on a clear, still product frame with readable SOLAE, Vitamin C Radiance Serum and 30 ml. No new text, claims, hands or changes to packaging.”
- Aceitação: rever frame inicial/final e amostras intermédias; rótulo, forma, tampa, reflexos, contacto com pedra, flicker e deformação; comparar com Brief e Direção aprovados.
- Pendentes: aprovação da nova peça, referência de origem, modelo e opções suportadas, duração/formato, custo e resultado de produção. **Rascunho para validação.**

## Resultado deste ensaio

| Critério estrutural | Observação |
|---|---|
| Duas operações e versões separadas | Cumpre |
| Invariantes e restrições presentes | Cumpre no texto; eficácia visual por testar |
| Claims e resultados não inventados | Cumpre |
| Aprovação e ferramenta em falta | Sinalizadas; sem estado «pronto para produção» |
| Comparação JM vs. controlo e iterações | Pendente de execução com as mesmas entradas aprovadas |
| Geração e revisão visual | Não executadas neste ensaio |

Uma comparação honesta exige executar duas variantes com as mesmas referências, registar tentativas/custos e submeter ambas à Revisão Lisalba. A existência do GPT JM e dos sete PDFs não comprova equivalência de comportamento.
