[README.md](https://github.com/user-attachments/files/30965589/README.md)
# 🎣 Virtual Fisher — Wiki Completa do Jogo

Bem-vindo à cabana do pescador! Este documento é a wiki completa do bot de pesca: todos os comandos, mecânicas, itens, raridades e sistemas do jogo, explicados do início ao fim.

---

## 📑 Índice

1. [Como começar](#-como-começar)
2. [Comandos](#-comandos)
3. [Pescando: como funciona](#-pescando-como-funciona)
4. [Biomas](#-biomas)
5. [Raridades de peixes](#-raridades-de-peixes)
6. [Peixes Shiny ✨ e Sparkling 🌈](#-peixes-shiny--e-sparkling-)
7. [Evento Global: Criaturas Extintas 🦴](#-evento-global-criaturas-extintas-)
8. [Varas de pescar](#-varas-de-pescar)
9. [Iscas](#-iscas)
10. [Barcos](#-barcos)
11. [Pets](#-pets)
12. [Relíquias Encantadas e Encantamento de Vara](#-relíquias-encantadas-e-encantamento-de-vara)
13. [Baús de Loot](#-baús-de-loot)
14. [Upgrades Permanentes](#-upgrades-permanentes)
15. [Boosts (consumíveis)](#-boosts-consumíveis)
16. [Gemas 💎 e Elixires](#-gemas--e-elixires)
17. [Presente Diário e Sequência (Streak)](#-presente-diário-e-sequência-streak)
18. [Ligas e Títulos](#-ligas-e-títulos)
19. [Nível, XP e Prestígio](#-nível-xp-e-prestígio)
20. [Fischpédia](#-fischpédia)
21. [Configuração para administradores](#-configuração-para-administradores)
22. [Glossário rápido](#-glossário-rápido)

---

## 🚀 Como começar

1. Digite `/pescar` para abrir a **Cabana do Pescador** — o menu principal do jogo. A resposta é **privada** (só você vê), então sinta-se livre para navegar à vontade.
2. Dentro da cabana, use os botões para pescar, ver seu inventário, acessar a loja, trocar de bioma, ver seu perfil e muito mais.
3. Todo peixe que você pesca vai para o seu **inventário**. Venda-os para ganhar moedas 🪙 e comprar equipamentos melhores.
4. Suba de nível pescando para desbloquear **biomas** mais avançados, com peixes mais raros e valiosos.

---

## 🕹️ Comandos

| Comando | Quem pode usar | O que faz |
|---|---|---|
| `/pescar` | Todos | Abre a Cabana do Pescador (menu principal, resposta privada). |
| `/perfil [jogador]` | Todos | Mostra seu perfil (ou o de outro jogador) publicamente no canal — nível, liga, vara, pets, prestígio, etc. |
| `/fischpedia` | Todos | Abre sua Fischpédia — coleção estilo Pokédex de todos os peixes já capturados. |
| `/definir-titulo` | Administradores | Concede um título especial e customizado a um jogador. |
| `/remover-titulo` | Administradores | Remove o título especial customizado de um jogador. |
| `/definir-icone-titulo` | Administradores | Troca só o ícone (emoji) do título especial que o jogador já tem. |
| `/definir-canal-eventos` | Administradores | Define o canal onde o bot anuncia capturas raras e Eventos Globais. |

---

## 🎣 Pescando: como funciona

Cada vez que você clica em **"Pescar"** na Cabana:

1. O bot calcula **quantos peixes** você fisga nesta rodada, com base na sua vara equipada (`minCatch`–`maxCatch`) e no seu barco (peixes extras fixos).
2. Para cada peixe, o jogo **sorteia** qual peixe será, entre os disponíveis no seu bioma atual — peixes mais raros têm peso (chance) muito menor.
3. Peixes difíceis para a sua vara atual podem **fugir da linha** (veja [Chance de fuga](#chance-de-fuga)).
4. Cada peixe capturado tem uma pequena chance de sair como **Shiny ✨** ou **Sparkling 🌈** (veja a seção dedicada).
5. Você ganha **XP** pelos peixes pescados, pode subir de nível, e tem chances (independentes entre si) de:
   - Ganhar um **Pet** raro (gacha);
   - Ganhar uma **Relíquia Encantada**;
   - Ganhar um **Baú de Loot** fechado;
   - Encontrar **Gemas 💎** soltas na água;
   - Ativar um **Boost Global cosmético** de +20% XP nesta pescaria.
6. Há um **cooldown** de 3.6 segundos entre pescarias (reduzível com o upgrade "Reflexos Rápidos").

### Chance de fuga

Cada peixe tem uma **dificuldade** ligada à sua raridade, e cada vara tem um **tier**. Se a dificuldade do peixe for maior que o tier da sua vara, ele tem chance de escapar da linha (até no máximo 75% de chance). Iscas, encantamentos de vara e alguns boosts reduzem essa chance de fuga.

| Fator | Efeito na fuga |
|---|---|
| Vara de tier mais alto | Reduz a chance de fuga contra peixes difíceis |
| Isca ativa (`escapeReduction`) | Reduz a chance de fuga |
| Encantamento de vara | Reduz a chance de fuga (até -60% no nível máximo) |
| Boost "Escudo da Linha" | -15% de chance de fuga |
| Elixires de Gemas | -20% ou -30% de chance de fuga |

---

## 🗺️ Biomas

Você pesca sempre em um bioma por vez — escolha o seu na tela **"Biomas"** do menu principal. Cada bioma desbloqueia com um nível mínimo e tem peixes exclusivos, cada vez mais raros e valiosos.

| Bioma | Nível mínimo | Dificuldade | Descrição |
|---|---|---|---|
| 🏞️ Lago Tranquilo | 1 | 1 | Águas calmas, ideal para começar a pescar. |
| 🌊 Rio Correnteza | 6 | 2 | Correnteza forte esconde peixes maiores. |
| 🐊 Pântano Sombrio | 12 | 3 | Água turva e criaturas estranhas. |
| 🏖️ Costa Rochosa | 20 | 4 | O encontro do rio com o mar. |
| 🪸 Recife de Coral | 30 | 5 | Águas coloridas cheias de vida. |
| ⛵ Mar Aberto | 45 | 6 | Longe da costa, peixes grandes rondam. |
| 🕳️ Fossa Abissal | 65 | 7 | Escuridão total nas profundezas. |
| ❄️ Geleira Polar | 90 | 8 | Águas geladas e criaturas raras. |
| 🌋 Rio de Lava | 130 | 9 | Pescaria lendária em magma vivo. |
| ☁️ Ilhas Flutuantes | 180 | 10 | O bioma mítico no topo do mundo. |

> Cada bioma tem peixes de todas as raridades, do **Comum** ao **Divino** — quanto mais avançado o bioma, mais valiosos são os peixes em cada raridade. Além disso, **todos** os biomas têm um peixe **Secreto 🌀**, um **Exótico 💠** e um **Divino ✨** próprios.

---

## 🌟 Raridades de peixes

Da mais comum para a mais rara:

| # | Raridade | Ícone | Cor | Onde aparece |
|---|---|---|---|---|
| 1 | Lixo | 🗑️ | Cinza | Qualquer bioma (itens sem valor, tipo bota velha) |
| 2 | Comum | ⚪ | Azul claro | Todos os biomas |
| 3 | Incomum | 🟢 | Verde | Todos os biomas |
| 4 | Raro | 🔵 | Azul | Todos os biomas |
| 5 | Raríssimo | 🟦 | Turquesa | Todos os biomas |
| 6 | Épico | 🟣 | Roxo | Todos os biomas |
| 7 | Lendário | 🟡 | Amarelo | Todos os biomas |
| 8 | Mítico | 🔴 | Vermelho | Todos os biomas |
| 9 | **Secreto** | 🌀 | Roxo escuro | Todos os biomas (1 peixe único por bioma) |
| 10 | Ancestral | 🌌 | Azul-marinho | Todos os biomas |
| 11 | Exótico | 💠 | Ciano | Todos os biomas (1 peixe único por bioma) |
| 12 | Divino | ✨ | Branco | Todos os biomas (1 peixe único por bioma) |
| 13 | **Extinto** | 🦴 | Preto-azulado | **Só durante o Evento Global** (não pertence a nenhum bioma específico) |

> 🔔 **Anúncio automático:** sempre que alguém pescar algo de raridade **Secreto pra cima** (Secreto, Ancestral, Exótico, Divino ou Extinto), o bot anuncia automaticamente no canal configurado por um administrador (veja [Configuração para administradores](#-configuração-para-administradores)).

---

## ✨ Peixes Shiny ✨ e Sparkling 🌈

Além da raridade normal, **qualquer peixe pescado** — de um Lambari comum até um Kraken Extinto — pode sair como uma variante especial:

| Variante | Emoji | Chance aproximada | Efeito |
|---|---|---|---|
| **Shiny** | ✨ | ~1 em 150 | Dobra (**x2**) o valor de venda **e** o XP do peixe |
| **Sparkling** | 🌈 | ~1 em 1.500 | Dobra (**x2**) o valor de venda **e** o XP do peixe |

- A variante é sorteada **de forma independente** para cada peixe fisgado — pode acontecer com um peixe Comum ou com um Divino, tanto faz.
- Peixes Shiny/Sparkling aparecem destacados no seu inventário e na tela de resultado da pescaria.
- Assim como as capturas raras, **qualquer peixe Shiny ou Sparkling é anunciado automaticamente** no canal configurado pelos administradores.
- Vender um peixe Shiny/Sparkling paga o dobro do preço normal dele.

---

## 🦴 Evento Global: Criaturas Extintas

Periodicamente, um **Evento Global** pode começar no servidor — desde que um administrador tenha configurado um canal com `/definir-canal-eventos`.

### Como funciona

- A cada **5 minutos**, o bot sorteia (12% de chance) se um novo evento começa no servidor.
- Quando o evento começa, o bot **anuncia no canal configurado** e o evento fica ativo por **10 minutos**.
- **Enquanto o evento estiver ativo**, toda pescaria de todo mundo no servidor — em **qualquer bioma** — tem uma chance extra (~12% por peixe fisgado) de vir uma **Criatura Extinta** em vez do peixe normal daquele bioma.
- Ao fim dos 10 minutos, o bot anuncia o encerramento do evento no mesmo canal.

### Criaturas Extintas disponíveis

| Peixe | Emoji |
|---|---|
| Megalodon | 🦈 |
| Lula Gigante | 🦑 |
| Nessie | 🐲 |
| Titanoboa | 🐍 |
| Leviatã dos Tempos Perdidos | 🐋 |
| Kraken | 🐙 |
| Dragão Marinho Pré-Histórico | 🐉 |

Essas criaturas têm os maiores valores de venda e XP do jogo — vale a pena ficar de olho nos anúncios do canal de eventos!

---

## 🎣 Varas de pescar

Cada vara define quantos peixes você pesca por rodada (`minCatch`–`maxCatch`), o bônus de sorte para peixes raros (`rareBoost`), o **tier** (usado contra a chance de fuga) e uma **habilidade exclusiva** que pode disparar a cada pescaria.

| Vara | Preço | Tier | Peixes/pescaria | Bônus de sorte | Habilidade |
|---|---|---|---|---|---|
| 🎣 Vara Básica | Grátis | 0 | 1–2 | x1.0 | Nenhuma |
| 🎋 Vara de Bambu | 🪙 350 | 1 | 1–3 | x1.15 | ⚡ Fisgada Crítica — 5% de chance de dobrar o XP da pescaria |
| 🎣 Vara de Ferro | 🪙 1.200 | 2 | 2–4 | x1.35 | 🍀 Instinto Apurado — 8% de chance de +60% sorte nesta pescaria |
| 🛠️ Vara Reforçada | 🪙 3.200 | 3 | 2–4 | x1.55 | 👯 Linha Dupla — 8% de chance de duplicar toda a captura |
| ✨ Vara Dourada | 🪙 8.500 | 4 | 3–5 | x1.8 | ⚡ Toque de Midas — 10% de chance de x2.5 XP |
| ⚙️ Vara de Carbono | 🪙 20.000 | 5 | 3–6 | x2.1 | 🎣 Fisgada Múltipla — 15% de chance de +2 peixes extras |
| 💎 Vara de Diamante | 🪙 55.000 | 6 | 4–7 | x2.5 | 👯 Reflexo Cristalino — 15% de chance de duplicar a captura |
| 🔮 Vara Mítica | 🪙 140.000 | 7 | 5–8 | x3.0 | 🍀 Chamado Abissal — 18% de chance de +120% sorte |
| 🌌 Vara Ancestral | 🪙 350.000 | 8 | 6–9 | x3.6 | ⚡ Bênção dos Mares Antigos — 20% de chance de x3.5 XP |
| 🔷 Vara de Mítrilo | 🪙 750.000 | 9 | 6–9 | x4.2 | 🎣 Fisgada Élfica — 22% de chance de +3 peixes extras |
| 🔺 Vara de Adamantium | 🪙 1.600.000 | 10 | 7–10 | x5.0 | 👯 Fúria de Adamantium — 20% de chance de duplicar a captura |
| 🌠 Vara Celestial | 🪙 3.500.000 | 11 | 8–12 | x6.0 | 🍀 Bênção Celestial — 25% de chance de +200% sorte |
| 🕳️ Vara do Mestre do Vazio | 🪙 8.000.000 | 12 | 10–15 | x7.5 | ⚡ Colapso do Vazio — 30% de chance de x5 XP |

> Comprar uma vara é **permanente** — depois de comprada, você pode trocar de volta para ela a qualquer momento sem custo. O botão fica verde ("Equipada"/"Selecionar") para varas já suas.

---

## 🪱 Iscas

Iscas são **compradas em quantidade** (não em "usos"). Você escolhe uma isca **selecionada**, que é consumida 1 unidade por pescaria enquanto houver estoque, aplicando seus bônus.

| Isca | Preço/unidade | Multiplicador de XP | Bônus de sorte | Redução de fuga |
|---|---|---|---|---|
| 🪱 Minhoca | 🪙 10 | x1.2 | x1.1 | -2% |
| 🦐 Isca de Camarão | 🪙 25 | x1.4 | x1.3 | -4% |
| 🦑 Isca de Lula | 🪙 60 | x1.6 | x1.5 | -7% |
| 🌟 Isca Dourada | 🪙 150 | x2.0 | x1.8 | -11% |
| 💎 Isca de Cristal | 🪙 350 | x2.5 | x2.3 | -16% |
| 🌑 Isca Abissal | 🪙 800 | x3.2 | x3.0 | -24% |
| 🕳️ Isca do Vazio | 🪙 1.800 | x4.2 | x4.0 | -35% |

---

## 🚤 Barcos

Barcos concedem **peixes extras garantidos** por pescaria, além do que a vara já dá. São comprados uma única vez.

| Barco | Preço | Peixes extras |
|---|---|---|
| 🛶 Canoa de Pesca | 🪙 2.000 | +1 |
| 🚣 Barco a Remo | 🪙 7.000 | +2 |
| 🚤 Lancha Motorizada | 🪙 22.000 | +3 |
| 🛥️ Iate de Luxo | 🪙 60.000 | +4 |
| 🚢 Navio Baleeiro | 🪙 160.000 | +6 |
| ⚓ Nau Almirante | 🪙 400.000 | +8 |

---

## 🐾 Pets

Pets **não são comprados** — são obtidos por pura sorte (gacha) a cada pescaria, com chance base de **1 em 10.000**. Quando o gacha acerta, a raridade do pet é sorteada e, dentro dela, um pet específico. O pet de maior raridade entre os seus é **automaticamente equipado**.

| Raridade | Peso (chance relativa) |
|---|---|
| Comum | 50% |
| Raro | 28% |
| Épico | 15% |
| Lendário | 5.5% |
| Mítico | 1.3% |
| Ancestral | 0.2% |

| Pet | Raridade | Bônus |
|---|---|---|
| 🐱 Gato Pescador | Comum | +3% XP, +2% moedas |
| 🦆 Pato Sortudo | Comum | +3% XP, +2% sorte |
| 🦦 Lontra Curiosa | Raro | +8% XP, +5% moedas |
| 🕊️ Gaivota Guia | Raro | +8% XP, +5% sorte |
| 🦭 Foca Amiga | Épico | +15% XP, +10% moedas |
| 🐬 Golfinho Veloz | Épico | +15% XP, +10% sorte |
| 🐲 Dragãozinho | Lendário | +25% XP, +18% moedas |
| 🦅 Grifo Celeste | Lendário | +25% XP, +18% sorte |
| 🔥 Fênix Marinha | Mítico | +40% XP, +30% moedas, +10% sorte |
| 🐙 Kraken Filhote | Mítico | +40% XP, +30% sorte, +10% moedas |
| ✨ Espírito Guardião | Ancestral | +70% XP, +50% moedas, +25% sorte |
| 🌌 Leviatã Ancestral | Ancestral | +70% XP, +50% sorte, +25% moedas |

Todos os pets obtidos ficam guardados na sua coleção — você pode ter vários, mesmo repetidos.

---

## 🔮 Relíquias Encantadas e Encantamento de Vara

- **Relíquias Encantadas** 🔮 são um drop raríssimo (chance base de **1 em 4.000** por pescaria).
- Use-as (junto com moedas) na tela **Encantamentos** para subir o nível de encantamento da vara **atualmente equipada**.
- O encantamento é salvo **por vara** — trocar de vara não zera o progresso da vara antiga.
- Nível máximo de encantamento: **15**.

Por nível de encantamento, a vara equipada ganha:

| Bônus | Por nível |
|---|---|
| Chance de peixes raros | +3% |
| XP ganho | +2% |
| Redução de chance de fuga | -1.5% (até -60% no nível máximo) |

O custo em relíquias e moedas cresce a cada nível.

---

## 📦 Baús de Loot

Baús caem **fechados** no seu inventário enquanto você pesca (chance base de ~1 em 12 por pescaria) — abra-os manualmente na tela **Baús**.

| Baú | Peso do sorteio | Moedas | Peixes | Raridades dos peixes | Chance de item bônus |
|---|---|---|---|---|---|
| 📦 Comum | 60% | 🪙 30–90 | 1–2 | Comum, Incomum | 12% |
| 🎁 Raro | 25% | 🪙 150–450 | 1–3 | Incomum, Raro | 25% |
| 💜 Épico | 11.5% | 🪙 600–1.500 | 2–3 | Raro, Raríssimo | 40% |
| 🏆 Lendário | 3.2% | 🪙 2.000–5.000 | 2–4 | Raríssimo, Épico | 60% |
| 🌌 Mítico | 0.3% | 🪙 8.000–20.000 | 3–5 | Épico, Lendário, Mítico | 85% |

Os itens bônus incluem iscas em quantidade, usos de boosts, Relíquias Encantadas e até Gemas — variando conforme o baú.

---

## 📈 Upgrades Permanentes

Comprados com moedas na loja, os upgrades são **permanentes** e podem ser comprados várias vezes até o nível máximo (o custo cresce a cada nível).

| Upgrade | Efeito por nível | Nível máximo |
|---|---|---|
| 🍀 Sorte do Pescador | +4% de chance de peixes raros | 20 |
| ⚡ Reflexos Rápidos | -0.25s no cooldown entre pescarias | 10 |

---

## 🧪 Boosts (consumíveis)

Boosts são comprados com moedas (ou obtidos em baús) e têm um número fixo de **usos**. Vários boosts diferentes podem estar ativos ao mesmo tempo — os efeitos se combinam.

| Boost | Preço | Usos | Efeito |
|---|---|---|---|
| 💹 Impulso de Vendas | 🪙 800 | 5 | +50% no valor de venda |
| 🧪 Poção da Sorte | 🪙 900 | 5 | +50% na chance de peixes raros |
| 📘 Elixir de Experiência | 🪙 1.000 | 6 | +60% de XP |
| 🕸️ Rede Reforçada | 🪙 1.100 | 6 | +2 peixes extras por pescaria |
| 🛡️ Escudo da Linha | 🪙 950 | 6 | -15% de chance de fuga |
| 🌟 Super Impulso do Pescador | 🪙 3.800 | 5 | Combo: +30% XP, +30% sorte, +30% venda, +1 peixe extra, -10% fuga |

---

## 💎 Gemas 💎 e Elixires

Gemas são uma **moeda especial**, separada das moedas normais. Você as obtém principalmente pelo Presente Diário, por uma chance mínima a cada pescaria (1 em 5.000) e em baús Lendários/Míticos.

Use Gemas na **Loja de Gemas** para ativar Elixires — diferente dos boosts normais, eles duram um **tempo real fixo** (comprar de novo enquanto já ativo **estende** a duração):

| Elixir | Preço | Duração | Efeito |
|---|---|---|---|
| 🔷 Elixir de Mítrilo | 💎 15 | 5 minutos | +100% XP, +80% sorte, +50% venda, +2 peixes extras, -20% fuga |
| 🔺 Elixir de Adamantium | 💎 40 | 20 minutos | +200% XP, +150% sorte, +100% venda, +3 peixes extras, -30% fuga |

---

## 🎁 Presente Diário e Sequência (Streak)

### Presente Diário

- Resgate uma vez por dia no menu principal — reseta à meia-noite (UTC).
- Base: **🪙 150 moedas** + **💎 2 Gemas**, crescendo **+25 moedas por dia de sequência** (até o dia 30).
- A cada **5 dias de sequência**, ganha **+5 Gemas extras**.
- Pular um dia inteiro reinicia a sequência.

### Sequência de Pescarias (Streak de XP)

- Pescar em dias consecutivos aumenta um multiplicador de XP **permanente**: **+1% de XP por dia**, até **+30%** no dia 30.
- Pular um dia sem pescar reinicia a sequência.

---

## 🏅 Ligas e Títulos

### Ligas (cosméticas, baseadas em nível)

| Liga | Nível mínimo |
|---|---|
| 🥉 Bronze | 1 |
| 🥈 Prata | 30 |
| 🥇 Ouro | 80 |
| 💠 Platina | 160 |
| 💎 Diamante | 280 |
| 👑 Mestre Pescador | 420 |

### Títulos da Loja da Liga

Cada título exige que você já tenha alcançado a liga correspondente.

| Título | Preço | Liga exigida |
|---|---|---|
| 🥉 Iniciante das Águas | Grátis | Bronze |
| 🥈 Pescador Persistente | 🪙 1.500 | Prata |
| 🥇 Mestre da Linha | 🪙 6.000 | Ouro |
| 💠 Lenda de Platina | 🪙 18.000 | Platina |
| 💎 Caçador Abissal | 🪙 45.000 | Diamante |
| 👑 Mestre Supremo dos Mares | 🪙 120.000 | Mestre Pescador |

### Títulos Especiais (concedidos por ADM)

Administradores podem usar `/definir-titulo` para dar um título **customizado** (texto + emoji) a qualquer jogador, independente da Loja da Liga — ótimo para donos de servidor, moderadores, etc. Esse título tem prioridade de exibição sobre o título comprado.

---

## 🆙 Nível, XP e Prestígio

- **Nível máximo do jogo:** 500.
- Cada nível exige progressivamente mais XP para subir.
- Subir de nível dá uma **recompensa em moedas**.

### Prestígio ⭐

Ao alcançar **nível 100** e ter pelo menos **🪙 50.000 moedas**, você pode **Prestigiar**:

- **Reseta:** nível, XP, moedas, vara, barco, bioma, upgrades permanentes, encantamentos de vara e boosts ativos.
- **Mantém:** pets, relíquias, baús guardados, Fischpédia e títulos.
- **Ganha:** +1 nível de Prestígio **permanente**, concedendo bônus passivos para sempre:
  - +5% de XP por nível de prestígio;
  - +5% de moedas ao vender por nível de prestígio;
  - +2% de chance de peixes raros por nível de prestígio.
- Pode ser feito até **20 vezes**.

---

## 📖 Fischpédia

Use `/fischpedia` (ou o botão no menu) para ver sua coleção completa, estilo Pokédex, organizada por bioma (e uma página extra para itens de Lixo e outra para **Criaturas Extintas** 🦴). Peixes ainda não descobertos aparecem como "🔒 não descoberto" até você pescar um pela primeira vez.

> A Fischpédia registra o peixe **base** — capturar a mesma espécie em versão Shiny/Sparkling não cria uma entrada nova, mas conta normalmente para a sua contagem de capturas.

---

## ⚙️ Configuração para administradores

### `/definir-canal-eventos`

Define o canal de texto onde o bot vai postar automaticamente:

1. **Anúncios de capturas raras** — sempre que alguém pescar um peixe de raridade **Secreto pra cima** (Secreto 🌀, Ancestral 🌌, Exótico 💠, Divino ✨ ou Extinto 🦴), ou **qualquer** peixe **Shiny ✨/Sparkling 🌈**.
2. **Início e fim de Eventos Globais** de Criaturas Extintas.

Apenas administradores do servidor podem usar este comando.

### `/definir-titulo`, `/remover-titulo`, `/definir-icone-titulo`

Permitem conceder, remover ou trocar o ícone de um título especial customizado, dado diretamente a um jogador específico (independente da Loja da Liga).

---

## 📚 Glossário rápido

| Termo | Significado |
|---|---|
| **Cabana do Pescador** | O menu principal, aberto com `/pescar` |
| **Bioma** | Área de pesca com seu próprio conjunto de peixes |
| **Rareboost** | Multiplicador que aumenta a chance de peixes raros |
| **Tier (vara)** | "Força" da vara contra a dificuldade dos peixes |
| **Fuga (escape)** | Chance de um peixe sorteado escapar antes de entrar no inventário |
| **Gacha** | Sorteio de item raro (pets, relíquias) independente de outras mecânicas |
| **Streak** | Sequência de dias consecutivos (pescando ou resgatando o Presente Diário) |
| **Prestígio** | Reset voluntário de progresso em troca de bônus permanentes |
| **Shiny / Sparkling** | Variantes especiais de qualquer peixe, com valor e XP em dobro |
| **Evento Global** | Janela de tempo aleatória em que Criaturas Extintas podem ser pescadas em qualquer bioma |

---

*Boa pesca! 🎣*
