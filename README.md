# Tour de Night City

A Zwift-style cycling ride through Night City, powered by your smart trainer and Cyberpunk 2077.

Got a smart trainer and bored of the usual virtual worlds and/or paying costly subscriptions? Tour de Night City puts you on a bike in Night City and hooks it up to your trainer, using your one time purchase of Cyberpunk 2077 as the engine.

Hit `F6` to open the mod console, pick a route and start pedaling. The bike steers itself and follows the road, so all you do is put out the watts. Hills change the resistance (quality checked and clean changes in inclines), workouts run in ERG, and every ride saves a FIT file (along with screenshots, final ride summary image) you can upload anywhere. Syncing to Intervals.icu is supported today on launch.

No trainer? You can still ride with simulated watts to preview the mod.

I'm a graphic designer, and this project is funded by my own company, [YouWorkForThem](https://www.youworkforthem.com), which sells fonts and stock graphics. If you're enjoying the mod, grabbing something there or sending it to a designer friend as a reference, helps a lot. 🙏

## Download

Get the files from the [latest release](https://github.com/Designgraphik/tour-de-night-city/releases/latest).

| File | What it is |
| --- | --- |
| Setup zip | The installer, and the recommended download. Unzip it and run the setup exe inside. |
| Manual zip | The mod files only: copy or extract them into your game folder. It does NOT include the six required frameworks, so install those first (or use the Setup zip, which installs them for you). |
| Starter save zip | Optional starter save. |

Optional, for the technically curious: `SHA256SUMS.txt` lists checksums to confirm your download is complete and untouched.

A Nexus Mods page is coming, just waiting on their approval. For now the downloads are here on GitHub.

## New to mods? Start here

- Download the Setup zip. It does everything: it installs the mod and the six frameworks it needs. The frameworks are small free helper mods that most Cyberpunk mods use.
- The setup finds your game by itself (Steam, GOG or Epic).
- Close the game before you run the setup.
- If Windows SmartScreen warns you, click More info, then Run anyway. The files aren't code-signed, I ain't spamming nobody with this mod.
- You need a save past the prologue, or tick "Add the starter save" in the setup.
- Only use the Manual zip if you already manage mods yourself.

## Installation instructions

### Setup exe (easiest)

1. Close the game.
2. Run the setup and follow along. It installs any missing frameworks and can add the starter save.
3. Start the game and load a save. The menu key is `F6`, set up automatically.

### Manual zip

1. This zip contains only Tour de Night City, not the six frameworks it needs. Install these first:
   - [RED4ext](https://github.com/wopss/RED4ext)
   - [redscript](https://github.com/jac3km4/redscript)
   - [Cyber Engine Tweaks](https://github.com/maximegmd/CyberEngineTweaks)
   - [ArchiveXL](https://github.com/psiberx/cp2077-archive-xl)
   - [TweakXL](https://github.com/psiberx/cp2077-tweak-xl)
   - [Codeware](https://github.com/psiberx/cp2077-codeware)
2. Close the game.
3. Right-click the zip, Properties, tick Unblock.
4. Extract into your game folder and merge.
5. Start the game and load a save. The menu key is `F6`, set up automatically.

Full steps are in `README-INSTALL.txt` inside the zip.

Default keys are set on the first start. If you already had a Cyber Engine Tweaks menu key, that key opens the menu. If another mod uses `F6`, Cyber Engine Tweaks asks you to pick a key.

### Starter save (optional)

If you are here mainly from a cycling community and have never played Cyberpunk 2077 (and finished the opening story), I added a save file you can load to get rolling right away. The setup can add one for you: a Nomad V, level 33, in free roam, with 6 riding outfits in the wardrobe. Manual users can grab it from the release downloads. It never overwrites your own saves.

## First ride

Do your first session as a route ride, before you try anything else. It works like Zwift and other platforms: the bike is locked to the road and steers itself, so all you do is pedal.

1. Start the game and load your save (starter save: Load Game > ManualSave-2077). Stand somewhere in the city, on foot.
2. Wake your sensors: pedal a few strokes to wake the trainer, and shake the HR and/or CORE sensor. Close Zwift or any other app connected to them. Most trainers only allow one Bluetooth connection.
3. Press `F6` to open the menu. On the DEVICES tab, connect your trainer and sensors (same as any other training platform).
4. On the RIDER tab, set your FTP (watts, default 200 W), your weight (rider, bike and gear, extra) and your riding position. FTP sets your power zones and the colors on the screen (and IF and TSS). Weight and position decide how fast you go for your watts, especially uphill. It all saves by itself.
5. On the RIDE tab, pick a route and start. Your watts set the speed. Stop pedaling and you coast.
6. To finish, press `F10` and confirm. The ride saves as a FIT file in `Documents\Tour de Night City\Activities`. Upload it anywhere, or sync to intervals.icu from the SHARING tab (or from the bridge app running behind the game in Windows). Getting off the bike only pauses, it doesn't end the ride.

### After your first ride

- Try WORKOUTS for structured workouts in ERG. Workouts can come from intervals.icu (see the next section).
- Once you're comfortable, try LUNATIC: a free ride where you steer. Just for fun, and still an early preview.
- No trainer? Use simulated watts (`Page Up` / `Page Down`) to try it out.

## Workouts and intervals.icu

Design and schedule your workouts in intervals.icu and they sync into the WORKOUTS tab, ready to ride in Night City. It's a great way to do your training in a nicer setting than a plain screen.

- Finished rides upload back to intervals.icu with all the data, including core sensor data.
- Coach: in F6 > WORKOUTS, the COACH option (Delamain or Off) decides whether Delamain texts you during workouts.
- ERG ease: in F6 > DEVICES, "ERG ease" (0 to 10 seconds) sets how gently the trainer fades from one interval target to the next. Most platforms don't let you adjust this.
- Tip: use a longer ease for long, steady intervals, and a short one for microbursts and other short sharp efforts so each effort hits right away.

## Controls (rebind in CET bindings)

| Key | Action |
| --- | --- |
| `F1` | Unstuck (sometimes police get in the way for road blocks, use this to get around them) |
| `F2` | Stats on/off |
| `F3` | Photo (spam this too many times in a row at your own peril) |
| `F4` | FPS counter |
| `F5` | U-turn |
| `F6` | Mod menu |
| `L` | New lap (ends the current lap, starts the next). Hold to hide or show the lap card. |
| `F10` | End ride (or hold `End` for 1 sec) |
| `F11` | Cycle cameras (1 to 8 to pick one) |
| `Page Up` / `Page Down` | Sim watts +/- 10 W |
| `Numpad +` / `Numpad -` | Workout intensity +/- 1% |
| `Numpad *` / `Numpad /` | Skip a step / go back a step |
| `Home` | ERG on/off |

## Important tips

- Something broken or need help? Open an issue here with your version (menu > ABOUT). The bridge's LOGS tab has a ZIP FOR SUPPORT button that saves all logs as one zip on your Desktop; attach that.

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
- Your intervals.icu workouts sync into the WORKOUTS tab. See "Workouts and intervals.icu" above.

### After the ride

- Every ride saved as FIT and JSON.
- Summary image at the end, plus ride photos.

### Extras

- Multiple cameras, including first person.
- Pick the time of day and weather.
- Gigs: short delivery runs for fixers, with rewards and badges. Experimental idea for some unique short training sessions.
- Lunatic mode: free ride, you steer, weapons allowed. Purely for fun. I haven't tested this fully, consider this very early preview feature. Controller support: pedal and the bike moves without holding W, and you steer with the stick. Elite Sterzo Smart steering works through the bridge's STEERING tab (beta, not tested on a real Sterzo yet). The game window must be active, because the bridge steers by pressing A and D.

## On the roadmap

- Race mode and group rides - there is group rides now (3 other bots), but it's super rough and provides little. But it's there...
- Power-ups
- NPC crowds on routes - some crack heads cheering you on from the sidelines.
- Strava upload (those goofballs don't make api access easy, dinosaur tech)
- Random start positions on routes (I dislike how every platform you always start from same place on routes).

## Requirements

- Cyberpunk 2077 v2.5 (Steam, GOG or Epic)
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
