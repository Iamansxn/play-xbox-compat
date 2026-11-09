> [!WARNING]
> **Experimental compatibility branch:** this fork adds userscript matching and startup support for `play.xbox.com`. It is not yet verified to launch or stream games on the redesigned site. The new site uses a different frontend stack, so some Better xCloud UI features may not work until their hooks are adapted.
>
> Install only the build produced by the **play-xbox-compat** branch workflow. This test build intentionally has no automatic update URL; do not expect it to update from the upstream release.

## Build and test this fork

1. Open the [Actions tab](https://github.com/Iamansxn/play-xbox-compat/actions) and enable GitHub Actions for this fork if prompted.
2. Run **Build play.xbox.com compatibility test** manually, or push a commit to the `play-xbox-compat` branch.
3. Download the `better-xcloud-play-xbox-test` artifact from the completed workflow run.
4. Extract `better-xcloud.pretty.user.js` and install it in Tampermonkey or Violentmonkey.
5. Open `https://play.xbox.com/` and inspect the browser console and Network tab. Report whether the userscript loads, the game library renders, and a game reaches the streaming state.

The first test is expected to validate initialization only. API endpoints and stream negotiation are still handled by the upstream implementation and need verification against the new site.

---

<div align="center">
    <img src="https://raw.githubusercontent.com/redphx/better-xcloud/refs/heads/typescript/resources/logos/better-xcloud.png" width="256"/>  
    <h1>Better xCloud</h1>
    <!-- Latest Version Badge -->
    <a href="https://github.com/redphx/better-xcloud/releases"><img src="https://img.shields.io/github/v/release/redphx/better-xcloud?label=latest" alt="Latest version" /></a>
    <!-- Total Downloads Badge -->
    <a href="https://github.com/redphx/better-xcloud/releases"><img src="https://img.shields.io/github/downloads/redphx/better-xcloud/total?color=%23e15f2c" alt="Total downloads" /></a>
    <!-- Total Stars Badge -->
    <a href="https://github.com/redphx/better-xcloud/stargazers"><img src="https://img.shields.io/github/stars/redphx/better-xcloud?color=%23cca400" alt="Total stars" /></a>
</div>

### Improve Xbox Cloud Gaming (xCloud) experience on [xbox.com/play](https://www.xbox.com/play). It also allows you to use Remote Play on the xCloud website.  

> [!WARNING]
> I only provide Better xCloud on the official repos. Don't download it from anywhere else  
> Fake websites:
>   - betterxcloud.com
>   - betterxcloud.net

> [!IMPORTANT]  
> I only accept pull requests for:
> - Custom touch controls
> - Bug fixes
> AI Slop PRs will be ignored

**Supported platforms:**  
- Windows
- macOS
- Linux, SteamOS (including Steam Deck)
- Android, Android TV (including Meta Quest VR Headsets): [redphx/better-xcloud-android](https://github.com/redphx/better-xcloud-android)
- iOS, iPadOS

This script makes me spend more time with xCloud, and I hope the same thing happens to you.  
If you like this project please give it a 🌟. Thank you 🙏.

## How to install
Visit the [home page](https://better-xcloud.github.io) to know how to install Better xCloud on your device.

## Full documentations
- For the full details please visit: [**better-xcloud.github.io**](https://better-xcloud.github.io)  
- [Demo video](https://youtu.be/hyp69Jrb2sQ)

## ⚠️ UPDATE Nov 06

Better xCloud currently only works on the `xbox.com/play` website. If it redirects you to `play.xbox.com`, you can opt-out by:  

1. Log in to the `play.xbox.com` website
2. Press on the profile image at top-right, select `Exit preview`
3. Fill the dialog or press `Cancel` if you want
4. You will be redirected to `xbox.com/play`
5. If you're using Better xCloud Android app, make sure to force close it and open again (clear app cache if needed)

<img height="400" alt="image" src="https://github.com/user-attachments/assets/1b66be2f-3ece-46f4-85b7-e0721e03a383" />

I'm working on the newer version of Better xCloud for the new website.

⚠️ Please DO NOT report **Better xCloud**'s bugs on [/r/xcloud subreddit](https://reddit.com/r/xcloud/). Report bugs in [Issues](https://github.com/redphx/better-xcloud/issues) or [Telegram channel](https://t.me/betterxcloud) instead.

## Donation
If you think this project is useful and want to support future developments, please consider making a donate via [my Ko-fi page](https://ko-fi.com/redphx).  
Or you can give this project a star, that's also helpful.  
Thank you.  

## Translation  
Help translating **Better xCloud** to another languagues using [Crowdin](https://crowdin.com/project/better-xcloud).  
Use [this post](https://github.com/redphx/better-xcloud/discussions/131) for discussion. 

## Acknowledgements  
- The mouse controlling feature is heavily inspired by the "Mouse spinning" feature in [Yuzu emulator](https://github.com/yuzu-emu/yuzu-mainline)
- [n-thumann/xbox-cloud-server-selector](https://github.com/n-thumann/xbox-cloud-server-selector) for the idea of IPv6 feature
- Icons by [Phosphor Icons](https://phosphoricons.com)
- [PromptFont](https://shinmera.com/promptfont) by Yukari "Shinmera" Hafner

## Disclaimers  
- Use it at your own risk.
- This project is not affiliated with Xbox in any way. All Xbox logos/icons/trademarks are copyright of their respective owners.
