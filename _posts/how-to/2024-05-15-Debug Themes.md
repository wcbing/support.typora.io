---
layout: post
title: Debug Themes / CSS
date: 2024-05-15
category: how-to
author: typora.io
tags: [style]
typora-root-url: ../../
typora-copy-images-to: ../../media/debug-themes
---

## macOS

For macOS ≥ 13.3 and Typora ≥ 1.9, you can debug. Typora theme CSS in following way:

1. **Enable Develop menu item in Safari** --- you must also have enabled Web Inspector in the Settings app under **Safari** > **Advanced** > **Web Inspector**. [Learn more about enabling Web Inspector…](https://webkit.org/web-inspector/enabling-web-inspector/)
2. Select **Safari** menu → **Develop** → [your device name] → **Typora** to open the DevTools.

<img src="/media/debug-themes/Screenshot 2024-05-15 at 18.31.36.png" alt="Screenshot 2024-05-15 at 18.31.36" style="zoom:50%;" />

<img src="/media/debug-themes/Screenshot 2024-05-15 at 18.32.38.png" alt="Screenshot 2024-05-15 at 18.32.38" style="zoom:50%;" />

For older macOS, you can enable debug mode from Typora preferences panel → General, restart Typora and then right click on Typora writing area and select *Inspect Element*.

## Windows / Linux

You could open DevTools from `View` -> `Toggle DevTools` menu item.

