<p align="center"><img src="logo.svg" width="96" alt="Give It Back logo"></p>

# Give It Back

An endless idle game in a single HTML file. A villain steals something small and
silly that matters a great deal to you. You set off to get it back. You never
will, but your party keeps trying while you are away.

## Play

Open `index.html` in any browser. There is nothing to install or build.

To put it online, turn on GitHub Pages for this repository (Settings → Pages →
deploy from the `main` branch, root folder). The game will be served at
`https://<your-username>.github.io/<repo-name>/`.

The game saves in the browser every few seconds. When you come back it runs the
time you were away, up to 8 hours, and tells you what happened.

## How it works

- **The theft.** Each new game picks a villain, a stolen thing, why it matters
  and a plan for getting it back. The villain escapes at every boss.
- **The run never ends.** The party fights through stages on its own, with a
  boss every 10 stages. When the party is beaten it falls back, trains, and
  tries again.
- **You only spend points.** Levels, gear and skills arrive on their own. Every
  hero earns 2 points per level to put into Might, Vigor, Guard, Haste, Luck or
  Wits. You can spend them by hand, have one hero's points spent automatically,
  or spend everyone's at once.
- **Your hero.** You build one hero from 20 points and one of 10 classes.
- **100 premade heroes.** Each is built from the same 20 points and joins
  because the villain took something of theirs too. They arrive as your best
  stage climbs: at stages 3, 6, 10, 15 and 20, then every 4 stages.
- **Party slots.** You start with one and unlock more at stages 3, 10, 25, 50
  and 100, for a party of up to six. Heroes on the bench do not gain
  experience, but anyone you bring in is trained up close to the party's level
  and handed basic gear.
- **Gear.** Each hero has a weapon, armour and a trinket. Better finds are
  equipped automatically.
- **Skills.** Each class has three, learned at levels 1, 10 and 30 and used
  automatically.

## Files

- `index.html`: the whole game: markup, styles, data and script
- `logo.svg`: repository logo and page icon
- `LICENSE`: MIT licence

## License

MIT. See `LICENSE`.
