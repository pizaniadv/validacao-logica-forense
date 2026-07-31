---
name: validacao-logica-forense
description: >
  Valida a estrutura lógica de um argumento jurídico e identifica falácias
  formais e materiais. Reconstrói a inferência em premissas e conclusão a
  partir da prosa corrida da peça, classifica o tipo de raciocínio (dedutivo,
  indutivo, abdutivo, analógico, por autoridade), verifica se a conclusão
  decorre validamente, se as premissas estão provadas ou apenas assumidas, e
  gradua a gravidade do vício encontrado. Catálogo de detecção baseado nas
  falácias clássicas de Aristóteles, nos estratagemas de Schopenhauer e nas
  falácias recorrentes da argumentação jurídica. Opera sob regime de defesa:
  reconhece a falácia para REFUTAR a do adversário, e veda o uso próprio —
  expor o estratagema alheio é ofício; empregá-lo é má-fé. Disparar ao ver
  "essa lógica fecha", "tem falácia aqui", "valida o raciocínio", "a conclusão
  decorre disso", "isso é petição de princípio", "o argumento dele é honesto",
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

## 1. Passo 1 — Extrair o argumento da prosa

A peça não vem em premissas numeradas. Vem em parágrafos de subordinadas,
remissões e ênfase. O procedimento para extrair a estrutura:

1. **Delimite a unidade.** Um argumento pode ocupar um parágrafo ou três;
   feche a unidade onde a conclusão parcial é sacada.
2. **Ache a conclusão primeiro.** Ela vem marcada por "portanto", "logo",
   "assim", "razão pela qual", "impõe-se", "é de rigor" — ou é o próprio
   pedido. Reescreva-a como frase simples e afirmativa.
3. **Liste as razões oferecidas.** Marcadores: "porque", "uma vez que", "na
   medida em que", "nos termos do art. X", "conforme decidido". Cada razão
   vira uma premissa em frase própria. O que não sustenta a conclusão —
   adjetivo, ênfase, indignação — não é premissa; descarte.
4. **Resolva as remissões.** "Como demonstrado" e "conforme visto" apontam
   para outro trecho: vá até ele e traga a proposição, não a remissão. Se a
   remissão não encontra nada no texto, isso já é um achado.
5. **Formule a premissa oculta.** Com as premissas escritas, a conclusão
   quase nunca sai. A distância é preenchida por uma premissa que ninguém
   enunciou — em regra a premissa maior, a regra geral. Pergunte: *que regra
   tornaria essa passagem obrigatória?* Escreva-a por extenso, na forma mais
   forte que o argumento exige.
6. **Teste a premissa oculta isolada.** Ela é direito posto? É incontroversa?
   Ou é exatamente o que se discute? O argumento jurídico costuma cair aqui:
   a premissa que precisaria ser a mais defendida é a que ninguém escreveu.

Exemplo mínimo. Texto: *"Tendo a ré, como demonstrado, deixado de responder
às notificações, e considerando que a boa-fé objetiva rege as relações
contratuais, a rescisão por culpa da ré é medida que se impõe."*

```
Premissa 1: a ré não respondeu às notificações  ← fato; exige lastro nos autos
Premissa 2: a boa-fé objetiva rege os contratos ← verdadeira, mas genérica
Premissa oculta: não responder a notificação é inadimplemento
                 grave o bastante para rescisão por culpa
Conclusão:  a ré deu causa à rescisão
```

A premissa oculta é a que decide o caso — e não está escrita nem provada.

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
2. **As premissas são verdadeiras — e estão provadas?** Distinga: premissa
   **falsa** (regra que não existe, fato desmentido) é vício **material**;
   premissa possivelmente verdadeira mas **sem prova nos autos** é vício
   **de lastro**. São problemas diferentes, com correções diferentes
   (seção 4).
3. **Os termos mantêm o mesmo sentido do começo ao fim?** A palavra que muda
   de significado no meio do raciocínio é o vício mais comum e o mais difícil
   de ver.

## 4. Premissa sem prova — o vício de lastro

Argumento **inválido** e argumento **válido com premissa não provada** são
defeitos distintos. O primeiro não se salva com prova nenhuma; o segundo é
logicamente são e juridicamente inacabado. Não confunda os rótulos.

**No texto próprio**, a premissa fática sem lastro se trata em uma destas
três vias, nesta ordem de preferência:

1. **Provar** — apontar a folha dos autos que a sustenta; se não há, juntar o
   documento ou requerer a prova. A premissa deixa de ser assumida.
2. **Rebaixar** — converter a afirmação em alegação com pedido de prova, ou
   deslocar o argumento inteiro para posição subsidiária, de modo que a tese
   principal não dependa dela.
3. **Reordenar** — o argumento que não depende da premissa incerta assume a
   liderança da peça.

O que **não** fazer: mascarar a fragilidade com adjetivo ("resta evidente",
"é cristalino"). Ênfase no lugar de prova é confissão de que a prova falta.

**No texto adversário**, premissa sem lastro é ponto de **impugnação**, não
de refutação lógica: impugna-se especificadamente o fato e devolve-se o ônus
a quem alegou. Não a chame de falácia — se o adversário suprir a prova
depois, o rótulo lógico terá sido errado e a impugnação, desmoralizada.

## 5. Catálogo — falácias clássicas

As treze falácias que Aristóteles cataloga nas *Refutações Sofísticas*: seis
dependentes da linguagem, sete independentes dela. Ao lado, o que cada uma
parece na prática forense.

**Dependentes da linguagem:**

| Falácia | Como aparece na peça |
|---|---|
| **Equivocidade** | O mesmo termo com dois sentidos na mesma cadeia: "posse" ora como poder de fato juridicamente qualificado, ora como mera ocupação |
| **Anfibolia** | Frase de sintaxe ambígua explorada no sentido conveniente |
| **Composição** | O que vale de cada parte é atribuído ao todo: cada cláusula é lícita, logo o contrato é lícito |
| **Divisão** | O inverso: o contrato é abusivo, logo cada cláusula é abusiva |
| **Acento** | Na origem, a pronúncia que muda o sentido; na prática forense, o grifo ou a ênfase seletiva que altera o sentido do trecho transcrito |
| **Forma de expressão** | Semelhança gramatical tomada por identidade jurídica |

**Independentes da linguagem:**

| Falácia | Como aparece na peça |
|---|---|
| **Acidente** | Confundir o acidental com o essencial: aplicar a regra geral ao caso cuja circunstância particular a excepciona |
| ***Secundum quid*** | Tomar o que vale sob condição como se valesse absolutamente — e o inverso |
| ***Ignoratio elenchi*** | Provar muito bem outra coisa: o argumento demonstra tese que não era a controvertida |
| **Petição de princípio** | A premissa já contém a conclusão: "o contrato é nulo porque padece de nulidade" |
| **Falácia do consequente** | Afirmar o consequente para concluir o antecedente: "se houve fraude, houve prejuízo; houve prejuízo — logo houve fraude". O prejuízo pode ter outra causa |
| **Falsa causa** | Tomar por causa o que não é causa; na prática, a sequência temporal tomada por nexo causal — vício frequente em responsabilidade civil |
| **Pergunta múltipla** | Uma pergunta que embute duas, sem resposta única possível: clássico em depoimento |

## 6. Catálogo — estratagemas de disputa, com a refutação

Schopenhauer reuniu trinta e oito manobras de quem quer **vencer a
discussão**, e não descobrir a verdade. As que mais aparecem em processo,
cada uma com a frase que a neutraliza na peça — nomeando o movimento sem
adjetivar o adversário:

| Estratagema | O que escrever na peça |
|---|---|
| **Ampliar a tese alheia** além do que foi dito, para refutar a versão inchada (o espantalho) | "Sustentou-se X sob a circunstância Y; a resposta combate X irrestrito, tese que não foi posta." |
| **Homonímia** — refutar sentido diverso do empregado | "O termo T foi empregado na inicial no sentido A; a impugnação o refuta no sentido B, estranho à causa." |
| **Generalizar o particular** — transformar afirmação circunstanciada em regra absoluta, para derrubá-la | "A afirmação foi feita para a hipótese dos autos; convertida em regra geral, refuta-se o que não se disse." |
| **Atribuir consequências odiosas** que o argumento não sustenta | "De X não se segue Z; a consequência atribuída à tese não decorre dela, e o silogismo que a produziria não foi apresentado." |
| **Mudar o objeto da disputa** quando o terreno fica desfavorável | "A questão controvertida é X; a manifestação desloca o debate para Y, ponto sobre o qual não há controvérsia, deixando X sem resposta." |
| **Petição de princípio disfarçada** — pressupor como aceito o que se discute | "A premissa da qual parte a resposta é exatamente o que se discute; assumi-la é concluir sem demonstrar." |
| **Autoridade sem pertinência** — citar o respeitável fora de sua competência, ou já superado | "A fonte invocada não trata da questão controvertida [ou: está superada]; requer-se o cotejo entre o que ela decide e o que aqui se discute." |
| ***Ad personam*** — atacar a pessoa quando o argumento se esgotou; Schopenhauer o coloca como o último recurso, o expediente de quem perdeu | "O ataque à pessoa do patrono não responde ao argumento, que permanece sem impugnação específica." E anote o diagnóstico: quando o outro lado passa a atacar o advogado, ficou sem tese. |

Nomear o movimento assim é mais eficaz do que acusar má-fé — e não expõe
você ao estratagema que denuncia.

## 7. Catálogo — falácias recorrentes do jurídico

A argumentação jurídica tem vícios que não constam dos catálogos clássicos —
tema estudado, entre outros, por Manuel Atienza. A lista abaixo é compilação
forense, não catálogo de autor:

- **Autoridade aparente** — citar precedente que não incide, ou doutrina que
  diz outra coisa. A verificação exige ler a fonte e cotejar os fatos.
- **Deslocamento do ônus** — argumentar como se coubesse à outra parte provar
  o que cabe a você.
- **Legalismo formal** — invocar a letra contra a finalidade evidente da
  norma, quando o próprio sistema afasta a leitura literal.
- **Consequencialismo desamparado** — sustentar que a tese contrária traria
  caos social, sem qualquer demonstração.
- **Precedente descontextualizado** — transcrever ementa e omitir os fatos
  que a explicam.
- **Interpretação que anula o dispositivo** — leitura que torna a norma
  inútil ou sem efeito.
- **Silogismo com premissa maior inventada** — a regra enunciada como se
  fosse o direito posto simplesmente não existe naquele enunciado.

## 7-bis. Aplicar à decisão recorrida

O regime fundante inclui a decisão judicial, e é ali que a análise lógica mais
rende: vício de fundamentação não é retórica de recurso, é matéria de
impugnação. Rode os passos 1 a 3 sobre a decisão e procure quatro defeitos
específicos, que a peça de parte não tem:

- **Argumento não enfrentado.** A decisão deixou de enfrentar fundamento
  deduzido que, se acolhido, infirmaria a conclusão? Não basta que ela decida
  contra você: ela precisa enfrentar o que foi deduzido e é capaz de mudar o
  resultado (CPC, art. 489, §1º, IV). Liste o argumento, onde foi deduzido, e
  por que infirmaria a conclusão — os três elementos, ou a alegação fica vazia.
- **Premissa não submetida ao contraditório.** A decisão fundou-se em
  fundamento sobre o qual as partes não tiveram oportunidade de se manifestar,
  ainda que se trate de matéria apreciável de ofício? É a vedação à decisão
  surpresa (CPC, art. 10).
- **Conclusão que não decorre da própria fundamentação.** A decisão assenta
  premissas que levariam a resultado diverso do que ela decreta. Aponte a
  contradição interna entre fundamentação e dispositivo — e note que
  contradição e omissão são justamente o terreno dos embargos de declaração.
- **Premissa maior inventada pelo juízo.** A regra enunciada na decisão não
  corresponde ao que o dispositivo citado diz. Transcreva os dois lado a lado:
  o texto da norma e a leitura que a decisão lhe deu.

Duas cautelas. Primeira: identificar o vício lógico é o começo, não o fim — o
recurso ainda exige a via adequada, o prazo e o requisito de admissibilidade.
Segunda: **tom.** Nomeie o defeito da decisão sem qualificar o julgador. "A
decisão não enfrentou o argumento X" é impugnação; "o juízo ignorou
deliberadamente" é ofensa gratuita que prejudica o cliente e expõe você.

## 8. Dose — quando o vício justifica mexer na peça

Nem todo achado merece reescrita na véspera do prazo. Gradue:

**Grave — corrija mesmo na véspera.** O vício está na cadeia que sustenta o
pedido principal: premissa maior falsa ou inexistente, conclusão que não
decorre do fundamento central, petição de princípio na tese nuclear. Sem
esse elo, o pedido fica sem fundamento — e o adversário consegue nomear o
vício em uma linha.

**Médio — corrija se houver tempo; senão, corte.** O vício está em argumento
subsidiário ou de reforço. Cortar o trecho viciado é quase sempre mais
rápido e mais seguro do que reescrevê-lo: argumento fraco a menos é peça
mais forte.

**Tolerável — não mexa na véspera.** Imprecisão retórica sem função
inferencial: ênfase, redundância, generalização de passagem que nada
sustenta. Registre para a próxima peça e siga.

Dois testes decidem o grau: *o trecho viciado sustenta o pedido?* e *o
adversário consegue nomear o vício em uma linha?* Qualquer "sim" exclui o
grau tolerável. A decisão final sobre mexer ou não é do advogado — esta
análise informa, não decide.

## 9. Formato de saída

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
- Premissas: [verdadeiras e provadas | premissa X falsa | premissa X sem lastro nos autos]
- Termos unívocos: [sim | não — o termo Y muda de sentido entre a premissa e a conclusão]

## Falácias detectadas
- [nome] — onde: [trecho] — por quê: [explicação] — como refutar: [uma frase]

## Veredito
[VÁLIDO E LASTREADO | VÍCIO FORMAL | VÍCIO MATERIAL | VÍCIO DE LASTRO | FALÁCIA]
Gravidade: [grave | média | tolerável] — [por quê, em uma linha]

## Correção sugerida
[o que muda para o argumento se sustentar — ou a constatação de que não se sustenta]

## Autoexame (uso próprio inadvertido)
- Risco: [baixo | médio | alto] — [qual trecho nosso flerta com falácia, e como corrigir]
```

## 10. Regras

1. **Nomeie a falácia com precisão ou não a nomeie.** Chamar de "petição de
   princípio" o que é *ignoratio elenchi* entrega ao adversário a chance de
   corrigir você em vez de responder ao ponto. Na dúvida entre dois nomes,
   descreva o defeito sem batizá-lo.
2. **Falácia não é sinônimo de conclusão errada.** Argumento viciado pode
   chegar a conclusão correta — e a conclusão correta continua precisando de
   argumento válido.
3. **Cada vício tem sua correção:** o formal se corrige reformulando a
   inferência; o material, trocando a premissa; o de lastro, provando,
   rebaixando ou reordenando (seção 4).
4. **A premissa oculta é obrigatória** na reconstrução. Se você não a
   encontrou, provavelmente não terminou o trabalho.
5. **Refute o argumento, não a pessoa** — inclusive porque, feito o
   contrário, você acaba de praticar o estratagema que estava denunciando.

## 11. Skills irmãs (complemento opcional)

- **critica-adversarial-juridica** — o ataque completo à tese; esta skill é o
  vetor lógico, aprofundado.
- **antialucinacao-juridica** — a premissa pode ser válida em forma e falsa
  em fato; lá se confere o fato e a fonte.
- **inferencia-jurisprudencial-mij** — para a falácia de autoridade aparente
  e o precedente descontextualizado.
