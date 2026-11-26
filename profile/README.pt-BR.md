# Revive360

**O 360 tá vivo. Cola pra construir.** A gente faz app novo e aberto pro Xbox 360. Fonte na mesa, teste no console e crédito pra quem abriu o caminho.

[English](README.md) · [Español](README.es.md)

## Catálogo e três níveis

- **Revive360 Project** — repo dentro de [revive360](https://github.com/revive360), regras/segurança da org, PR revisado e release do CI assinada/atestada; validade contínua enquanto cumprir as regras. Selo de linha verde neon com mascote e medalha exclusiva Project, o mais forte.
- **Reviewed · vX.Y.Z** — repo do autor, só versão/hash/data revisados. Binário novo ou substituído volta à fila manual de menor prioridade, por chegada (alvo 14 dias); **versão atual não revisada** até o aceite. Autor compila, org confere hash e vínculo com fonte; sem canal de atualização da org. Se o autor sumir, o selo expira.
- **Community list** — descoberta sem selo: **Não verificado pela Revive360, não é recomendação, use por sua conta e risco.** Pode sair a qualquer momento.

O [catálogo](https://github.com/revive360/catalog) é a fonte da verdade; os selos levam às fichas e mostram válido, versão atual não revisada, expirado ou revogado. Ser membro não é selo. A org assume responsabilidade operacional pelos repos dela e pelas versões externas revisadas, no escopo documentado; repo de membro fora do catálogo é só do autor. Nome/selo sem ficha é uso indevido. Revisão não é auditoria completa; software **como está**, sem garantia pelo selo.

**[Tube360](https://github.com/revive360/tube360)**: app nativo de YouTube para o 360, MIT, de [@PedroHenrique0713](https://github.com/PedroHenrique0713). Está na org desde 2026-11-25. A ficha no catálogo e o selo Official chegam com a primeira release feita pelo CI da org; hoje o registro Project do catálogo é um exemplo fictício.

Segurança em qualquer nível: resposta em **48 h**, revogação imediata se grave. Releases Project seguem o CI automático após revisão e teste do binário exato em console real; revisão externa por chegada, alvo **14 dias**; Community quando der. Ninguém revisa o próprio app **exceto o fundador Pedro**, inclusive no nível máximo. Veja [checklist e limites](../REVIEW.md).

## Regras

1. **Lixo não entra.** Se não roda num 360 de verdade, nem abre PR.
2. **IA à vontade, slop não.** Usa a IA que quiser, mas o que chega aqui tem que ser bom. Slop é: código que você não sabe explicar, PR gigante sem teste, README genérico cheio de emoji, “app novo” que é template com outro nome.
3. **“Foi a IA” não é desculpa.** Assinou, é teu. Se o revisor perguntar, quem responde é você.
4. **Mais do mesmo, não.** Antes de propor app, mostra o que ele faz que ninguém faz, ou por que o teu é melhor. Clone de clone fica de fora.
5. **Pirataria aqui não.** Usa código aberto ou faz você mesmo. Nada de software pirata, jogo, chave ou SDK vazado. Trouxe, tá fora.
6. **Rodou no console ou não rodou.** Sem log ou outro registro do 360 real (foto, vídeo), não sai release.
7. **Zoeira sim, ataque não.** Pode zoar e pode discordar. Atacar pessoa, não. Crítica com argumento técnico é sempre bem-vinda.
8. **Teu app, tua responsa.** Dono cuida das issues e dos furos do próprio projeto.
9. **Crédito é sagrado.** Usou código de alguém, credita e respeita a licença.
10. **Aqui tem hierarquia.** Na org quem decide são os donos; no projeto, o mantenedor. Discute à vontade, mas a palavra final é de quem responde por aquilo. Sem isso vira bagunça.
11. **Sobe quem soma.** Acesso e papel crescem por mérito e contribuição de verdade (qualidade, confiança, presença), por convite de quem já está acima. Não existe conta do tipo “X PRs = vira tal coisa”; não é automático e ninguém sobe porque a cadeira está vazia.

## Cola pra somar

Chega nas [Discussions](https://github.com/orgs/revive360/discussions), mostra o que teu app acrescenta e traz uma parte funcionando. Quando estiver no ponto, abre **App proposal** ou **Join Revive360** no `.github`. Diz quem cuida, qual é a licença e de onde veio cada dependência. Não precisa de carteirinha pra contribuir. Projeto de outra pessoa só entra com o sim dela. Lê [CONTRIBUTING](../CONTRIBUTING.md), [GOVERNANCE](../GOVERNANCE.md) e o [Código de Conduta](../CODE_OF_CONDUCT.md). Pode falar português, inglês ou espanhol.

Ninguém construiu isso sozinho. Salve a [xenosworks](https://github.com/xenosworks), pelos projetos [xsdk](https://github.com/xenosworks/xsdk), [vulkan4xenon](https://github.com/xenosworks/vulkan4xenon) e [SDL-xenon](https://github.com/xenosworks/SDL-xenon), e a [Free60/libxenon](https://github.com/Free60Project/libxenon). A Revive360 complementa esse trabalho e preserva seus créditos.

## Pessoas, risco e contato

Hoje só o fundador Pedro é dono da org. Membros entram com acesso mínimo e sobem por histórico; não há promoção automática a dono. DCO obrigatório. O fundador decide mudanças de regras com 14 dias de aviso público; urgências de segurança são imediatas. O autor pode levar seu projeto de volta; arquivamento após 12 meses parado ou por violação. A org não recebe nem divide doações por enquanto.

**Homebrew pode causar banimento no Xbox Live, perda de dados e dano ao console; use por sua conta e risco.** Nada de coleta sem opt-in; login/tokens ficam no console. Risco dos termos de terceiros é do autor; proibido quebrar DRM/paywall.

O canal oficial da comunidade é [Revive360 Discussions](https://github.com/orgs/revive360/discussions), com `.github` como fonte; sem Discord no começo. Categorias: Anúncios, Ideias de apps, Ajuda e Mostre seu projeto. Issues/PRs ficam para bugs acionáveis e registros formais de revisão/entrada. Até dezembro, segurança por private vulnerability reporting e contato público por Discussions.

Xbox e Xbox 360 são marcas da Microsoft. A Revive360 é independente, sem vínculo ou endosso da Microsoft, Google ou dos projetos agradecidos.
