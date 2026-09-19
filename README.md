# Walkman Language / Destination Tool

A small Windows GUI for changing the region ("destination code") on Sony
NW/NWZ Walkman digital audio players — which is what actually controls how
many interface languages the player will let you choose from.

It's a friendly wrapper around the community `scsitool` command-line
utility: instead of typing commands, you get a window with buttons.

▶️ **Video walkthrough:** https://www.youtube.com/@samouch6347

## Why you'd want this

Sony ships different firmware "destinations" for different markets (Japan,
USA, Europe, China...), and each one unlocks a different set of interface
languages on the player. A Japan-region unit, for example, may only offer
Japanese. Setting the destination to Europe usually gives you the widest
language choice.

## Features

- Auto-detects the connected Walkman drive
- One click to check the current region, model, and storage capacity
- Change the destination/region (affects available interface languages)
- Built-in S77x-series mod support (for models the stock tool doesn't
  cover) — **beta/experimental**, use with extra caution
- Collapsible log panel if you want to see the raw tool output
- Interface available in English, Ukrainian, Spanish, French, Italian,
  German, Russian, and Chinese

## Download

Grab the latest `WalkmanLanguageTool.exe` from the
[Releases](../../releases) page. No installation needed — just run it.

## How to use

1. Connect your Walkman via USB.
2. Open `WalkmanLanguageTool.exe`.
3. Click **Check region, model & storage** to confirm the tool sees your
   player correctly.
4. Pick a region from the **Region** dropdown (Europe is usually the safest
   choice for the widest language selection).
5. Click **Apply region**.
6. On the player itself, go to **Settings -> Reset -> Reset all settings**.
   This step is required — the new language won't show up otherwise.

## ⚠️ Disclaimer

This changes a service area of your player's firmware. It's generally safe
and well documented by the community, but it's done **entirely at your own
risk**. The author is not responsible for any damage to your device.


## Credits

Built on top of the `scsitool-nwz` command-line utility from the Walkman
modding community. See the [Rockbox wiki](https://www.rockbox.org/wiki/SonyNWDestTool)
and the [head-fi.org](https://www.head-fi.org/) Sony Walkman threads for
background on destination codes.

## Support

If this saved you a trip to a repair shop or a new player, you can buy me
a coffee:

- Ko-fi: https://ko-fi.com/nick_w_w
- Card (Visa/Mastercard via Monobank): https://send.monobank.ua/jar/5wpJ7Xxpvo

## License

MIT
