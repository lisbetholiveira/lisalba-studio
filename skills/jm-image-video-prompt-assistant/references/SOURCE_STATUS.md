# Fontes, limites e dependências

## Verificado para a integração

- `lisbetholiveira/lisalba-studio` no branch `main`: `README.md`, `docs/agent-system.md`, `docs/creative-workflow.md`, `docs/quality-principles.md` e `case-studies/README.md` definem etapas, gates, responsabilidades, regras de publicação e SOLAE como teste da integração.
- Página Notion «Lisalba Studio» (consultada em 01-10-2026): integra o JM entre Direção e Produção, pede prompts versionados e revisão visual, e prevê `SKILL.md`, `references/ROUTING.md`, sete PDFs e `tests/TEST_CASES.md`.
- Nota de integração `JM_Prompt_Assistant_Integracao_Lisalba.md`: define a Ficha de Prompt, operações, versão e comparação SOLAE.

## Dependências externas não incorporadas

- **Sete PDFs originais do GPT JM:** não foram localizados nas fontes consultadas; títulos, conteúdo, licença e compatibilidade não verificados. Não atribuir a este pacote regras desses documentos. Após acesso legítimo, inventariar nome, versão, origem e permissão; rever a skill antes de os integrar.
- **GPT externo JM:** URL registado na nota interna, mas instruções internas e saída real não foram inspecionadas. Esta skill é uma implementação Lisalba baseada nas fontes verificadas, não uma cópia fiel nem uma migração completa do GPT.
- **Plataformas de geração:** capacidades, preços e sintaxe podem mudar. Confirmar no destino concreto antes da execução; não fixar custos ou comandos presumidos.

O repositório público contém apenas regras operacionais genéricas e um teste conceptual. Referências privadas, chaves, PDFs com direitos incertos e prompts de clientes ficam fora dele.
