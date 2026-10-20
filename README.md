# Getting started with MyCustom
Please download the respective newest version of the application. All versions of the program are listed below.
## 1. Install

1. Install BetterDiscord from betterdiscord.app.
2. Download **MyCustom.plugin.js** (it's in the zip).
3. In Discord, go to User Settings → BetterDiscord → Plugins → **Open Plugins Folder**, and drop the file in. 
4. Switch **MyCustom** on.
-# Upgrading from Customizant? Delete the old Customizant.plugin.js first. Your emojis, fonts and settings carry over.
(Stuck? Check https://www.youtube.com/watch?v=opcJOPKWJb8 (skip to 1:10))

## 2. Send your first message
1. Type `(wave/hello everyone)` and press **Enter**.
2. The plugin turns it into an animated image and puts it in your upload tray.
3. Press **Enter** again to send it.
Messages without effects are sent normally, as plain text. Add `/cz` to turn a message into an image anyway.

## 3. How the codes work
- Effect: `(wave/text)`
- Color: `(#ff0000/text)`
- Stack as many as you like, with the text always last: `(#ff0000/wave/glow/text)`
- Nest them: `(wave/hi (shake/there))`
- Any bracket works: `()` `[]` `{}` `<>`
- The long form works too: `(wave)text(/wave)`
- Want a symbol to stay as text? Put a backslash in front: `\(wave/text)`
- No codes: select text, right-click the message box → **MyCustom** (Effects, Color, Gradient, Font, Whole message)
## 4. Effects
- `(rb/text)` or `:two words:` rainbow
- `(wave/text)` letters ripple up and down
- `(shake/text)` letters jitter
- `(bounce/text)` letters hop one by one
- `(glow/text)` pulsing glow
- `(pulse/text)` fades in and out
- `(glitch/text)` RGB glitches
- `(spin/text)` each letter spins, one after another
- `(jelly/text)` squish and stretch
- `(drunk/text)` letters sway and stumble
- `(scramble/text)` hacker-style decode
- `(ghost/text)` floats with faded echoes
- `(swing/text)` eased swinging
- `(bop/text)` headbop, squashes on every beat (75 BPM). Set the speed: `(bop=120/text)`
- `(bill/text)` billboard, that part scrolls in its own window. `(bilr/…)` right, `(bilu/…)` up, `(bild/…)` down. Stack them: `(bill/bilu/text)`

## 5. Colors
- Any hex color: `(#ff0000/text)`
- Gradient, as many colors as you like: `(#ff0000>#ffd23f>#0000ff/text)`
- Or: `(gradient(#ff0000/#0000ff)text)`
## 6. Whole message
Put these anywhere in your message:
- `/nudge` MSN-style nudge, shakes hard once, then stays still
- `/shake` everything shakes
- `/rb` `/wave` `/swing` `/bop` rainbow, wave, swing or headbop everything
- `/spin` `/jelly` `/drunk` `/scramble` `/ghost` the odd ones, for everything
- `/type` typewriter
- `/billboard` or `/bill` scrolls left, `/bilr` right, `/bilu` up, `/bild` down
  - Stack them: `/bill /bilu` diagonal, `/bill /bilr` back and forth, `/bilu /bild` bobs up and down
- `/cz` makes an image even with no effects
Combine as many as you like: `/shake /rb`

## 7. Make it yours
In plugin settings ⚙️:
- **My emojis:** add a picture, then type `.name.` anywhere, in any server or DM. Animated GIFs keep moving.
- **My fonts:** add a font, then use `(fonta/text)`. It goes from fonta to fontb … fontz, and then fontaa, fontab and so on.
- **Loop length** and **Max width** (lower it if your messages look small).

## 8. Also works
- Discord formatting: **bold**, *italic*, __underline__, ~~strike~~, `code`, # headings, -# subtext, > quotes, lists
- Normal emojis and server emojis (animated too)
- A message with only emojis becomes big jumbo emojis
