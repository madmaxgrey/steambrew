---
order: 4
description: Questions asked frequently.
---

# FAQ

::: details Antivirus detections?

Due to the nature of how Millennium modifies Steam's interface, some antivirus programs may mistakenly flag it as suspicious. To significantly reduce these false positives, Millennium's releases are now officially code-signed on Windows with a certificate provided by the SignPath Foundation.

If any alerts do appear, they are almost certainly false positives. You can always verify the software's safety by running the files through VirusTotal. For complete peace of mind, we encourage you to compile, test, and audit Millennium's source code on GitHub. If you have further questions, you can always reach out to us in [Discord](https://steambrew.app/discord).

Remember, the best antivirus is a smart end-user!

:::

::: details Can I Get Banned?

No, in short, you will not get banned for using Millennium as it doesn't violate any of Steam's policies. With that said, Millennium, and any of its developers are not responsible for any of your actions, or the potential repercussions nonetheless. Learn more about MIT Licensing [here](https://github.com/SteamClientHomebrew/Millennium/blob/main/LICENSE.md)

:::

::: details Is Millennium against the Steam® Subscriber Agreement?

No, Millennium and all official plugins and themes do not violate Steam's Subscriber Agreement. While Steam strictly prohibits modifying, disassembling, and decompiling services and content distributed through Steam (such as games and applications), these restrictions do not apply to the Steam client software itself.

[Steam Subscriber Agreement](https://store.steampowered.com/subscriber_agreement/)

:::

::: details Is Millennium against the Steam® Privacy Policy?

No, Millennium does not store or log any form of user data and ensures that approved plugins do not store user data without consent.

:::

::: details Where does Millennium save data?

#### Windows

In your Steam folder:

- `user32.dll`
- `python311.dll`
- `millennium.dll`
- `ext/` - Millennium Internal Data
- `plugins/` - User Plugins
- `steamui/skins/` - User Themes

#### Linux

- `/usr/bin/steam` - Patched Steam Binary
- `/usr/lib/millennium/` - Millennium Core Files
- `/usr/share/millennium/` - Millennium Shims
- `~/.local/share/millennium/` - Millennium Skins and Plugins
- `~/.config/millennium/` - Millennium Configuration

:::

::: details How do I uninstall Millennium?

Refer to the [uninstaller guide](../parting-ways/uninstall.md). There you will find documentation on how to uninstall Millennium's components.
:::
