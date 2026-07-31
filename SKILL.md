---
name: validacao-logica-forense
description: >
  Valida a estrutura lógica de um argumento jurídico e identifica falácias
  formais e materiais. Reconstrói a inferência em premissas e conclusão,
  classifica o tipo de raciocínio (dedutivo, indutivo, abdutivo, analógico, por
  autoridade), verifica se a conclusão decorre validamente e se as premissas
  estão provadas ou apenas assumidas. Catálogo de detecção baseado nas falácias
  clássicas de Aristóteles, nos estratagemas de Schopenhauer e nas falácias
  próprias da argumentação jurídica. Opera sob regime de defesa: reconhece a
  falácia para REFUTAR a do adversário, e veda o uso próprio — expor o
  estratagema alheio é ofício; empregá-lo é má-fé. Disparar ao ver "essa lógica
  fecha", "tem falácia aqui", "valida o raciocínio", "a conclusão decorre
  disso", "isso é petição de princípio", "o argumento dele é honesto",
  "revisa a fundamentação antes de eu fechar".
# --- proveniência ---
tipo: skill
data: 2026-07-30
produzido-por: Raphael Sousa Pizani Silva (OAB/BA 32.472)
versao-core: 1.0
---

# Validação lógica forense

## 0. Regime fundante — defesa, vedado uso próprio

Este catálogo existe para **reconhecer e refutar** o raciocínio viciado do
outro lado, do parecer contrário e da decisão recorrida.

**É vedado o uso próprio.** Conhecer os estratagemas para empregá-los é o
oposto do ofício: viola a boa-fé processual (CPC, arts. 5º e 77) e o dever de
lealdade do advogado. E é ruim de resultado — juiz experiente reconhece o
truque, e a peça inteira perde crédito junto com ele.

Toda análise produzida aqui inclui, por isso, uma seção final que examina o
**próprio texto do usuário** em busca de falácia inadvertida.

## 1. Passo 1 — Reconstruir a inferência

Antes de julgar, reformule o argumento na sua forma explícita. A maior parte
dos vícios aparece só nessa hora, porque a prosa jurídica esconde a estrutura.

```
Premissa 1: [...]
Premissa 2: [...]
(Premissa oculta: [...])   ← quase sempre é aqui que está o problema
Conclusão:  [...]
```

**A premissa oculta é o achado mais valioso.** Argumentos jurídicos raramente
enunciam a premissa maior; ela vai pressuposta. Explicitá-la costuma revelar
que é ela — e não a conclusão — que precisaria ser provada.

## 2. Passo 2 — Classificar o tipo de raciocínio

| Tipo | Forma | O que o valida | Vício típico |
|---|---|---|---|
| **Dedutivo** | Da regra ao caso (subsunção) | Validade formal + verdade das premissas | Premissa maior falsa; termo médio ambíguo |
| **Indutivo** | Dos casos à regra | Amostra suficiente e representativa | Generalização apressada |
| **Abdutivo** | Do efeito à melhor explicação | Ter afastado as explicações concorrentes | Tratar "possível" como "provado" |
| **Analógico** | De caso a caso semelhante | Semelhança relevante, não qualquer semelhança | Analogia com diferença material ignorada |
| **Por autoridade** | Da fonte à conclusão | Autoridade legítima, pertinente e vigente | Autoridade fora de sua competência; fonte superada |

Explicitar o tipo importa: exigir de um argumento analógico o rigor de uma
dedução é erro tanto quanto aceitar uma indução como se fosse necessária.

## 3. Passo 3 — Testar

Três perguntas, nessa ordem:

1. **A conclusão decorre?** Assumidas as premissas como verdadeiras, a
   conclusão é forçosa (dedução) ou razoavelmente sustentada (demais tipos)?
   Se não, o vício é **formal**.
2. **As premissas são verdadeiras — e estão provadas?** Premissa juridicamente
   correta, mas fática não provada nos autos, derruba o argumento tanto quanto
   uma premissa falsa. Se falha aqui, o vício é **material**.
3. **Os termos mantêm o mesmo sentido do começo ao fim?** A palavra que muda de
   significado no meio do raciocínio é o vício mais comum e o mais difícil de
   ver.

## 4. Catálogo — falácias clássicas

As treze falácias que Aristóteles cataloga nas *Refutações Sofísticas*, com o
que cada uma parece na prática forense.

**Dependentes da linguagem:**

| Falácia | Como aparece na peça |
|---|---|
| **Equivocidade** | O mesmo termo com dois sentidos: "posse" no sentido civil e no sentido possessório coloquial |
| **Anfibolia** | Frase de sintaxe ambígua explorada no sentido conveniente |
| **Composição** | O que vale de cada parte é atribuído ao todo: cada cláusula é lícita, logo o contrato é lícito |
| **Divisão** | O inverso: o contrato é abusivo, logo cada cláusula é abusiva |
| **Acento** | Ênfase ou grifo que altera o sentido do trecho transcrito |
| **Forma de expressão** | Semelhança gramatical tomada por identidade jurídica |

**Independentes da linguagem:**

| Falácia | Como aparece na peça |
|---|---|
| **Acidente** | Aplicar a regra geral a caso que tem circunstância que a excepciona |
| ***Secundum quid*** | Tomar o que vale sob condição como se valesse absolutamente — e o inverso |
| ***Ignoratio elenchi*** | Provar muito bem outra coisa: o argumento demonstra tese que não era a controvertida |
| **Petição de princípio** | A premissa já contém a conclusão: "o contrato é nulo porque padece de nulidade" |
| **Falácia do consequente** | Inverter a condicional: se há dano há culpa; há dano, logo há culpa |
| **Falsa causa** | Tomar sequência temporal por nexo causal — vício frequentíssimo em responsabilidade civil |
| **Pergunta múltipla** | Uma pergunta que embute duas, sem resposta única possível: clássico em depoimento |

## 5. Catálogo — estratagemas de disputa

Schopenhauer reuniu trinta e oito manobras de quem quer **vencer a discussão**,
e não descobrir a verdade. As que mais aparecem em processo:

- **Ampliar a tese alheia** além do que foi dito, para refutar a versão inchada
  — o espantalho. É o estratagema mais frequente em contestação.
- **Homonímia**: refutar sentido diverso do empregado pela outra parte.
- **Generalizar o particular**: transformar afirmação circunstanciada em regra
  absoluta, para então derrubá-la.
- **Escolher consequências odiosas**: atribuir ao argumento alheio conclusões
  que ele não sustenta.
- **Mudar o objeto da disputa** quando o terreno fica desfavorável.
- **Petição de princípio disfarçada**: pressupor como aceito o que se
  discute.
- **Argumento de autoridade sem pertinência**: citar o respeitável fora de sua
  competência, ou já superado.
- ***Ad personam***: atacar a pessoa quando o argumento se esgotou. Schopenhauer
  o coloca como o último recurso — e é exatamente esse o diagnóstico: quando o
  outro lado passa a atacar o advogado, ele ficou sem tese.

**Como refutar, em geral:** nomeie o movimento sem adjetivar o adversário.
"A contestação amplia a tese: sustentamos X em determinada circunstância, e a
resposta combate Y, que não foi afirmado." Isso é mais eficaz do que acusar
alguém de má-fé, e não expõe você.

## 6. Catálogo — falácias próprias do jurídico

A argumentação jurídica tem vícios que não constam dos catálogos clássicos —
tema tratado, entre outros, por Manuel Atienza:

- **Autoridade aparente** — citar precedente que não incide, ou doutrina que
  diz outra coisa. Cruze com a skill de inferência jurisprudencial.
- **Deslocamento do ônus** — argumentar como se coubesse à outra parte provar
  o que cabe a você.
- **Legalismo formal** — invocar a letra contra a finalidade evidente da norma,
  quando o próprio sistema afasta a leitura literal.
- **Consequencialismo desamparado** — sustentar que a tese contrária traria
  caos social, sem qualquer demonstração.
- **Precedente descontextualizado** — transcrever ementa e omitir os fatos que
  a explicam.
- **Interpretação que anula o dispositivo** — leitura que torna a norma inútil
  ou sem efeito.
- **Silogismo com premissa maior inventada** — a regra enunciada como se fosse
  o direito posto simplesmente não existe naquele enunciado.

## 7. Formato de saída

```markdown
## Trecho analisado
[transcrição ou referência]

## Reconstrução
Premissa 1: [...]
Premissa 2: [...]
Premissa oculta: [...]
Conclusão: [...]

## Tipo de raciocínio
[dedutivo | indutivo | abdutivo | analógico | por autoridade]

## Testes
- Conclusão decorre: [sim | não] — [por quê]
- Premissas verdadeiras e provadas: [sim | não | premissa X sem lastro nos autos]
- Termos unívocos: [sim | não — o termo Y muda de sentido entre a premissa e a conclusão]

## Falácias detectadas
- [nome] — onde: [trecho] — por quê: [explicação] — como refutar: [uma frase]

## Veredito
[VÁLIDO | VÍCIO FORMAL | VÍCIO MATERIAL | FALÁCIA]

## Correção sugerida
[o que muda para o argumento se sustentar — ou a constatação de que não se sustenta]

## Autoexame (uso próprio inadvertido)
- Risco: [baixo | médio | alto] — [qual trecho nosso flerta com falácia, e como corrigir]
```

## 8. Regras

1. **Nomeie a falácia com precisão ou não a nomeie.** Chamar de "petição de
   princípio" o que é *ignoratio elenchi* entrega ao adversário a chance de
   corrigir você em vez de responder ao ponto.
2. **Falácia não é sinônimo de conclusão errada.** Argumento viciado pode
   chegar a conclusão correta — e a conclusão correta continua precisando de
   argumento válido.
3. **Vício formal e vício material se corrigem de modo diferente:** o formal se
   corrige reformulando a inferência; o material, provando ou trocando a
   premissa.
4. **A premissa oculta é obrigatória** na reconstrução. Se você não a
   encontrou, provavelmente não terminou o trabalho.
5. **Refute o argumento, não a pessoa** — inclusive porque, feito o contrário,
   você acaba de praticar o estratagema que estava denunciando.

## 9. Skills irmãs

- **critica-adversarial-juridica** — o ataque completo à tese; esta skill é o
  vetor lógico, aprofundado.
- **antialucinacao-juridica** — a premissa pode ser válida em forma e falsa em
  fato; lá se confere o fato e a fonte.
- **inferencia-jurisprudencial-mij** — para a falácia de autoridade aparente e
  o precedente descontextualizado.
