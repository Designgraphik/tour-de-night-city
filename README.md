# Tour de Night City

A Zwift-style cycling ride through Night City, powered by your smart trainer and Cyberpunk 2077.

Got a smart trainer and bored of the usual virtual worlds and/or paying costly subscriptions? Tour de Night City puts you on a bike in Night City and hooks it up to your trainer, using your one time purchase of Cyberpunk 2077 as the engine.

Hit `F6` to open the mod console, pick a route and start pedaling. The bike steers itself and follows the road, so all you do is put out the watts. Hills change the resistance (quality checked and clean changes in inclines), workouts run in ERG, and every ride saves a FIT file (along with screenshots, final ride summary image) you can upload anywhere. Syncing to Intervals.icu is supported today on launch.

No trainer? You can still ride with simulated watts to preview the mod.

I'm a graphic designer, and this project is funded by my own company, [YouWorkForThem](https://www.youworkforthem.com), which sells fonts and stock graphics. If you're enjoying the mod, grabbing something there or sending it to a designer friend as a reference, helps a lot. 🙏

## Download

Get the files from the [latest release](https://github.com/Designgraphik/tour-de-night-city/releases/latest). The file names carry the version number, so this README doesn't need editing each release.

| File | What it is |
| --- | --- |
| Setup zip | The installer, and the recommended download. Unzip it and run the setup exe inside. |
| Manual zip | The manual install. |
| Starter save zip | Optional starter save. |

Check your downloads against `SHA256SUMS.txt`.

The Nexus Mods page, <https://www.nexusmods.com/cyberpunk2077/mods/38198>, is the main home.

## Installation instructions

### Setup exe (easiest)

1. Close the game.
2. Run the setup and follow along. It installs any missing frameworks and can add the starter save.
3. Launch the game. When Cyber Engine Tweaks asks for an overlay key, press `F6`.

### Manual zip

1. Install the six frameworks listed under Requirements.
2. Close the game.
3. Right-click the zip, Properties, tick Unblock.
4. Extract into your game folder and merge.
5. Launch the game and set `F6` as the CET overlay key.

Full steps are in `README-INSTALL.txt` inside the zip.

### Starter save (optional)

If you are here mainly from a cycling community and have never played Cyberpunk 2077 (and finished the opening story), I added a save file you can load to get rolling right away. The setup can add one for you: a Nomad V, level 33, in free roam, with 6 riding outfits in the wardrobe. Manual users can grab it from the release downloads. It never overwrites your own saves.

## First ride

1. Load a save (or the one I provided) and stand somewhere in the city, on foot.
2. Pedal a few strokes to wake the trainer, shake the HR and/or core sensor to wake them up. Close Zwift or anything else connected to these sensors.
3. Press `F6`, open DEVICES and connect your trainer and other sensors (same as any other training platform).
4. Open RIDE, pick a route and go. Or pick a workout from WORKOUTS.
5. Press `F10` and confirm to end and save.

Rides are saved to `Documents\Tour de Night City\Activities`.

Using intervals.icu? Click the connect from the sharing tab or from the open bridge app running behind the game in Windows.

## Controls (rebind in CET bindings)

| Key | Action |
| --- | --- |
| `F1` | Unstuck (sometimes police get in the way for road blocks, use this to get around them) |
| `F2` | Stats on/off |
| `F3` | Photo (spam this too many times in a row at your own peril) |
| `F4` | FPS counter |
| `F5` | U-turn |
| `F6` | Mod menu |
| `F10` | End ride (or hold `End` for 1 sec) |
| `F11` | Cycle cameras (1 to 8 to pick one) |
| `Page Up` / `Page Down` | Sim watts +/- 10 W |
| `Numpad +` / `Numpad -` | Workout intensity +/- 1% |
| `Numpad *` / `Numpad /` | Skip a step / go back a step |
| `Home` | ERG on/off |

## Important tips

- Most trainers only take one Bluetooth connection, so close other apps first.
- The bridge isn't code-signed, so Windows may warn you. Click More info, then Run anyway, I ain't spamming nobody with this mod.
- Something broken? Open an issue here or post in the Nexus Bugs tab with your version (menu > ABOUT) and attach `bridge-log.txt` and `ride-log.txt` from the mod folder.

## Main features

### Riding

- 26 routes, from flat loops to long climbs. Most work in reverse too. Many of the inclines in Night City are pretty extreme, so this is why I made the simulated grade lock so your trainer doesn't go into a death grind.
- Speed comes from your watts. Stop pedaling and you coast, like a real bike, dynamics are based on real world physics (speed, weight, crr, etc).
- Laps, drafting, named climb and sprint segments, and a record of your best lap.
- Set your FTP, weight, riding position and road surface. Maybe more detail than most need, but it's there if you want to tweak.

### Trainer and sensors

- Smart trainers over Bluetooth (FTMS). Resistance changes with the hills.
- HR straps, cadence sensors, power meters and CORE body temp.
- Color of power in top hud adjusts based on zones you are in, zones calculated based on the ftp you define in your settings.
- Core body sensor data shows bottom left, and color adjusts as you hit heat training zones.

### Workouts

- Structured workouts with ERG. Skip steps or nudge intensity mid-ride. Also added a masochist "back" feature to the workout controls, so you can always go back and do an interval again.
- intervals.icu sync: pulls your planned workouts, uploads finished rides, includes all data, including core sensor data.

### After the ride

- Every ride saved as FIT and JSON.
- Summary image at the end, plus ride photos.

### Extras

- Multiple cameras, including first person.
- Pick the time of day and weather.
- Gigs: short delivery runs for fixers, with rewards and badges. Experimental idea for some unique short training sessions.
- Lunatic mode: free ride, you steer, weapons allowed. Purely for fun. I haven't tested this fully, consider this very early preview feature. I will add steering support soon once I can test it myself.

## On the roadmap

- Race mode and group rides - there is group rides now (3 other bots), but it's super rough and provides little. But it's there...
- Power-ups
- NPC crowds on routes - some crack heads cheering you on from the sidelines.
- Strava upload (those goofballs don't make api access easy, dinosaur tech)
- Random start positions on routes (I dislike how every platform you always start from same place on routes).

## Requirements

- Cyberpunk 2077 v2.5 (Steam or GOG)
- A save past the prologue, or use the starter save
- Windows 10 (2004+) or 11 with Bluetooth LE
- Smart trainer recommended. HR, cadence and power sensors are optional.
- RED4ext, redscript, Cyber Engine Tweaks, ArchiveXL, TweakXL and Codeware. The setup exe installs any you're missing. Manual users, install these first.
- Optional: the Cycling.Native plugin (included) for a smoother camera, built for game version 2.5.

## Shout outs

Huge thanks to the people behind the frameworks this runs on:

- RED4ext by WopsS
- redscript by jac3km4
- Cyber Engine Tweaks by maximegmd and contributors
- ArchiveXL, TweakXL and Codeware by psiberx

## Licence

The mod is free to use; see `LICENSE.txt` in the downloads. Bundled frameworks keep their own licences.
