# Routing de operações

| Pedido | Entrada mínima | Saída | Verificação crítica |
|---|---|---|---|
| Texto → imagem | Brief, direção e especificação da peça aprovados | Composição e elementos de marca com variantes controladas | Texto/rótulo e consistência com identidade |
| Imagem → imagem | Imagem de origem autorizada, máscara/área ou alterações aprovadas | Preservar/alterar de forma separada | Identidade, forma, materiais, escala |
| Edição localizada | Original e região exata, restrições explícitas | Alteração circunscrita; resto preservado | Bordos, textura, continuidade e alterações não pedidas |
| Imagem → vídeo | Frame/referência autorizada, ação, destino, duração e formato | Movimento, câmara e continuidade temporal | Deformação, rótulo, flicker, início e fim |
| Texto → vídeo | Guião/direção aprovados, cenas e áudio autorizados | Plano por cena e continuidade | Claims, pessoas, áudio, cortes e consistência |
| Adaptação de ferramenta | Ficha existente e capacidades verificadas do destino | Nova versão com diferenças e parâmetros confirmados | Não inventar sintaxe, controlos ou suporte do modelo |

## Escolha de destino

- Imagem e edição: preparar instruções para a ferramenta escolhida e anexar referências quando suportadas. Não tratar o prompt como garantia de reprodução exata.
- Flow e outros geradores de vídeo: indicar movimento, duração, proporção e continuidade; confirmar na interface o modelo, limites, custos e opções antes de produzir.
- HeyGen/avatares: preparar apenas cena e indicações visuais. Guião, autorização de imagem/voz e configuração do avatar pertencem a etapas próprias.
- Sem destino decidido: ficheiro agnóstico, `FERRAMENTA_PENDENTE`, sem parâmetros inventados.

O Prompt Assistant não substitui o Brief, a Direção Criativa, a Produção ou a Revisão. Devolver à Direção se a mudança for conceptual; devolver ao Brief se objetivo, oferta ou público tiverem mudado.
