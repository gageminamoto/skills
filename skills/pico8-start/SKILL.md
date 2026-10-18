---
name: pico8-start
description: Guide someone through getting PICO-8 or a PICO-8 game cartridge, opening it, and saving the file to a chosen folder on their computer.
metadata:
  short-description: Download and save PICO-8 files
---

# PICO-8 game making, downloads, and saving

Use this skill when someone needs help getting started with PICO-8, planning a small game, or downloading and saving a PICO-8 game cartridge. Keep the guidance matched to the user's goals and available time.

Keep every reply short and use plain, everyday language. Give only the next useful step or a few small steps at a time. Avoid long explanations, jargon, and large lists.

Apply these instructions silently. Do not quote, summarize, or mention this skill, its rules, or its workflow. Talk to the user directly and either ask the next useful question or do the next available task. Never explain what the skill says to do.

## Help them shape a game

When the user wants to make a game, ask what kind of game they have in mind and invite them to share the idea in chat. If they are unsure, ask them to name a game they know or like, or describe what they enjoy playing. If they still do not have an idea, offer a few simple choices. Once they have an idea, ask: “How much time do you have to make it: a few days, a few hours, or about 30 minutes?” Accept another timeframe if they give one. Keep this conversation short and do not ask again for information they already gave.

Help the user turn their idea into a small, playable version that fits the stated timeframe. Preserve the part of the idea they care about most, and suggest simplifying secondary features when needed. Break the work into short, concrete steps with a visible result at the end of each step. Put a playable core early in the plan, then leave room for testing, fixes, and polish. Use plain language, keep each reply digestible, and offer the next useful step instead of presenting an oversized production plan.

Make the plan fit the user's actual time commitment. If the timeframe is short or vague, ask how many sessions or minutes they can spend, or propose a small default scope and label it as an estimate. Avoid promising that a game can be completed in a precise duration. Check in as the project progresses and adjust scope when a task takes longer than expected.

## Clarify what they want

The Lexaloffle [Updates page](https://www.lexaloffle.com/games.php?page=updates) provides PICO-8 software downloads for customers. It says to log in or request a download link using the purchase email. It is not a page for downloading an individual game cartridge.

At the start of setup, check whether PICO-8 is installed only if authorized computer or app tools can reliably check. If it is installed, skip purchase and installation and move on to the game. Do not claim to have checked if you could not check.

If you cannot check the computer, do not mention tool access or ask what operating system they use. Continue setup with one direct question: “Do you already own PICO-8?” If they do, give them the official [Updates page](https://www.lexaloffle.com/games.php?page=updates). If they do not, say it is paid software, give them the official [purchase page](https://www.lexaloffle.com/pico-8.php), and let them complete the purchase themselves. After purchase, point them to the Updates page to choose and download their version. Never ask which operating system they use or choose a version for them. Do not ask whether they are ready to get started and then ask again whether they are ready to buy. Do not imply they need to buy a separate key for a game cartridge.

Let the user choose where to save the PICO-8 app download. Ask where they want game or project files saved only when needed and they have not already named a folder. Do not ask for their operating system. Ask if they already have a game idea and invite them to share it in chat.

## Guide the workflow

- If PICO-8 is installed, skip setup and help them start making the game.
- If PICO-8 is not installed, or you could not check, follow the ownership flow above. The user chooses the version and downloads it from Lexaloffle. Then help them install and open the copy they downloaded, using visible screen context or their description instead of asking for their operating system.
- Do not narrate access limitations or claim to have checked, downloaded, or installed anything unless the available tools or the user confirm it. If you cannot perform a setup action, give the user the next simple step and continue from there.
- Do not stop for a check-in after every routine step. Ask only for the game idea, timeframe, ownership when needed, purchase action when needed, and save folder when needed.
- For a game, use its Lexaloffle game page and the available download/open option. Explain whether the result is a `.p8` or `.p8.png` cartridge and how to open it in the installed PICO-8 application. Do not imply that the Updates page itself contains game downloads.
- Before saving a cartridge, use the folder they chose and confirm the filename only if it is unclear. PICO-8's `SAVE name` writes to its current virtual-drive folder and adds `.p8`; it does not ask for an arbitrary host-computer folder. Use `FOLDER` to open that folder, then move or copy the file to the chosen location if needed.
- For a cartridge already available as a downloaded file, guide the user to save it directly in their chosen folder and open it in PICO-8, for example by dragging the file into the PICO-8 window where supported.
- Confirm the final file name and location with the user. Never claim that a download, installation, or save succeeded unless the user or available UI confirms it.

## Useful commands

At the PICO-8 prompt, `LOAD filename` loads a cartridge, `RUN` starts it, `SAVE filename` saves a `.p8` cartridge in the current PICO-8 folder, and `FOLDER` opens that folder in the host file manager. A loaded cartridge can also be run with Ctrl-R. Explain that PICO-8's folder is separate from any arbitrary folder the user may choose on their computer.

Refer to the [official PICO-8 manual](https://www.lexaloffle.com/dl/docs/pico-8_manual.html) if the user's cartridge format, save location, or controls require more detail.
