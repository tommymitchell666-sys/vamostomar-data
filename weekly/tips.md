# Tips for edition 9 (Sunday 22 Nov 2026)

Written 21 Nov 2026. Tommy's instructions for this week's build.

## The cover story is the Christmas guide, not a business

The headline (cover) story this week is **the Vamos Tomar Christmas guide going live**, not the usual
spotlight business. No business spotlight until paid partnerships start — the guide and the advent
calendar take its place in the Saturday Instagram caption too.

Set `"theme": "christmas"` at the top level of the edition. The page (`weekly/index.html`) already
supports this: a tinsel garland across the cover, a red-bauble logo in place of the Templar cross, and
an extra window (`spotlight.extra`) inside the cover story teasing the advent calendar, which opens
1 December (no prize — no sponsor has signed yet, so never promise one).

Use the `spotlight` block below exactly (translate further only if something needs correcting):

```json
{
  "listing": "natal-em-tomar",
  "name": {
    "en": "Christmas in Tomar",
    "pt": "Natal em Tomar",
    "es": "Navidad en Tomar"
  },
  "title": {
    "en": "Your Tomar Christmas, day by day",
    "pt": "O seu Natal em Tomar, dia a dia",
    "es": "Tu Navidad en Tomar, día a día"
  },
  "dek": {
    "en": "Our Christmas guide is live: the whole season, day by day, from 1 December to 10 January.",
    "pt": "O nosso guia de Natal já está online: toda a época, dia a dia, de 1 de dezembro a 10 de janeiro.",
    "es": "Nuestra guía de Navidad ya está en línea: toda la temporada, día a día, del 1 de diciembre al 10 de enero."
  },
  "photo": null,
  "photoAlt": null,
  "sources": [],
  "story": [
    {
      "en": "The guide goes live today in PT/EN/ES. One page holds the season: a day-by-day calendar from 1 Dec to 10 Jan; the village Christmases of Santa Cita, Freixo, Linhaceira and Longra; and ideas for the two long weekends, 28 Nov–1 Dec and 5–8 Dec.",
      "pt": "O guia entra online hoje em PT/EN/ES. Uma única página reúne toda a época: um calendário dia a dia de 1 de dezembro a 10 de janeiro; os Natais das aldeias de Santa Cita, Freixo, Linhaceira e Longra; e ideias para os dois fins de semana prolongados, 28 nov–1 dez e 5–8 dez.",
      "es": "La guía entra en línea hoy en PT/EN/ES. Una sola página reúne toda la temporada: un calendario día a día del 1 de diciembre al 10 de enero; las Navidades de las aldeas de Santa Cita, Freixo, Linhaceira y Longra; e ideas para los dos fines de semana largos, 28 nov–1 dic y 5–8 dic."
    },
    {
      "en": "Every item says whether it's confirmed or still provisional. The Câmara's full programme is still to come, so dates carried over from past years are marked until it's published. Confirmed items get an \"Add to calendar\" button.",
      "pt": "Cada item diz se está confirmado ou ainda provisório. O programa completo da Câmara ainda não saiu, por isso as datas transportadas de anos anteriores ficam marcadas até serem publicadas. Os itens confirmados têm um botão \"Adicionar ao calendário\".",
      "es": "Cada elemento indica si está confirmado o aún es provisional. El programa completo del Ayuntamiento todavía no ha salido, así que las fechas trasladadas de años anteriores quedan marcadas hasta su publicación. Los elementos confirmados tienen un botón \"Añadir al calendario\"."
    },
    {
      "en": "Day trips for the holidays (Ourém and Fátima, Abrantes, Leiria, Óbidos, Perlim), the Lopes-Graça at 120 programme, and answers to visitors' most common questions. Save the page: it's updated as the programme comes in.",
      "pt": "Passeios de um dia para as férias (Ourém e Fátima, Abrantes, Leiria, Óbidos, Perlim), o programa Lopes-Graça aos 120 e respostas às perguntas mais comuns dos visitantes. Guarda a página: é atualizada à medida que o programa chega.",
      "es": "Excursiones de un día para las fiestas (Ourém y Fátima, Abrantes, Leiria, Óbidos, Perlim), el programa Lopes-Graça a los 120 y respuestas a las preguntas más comunes de los visitantes. Guarda la página: se actualiza a medida que llega el programa."
    }
  ],
  "facts": [
    {
      "k": {
        "en": "What",
        "pt": "O quê",
        "es": "Qué"
      },
      "v": {
        "en": "Christmas guide, PT · EN · ES",
        "pt": "Guia de Natal, PT · EN · ES",
        "es": "Guía de Navidad, PT · EN · ES"
      }
    },
    {
      "k": {
        "en": "Covers",
        "pt": "Cobre",
        "es": "Cubre"
      },
      "v": {
        "en": "1 Dec – 10 Jan, day by day",
        "pt": "1 dez – 10 jan, dia a dia",
        "es": "1 dic – 10 ene, día a día"
      }
    },
    {
      "k": {
        "en": "Game",
        "pt": "Jogo",
        "es": "Juego"
      },
      "v": {
        "en": "Advent calendar from 1 Dec",
        "pt": "Calendário do Advento a partir de 1 dez",
        "es": "Calendario de Adviento desde el 1 dic"
      }
    },
    {
      "k": {
        "en": "Cost",
        "pt": "Custo",
        "es": "Costo"
      },
      "v": {
        "en": "Free",
        "pt": "Grátis",
        "es": "Gratis"
      }
    }
  ],
  "tags": [
    {
      "en": "Christmas",
      "pt": "Natal",
      "es": "Navidad"
    },
    {
      "en": "Events",
      "pt": "Eventos",
      "es": "Eventos"
    },
    {
      "en": "Family",
      "pt": "Família",
      "es": "Familia"
    },
    {
      "en": "Free",
      "pt": "Grátis",
      "es": "Gratis"
    }
  ],
  "urls": {
    "en": "https://vamostomar.pt/en/christmas-in-tomar/",
    "pt": "https://vamostomar.pt/pt/natal-em-tomar/",
    "es": "https://vamostomar.pt/es/navidad-en-tomar/"
  },
  "url": "https://vamostomar.pt/pt/natal-em-tomar/",
  "links": {},
  "cta": {
    "en": "Open the Christmas guide",
    "pt": "Abrir o guia de Natal",
    "es": "Abrir la guía de Navidad"
  },
  "extra": {
    "kicker": {
      "en": "Coming 1 December",
      "pt": "Chega a 1 de dezembro",
      "es": "Llega el 1 de diciembre"
    },
    "title": {
      "en": "The Vamos Tomar advent calendar",
      "pt": "O Calendário do Advento do Vamos Tomar",
      "es": "El Calendario de Adviento de Vamos Tomar"
    },
    "text": [
      {
        "en": "Twenty-four doors, all still shut. From 1 Dec a new one opens every day, and behind each is a free mini-game set in Tomar: spot the difference in the Praça, light up the Charola, ride down the Nabão, stack a tabuleiro. Missed a day? Earlier doors stay open to play.",
        "pt": "Vinte e quatro portas, todas ainda fechadas. A partir de 1 de dezembro abre uma nova todos os dias, e por detrás de cada está um mini-jogo gratuito passado em Tomar: encontra as diferenças na Praça, ilumina a Charola, desce o Nabão, empilha um tabuleiro. Perdeste um dia? As portas anteriores continuam abertas para jogar.",
        "es": "Veinticuatro puertas, todas aún cerradas. Desde el 1 de diciembre se abre una nueva cada día, y detrás de cada una hay un mini-juego gratuito ambientado en Tomar: encuentra las diferencias en la Praça, ilumina la Charola, baja el Nabão, apila un tabuleiro. ¿Te perdiste un día? Las puertas anteriores siguen abiertas para jugar."
      },
      {
        "en": "Every game has its own scoreboard, and on Christmas Eve door 24 strings your four favourite games into one big run.",
        "pt": "Cada jogo tem o seu próprio marcador, e na véspera de Natal a porta 24 junta os teus quatro jogos favoritos numa grande maratona.",
        "es": "Cada juego tiene su propio marcador, y en Nochebuena la puerta 24 une tus cuatro juegos favoritos en una gran maratón."
      }
    ],
    "image": "https://vamostomar.pt/data/images/advent-calendar-preview-pt-20261122.webp",
    "imageAlt": {
      "en": "The Vamos Tomar advent calendar, all 24 doors still closed",
      "pt": "O Calendário do Advento do Vamos Tomar, com as 24 portas ainda fechadas",
      "es": "El Calendario de Adviento de Vamos Tomar, con las 24 puertas aún cerradas"
    },
    "date": "2026-12-01",
    "dateLabel": {
      "en": "Tue 1 December",
      "pt": "Ter 1 de dezembro",
      "es": "Mar 1 de diciembre"
    },
    "cta": {
      "en": "Follow @vamostomarinsta to see door 1 open →",
      "pt": "Segue @vamostomarinsta para ver a porta 1 abrir →",
      "es": "Sigue @vamostomarinsta para ver la puerta 1 abrir →"
    },
    "url": "https://instagram.com/vamostomarinsta"
  }
}
```

First `cover.lines` entry must point at `#cover-story`:

```json
{
  "lines": [
    {
      "label": {
        "en": "Coming 1 Dec",
        "pt": "Chega a 1 dez",
        "es": "Llega el 1 dic"
      },
      "text": {
        "en": "Advent calendar: 24 doors, 24 games",
        "pt": "Calendário do Advento: 24 portas, 24 jogos",
        "es": "Calendario de Adviento: 24 puertas, 24 juegos"
      },
      "href": "#cover-story"
    },
    {
      "label": {
        "en": "The big one",
        "pt": "Em destaque",
        "es": "El gran evento"
      },
      "text": {
        "en": "Planos Film Fest opens its 10th edition",
        "pt": "O Planos Film Fest abre a 10.ª edição",
        "es": "El Planos Film Fest abre su 10.ª edición"
      },
      "href": "#feature"
    },
    {
      "label": {
        "en": "Don't Miss",
        "pt": "Não Perca",
        "es": "No Te Pierdas"
      },
      "text": {
        "en": "Filarmonias in Carregueiros, Sun 16:00",
        "pt": "Filarmonias em Carregueiros, dom 16:00",
        "es": "Filarmonias en Carregueiros, dom 16:00"
      },
      "href": "#dm-h"
    },
    {
      "label": {
        "en": "News",
        "pt": "Notícias",
        "es": "Noticias"
      },
      "text": {
        "en": "Festa Templária posts a €255,000 loss",
        "pt": "Festa Templária com prejuízo de 255 mil euros",
        "es": "Festa Templária con pérdida de 255.000 euros"
      },
      "href": "#nw-h"
    }
  ]
}
```

## Assets

- `weekly/logo-natal.webp` — the bauble logo, already built, 1000×93, lossless.
- `images/advent-calendar-preview-pt-20261122.webp` — screenshot of the real advent-calendar board,
  all 24 doors closed. EN and ES versions are still outstanding (the board's title banner is in
  Portuguese); until they arrive, the PT image is reused for all three languages in `spotlight.extra.image`.
- Cover photo: still pending from Tommy. Until it arrives, `spotlight.photo` stays `null` and the cover
  shows the side column only (no photo panel) — this is a known, deliberate gap, not a bug.

## Rules to keep

- Promise no prizes for the advent calendar.
- Door 24 is a Christmas Eve run built from the top 4 games by plays (reviewed 23 Dec, announced
  24 Dec morning) — never call it a mystery or secret game.
- No downloadable/offline versions of the guide or game (no PDF, no .ics feeds, no daily reminder);
  per-event "Add to calendar" links are fine.
- No AR trail this year — advent calendar only.
- Instagram captions: no "amanhã", no WhatsApp, `#vamostomar` plus `#natalemtomar` this week,
  3–5 hashtags at the very end.
- Never touch the site repo `vamostomar` (costs Netlify credits) — the `christmas-guide` branch merge
  into `main` is Tommy's to do, not the weekly run's.
