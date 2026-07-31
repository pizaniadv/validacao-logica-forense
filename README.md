---
tipo: readme
data: 2026-07-30
produzido-por: Raphael Sousa Pizani Silva (OAB/BA 32.472)
versao-core: 1.0
---

# Validação lógica forense

> Skill para assistentes de IA. Reconstrói o argumento em premissas e
> conclusão, testa se ela decorre, e nomeia a falácia quando há uma.

## Regime fundante — defesa, vedado uso próprio

Este catálogo existe para **reconhecer e refutar** o raciocínio viciado do
outro lado, do parecer contrário e da decisão recorrida.

**É vedado o uso próprio.** Conhecer os estratagemas para empregá-los viola a
boa-fé processual (CPC, arts. 5º e 77) e o dever de lealdade — e é ruim de
resultado: juiz experiente reconhece o truque, e a peça inteira perde crédito
junto com ele. Por isso toda análise termina com um **autoexame** do próprio
texto, em busca de falácia inadvertida.

## O que ela faz

**Passo 1 — reconstrói.** Reformula o argumento em premissas explícitas. É aqui
que aparece o achado mais valioso: **a premissa oculta**. Argumentos jurídicos
raramente enunciam a premissa maior, e explicitá-la costuma revelar que é ela —
não a conclusão — que precisaria ser provada.

**Passo 2 — classifica** o tipo de raciocínio (dedutivo, indutivo, abdutivo,
analógico, por autoridade), porque exigir de uma analogia o rigor de uma dedução
é erro tanto quanto aceitar uma indução como necessária.

**Passo 3 — testa** três coisas: a conclusão decorre? as premissas são
verdadeiras **e provadas nos autos**? os termos mantêm o mesmo sentido do começo
ao fim?

## Três catálogos de detecção

- **As treze falácias de Aristóteles** (*Refutações Sofísticas*), traduzidas
  para o que cada uma parece numa peça: equivocidade, anfibolia, composição,
  divisão, acento, forma de expressão · acidente, *secundum quid*, *ignoratio
  elenchi*, petição de princípio, falácia do consequente, falsa causa, pergunta
  múltipla.
- **Os estratagemas de Schopenhauer** — as manobras de quem quer vencer a
  discussão, não descobrir a verdade: ampliar a tese alheia (o espantalho, o
  mais frequente em contestação), mudar o objeto da disputa, autoridade sem
  pertinência, e o *ad personam*, que Schopenhauer põe como último recurso — e
  é exatamente esse o diagnóstico: quando o outro lado passa a atacar o
  advogado, ele ficou sem tese.
- **As falácias próprias do jurídico** (tema tratado, entre outros, por Manuel
  Atienza): autoridade aparente, deslocamento do ônus, legalismo formal,
  consequencialismo desamparado, precedente descontextualizado, interpretação
  que anula o dispositivo, silogismo com premissa maior inventada.

## Instalação

```bash
git clone https://github.com/pizaniadv/validacao-logica-forense.git \
  ~/.claude/skills/validacao-logica-forense
```

Skills seguem o padrão aberto [Agent Skills](https://agentskills.io).

## Como usar

`/validacao-logica-forense`, ou: "essa lógica fecha?", "tem falácia aqui?",
"valida o raciocínio", "o argumento dele é honesto?".

## Duas regras que evitam vexame

**Nomeie a falácia com precisão ou não a nomeie** — chamar de "petição de
princípio" o que é *ignoratio elenchi* dá ao adversário a chance de corrigir
você em vez de responder ao ponto. E **falácia não é sinônimo de conclusão
errada**: argumento viciado pode chegar à conclusão correta, que continua
precisando de argumento válido.

## A família

- [`critica-adversarial-juridica`](https://github.com/pizaniadv/critica-adversarial-juridica)
  — o ataque completo à tese; esta skill é o vetor lógico, aprofundado.
- [`antialucinacao-juridica`](https://github.com/pizaniadv/antialucinacao-juridica)
  — a premissa pode ser válida em forma e falsa em fato.
- [`inferencia-jurisprudencial-mij`](https://github.com/pizaniadv/inferencia-jurisprudencial-mij)
  — para a autoridade aparente e o precedente descontextualizado.

## Licença

Licenciamento duplo, ambos copyleft, ambos com **atribuição nominal
obrigatória**: **[AGPL-3.0](LICENSE)** para o componente executável e
**[CC BY-SA 4.0](LICENSE-DOCS)** para a obra textual.

Uso no seu escritório não gera obrigação nenhuma. **Distribuir** versão
modificada, ou **oferecê-la a terceiros como serviço**, exige abrir o código e
manter a atribuição. O [NOTICE](NOTICE) é parte da licença.

## Autor

**Raphael Sousa Pizani Silva** — OAB/BA 32.472
[github.com/pizaniadv](https://github.com/pizaniadv)
