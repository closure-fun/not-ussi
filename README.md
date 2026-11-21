> [!NOTE]
> Rehosted at https://github.com/closure-fun/not-ussi on 2026-11-21 after the `luau` organization went away. This copy keeps the AGPL-3.0 license, the credit string, and the original authorship notices. `saveinstance.luau` loads from this repository, including the modules in `SomeHub/`.

# Loadstring

```lua
local Params = {
 RepoURL = "https://raw.githubusercontent.com/closure-fun/not-ussi/main/",
 SSI = "saveinstance",
}
local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
local Options = {} -- Documentation here https://github.com/closure-fun/not-ussi
synsaveinstance(Options)
```

# Support

Support the original developers' work, as they've made a huge impact on the community it has been a part of.

[![Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/M4M1JNH5G)

Ko-fi: https://ko-fi.com/M4M1JNH5G

Discord: https://discord.gg/wx4ThpAsmw

# Acknowledgments
> [!IMPORTANT]
> This document is based largely on the efforts of [@Anaminus] & [@Dekkonot], authors of the [Roblox Format Specifications]. Additional
> resources include:
>
> - [Syngp Synapse X Source code 2019][Synapse X Source 2019] for base saveinstance code (extended by [@mblouka] & [@Acrillis])
> - [Moon/LorekeeperZinnia][@LorekeeperZinnia] for being the original creator of saveinstance that was used in Synapse X, Elysian and many others. As well as being an inspiration for this project.
> - [Rojo Rbx Dom Xml] for being a fallback documentation in case something wasn't clear in the [Roblox Format Specifications]
> - [Roblox File Format] for a list of redirects of old/deprecated xml properties that still use the old tag values
> - [Roblox Client Tracker] for an extended & close to full JSON Api Dump (with hidden properties & default values)

\*\*\* View source code of this file for more credits

[@Acrillis]: https://github.com/Acrillis
[@Anaminus]: https://github.com/Anaminus
[@Dekkonot]: https://github.com/Dekkonot
[@mblouka]: https://github.com/mblouka
[@LorekeeperZinnia]: https://github.com/LorekeeperZinnia
[Rojo Rbx Dom Xml]: https://github.com/rojo-rbx/rbx-dom/blob/master/docs/xml.md
[Roblox Client Tracker]: https://github.com/MaximumADHD/Roblox-Client-Tracker
[Roblox File Format]: https://github.com/MaximumADHD/Roblox-File-Format
[Roblox Format Specifications]: https://github.com/RobloxAPI/spec/
[Synapse X Source 2019]: https://github.com/Acrillis/SynapseX
