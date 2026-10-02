# IMAGE-BRIEF — PDP Horse Jello®

Nada foi gerado por IA nesta rodada: as 5 fotos do carrossel **já existiam** na pasta
do produto (geradas com Magnific), e as provas sociais também.

| Arquivo | Origem |
|---|---|
| `00-logo.svg` / `00-logo-white.svg` | `Arquivos DEV/HorseJello-Logo.svg`. A variante branca troca o `#e83f2e` e o `#f1f2f2` por branco, para o header escuro |
| `00-bottle.webp` | `Arquivos DEV/HorseJello-Arquivos_DEV-Bottle.webp`, recortado no alfa — sticky |
| `02-gal-1.webp` | `img1.png` — frasco com o cavalo e a lua |
| `02-gal-2.webp` | **refeita 27/08** — flat-lay de cima, ardósia escura, gomas em arco |
| `02-gal-3.webp` | **refeita 27/08** — macro, terço superior do rótulo em foco, bokeh vermelho |
| `02-gal-4.webp` | **refeita 27/08** — homem ~50 anos, banheiro em meia-luz, segurando o pote |
| `02-gal-5.webp` | `Mockups/DTC/3+3-DTC-HorseJello.png` |
| `18-ugc-01…12.webp` | 12 das 17 selfies de `Provas Sociais`, 560×560 |
| `17-seal-90.webp`, `cc-visa.svg`, `cc-mastercard.svg` | herdados — genéricos |

As quatro cenas fotográficas foram cortadas no centro para 1:1; os mockups com alfa
foram centralizados sobre a faixa escura `#1E1E1E`.

## Geradas em 27/08 (Nano Banana 2)

`06-cycle-1…4.webp` — as quatro ilustrações do ciclo do tecido. As do VigorBoost são
corte de **veia**; aqui a tese é **tecido esponjoso**, então precisavam ser outras.
Tecido saudável → placas se formando → tecido rígido → **câmaras colapsadas** (refeita
em 27/08: antes era um símbolo de Marte em círculo tracejado, um placeholder que não
fechava a narrativa). A quarta foi gerada em modo edição sobre a terceira, para herdar
traço, paleta e fundo branco. Custo: 6 × US$ 0,08 = **US$ 0,48** (a terceira saiu
fotorrealista na primeira tentativa e foi refeita usando a segunda como referência).

## Rodada de 27/08 — carrossel e ingredientes

**Carrossel (3 novas).** O pedido era variar disposição, ângulo e lente, e ter um humano.
Todas geradas em **modo edição** com `Arquivos DEV/HorseJello-Arquivos_DEV-Bottle.webp`
como referência — é o que mantém o rótulo e a arte do cavalo reais em vez de inventados.
`--ar 1:1 --res 2K`, sementes 9101–9103. As três substituíram os upscales `magnific_*`.

**Ingredientes (4 novas).** `08-ing-1…4.webp`, 720×405, textura de topo em luz baixa:
colágeno em pó, gomos de laranja, casca de pinheiro marítimo, raiz de tongkat fatiada.
Cada uma leva um degradê preto na base, aplicado no build, para o nome do ingrediente
ficar legível por cima sem depender de sombra de texto pesada.

Custo da rodada: 7 × US$ 0,08 = **US$ 0,56**.

> As fotos de ingrediente são ilustrativas do insumo, não do lote usado na produção.

## Ainda falta

| Slot | Spec |
|---|---|
| Nada bloqueante | O depoimento do hero, os logos de imprensa, o trio da faixa promo e o blister do comparativo foram herdados da PDP do VigorBoost — são fotos de banco, ilustração genérica e logos de imprensa. Se o Horse Jello tiver os próprios, trocar. |

## Card de depoimento (§12)

`12-depo.webp` (1024x1024) e a arte que o Renan entregou pronta, com o texto ja
dentro. So foi convertida para webp. Vale em todas as larguras.

O texto vai inteiro no `alt`, que e o que leitor de tela e buscador leem. O
contraste dele nao passa pelo auditor da pagina, que nao enxerga dentro de
imagem.

> **Pendencia:** a arte diz *Trusted by 12,000+*. A pagina afirma *17,012+* em
> tres lugares (nota do topo, aba de reviews e "Based on 17,012+ reviews").
> Um dos dois numeros precisa mudar.

## Faixa promo (§9) — banner de ponta a ponta

`09-banner.webp` (2400x571, 21:5) e `09-banner-m.webp` (1000x435, recorte).

Cena gerada no Nano Banana 2 em modo edicao, com o frasco real como referencia.
Os frascos nao sao mais recorte por cima de um fundo: estao na cena, com sombra
de contato na ardosia molhada e reflexo. O terco esquerdo foi pedido vazio e
escuro de proposito — e ali que o texto corre.

No desktop a imagem E a faixa: ela define a altura (largura / 4.2) e o conteudo
fica sobreposto, limitado a 54% da largura para nao invadir os frascos. No
celular a cena entra recortada como bloco e o texto vem abaixo, no escuro da
secao.

A seta que ligava os frascos ao botao saiu junto: ela existia para costurar um
recorte ao layout, e agora os frascos fazem parte da cena.

Contraste do texto sobre o banner conferido por pixel em 1440/1100/960/390
(o auditor le `background-color` e nao a foto): pior caso 5.16.

## Faixa de confianca (§8)

Quatro icones fornecidos pelo Renan. Os de traco nao declaram cor nenhuma —
herdariam preto e sumiriam no escuro —, entao viram `symbol` com
`fill="currentColor"` e pegam o branco do CSS.

## Rodada de 27/08 — provas sociais, carrossel e avatar

**Provas sociais.** Cinco tiles trocados: `18-ugc-04/05/11` tinham o frasco com
perspectiva e luz que nao batiam com a mao — lia como colagem — e `06/07` eram
homens novos demais para o publico. As cinco novas sao homens de 55 a 67 anos,
geradas em modo edicao com o frasco real, em selfie de celular com flash e ruido
de sensor. As sete originais que ficaram nao foram tocadas.

**`02-gal-5`** deixa de ser o mockup 3+3 e passa a ser o frasco no criado-mudo ao
amanhecer, com relogio, oculos e copo d'agua. O carrossel ganha uma cena de
rotina que nao existia entre as outras quatro.

**`03-avatar-david`** refeito com um homem de ~59 anos.

Custo da rodada: 7 x US$ 0,08 = **US$ 0,56**.
