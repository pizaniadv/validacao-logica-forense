---
tipo: readme
data: 2026-07-30
produzido-por: Raphael Sousa Pizani Silva (OAB/BA 32.472)
versao-core: 1.0
---

# Validação lógica forense

> Skill para assistentes de IA. Extrai o argumento da prosa corrida da peça,
> testa se a conclusão decorre, e nomeia a falácia quando há uma.

## Regime fundante — defesa, vedado uso próprio

O catálogo existe para **reconhecer e refutar** o raciocínio viciado do outro
lado, do parecer contrário e da decisão recorrida. **É vedado o uso próprio:**
conhecer os estratagemas para empregá-los viola a boa-fé processual e o dever de
lealdade — e é ruim de resultado, porque juiz experiente reconhece o truque e a
peça inteira perde crédito junto com ele.

Por isso toda análise termina com um **autoexame** do próprio texto, em busca de
falácia inadvertida.

## Passo 1 — extrair o argumento da prosa

A peça não vem em premissas numeradas. Vem em parágrafos de subordinadas,
remissões e ênfase. O procedimento tem seis passos: delimitar a unidade, achar a
conclusão primeiro (marcada por "portanto", "impõe-se", "é de rigor"), listar as
razões, resolver as remissões — e então o passo que decide:

**Formular a premissa oculta.** Com as premissas escritas, a conclusão quase
nunca sai. A distância é preenchida por uma premissa que ninguém enunciou, em
regra a premissa maior. E o argumento jurídico costuma cair exatamente aí: *a
premissa que precisaria ser a mais defendida é a que ninguém escreveu.*

```
Premissa 1: a ré não respondeu às notificações  ← fato; exige lastro nos autos
Premissa 2: a boa-fé objetiva rege os contratos ← verdadeira, mas genérica
Premissa oculta: não responder a notificação é inadimplemento
                 grave o bastante para rescisão por culpa
Conclusão:  a ré deu causa à rescisão
```

## Três vícios que não se confundem

- **formal** — a conclusão não decorre; não se salva com prova nenhuma;
- **material** — a premissa é falsa: regra que não existe, fato desmentido;
- **de lastro** — a premissa é possivelmente verdadeira, mas **sem prova nos
  autos**. É logicamente são e juridicamente inacabado.

O vício de lastro tem tratamento próprio: no texto próprio, provar, rebaixar a
alegação ou reordenar os argumentos — nunca mascarar com adjetivo ("resta
evidente" é confissão de que a prova falta). No texto do adversário, é ponto de
**impugnação**, não de refutação lógica: se ele suprir a prova depois, o rótulo
de falácia cai junto e a impugnação se desmoraliza.

## Três catálogos

**As treze de Aristóteles** (*Refutações Sofísticas*), seis dependentes da
linguagem e sete independentes, cada uma traduzida para o que parece numa peça —
da equivocidade à pergunta múltipla, passando por *ignoratio elenchi* (provar
muito bem outra coisa) e falsa causa (sequência temporal tomada por nexo).

**Os estratagemas de Schopenhauer**, convertidos em tabela de refutação: para
cada manobra, a frase que a neutraliza na peça, nomeando o movimento sem
adjetivar o adversário. Inclusive o *ad personam*, que ele coloca como último
recurso — e é esse o diagnóstico: quando o outro lado passa a atacar o advogado,
ficou sem tese.

**As falácias recorrentes do jurídico**: autoridade aparente, deslocamento do
ônus, legalismo formal, consequencialismo desamparado, precedente
descontextualizado, interpretação que anula o dispositivo, silogismo com premissa
maior inventada.

## Aplicar à decisão recorrida

É onde a análise lógica mais rende, porque vício de fundamentação não é retórica
de recurso — é matéria de impugnação. Quatro defeitos específicos: argumento
deduzido e não enfrentado; premissa não submetida ao contraditório; conclusão que
não decorre da própria fundamentação; e premissa maior inventada pelo juízo.

Com a cautela do tom: "a decisão não enfrentou o argumento X" é impugnação; "o
juízo ignorou deliberadamente" é ofensa gratuita que prejudica o cliente.

## Dose — quando o vício justifica mexer na peça

Nem todo achado merece reescrita na véspera. **Grave**: o vício está na cadeia
que sustenta o pedido — corrija mesmo na véspera. **Médio**: está em argumento
subsidiário — se não houver tempo, cortar é mais rápido e mais seguro que
reescrever. **Tolerável**: imprecisão retórica sem função inferencial — registre
e siga. Dois testes decidem: o trecho sustenta o pedido? o adversário nomeia o
vício em uma linha?

## Instalação

```bash
git clone https://github.com/pizaniadv/validacao-logica-forense.git \
  ~/.claude/skills/validacao-logica-forense
```

Skills seguem o padrão aberto [Agent Skills](https://agentskills.io).

## Como usar

`/validacao-logica-forense`, ou: "essa lógica fecha?" · "tem falácia aqui?" ·
"valida o raciocínio" · "o argumento dele é honesto?".

## Duas regras que evitam vexame

**Nomeie a falácia com precisão ou não a nomeie** — chamar de petição de
princípio o que é *ignoratio elenchi* dá ao adversário a chance de corrigir você
em vez de responder ao ponto; na dúvida, descreva o defeito sem batizá-lo. E
**falácia não é sinônimo de conclusão errada**: argumento viciado pode chegar à
conclusão correta, que continua precisando de argumento válido.

## Executa sozinha

Não depende de outra skill. As irmãs estendem:
[`critica-adversarial-juridica`](https://github.com/pizaniadv/critica-adversarial-juridica) ·
[`antialucinacao-juridica`](https://github.com/pizaniadv/antialucinacao-juridica) ·
[`inferencia-jurisprudencial-mij`](https://github.com/pizaniadv/inferencia-jurisprudencial-mij).

## Licença

Licenciamento duplo, ambos copyleft, ambos com **atribuição nominal
obrigatória**: **[AGPL-3.0](LICENSE)** e **[CC BY-SA 4.0](LICENSE-DOCS)**. Uso
próprio não gera obrigação; distribuir ou servir a terceiros exige abrir o
código e manter a atribuição. O [NOTICE](NOTICE) é parte da licença.

## Autor

**Raphael Sousa Pizani Silva** — OAB/BA 32.472
[github.com/pizaniadv](https://github.com/pizaniadv)

Histórico de versões no [CHANGELOG](CHANGELOG.md).
