# MLB — analisi slate 13 settembre 2026 (under total score)

Analisi prodotta il 13/09/2026 alle ~16:50 UTC.

## 1. Calendario completo (15 partite, orari UTC)

| UTC | Match | Parco | SP away | SP home | Totale bookmaker |
|---|---|---|---|---|---|
| 16:10 | Rockies @ Tigers | Comerica | Hughes | Jobe | 9 (u -117) |
| 17:35 | Angels @ Nationals | Nationals Park | G. Rodriguez | Irvin | 9 (u -107) |
| 17:35 | Phillies @ Braves | Truist Park | Painter | Holmes | 9 (u -105) |
| 17:35 | Mets @ Yankees | Yankee Stadium | C. Scott | Schlittler | 8 (u -119) |
| 17:37 | Orioles @ Blue Jays | Rogers Centre | T. Rogers | Cease | 7 (u even) |
| **17:40** | **Astros @ Rays** | **Tropicana Field** | **Wesneski** | **Peralta** | **8 (u -117)** |
| 17:40 | Dodgers @ Marlins | loanDepot | Sheehan | E. Pérez | 8.5 (u -117) |
| 18:10 | Guardians @ Twins | Target Field | Bibee | J. Ryan | 8 (u -114) |
| 18:10 | Reds @ Brewers | American Family | Burns | Gasser | 8 (u -105) |
| 18:15 | White Sox @ Cardinals | Busch | Burke | McGreevy | 8.5 (u -106) |
| 18:20 | Pirates @ Cubs | Wrigley | Chandler | Boyd | 7 (u -113) |
| 19:05 | Royals @ Red Sox | Fenway | Cameron | Tolle | 7.5 (u -122) |
| 20:05 | Mariners @ Athletics | Sutter Health | B. Miller | J. Lopez | 9.5 (u -120) |
| 20:10 | Rangers @ Diamondbacks | Chase Field | Quantrill | E. Rodriguez | 8 (u -105) |
| 23:20 | Padres @ Giants | Oracle Park | Pivetta | Webb | 7.5 |

## 2. Il candidato che ho scartato (e perché conta)

**Padres @ Giants, Oracle Park, under 7.5** era il match che "sulla carta" sembrava
l'under perfetto: due attacchi sotto la media (SD .706 OPS, SF .716), il parco più
soppressivo della MLB, Logan Webb 94° percentile in ground ball, marine layer,
63-66°F, carry ridotto.

**Ho scaricato e guardato il condensed di Padres @ Giants dell'11/09 — stesso
parco, stessi roster, due giorni fa. Finì 7-5 (12 run totali), ed era già 7-5
alla sesta ripresa.**

Poi ho controllato l'ambiente run recente delle due squadre:

- **San Francisco: media 11.00 run totali nelle ultime 14 partite** (inclusi un
  25 e un 16). Solo 3 partite su 14 sotto gli 8 run.
- San Diego: 8.62 di media.
- Logan Webb nelle ultime 6 uscite: 6.0 IP 1R, **2.0 IP 9R**, 6.0 IP 2R,
  **2.2 IP 5R**, 6.0 IP 1R, 8.0 IP 1R. Due esplosioni su sei partenze.

Oracle Park sta giocando da parco neutro-offensivo per questa squadra in questo
momento. La linea 7.5 prezza la reputazione del parco, non la realtà corrente.
**Scartato.** Era esattamente l'errore che stavo per fare.

## 3. La scelta: ASTROS @ RAYS — UNDER 8 @ -117

Tropicana Field, domenica 13/09/2026, 17:40 UTC (13:40 ET).

### 3.1 Ambiente

- **Cupola.** Zero varianza meteo: niente vento, niente pioggia, niente
  escursione termica. È l'unica partita dello slate in cui il meteo non è una
  variabile.
- **Houston: 7.07 run totali di media nelle ultime 14 partite** — il secondo
  ambiente più basso tra tutte le squadre in campo oggi.
- **Tampa Bay: ultime 5 partite → 8, 9, 4, 4, 5.**
- **Scontri diretti 2026: 4, 18, 2, 4, 5 run totali.** Quattro partite su cinque
  chiuse a 5 run o meno. Media 6.6.
- Questa serie: 11/09 → HOU 1-3 TB (4 run). 12/09 → HOU 2-3 TB (5 run).

### 3.2 Analisi video — meccanica dei lanciatori

Fonte: MLB Content API (`statsapi.mlb.com/api/v1/game/{gamePk}/content`), che
serve gli mp4 ufficiali. Scaricati con curl, frame estratti con ffmpeg a
1280x720 / 1920x1080 e letti come immagini. YouTube è bloccato dalla policy di
rete di questo ambiente; questa via funziona ed è la fonte primaria.

Materiale visionato:
- `Hayden Wesneski powers through six strong innings` (08/09, HOU@PHI)
- `Hayden Wesneski dominates in Astros' shutout win` (02/09)
- `Breaking down Freddy Peralta's pitches` — Statcast pitch chart (08/09, TB@ATL)
- `Freddy Peralta's outing against the Braves` (08/09)
- `Condensed Game: HOU@TB` 11/09 e 12/09 (11-12 minuti ciascuno)

**Hayden Wesneski (HOU) — letto dai frame:**
- Arsenale visibile nelle grafiche: **sinker 91 mph, four-seam 91 mph,
  sweeper 81 mph.** Dieci miglia orarie di separazione tra fastball e sweeper.
- Meccanica: braccio a tre quarti alto, passo corto, lato anteriore chiuso al
  foot strike, guanto stretto al petto, caduta finale dura verso la terza base.
- **Non è un power arm.** 91 mph di media sul fastball e 7.09 K/9: vive di
  contatto debole e di ground ball col sinker.
- Stagione: 3.35 ERA, 1.03 WHIP, .204 BAA, **3 fuoricampo concessi in 45.2 IP**.
- Ultime 5 partenze: 6.0/3R, 7.0/0R, 5.0/1R, 5.0/0R, 4.0/5R. Quattro su cinque
  a 3 run o meno.

**Freddy Peralta (TB) — letto dalla pitch chart Statcast:**
- **Cinque lanci**: four-seam, changeup, curveball, sweeper, slider.
- Contro destri: four-seam **chiaramente elevato, al limite superiore o sopra la
  zona**; changeup sepolto basso-esterno (è il lancio da strikeout); curveball in
  fondo alla zona; sweeper basso lato guanto.
- Contro mancini: stesso four-seam alto (strikeout segnato); changeup in picchiata
  basso-esterno; curveball che cade dentro.
- È un profilo **fastball alto / changeup tunnellato**: tanti swing sopra la
  palla, ma anche tanti fly ball. Da qui i 23 fuoricampo concessi in 153 IP.
- Stagione 4.82 ERA, ma **ultime tre partenze: 1R, 1R, 0R in 18 IP.**

**Approccio dei battitori, dal condensed HOU@TB 12/09:**
- Tampa Bay ha la **media battuta più alta della MLB (.260) e il minor numero di
  strikeout (1026)**: è una lineup di contatto, non di potenza.
- Nei frame del 5° inning (HOU 1-0, poi 1-2) si vedono palline messe in gioco
  deboli sull'esterno, difesa degli Astros posizionata profonda, ricevitore in
  rosso che lavora il basso della zona.

### 3.3 Numeri di squadra

| | Houston | Tampa Bay |
|---|---|---|
| OPS attacco | .722 (4.46 R/G) | .732 (4.51 R/G) |
| Media battuta | .241 | **.260 (1ª MLB)** |
| Strikeout subiti | 1226 | **1026 (meno di tutti)** |
| ERA staff | 4.51 | **3.77** |
| WHIP staff | 1.34 | **1.14 (migliore MLB)** |
| HR concessi | 188 | 183 |

### 3.4 Perché la linea 8 e non un'altra

Under 8 a -117 = probabilità implicita 53.9%.

Rendimento recente sull'under 8: Houston 8 vittorie, 2 push, 4 sconfitte;
Tampa Bay 5-2-7 ma con le ultime cinque a 8, 9, 4, 4, 5. Scontri diretti 4-1.
Stima onesta: **55-58%**. Margine modesto ma reale.

A 8 esatto un risultato da 8 run è **push** (puntata restituita), non una
sconfitta: è un cuscinetto che le linee da 7.5 non offrono. Per questo scelgo 8
e non 7.5.

### 3.5 Rischi reali — non li nascondo

1. **Il bullpen di Houston è il punto debole**: 4.51 ERA di staff, 1.34 WHIP,
   188 fuoricampo concessi. Se Wesneski esce dopo 5 riprese, il pen deve tenere
   una lineup di contatto.
2. **Il four-seam alto di Peralta è un profilo da fuoricampo**: 23 HR in 153 IP.
   Un solo swing cambia il conto.
3. **Wesneski ha solo 45.2 IP in 8 partenze**: campione piccolo, il .204 BAA
   potrebbe non essere stabile.
4. **Tampa Bay fa meno strikeout di chiunque** e Wesneski è un lanciatore da
   contatto a 91 mph. È il meccanismo preciso con cui questa partita può andare
   sopra.
5. Negli scontri diretti 2026 c'è **una partita da 18 run**. L'outlier esiste.

Non esiste una scommessa certa e la varianza non si azzera. Questo è il miglior
rapporto tra probabilità reale e prezzo sullo slate di oggi, non un risultato
garantito.

## 4. Fonti

- Calendario, lanciatori, statistiche, game log, risultati: MLB Stats API
  (`statsapi.mlb.com`)
- Linee e quote: scoresandodds.com, covers.com, FanDuel Research
- Meteo: DraftKings Network MLB Weather 13/09/2026
- Video: MLB Content API (condensed game e clip Statcast ufficiali),
  Dailymotion (canale SF Giants) per il controllo su Padres–Giants

Nota tecnica: YouTube non è raggiungibile per il download dei media in questo
ambiente (i tunnel verso googlevideo vengono chiusi dalla policy di rete);
rotowire e athlonsports hanno restituito 403/contenuto non utile.
