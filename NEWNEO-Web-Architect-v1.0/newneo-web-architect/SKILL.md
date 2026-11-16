---
name: newneo-web-architect
description: Metodologia NEWNEO para planejar, auditar, construir e validar sites, landing pages e aplicações web por etapas com aprovação explícita, preservação do código aprovado e qualidade premium.
---

# NEWNEO Web Architect — v1.0

## Quando usar
Ativar em projetos NEWNEO de criação, evolução, auditoria e publicação de sites e aplicações web, especialmente quando o trabalho é conduzido no Google Antigravity. Adaptar rigor e stack ao tipo de projeto; não impor estilo cinematográfico ou tecnologia específica.

## Regras inegociáveis
1. **Auditar antes de modificar.** Primeiro compreender objetivo, código, infraestrutura, mídias, riscos e estado atual.
2. **Etapas com autorização explícita.** Propor escopo, executar apenas a etapa autorizada, testar, relatar e aguardar aprovação antes de continuar. Aprovação visual não substitui testes técnicos.
3. **Preservar o aprovado.** Não alterar, refatorar, renomear, remover ou redesenhar partes aprovadas sem autorização. Exceção: risco crítico de segurança deve ser comunicado imediatamente, com correção proposta e autorização apropriada.
4. **Não inventar fatos comerciais.** Nunca criar preços, certificações, depoimentos, números, horários, garantias, avaliações ou serviços não confirmados.
5. **Escolher tecnologia pelo problema.** GSAP, WebGL, vídeo, 3D, Supabase e integrações são opcionais, não requisitos automáticos.
6. **Performance, acessibilidade, responsividade e segurança são critérios de aceite**, não uma etapa opcional no fim.
7. **Não publicar sem autorização.** Commits, pushes, deploys, alterações em produção e ações destrutivas precisam de escopo e autorização específicos.
8. **Relatar o que foi realmente testado.** Não declarar sucesso de dispositivos físicos, integrações externas ou métricas sem evidência.

## Fluxo operacional
0. **Identificar categoria:** institucional, landing page, e-commerce, SaaS/app ou híbrido; reconhecer objetivos de conversão, público, manutenção e restrições.
1. **Briefing e inventário:** usar `references/briefing.md` e `references/auditoria-inicial.md`; separar fatos confirmados, hipóteses e pendências.
2. **Plano técnico e visual:** arquitetura de informação, design system, stack, mapa de seções, acessibilidade, mídias, orçamento de performance e critérios de aceite; consultar `references/design-system.md`.
3. **Propor roadmap por etapas:** cada etapa deve ter objetivo, limites, dependências, entregáveis, testes e decisão de aprovação. Usar `templates/plano-de-execucao.md`.
4. **Implementar somente a etapa autorizada:** preservar os componentes aprovados; mudanças mínimas, legíveis, reversíveis; usar `references/desenvolvimento-por-etapas.md`.
5. **Validar e reportar:** executar verificações pertinentes e produzir `templates/relatorio-de-etapa.md`; marcar o estado como `AGUARDANDO_APROVACAO`.
6. **Após aprovação explícita:** registrar decisões e seguir à próxima etapa autorizada.
7. **Auditoria final independente:** `references/performance-seo.md` e `references/checklist-final.md`. Primeiro diagnosticar; correções em etapa separada quando solicitado.
8. **Publicação:** somente após autorização, com checklist de ambiente, backup/rollback e validação pós-deploy.

## Estado persistente obrigatório
Manter no projeto `NEWNEO_PROJECT_STATE.md` com: contexto, stack, inventário, etapas e status (`PLANEJADA`, `AUTORIZADA`, `EM_EXECUCAO`, `AGUARDANDO_APROVACAO`, `APROVADA`, `BLOQUEADA`), decisões aprovadas, áreas congeladas, pendências, testes e próximo passo. Não inferir aprovação pelo silêncio.

## Estratégia de resposta
- Antes de executar: apresentar resumo do escopo e do que NÃO será alterado.
- Durante execução: apontar bloqueios reais e solicitar dados essenciais, sem fabricar soluções.
- Após executar: relatório objetivo de arquivos, alterações, testes, limitações, riscos e evidências.
- Se pedido ultrapassar o escopo: solicitar autorização adicional.

## Referências sob demanda
- `references/briefing.md`
- `references/auditoria-inicial.md`
- `references/design-system.md`
- `references/desenvolvimento-por-etapas.md`
- `references/experiencias-cinematograficas.md`
- `references/responsividade.md`
- `references/performance-seo.md`
- `references/checklist-final.md`
- `templates/plano-de-execucao.md`
- `templates/relatorio-de-etapa.md`

## Caso de referência — Batistela Auto Center
Sequência validada como **exemplo adaptável**, não receita universal: auditoria de mídias → benchmark e otimização de vídeo → fundação/design system → header/hero → refinamento mobile → institucional/scroll cinematográfico → ajustes de duração e legibilidade → serviços → galeria real/lightbox → contato/mapa/rodapé → auditoria final. Lições: reduzir HUD técnico em experiências editoriais, preservar conteúdo real, evitar duplicação de cards, usar overlays localizados para legibilidade e testar mobile. Não copiar textos, contatos, imagens ou identidade da Batistela para outros projetos.
