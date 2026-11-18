# Pursuit

Police vs. criminals in a city. Every round, the players are split into a few criminals and a larger police force,
and bots fill the empty slots. The criminals try to stay free until the clock runs out; the police hunt them down
on foot and in patrol cars.

## Download

**[Download the Pursuit launcher](https://github.com/corporal-pursuit/PursuitLauncher/releases/latest/download/PursuitLauncher.exe)**
and run it. It installs the game (about 620 MB to download, 1.8 GB on disk) and keeps it up to date: updates
download only what changed, usually a few MB.

- Windows 10 or 11, 64-bit.
- The launcher is not code-signed, so Windows SmartScreen may warn you the first time: choose **More info → Run anyway**.
- Matches only include players on the same version. The launcher updates the game by itself when you start it.
- To uninstall, use **⋯ → Uninstall** in the launcher, or *Settings → Apps → Pursuit*.

The [Releases](https://github.com/corporal-pursuit/Pursuit/releases) page has the release notes; its files are what
the launcher downloads. The launcher's source is at [corporal-pursuit/PursuitLauncher](https://github.com/corporal-pursuit/PursuitLauncher).

## Playing

**Play** puts you in the matchmaking queue. Pick any combination of modes and you join the first match that fills:

| Mode  | Players | Round  |
|-------|---------|--------|
| Blitz | 12      | 10 min |
| Core  | 24      | 20 min |
| Grand | 48      | 40 min |

One player in each match hosts it for everyone (picked automatically by connection and PC). Bots take any slot no
player has.

**Custom Game** lets you host a match yourself or join one by IP address (UDP port 7777).

### Rules

- About 30% of the players are criminals, the rest police.
- Criminals start **clean**: bullets can't hurt them, and the only way to take one down is the police stun gun.
  A tase is an arrest.
- A criminal who draws a gun becomes **wanted** and can be shot for the rest of the round.
- Police win by arresting or killing every criminal. Criminals win by surviving until time runs out, or by taking
  out every police officer.
- Criminals can rob the banks: crack the vault for money.
- Criminal positions flash on the map at regular intervals.
- Kills, arrests and wins earn XP and money. Police rank up with XP and unlock better weapons.

Press **F1** in game for the full How to Play panel.

### Controls

All keys can be changed in **Settings**.

| Action                        | Key                |
|-------------------------------|--------------------|
| Move / drive                  | W A S D            |
| Look                          | Mouse              |
| Shoot / aim                   | Left / right mouse |
| Sprint                        | Left Shift         |
| Jump, handbrake               | Space              |
| Crouch                        | C or Left Ctrl     |
| Reload                        | R                  |
| Use (get in/out, rob, drag out) | F                |
| Lean left / right             | Q / E              |
| Siren / light bar (police car)  | E / L            |
| Weapons                       | 1 – 4              |
| Holster                       | X                  |
| Map                           | M                  |
| Scoreboard                    | Tab                |
| Spectate (while out)          | C                  |
| How to Play                   | F1                 |
| Controls help                 | H                  |

## Credits

Made with Unity. Models used under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/):

- Cars by [Daniel Zhabotinsky](https://sketchfab.com/DanielZhabotinsky):
  [Fairheaven LT '80 Cop Cruiser](https://sketchfab.com/3d-models/fairheaven-lt-80-cop-cruiser-low-poly-model-61766c1e6e1e4b2b803c174f33433a74),
  [Saba V12 '95](https://sketchfab.com/3d-models/saba-v12-95-low-poly-model-3ab977050c334c13b6abb5de078b4957),
  [Negotiator '80](https://sketchfab.com/3d-models/negotiator-80-low-poly-model-892b2684fb37442299bfad9222cf331c),
  [Milano '95](https://sketchfab.com/3d-models/milano-95-low-poly-model-122a22d210234596ad23623588d0d166),
  [Illinois '90](https://sketchfab.com/3d-models/illinois-90-low-poly-model-d604871eee5b4181bb298163b0b675b7)
- [9mm Pistol](https://sketchfab.com/3d-models/9mm-pistol-43bc09f5aace4346a8a2b6e1580fc03f) by [TORI106](https://sketchfab.com/TORI106)
- [Taser X26 Low Poly](https://sketchfab.com/3d-models/taser-x26-low-poly-4f3d6c6b94ae4d959bb00da11f5ef098) by [Mox](https://sketchfab.com/MoxAlehin)
- [Remington 870 Police Magnum](https://sketchfab.com/3d-models/remington-870-police-magnum-12-gauge-shotgun-eea11de7e9d24b6683962b8388c319eb) by [8sianDude](https://sketchfab.com/haoliu95)
- [Sawed-off Winchester](https://sketchfab.com/3d-models/sawed-off-winchester-b009decb8313474fb2ed0902dd37c5cf) by [Richard Speight](https://sketchfab.com/richardsp8.2)
- [Low-Poly M4a1](https://sketchfab.com/3d-models/low-poly-m4a1-8cab1cbeb82c4396a154f9fc8771417b) by [TastyTony](https://sketchfab.com/TastyTony)
- [M16 Assault Rifle](https://sketchfab.com/3d-models/m16-assault-rifle-339d0f7b21024387853dd926a5d51b50) by [SpatialNeglect](https://sketchfab.com/jeandiz)

Also with thanks to (no attribution required): [Poly Haven](https://polyhaven.com) and [ambientCG](https://ambientcg.com)
for textures, props and sky; buildings from the vrbn studios Free Buildings URP Bundle (Unity Asset Store); [Quaternius](https://quaternius.com) models; sound recordings from
[Freesound](https://freesound.org) contributors (CC0); characters and animations from [Mixamo](https://www.mixamo.com);
character bodies made with [MakeHuman](http://www.makehumancommunity.org).

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/corporal-pursuit/Pursuit/issues).
