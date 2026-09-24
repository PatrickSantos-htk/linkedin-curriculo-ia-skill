# Reformular LinkedIn (e GitHub) por Currículo — Skill para Claude

Uma **skill** para o [Claude](https://claude.ai) que transforma o seu currículo num perfil de LinkedIn (e num GitHub, se você é de tecnologia) mais fácil de encontrar por recrutadores e sistemas ATS, **sem inventar ou exagerar nenhuma qualificação**.

Serve para qualquer área: desenvolvimento, dados, design, vendas, RH, marketing...

## O que ela faz

1. **Lê o seu currículo** e pergunta o que estiver faltando (números reais, projetos, instituições).
2. **Analisa vagas reais da sua área:** separa o que é requisito, o que é desejável e quais lacunas se repetem.
3. **Avalia a sua senioridade** (estágio, júnior, pleno...) e mostra o que falta para o próximo nível, com um plano.
4. **Gera um currículo otimizado para ATS.**
5. **Audita o seu LinkedIn** e entrega os textos novos prontos para copiar: título, Sobre, experiências, competências e destaque.
6. **Monta um banner de capa** (1584×396) com a sua identidade.
7. **Revisa o seu GitHub:** bio, README de perfil, projetos em destaque, fixados, descrições e topics.
8. **Dá uma nota** para o perfil antes e depois, com os próximos passos.

## Princípios

- 🧾 **Só entra o que você confirmar.** Nada de tecnologia que você não usa, tempo inflado ou número inventado.
- 🔗 **Currículo, LinkedIn e GitHub coerentes:** mesmo cargo, mesmas datas, mesmas instituições.
- 🤫 **Discrição por padrão:** para quem está empregado e não quer que a busca fique visível. Nada de #OpenToWork público, e "Compartilhar com a rede" sempre desligado ao editar.
- 🙋 **Você no controle:** a skill **não automatiza o LinkedIn**. Você revisa e aplica cada mudança.

## Como instalar

**Claude (app ou web):** vá em *Configurações → Capacidades → Skills*, crie uma skill nova e cole o conteúdo de [`skill/SKILL.md`](skill/SKILL.md). Também dá para enviar a pasta `skill/` compactada em .zip.

**Claude Code:** copie a pasta `skill/` para `~/.claude/skills/reformular-linkedin-por-curriculo/`.

Depois, é só pedir algo como:

> "Quero reformular meu LinkedIn a partir do meu currículo. Sou analista de dados júnior e busco vagas remotas."

e anexar o currículo.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| [`skill/SKILL.md`](skill/SKILL.md) | A skill em si |
| [`templates/checklist-linkedin.md`](templates/checklist-linkedin.md) | Checklist para auditar o LinkedIn |
| [`templates/checklist-github.md`](templates/checklist-github.md) | Checklist para auditar o GitHub |
| [`templates/modelo-curriculo-ats.md`](templates/modelo-curriculo-ats.md) | Estrutura de currículo que o ATS lê bem |
| [`templates/banner.html`](templates/banner.html) | Gerador de banner editável |
| [`exemplos/exemplo-ficticio.md`](exemplos/exemplo-ficticio.md) | Exemplo de antes e depois |
| [`CHANGELOG.md`](CHANGELOG.md) | Histórico de versões |

## Aviso

A skill é uma ferramenta de apoio e não garante contratação. Ela não faz automação nem raspagem de dados no LinkedIn: respeite os [Termos de Uso do LinkedIn](https://www.linkedin.com/legal/user-agreement) e aplique as mudanças manualmente.

## Contribua

Sugestões, correções e adaptações para outras áreas são muito bem-vindas. Veja o [CONTRIBUTING.md](CONTRIBUTING.md).

---

Feito por **Patrick Santos Ribeiro** · [LinkedIn](https://www.linkedin.com/in/patrick-santos-162899207/) · [Portfólio](https://patricksantosribeiro.vercel.app) · Licença [MIT](LICENSE)
