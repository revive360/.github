# Revive360

**Software novo e aberto para um console de vinte anos.** Fazemos apps de verdade para o Xbox 360 de hoje, do zero e abertos, apoiados no ecossistema homebrew existente.

[English](README.md) · [Español](README.es.md)

## Catálogo e três níveis

- **Revive360 Project** — repo dentro de [revive360](https://github.com/revive360), regras/segurança da org, PR revisado e release do CI assinada/atestada; validade contínua enquanto cumprir as regras. Selo de linha verde neon com mascote e medalha exclusiva Project, o mais forte.
- **Reviewed · vX.Y.Z** — repo do autor, só versão/hash/data revisados. Binário novo ou substituído volta à fila manual de menor prioridade, por chegada (alvo 14 dias); **versão atual não revisada** até o aceite. Autor compila, org confere hash e vínculo com fonte; sem canal de atualização da org. Se o autor sumir, o selo expira.
- **Community list** — descoberta sem selo: **Não verificado pela Revive360, não é recomendação, use por sua conta e risco.** Pode sair a qualquer momento.

O [catálogo](https://github.com/revive360/catalog) é a fonte da verdade; os selos levam às fichas e mostram válido, versão atual não revisada, expirado ou revogado. Ser membro não é selo. A org assume responsabilidade operacional pelos repos dela e pelas versões externas revisadas, no escopo documentado; repo de membro fora do catálogo é só do autor. Nome/selo sem ficha é uso indevido. Revisão não é auditoria completa; software **como está**, sem garantia pelo selo.

**Tube360** — app nativo de YouTube, MIT, dono [Pedro](https://github.com/PedroHenrique0713). O [repo real](https://github.com/PedroHenrique0713/tube360) continua na conta do autor. O registro Project no catálogo local é **demonstração de um estado futuro dentro da org**, sem transferência ou certificação real. Nenhum outro app real está listado.

Segurança em qualquer nível: resposta em **48 h**, revogação imediata se grave. Releases Project seguem o CI automático após revisão e teste do binário exato em console real; revisão externa por chegada, alvo **14 dias**; Community quando der. Ninguém revisa o próprio app **exceto o fundador Pedro**, inclusive no nível máximo. Veja [checklist e limites](../REVIEW.md).

## Regras

1. Só código aberto e feito pelos membros, ou bibliotecas abertas com licença compatível.
2. Nada de pirataria, jogos, chaves, SDK vazado da Microsoft nem exploit distribuído. BadUpdate/RGH são pré-requisito de quem usa, fora da org.
3. Cada projeto tem dono e licença própria (MIT, GPL e afins convivem); código só passa de um projeto a outro respeitando a licença.
4. Todo lançamento é testado em console de verdade.
5. IA como ferramenta é permitida; quem assina responde pelo código.
6. Comunidade em português, espanhol e inglês.

## Propor um app ou entrar

Abra uma issue **App proposal** ou **Join Revive360** neste repositório. Informe o app, a pessoa responsável, a licença e a origem das dependências. Projeto existente só entra com a concordância do dono. Não é preciso ser membro para contribuir. Leia [CONTRIBUTING](../CONTRIBUTING.md), [GOVERNANCE](../GOVERNANCE.md) e o [Código de Conduta](../CODE_OF_CONDUCT.md); aceitamos discussão nos três idiomas.

Obrigado a [xenosworks](https://github.com/xenosworks), pelos projetos [xsdk](https://github.com/xenosworks/xsdk), [vulkan4xenon](https://github.com/xenosworks/vulkan4xenon) e [SDL-xenon](https://github.com/xenosworks/SDL-xenon), e a [Free60/libxenon](https://github.com/Free60Project/libxenon). A Revive360 complementa esse trabalho e preserva seus créditos.

## Pessoas, risco e contato

Hoje só o fundador Pedro é dono da org. Membros entram com acesso mínimo e sobem por histórico; não há promoção automática a dono. DCO obrigatório. O fundador decide mudanças de regras com 14 dias de aviso público; urgências de segurança são imediatas. O autor pode levar seu projeto de volta; arquivamento após 12 meses parado ou por violação. A org não recebe nem divide doações por enquanto.

**Homebrew pode causar banimento no Xbox Live, perda de dados e dano ao console; use por sua conta e risco.** Nada de coleta sem opt-in; login/tokens ficam no console. Risco dos termos de terceiros é do autor; proibido quebrar DRM/paywall.

O canal oficial da comunidade é [Revive360 Discussions](https://github.com/orgs/revive360/discussions), com `.github` como fonte; sem Discord no começo. Categorias: Anúncios, Ideias de apps, Ajuda e Mostre seu projeto. Issues/PRs ficam para bugs acionáveis e registros formais de revisão/entrada. Até dezembro, segurança por private vulnerability reporting e contato público por Discussions. `CONTACT_DECEMBER_2026_TODO`: inserir depois e-mail/domínio confirmados.

Xbox e Xbox 360 são marcas da Microsoft. A Revive360 é independente, sem vínculo ou endosso da Microsoft, Google ou dos projetos agradecidos.
