[README (3).md](https://github.com/user-attachments/files/31094133/README.3.md)
# 🎣 V-FISCH — Wiki do Jogador

Bem-vindo à cabana do pescador! Este bot transforma seu servidor num
jogo completo de pesca: pescarias, biomas, loja, pets, baús, eventos
globais e um sistema de progressão bem recheado. Tudo funciona por
menus e botões — não precisa decorar nada.

## Novidades desta atualização

- 🚀 **Bot mais rápido e estável** — melhorias internas deixaram as
  respostas mais ágeis, principalmente em servidores grandes ou com
  muita gente pescando ao mesmo tempo.
- 🧪 **Poções renovadas** — agora compradas em **estoque** e ativadas
  quando você quiser, durando um **tempo real fixo** em vez de um
  número de usos (veja [Poções](#poções)).
- 🧹 **Novo upgrade: Faro Apurado** — reduz a chance de pescar Lixo
  (veja [Upgrades permanentes](#upgrades-permanentes)).
- 🌐 **Efeitos Globais** — buffs comprados com Gemas que beneficiam
  **o servidor inteiro**, não só quem comprou (veja [Efeitos
  Globais](#efeitos-globais)).

## Índice

- [Como começar](#como-começar)
- [Como pescar](#como-pescar)
- [Raridades dos peixes](#raridades-dos-peixes)
- [Biomas](#biomas)
- [Ligas](#ligas)
- [Progressão](#progressão)
- [Equipamento](#equipamento)
- [Prestígio](#prestígio)
- [Poções](#poções)
- [Efeitos Globais](#efeitos-globais)
- [Gemas e Elixires](#gemas-e-elixires)
- [Presente Diário](#presente-diário)
- [Pets](#pets)
- [Baús e Relíquias](#baús-e-relíquias)
- [Evento Global: Criaturas Extintas](#evento-global-criaturas-extintas)
- [Títulos](#títulos)
- [Fischpédia e Ranking](#fischpédia-e-ranking)
- [Perfil](#perfil)
- [Comandos disponíveis](#comandos-disponíveis)
- [Multiservidor](#multiservidor)

## Como começar

- Use `/pescar` para abrir sua cabana de pescador — a resposta é
  **privada** (só você vê), então pode usar à vontade sem poluir o
  canal.
- No menu você navega por botões entre **Pescar, Inventário, Loja,
  Perfil, Ranking e Viajar** (trocar de bioma).
- Use `/perfil` a qualquer momento para ver seu progresso
  publicamente no canal — marque outro membro (`/perfil @alguém`) ou
  busque pelo nick de qualquer jogador registrado no bot, mesmo fora
  do servidor atual.

## Como pescar

- Cada pescaria puxa 1 ou mais peixes de uma vez — a quantidade
  depende da sua **vara** e do seu **barco**.
- Peixes raros em biomas avançados podem **escapar da linha** se sua
  vara não for forte o bastante para aquele nível de dificuldade.
  Uma vara melhor, uma isca melhor ou poções/elixires ativos reduzem
  essa chance de fuga.
- Volta e meia um peixe sai como uma variante especial:
  - ✨ **Shiny** — vale **2x** em moedas e XP.
  - 🌈 **Sparkling** — muito mais rara, vale **4x** em moedas e XP.
- Pescar em dias seguidos aumenta um bônus permanente de XP
  (sequência diária) — pular um dia inteiro reinicia a sequência.

## Raridades dos peixes

Da mais fraca para a mais forte:

| Raridade | Ícone |
|---|---|
| Lixo | 🗑️ |
| Comum | ⚪ |
| Incomum | 🟢 |
| Raro | 🔵 |
| Raríssimo | 🟦 |
| Épico | 🟣 |
| Lendário | 🟡 |
| Mítico | 🔴 |
| Secreto | 🌀 |
| Ancestral | 🌌 |
| Exótico | 💠 |
| Divino | ✨ |
| **Extinto** (só durante Eventos Globais) | 🦴 |

Capturas de raridade **Secreto** pra cima — e qualquer peixe
Shiny/Sparkling — são anunciadas publicamente no canal de eventos do
servidor, se um administrador tiver configurado um.

## Biomas

10 biomas, cada um desbloqueado a partir de um **nível mínimo**, com
seu próprio conjunto de peixes cada vez mais raros e valiosos:

| Bioma | Nível mínimo |
|---|---|
| 🏞️ Lago Tranquilo | 1 |
| 🌊 Rio Correnteza | 6 |
| 🐊 Pântano Sombrio | 12 |
| 🏖️ Costa Rochosa | 20 |
| 🪸 Recife de Coral | 30 |
| ⛵ Mar Aberto | 45 |
| 🕳️ Fossa Abissal | 65 |
| ❄️ Geleira Polar | 90 |
| 🌋 Rio de Lava | 130 |
| ☁️ Ilhas Flutuantes | 180 |

Use o botão **Viajar** no menu principal para trocar de bioma assim
que tiver o nível necessário.

## Ligas

Sua liga sobe junto com seu nível e determina, entre outras coisas,
quais títulos você pode comprar na Loja da Liga:

| Liga | Nível mínimo |
|---|---|
| 🥉 Bronze | 1 |
| 🥈 Prata | 30 |
| 🥇 Ouro | 80 |
| 💠 Platina | 160 |
| 💎 Diamante | 280 |
| 👑 Mestre Pescador | 420 |

O nível máximo do jogo é **500**.

## Progressão

- **Níveis e XP:** cada pescaria dá XP. Subir de nível libera novos
  biomas, novas varas/iscas e dá recompensas em moedas.
- **Varas e iscas por nível e área:** cada vara e cada isca exige um
  **nível mínimo** para ser comprada, alinhado à área (bioma) a que
  pertence — então seu equipamento sempre acompanha o ritmo dos
  biomas que você já desbloqueou. Itens ainda bloqueados aparecem
  com 🔒 na loja, mostrando o nível necessário.
- **Sequência diária de pesca:** pescar todos os dias mantém um
  bônus permanente de XP vivo — faltar um dia inteiro reinicia a
  contagem.

## Equipamento

### Varas

13 varas, cada uma com preço, nível mínimo, poder de captura e uma
**habilidade exclusiva** (crítico de XP, duplicar a captura, surto
de sorte, peixes extras, etc.):

| Vara | Nível mín. | Área | Preço | Captura | Habilidade |
|---|---|---|---|---|---|
| 🎣 Vara Básica | 1 | Lago Tranquilo | Grátis | 1-2 | — |
| 🎋 Vara de Bambu | 1 | Lago Tranquilo | 🪙 1.000 | 1-3 | Fisgada Crítica |
| 🎣 Vara de Ferro | 6 | Rio Correnteza | 🪙 3.500 | 2-4 | Instinto Apurado |
| 🛠️ Vara Reforçada | 12 | Pântano Sombrio | 🪙 9.000 | 2-4 | Linha Dupla |
| ✨ Vara Dourada | 20 | Costa Rochosa | 🪙 24.000 | 3-5 | Toque de Midas |
| ⚙️ Vara de Carbono | 30 | Recife de Coral | 🪙 60.000 | 3-6 | Fisgada Múltipla |
| 💎 Vara de Diamante | 45 | Mar Aberto | 🪙 160.000 | 4-7 | Reflexo Cristalino |
| 🔮 Vara Mítica | 65 | Fossa Abissal | 🪙 400.000 | 5-8 | Chamado Abissal |
| 🌌 Vara Ancestral | 90 | Geleira Polar | 🪙 950.000 | 6-9 | Bênção dos Mares Antigos |
| 🔷 Vara de Mítrilo | 130 | Rio de Lava | 🪙 2.000.000 | 6-9 | Fisgada Élfica |
| 🔺 Vara de Adamantium | 180 | Ilhas Flutuantes | 🪙 4.200.000 | 7-10 | Fúria de Adamantium |
| 🌠 Vara Celestial | 250 | Ilhas Flutuantes | 🪙 9.000.000 | 8-12 | Bênção Celestial |
| 🕳️ Vara do Mestre do Vazio | 350 | Ilhas Flutuantes | 🪙 20.000.000 | 10-15 | Colapso do Vazio |

Reequipar uma vara que você já comprou é sempre de graça — o preço
só vale na primeira compra.

### Iscas

7 iscas, cada uma com usos consumíveis, também limitadas por nível e
área. Comprar a isca que já está selecionada empilha os usos em vez
de travar a compra:

| Isca | Nível mín. | Área | Preço (cada) | XP | Chance rara | Redução de fuga |
|---|---|---|---|---|---|---|
| 🪱 Minhoca | 1 | Lago Tranquilo | 🪙 10 | x1.2 | x1.1 | -2% |
| 🦐 Isca de Camarão | 6 | Rio Correnteza | 🪙 25 | x1.4 | x1.3 | -4% |
| 🦑 Isca de Lula | 20 | Costa Rochosa | 🪙 60 | x1.6 | x1.5 | -7% |
| 🌟 Isca Dourada | 30 | Recife de Coral | 🪙 150 | x2.0 | x1.8 | -11% |
| 💎 Isca de Cristal | 45 | Mar Aberto | 🪙 350 | x2.5 | x2.3 | -16% |
| 🌑 Isca Abissal | 65 | Fossa Abissal | 🪙 800 | x3.2 | x3.0 | -24% |
| 🕳️ Isca do Vazio | 130 | Rio de Lava | 🪙 1.800 | x4.2 | x4.0 | -35% |

### Barcos

Aumentam quantos peixes você fisga por pescaria:

| Barco | Preço | Peixes extras |
|---|---|---|
| 🛶 Canoa de Pesca | 🪙 6.000 | +1 |
| 🚣 Barco a Remo | 🪙 21.000 | +2 |
| 🚤 Lancha Motorizada | 🪙 66.000 | +3 |
| 🛥️ Iate de Luxo | 🪙 180.000 | +4 |
| 🚢 Navio Baleeiro | 🪙 480.000 | +6 |
| ⚓ Nau Almirante | 🪙 1.200.000 | +8 |

### Upgrades permanentes

Comprados na loja e melhorados nível por nível — cada nível fica
mais caro que o anterior:

| Upgrade | Efeito por nível | Nível máximo |
|---|---|---|
| 🍀 Sorte do Pescador | +4% de chance de peixes raros | 20 |
| ⚡ Reflexos Rápidos | -0.25s no tempo de espera entre pescarias | 10 |
| 🧹 Faro Apurado | -6% na chance de pescar Lixo | 10 |

### Encantamentos de vara

Use **Relíquias Encantadas** (item raro obtido pescando) na tela de
Encantamentos para fortalecer permanentemente a vara equipada — até
o nível 15, cada nível dá +3% de chance de peixe raro, +2% de XP e
-1.5% de chance de fuga. Trocar de vara não perde o progresso de
encantamento — cada vara guarda o seu próprio nível.

## Prestígio

Ao chegar no **nível 100** com **🪙 50.000 ou mais**, você pode
prestigiar. Isso reinicia nível, XP, moedas, vara, barco, bioma e
encantamentos — mas concede um **nível de prestígio permanente**
(até 20 níveis), com bônus para sempre:

- +5% XP por nível de prestígio
- +5% moedas por nível de prestígio
- +2% sorte por nível de prestígio

Pets, relíquias, baús, títulos e sua Fischpédia **não são
perdidos** ao prestigiar.

## Poções

Compradas com moedas na **Loja de Poções**, as poções agora ficam
guardadas no seu **estoque** — comprar não ativa nada na hora. Use o
comando `/pocoes` (ou o botão **Minhas Poções**) quando quiser
ativar uma: uma vez ativada, ela dura um **tempo real fixo**, e
usar de novo enquanto uma já está ativa **estende** a duração em vez
de desperdiçar. Várias poções diferentes podem ficar ativas ao
mesmo tempo, com efeitos combinados:

| Poção | Preço | Duração | Efeito |
|---|---|---|---|
| 💹 Poção de Vendas | 🪙 700 | 15 min | +50% no preço de venda |
| 🛡️ Poção do Escudo | 🪙 850 | 18 min | -15% chance de fuga |
| 🧪 Poção da Sorte | 🪙 950 | 20 min | +50% chance de peixe raro |
| 📘 Poção de Experiência | 🪙 1.100 | 25 min | +60% XP |
| 🕸️ Poção da Rede Reforçada | 🪙 1.300 | 30 min | +2 peixes extras |
| 🌟 Poção Suprema do Pescador | 🪙 4.200 | 45 min | +30% XP, +30% sorte, +30% venda, +1 peixe extra, -10% fuga |

## Efeitos Globais

Comprados com Gemas 💎 na Loja de Efeitos Globais, mas diferente dos
Elixires pessoais: um Efeito Global beneficia **todo mundo que
estiver pescando no servidor** enquanto durar, não só quem comprou.
Só um Efeito Global fica ativo por vez em cada servidor — comprar o
mesmo efeito enquanto ele já está ativo estende a duração em vez de
desperdiçar:

| Efeito | Preço | Duração | Efeito |
|---|---|---|---|
| 🌊 Frenesi de Cardume | 💎 60 | 10 min | +30% XP, +20% sorte, +1 peixe extra pra todos |
| 🪙 Corrida do Ouro | 💎 70 | 10 min | +40% no preço de venda, +10% XP pra todos |
| 🕊️ Águas Calmas | 💎 55 | 10 min | -25% chance de fuga, +15% sorte pra todos |
| 🌟 Maré da Fartura | 💎 150 | 15 min | +50% XP, +40% sorte, +30% venda, +2 peixes extras, -20% fuga pra todos |

## Gemas e Elixires

- **Gemas 💎** são uma moeda especial, separada das moedas normais —
  ganhas no Presente Diário, por uma chance mínima em cada pescaria,
  ou como item bônus em baús Lendários/Míticos.
- Use Gemas na **Loja de Gemas** para comprar Elixires pessoais
  temporários, que duram um tempo real fixo. Comprar um elixir que
  já está ativo **estende a duração** em vez de desperdiçar:

| Elixir | Preço | Duração | Efeito |
|---|---|---|---|
| 🔷 Elixir de Mítrilo | 💎 15 | 5 minutos | +100% XP, +80% sorte, +50% venda, +2 peixes extras, -20% fuga |
| 🔺 Elixir de Adamantium | 💎 40 | 20 minutos | +200% XP, +150% sorte, +100% venda, +3 peixes extras, -30% fuga |

## Presente Diário

Resgatável uma vez por dia no menu principal:

- Moedas: começa em 🪙 150 e cresce +25 por dia de sequência
  (até o dia 30).
- Gemas: 💎 2 por resgate, com +5 de bônus a cada 5 dias seguidos
  resgatando.

## Pets

Pets aparecem com uma chance mínima a cada pescaria (uma espécie de
"gacha"). Você acumula todos os que já pegou e o melhor é equipado
automaticamente, somando bônus permanentes de XP, moedas e/ou sorte:

| Raridade | Pets | Bônus (XP / Moedas / Sorte) |
|---|---|---|
| ⚪ Comum | 🐱 Gato Pescador · 🦆 Pato Sortudo | +3% XP · +2% moedas ou sorte |
| 🔵 Raro | 🦦 Lontra Curiosa · 🕊️ Gaivota Guia | +8% XP · +5% moedas ou sorte |
| 🟣 Épico | 🦭 Foca Amiga · 🐬 Golfinho Veloz | +15% XP · +10% moedas ou sorte |
| 🟡 Lendário | 🐲 Dragãozinho · 🦅 Grifo Celeste | +25% XP · +18% moedas ou sorte |
| 🔴 Mítico | 🔥 Fênix Marinha · 🐙 Kraken Filhote | +40% XP · +10-30% moedas e sorte |
| 🌌 Ancestral | ✨ Espírito Guardião · 🌌 Leviatã Ancestral | +70% XP · +25-50% moedas e sorte |

## Baús e Relíquias

- **Baús de loot** caem com chance mínima (cerca de 1 em 12) durante
  a pesca, em 5 raridades: 📦 Comum, 🎁 Raro, 💜 Épico, 🏆 Lendário e
  🌌 Mítico. Ficam guardados fechados no inventário — abra um por
  vez ou use **"Abrir Todos"**.
- **🔮 Relíquia Encantada:** item raro (chance mínima por pescaria)
  usado para encantar sua vara equipada.

## Evento Global: Criaturas Extintas

Quando um administrador do servidor configura um canal de eventos
(`/definir-canal-eventos`), o bot passa a anunciar automaticamente,
**a cada hora**, um **Evento Global** de 5 minutos: durante essa
janela, criaturas 🦴 **Extintas** — Megalodon, Kraken, Nessie, Lula
Gigante e outras lendas perdidas — podem aparecer em **qualquer
bioma**, para qualquer jogador que estiver pescando no servidor.

Elas são bem mais difíceis de fisgar que qualquer peixe normal — a
chance de fuga depende muito da sua vara equipada (varas fracas
quase sempre a perdem; só varas de ponta, a partir da Vara de
Mítrilo, dão uma chance real de sucesso) — mas valem recompensas
enormes de moedas e XP. Vale a pena empilhar sorte (iscas, poções,
elixires, Efeitos Globais) antes do próximo evento aparecer.

Ao final do evento, o bot publica um **ranking com os 4 jogadores
que mais capturaram criaturas Extintas** naquela janela (🥇🥈🥉🏅). Um
administrador também pode configurar um cargo ou pessoa para ser
mencionado sempre que um evento começar
(`/definir-mencao-eventos`).

## Títulos

Comprados na Loja da Liga conforme você sobe de nível/liga:

| Título | Liga exigida | Preço |
|---|---|---|
| 🥉 Iniciante das Águas | Bronze | Grátis |
| 🥈 Pescador Persistente | Prata | 🪙 1.500 |
| 🥇 Mestre da Linha | Ouro | 🪙 6.000 |
| 💠 Lenda de Platina | Platina | 🪙 18.000 |
| 💎 Caçador Abissal | Diamante | 🪙 45.000 |
| 👑 Mestre Supremo dos Mares | Mestre Pescador | 🪙 120.000 |

Administradores também podem conceder um **título especial
customizado** a qualquer jogador (`/definir-titulo`, com emoji
próprio via `/definir-icone-titulo`, e removível com
`/remover-titulo`) — por exemplo, o dono do servidor dando a si
mesmo o título "Dono". Um título especial tem prioridade sobre os
títulos comprados e aparece em destaque no perfil.

## Fischpédia e Ranking

- `/fischpedia` mostra sua "Pokédex" pessoal de peixes já
  capturados — raridade, valor, XP e bioma de cada um, paginada por
  bioma. Peixes ainda não descobertos aparecem como "🔒 ???". Esse
  progresso é permanente e não é perdido ao vender seu inventário.
- O menu principal tem um botão de **Ranking**, mostrando os
  pescadores em destaque no servidor por nível/XP.

## Perfil

`/perfil` mostra um cartão compacto com:

- **PROGRESSO** — liga, nível, barra de XP e área (bioma) atual.
- **ESTATÍSTICAS** — nível de Sorte, nível de Reflexos e total de
  peixes já pescados.
- **EQUIPAMENTO** — vara, barco e isca equipados.
- **DINHEIRO** — moedas, gemas e relíquias.
- Título ativo, pet ativo e um resumo da coleção (Fischpédia + baús
  guardados).
- **RANK** no rodapé, mostrando sua posição no ranking geral de
  pescadores.

## Comandos disponíveis

| Comando | O que faz |
|---|---|
| `/pescar` | Abre sua cabana de pescador (menu principal, privado) |
| `/perfil [jogador]` | Mostra seu perfil ou o de outro membro, publicamente |
| `/fischpedia` | Sua "Pokédex" de peixes já capturados |
| `/pocoes` | Veja seu estoque de poções e ative uma |
| `/definir-canal-eventos` | (ADM) Define o canal de capturas raras e Eventos Globais |
| `/definir-mencao-eventos` | (ADM) Define quem é marcado (@) quando um Evento Global começa |
| `/definir-titulo` | (ADM) Concede um título especial customizado a um jogador |
| `/definir-icone-titulo` | (ADM) Troca o emoji de um título especial já concedido |
| `/remover-titulo` | (ADM) Remove o título especial de um jogador |

## Multiservidor

Seu progresso (moedas, nível, inventário, iscas, pets, tudo) é salvo
pela sua conta do Discord, não por servidor — então você joga com a
mesma conta em qualquer servidor onde o bot estiver presente. Tudo é
salvo automaticamente a cada ação, sem precisar fazer nada.
