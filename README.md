# ⚽ Penalty Fever 2026 🏆

A World Cup 2026 penalty-shootout game in a single HTML file. No frameworks,
no assets, no build step — every pixel is drawn on canvas and every sound is
synthesized live with the Web Audio API.

## Play

Open `index.html` in any modern browser. That's it.

```bash
# or serve it, if you prefer
npx serve .
```

## How it works

- **Pick your nation** — 16 teams including the three 2026 host nations
  (USA, Mexico, Canada). Star ratings show each team's penalty pedigree,
  which drives how sharp their shooters and keeper are.
- **🎯 Shooting** — move the mouse to aim anywhere in (or around…) the goal,
  hold to charge the power bar, release to fire. More power means a faster,
  harder-to-save shot — but your accuracy falls apart the harder you blast it.
  The opposing keeper reads your aim more often the better their team is.
- **🧤 Goalkeeping** — you defend every other kick. Track the shot with your
  mouse (height matters: mouse high = dive high) until the keeper commits
  mid-flight. Guess right and the crowd goes wild.
- **🏆 The bracket** — win four shootouts (Round of 16 → Quarter → Semi →
  Final) to lift the trophy. Level scores after five kicks go to sudden
  death. Lose once and you're on the plane home.

## Features

- Full best-of-5 shootout rules with early decision and sudden death
- Escalating difficulty through the knockout rounds
- Animated stadium: shimmering crowd, floodlights, scrolling hoardings,
  mown-stripe pitch
- Synthesized crowd swells, kick thumps, whistles, goal fanfares — no audio
  files
- Confetti, goal sparks, screen shake, and a golden trophy ceremony
- Mouse and touch controls

Built for fun. May contain heartbreak — it *is* penalties, after all.
