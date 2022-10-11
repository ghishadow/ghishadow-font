# Ghishadow Fonts
**Ghishadow Mono** & **Ghishadow Sans** are custom builds of [Iosevka](https://github.com/be5invis/Iosevka) liscensed under the SIL Open Font License, Version 1.1.

You can read the license here: [README.md](https://github.com/ghishadow/ghishadow-font/blob/master/LICENSE.md).


## Screenshot

![image](https://user-images.githubusercontent.com/9583775/180100813-828a1274-15db-4708-9af8-3f9dc5354e12.png)

> Editor: [Lapce](https://lapce.dev/) Theme: [Catppuccin theme](https://github.com/ghishadow/lapce-catppuccin)

## Building Ghishadow Mono

Custom configurations are set up in `private-build-plans.toml`.

1. Install node modules with `npm install`
2. Run `npm run build -- contents::ghishadow-mono` to build the font.
3. Output will be in `/dist`
Don't check the `/dist` folder into the repo!
=======
<!-- BEGIN Section-OT-Ligation-Tags-1 -->
<!-- THIS SECTION IS AUTOMATICALLY GENERATED. DO NOT EDIT. -->

<table>
<tr>
<td><code>calt off</td>
<td>Ligation Off</td>
</tr>
<tr>
<td colspan="2"><img src="images/ligset-calt-0.light.svg#gh-light-mode-only"/><img src="images/ligset-calt-0.dark.svg#gh-dark-mode-only"/></td>
</tr>
<tr>
<td><code>calt</code></td>
<td>Default setting in text editors</td>
</tr>
<tr>
<td colspan="2"><img src="images/ligset-calt-1.light.svg#gh-light-mode-only"/><img src="images/ligset-calt-1.dark.svg#gh-dark-mode-only"/></td>
</tr>
<tr>
<td><code>dlig</code></td>
<td>Discretionary ligatures</td>
</tr>
<tr>
<td colspan="2"><img src="images/ligset-dlig-1.light.svg#gh-light-mode-only"/><img src="images/ligset-dlig-1.dark.svg#gh-dark-mode-only"/></td>
</tr>
</table>

<!-- END Section-OT-Ligation-Tags-1 -->

Iosevka supports Language-Specific Ligations, which is the ligation set enabled only under certain languages. These ligation sets are assigned to custom feature tags. To use them, you need to turn **off** `calt` and enable the corresponded feature. The feature list is:

<table><tr><td><h2><a href="doc/language-specific-ligation-sets.md">View list of language-specific ligations.</a></h2></td></tr></table>

Please note that, due to the complex interactions when forming ligations, cherry-picking ligation groups will require a custom Iosevka build. The instructions could be seen below.

## Building from Source

<table><tr><td><h2><a href="doc/custom-build.md">Read instructions.</a></h2></td></tr></table>

## For Chinese and Japanese users...

→ [Sarasa Gothic](https://github.com/be5invis/Sarasa-Gothic).

## Mirrors

- TUNA (CN): https://mirrors.tuna.tsinghua.edu.cn/github-release/be5invis/Iosevka
- NJU (CN): https://mirrors.nju.edu.cn/github-release/be5invis/Iosevka
---

![Family Matrix](images/matrix.light.svg#gh-light-mode-only)![Family Matrix](images/matrix.dark.svg#gh-dark-mode-only)
