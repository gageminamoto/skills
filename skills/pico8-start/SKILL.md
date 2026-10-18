---
name: pico8-start
description: Guide someone through getting PICO-8 or a PICO-8 game cartridge, opening it, and saving the file to a chosen folder on their computer.
metadata:
  short-description: Download and save PICO-8 files
---

# PICO-8 game making, downloads, and saving

Use this skill when someone needs help getting started with PICO-8, planning a small game, or downloading and saving a PICO-8 game cartridge. Keep the instructions matched to the user's operating system, goals, and available time.

Keep every reply short and use plain, everyday language. Give only the next useful step or a few small steps at a time. Avoid long explanations, jargon, and large lists.

## Help them shape a game

When the user wants to make a game, ask what kind of game they have in mind and invite them to share the idea in chat. If they are unsure, ask them to name a game they know or like, or describe what they enjoy playing. If they still do not have an idea, offer a few simple choices. Once they have an idea, ask: “How much time do you have to make it: a few days, a few hours, or about 30 minutes?” Accept another timeframe if they give one. Keep this conversation short and do not ask again for information they already gave.

Help the user turn their idea into a small, playable version that fits the stated timeframe. Preserve the part of the idea they care about most, and suggest simplifying secondary features when needed. Break the work into short, concrete steps with a visible result at the end of each step. Put a playable core early in the plan, then leave room for testing, fixes, and polish. Use plain language, keep each reply digestible, and offer the next useful step instead of presenting an oversized production plan.

Make the plan fit the user's actual time commitment. If the timeframe is short or vague, ask how many sessions or minutes they can spend, or propose a small default scope and label it as an estimate. Avoid promising that a game can be completed in a precise duration. Check in as the project progresses and adjust scope when a task takes longer than expected.

## Clarify what they want

The Lexaloffle [Updates page](https://www.lexaloffle.com/games.php?page=updates) provides PICO-8 software downloads for customers. It says to log in or request a download link using the purchase email. It is not a page for downloading an individual game cartridge.

If it is unclear whether they own PICO-8, ask once. If they do not own it, explain briefly that it is paid software and ask whether they want to purchase a key. If yes, send them to the official [PICO-8 page](https://www.lexaloffle.com/pico-8.php) to complete payment themselves. Do not make a purchase or ask them to confirm readiness twice. Once they say they have a key, help access the download. Do not imply they need to buy a separate key for a game cartridge.

Before downloading, ask where they want the PICO-8 app or game files saved, unless they already named a folder. Ask if they already have a game idea and invite them to share it in the chat. Infer the operating system from available context when possible; ask only if it is needed to choose the right download.

## Guide the workflow

- Do the available setup work for the user with browser, file, and computer tools. Use the official Lexaloffle page, choose the right download for their operating system, save it to their chosen folder, and extract or launch it when tools allow. Do not make them perform steps the agent can complete.
- For the PICO-8 application, use the official Updates page. Explain the customer login or purchase-email requirement plainly. If sign-in, purchase, a license key, or an agreement requires the user's input, hand that step to them, then continue once they say it is done.
- Do not stop for a user check-in after every routine step. Ask only for the save folder, needed account or purchase action, or a decision the agent cannot make. If the agent cannot access the user's computer or browser, say so briefly and give the next simple step instead of implying the setup was done.
- For a game, use its Lexaloffle game page and the available download/open option. Explain whether the result is a `.p8` or `.p8.png` cartridge and how to open it in the installed PICO-8 application. Do not imply that the Updates page itself contains game downloads.
- Before saving a cartridge, use the folder they chose and confirm the filename only if it is unclear. PICO-8's `SAVE name` writes to its current virtual-drive folder and adds `.p8`; it does not ask for an arbitrary host-computer folder. Use `FOLDER` to open that folder, then move or copy the file to the chosen location if needed.
- For a cartridge already available as a downloaded file, guide the user to save it directly in their chosen folder and open it in PICO-8, for example by dragging the file into the PICO-8 window where supported.
- Confirm the final file name and location with the user. Never claim that a download, installation, or save succeeded unless the user or available UI confirms it.

## Useful commands

At the PICO-8 prompt, `LOAD filename` loads a cartridge, `RUN` starts it, `SAVE filename` saves a `.p8` cartridge in the current PICO-8 folder, and `FOLDER` opens that folder in the host file manager. A loaded cartridge can also be run with Ctrl-R. Explain that PICO-8's folder is separate from any arbitrary folder the user may choose on their computer.

Refer to the [official PICO-8 manual](https://www.lexaloffle.com/dl/docs/pico-8_manual.html) if the user's cartridge format, save location, or controls require more detail.
