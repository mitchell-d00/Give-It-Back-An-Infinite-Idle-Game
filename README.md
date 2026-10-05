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
  tries again. You can also tell it to hold the stage it is on.
- **Speed.** A button switches between 1×, 2× and 4× while the page is open.
  Time away always runs at 1×, for up to 8 hours (more with Night Shift).
- **You only spend points.** Levels, gear and skills arrive on their own. Every
  hero earns 2 points per level to put into Might, Vigor, Guard, Haste, Luck or
  Wits. You can spend them by hand, have one hero's points spent automatically,
  or spend everyone's at once.
- **Your hero.** You build one hero from 20 points and one of 10 classes.
- **100 premade heroes.** Each is built from the same 20 points and joins
  because the villain took something of theirs too. A new one turns up after a
  number of stage clears that grows as the collection does.
- **Death and reincarnation.** After stage 10, the hero flattened first in a
  lost fight has a small chance of dying for good. They come back as somebody
  new, with a new name, a new class and extra build points for each life, and a
  new place opens in the collection. They are the next hero to be found, and
  the villain has robbed them again.
- **Party slots.** You start with one and unlock more at stages 3, 8, 15, 30
  and 50, for a party of up to six. Heroes on the bench do not gain experience
  unless you buy Homework, but anyone you bring in is trained up close to the
  party's level and handed basic gear.
- **Foes.** Twelve kinds, each trading health, damage and speed against a
  trick: some dodge, some ignore Guard, some go for the weakest hero, some hit
  everyone. Bosses come in three kinds with their own tricks. Foes grow
  stronger as the party grows.
- **Grudge.** A second kind of point, earned from 43 milestones and from
  starting a new chase. Spend it on nine permanent upgrades for the whole
  party.
- **New chases.** Once you have cleared stage 20 you can give up the trail and
  start again from stage 1 for Grudge. Stage, levels, spent hero points and
  gear are lost. Heroes, slots, upgrades and milestones are kept.
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
