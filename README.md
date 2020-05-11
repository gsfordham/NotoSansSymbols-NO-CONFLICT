# NotoSansSymbols-NO-CONFLICT
📃🖊🍵 Stripped and combined version of "Noto Sans Symbols -- Regular" and "Noto Sans Symbols2" fonts, using FontForge, to remove 🗑 conflicting symbols with "Noto Color Emoji"

# What It's About ℹ
💭❤ I like my color emoji, and I'm sure others do, too. I also use GNU+Linux, and some fonts seem to override each other. However, some of said fonts **ALSO** contain numerous non-emoji symbols that cannot otherwise be used/seen.

# UPDATES ❗
1) **2020-May-11** _Realized some fonts were overridden by ANOTHER font series, so I disabled those, copied the differing glyphs into the same FontForge directory, and then weeded through the emoji best I could -- seemed to only be a few tens of new ones_
1) **2020-May-11** _IMPORTANT: RENAMED REPO_

# INSTALLATION (For Linux 🐧)
## No, I will not explain Windows, because the conflicts are probably different, and I don't use Windows, anymore
## No, I will not explain Mac, either, because I will **NOT** buy Apple®'s price-skimming exorbitantly marked-up trash boxes
1) Go to your fonts manager (something like ``systemsettings5``, if on KDE [or if you use that to manage these types of settings, anyway, like I do])
1) **DISABLE OTHER EMOJI AND SYMBOLS FONTS, SO THEY DO NOT INTERFERE**
1) Select whatever option allows you to install the font from a file -- regardless of if you use KDE, I still have to use ``systemsettings5`` as my example, b/c I use that to manage fonts, among a few other things, and it's simply "Install from file" under the "Font Management" section, so I actually _HAVE_ an example for y'all
1) Select ***NotoSymbols-FULL-NO-CONFLICT.ttf***
1) If you have not already installed "Noto Sans Color Emoji", you can also install that from the file ***NotoColorEmoji.ttf*** right next to it

# NOTE
💡 If you have already installed Noto fonts, you will need to disable the **ENTIRE** "Noto Sans Symbols" group (Regular, Black, Thin, [..]) AND the "Noto Sans Symbols2" group/font (I'm not sure if any other distros have more than one version of this, but I actually _manually_ installed it on mine)

# What to Expect
🤔 I will occasionally come back to this, either on request (someone says I missed one), or if I happen to notice one I missed.


⌚ *Don't really expect it to be updated often, though -- I'm just trying to expunge glyphs that will override the color emoji. I do not see it as "likely" or even "probable" there are many people who will notice if a couple color emoji are added, that are being overridden.*\*

# How YOU Can Help
👀 \*If you ARE, however, one of those people, please list any such Unicode code points as an issue, and I will get to it. Unicode code points are the things that look like: "U+1F32A" (in this case, that's a tornado 🌪) -- you can find such code points on several sites, one of the easiest to use being https://emojipedia.org/, which allows you to look it up by name (e.g. "fork", "cookie").


😵 Being that there's literally hundreds of thousands of symbols, I STRONGLY request you give me the code point and not just a word like "potato" or "red circle", b/c FontForge **DOES** let me search for code points, so I can find it that way w/o digging for God knows how long...