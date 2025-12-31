# wPLACE-bot

A browser script to automate painting images on [wplace.live](https://wplace.live).

> **Note:** This is a modified version of an existing project. I tweaked the code, improved the UI, and added new features to make it work better for my own use.

## Features
*   **Image Support:** Upload PNG or JPEG images directly.
*   **Smart Color Matching:** Automatically picks the closest available color from the site palette.
*   **Painting Strategies:** Choose how to paint: Linear, Random, or Edges-first (good for outlines).
*   **Save System:** Saves your progress locally or to a file, so you can refresh the page and continue later.
*   **Multi-Language:** Supports EN, PT, VI, and FR.

## Installation (Easy Way)
You can run this bot with a single click using a bookmarklet:

1.  Create a new bookmark in your browser.
2.  Name it **"Start Bot"**.
3.  In the **URL** field, paste this code:
    ```javascript
    javascript:(async()=>{const r=await fetch('https://raw.githubusercontent.com/Tunar-ssp/wPLACE-bot/main/Auto-Image.js');const c=await r.text();eval(c);})()
    ```
4.  Go to [wplace.live](https://wplace.live), click the bookmark, and the bot will appear.

## Manual Usage
1.  Copy the code from `Auto-Image.js`.
2.  Go to [wplace.live](https://wplace.live).
3.  Open the browser console (`F12`).
4.  Paste the code and press **Enter**.

## Tips
*   **CAPTCHA:** You need to paint **one pixel manually** after selecting the position. This lets the bot capture the token it needs to run.
*   **Color Palette:** Always open the color palette on the website before starting the bot.
*   **Speed:** You can adjust the painting speed in the settings.
