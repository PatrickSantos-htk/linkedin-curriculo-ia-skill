---
name: reformular-linkedin-por-curriculo
description: Use quando alguém quiser reformular o perfil do LinkedIn a partir do currículo e da área de atuação, com otimização para recrutadores e ATS, sem inflar qualificações.
---

# Reformulação de LinkedIn a partir do currículo

Objetivo: deixar o perfil do LinkedIn da pessoa alinhado ao currículo, às vagas reais da área e ao nível de senioridade dela. Ele deve ser encontrado nas buscas de recrutadores e convencer quem lê. **Nunca invente ou exagere qualificações.**

## Escopo

**Faz:** análise do currículo, leitura de vagas da área, avaliação de senioridade, currículo otimizado para ATS, textos novos para o LinkedIn (título, Sobre, experiências, formação, competências, destaque), banner de capa e nota do perfil com plano de melhoria.

**Não faz:** automação do LinkedIn (preencher formulários, raspar dados, candidaturas em massa), login, publicações ou mensagens em nome da pessoa, nem exclusão de conteúdo. **A pessoa revisa e aplica as mudanças no perfil por conta própria.**

## Regras que não mudam

1. **Só vale o que a pessoa confirmou.** O currículo e as respostas dela são a base de verdade. Não acrescente ferramenta, tempo de experiência, número ou resultado que ela não confirmou. Se faltar um dado, pergunte.
2. **Nenhum número inventado.** Sem o valor real, escreva o resultado sem número (ex.: "reduzindo custos").
3. **Mantenha tudo coerente.** Cargo, datas e instituições têm de bater entre currículo e LinkedIn. Quando houver divergência, pergunte qual está certo.
4. **Avise quando um texto soar maior do que a experiência.** Ex.: o resumo diz "engenharia de dados", mas a experiência é "apoio ao time de dados". Aponte e alinhe.
5. **Discrição é o padrão.** Parta do princípio de que a pessoa pode estar empregada e não quer que saibam da busca.

## Fluxo

### 1. Coleta
- Peça o currículo (PDF ou DOCX) e, se houver, o link do portfólio.
- Pergunte a área-alvo, os tipos de vaga, o nível e a modalidade (remoto, híbrido, presencial, cidade).
- Peça que a pessoa cole o texto atual do LinkedIn (título, Sobre, experiências, formação e lista de competências) ou exporte o perfil em PDF (**Mais → Salvar como PDF**).
- Pergunte o que falta: nome das instituições, números reais, projetos com link, o que a pessoa faz em cada função e ferramentas usadas de verdade que não estão no currículo.

### 2. Vagas da área
- Peça que a pessoa cole de 10 a 20 descrições de vagas que interessam, ou pesquise vagas públicas na web quando houver ferramenta de busca.
- Separe o que é **requisito**, o que é **desejável** e quais **lacunas se repetem**.
- Monte uma tabela com as vagas de maior aderência (aderência alta, média ou baixa e o motivo).

### 3. Senioridade
- Compare tempo de experiência (efetivo ou estágio/freelance), autonomia, escopo e ferramentas com o que as vagas pedem em cada nível.
- Dê um veredito claro (ex.: "júnior forte, pleno ainda não") e uma tabela do que falta para o próximo nível, com plano prático e prazo realista.

### 4. Currículo otimizado para ATS
- Uma coluna, texto selecionável, sem tabelas, colunas ou ícones que o ATS não lê. Uma página sempre que der.
- Título com cargo, nível e 3 ou 4 palavras-chave da área. Bullets que começam com verbo e citam ferramenta e resultado. Projetos com link no bullet.
- Use `templates/modelo-curriculo-ats.md` como base.

### 5. Auditoria do perfil
Use `templates/checklist-linkedin.md`. Procure principalmente:
- Título sem palavras-chave.
- **Setor** errado. Ele não aparece no perfil, mas os recrutadores filtram por ele.
- Cargo ou datas diferentes do currículo.
- Competências de outra área ocupando espaço (o LinkedIn aceita no máximo 100).
- #OpenToWork ou "buscando oportunidades" em posts públicos ou no Em destaque.

### 6. Textos novos
Entregue prontos para copiar e colar:
- **Título (até 220 caracteres):** cargo + nível + competências principais + diferencial.
- **Sobre (até 2.600 caracteres):** frase de posicionamento, emprego atual com entregas, projetos próprios, formação, linha de competências e link do portfólio.
- **Experiências:** as mesmas descrições do currículo, com ▸ nos bullets.
- **Competências:** o que adicionar (ligado a cada experiência), o que remover e as 5 principais.
- **Em destaque:** projetos no ar e portfólio.

### 7. Banner (opcional)
- 1584×396 px. Deixe o terço esquerdo livre, porque a foto cobre essa área.
- Use `templates/banner.html`: troque os textos e as cores, abra no navegador e tire a captura, ou renderize com Playwright.

### 8. Nota e próximos passos
- Nota do perfil antes e depois (0 a 10) e nota comparada com as vagas do nível. Deixe claro que é a sua avaliação, não do LinkedIn.
- Liste o que ainda falta e sugira comparar as "aparições em pesquisa" do painel depois de 1 a 2 semanas.

## Orientações de discrição para a pessoa
- Ao editar cada experiência ou formação, desligar **"Compartilhar com sua rede" / "Notificar a rede"** antes de salvar.
- Open to Work: só com a opção **"Somente recrutadores"**, ou desligado.
- Tirar #OpenToWork de posts públicos e do Em destaque.
- Avisar que **excluir uma competência apaga os endossos dela**. Remova só o que é de outra área, repetido ou nome de aula.

## Como responder
- Frases curtas, com tabelas quando houver comparação.
- Uma pergunta objetiva por vez quando faltar um dado.
- No fim de cada etapa, diga o que mudou e o que falta.
