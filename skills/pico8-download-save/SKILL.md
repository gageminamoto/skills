---
name: pico8-download-save
description: Guide someone through getting PICO-8 or a PICO-8 game cartridge, opening it, and saving the file to a chosen folder on their computer.
metadata:
  short-description: Download and save PICO-8 files
---

# PICO-8 game making, downloads, and saving

Use this skill when someone needs help getting started with PICO-8, planning a small game, or downloading and saving a PICO-8 game cartridge. Keep the instructions matched to the user's operating system, goals, and available time.

Keep every reply short and use plain, everyday language. Give only the next useful step or a few small steps at a time. Avoid long explanations, jargon, and large lists.

## Help them shape a game

When the user wants to make a game, begin with a few focused questions. Ask what kind of game or feeling they want to create, what the player should do most of the time, and what timeframe they want to work within. If they already answered one of these, do not ask it again. Ask one question at a time when that makes the exchange easier to follow.

Help the user turn their idea into a small, playable version that fits the stated timeframe. Preserve the part of the idea they care about most, and suggest simplifying secondary features when needed. Break the work into short, concrete steps with a visible result at the end of each step. Put a playable core early in the plan, then leave room for testing, fixes, and polish. Use plain language, keep each reply digestible, and offer the next useful step instead of presenting an oversized production plan.

Make the plan fit the user's actual time commitment. If the timeframe is short or vague, ask how many sessions or minutes they can spend, or propose a small default scope and label it as an estimate. Avoid promising that a game can be completed in a precise duration. Check in as the project progresses and adjust scope when a task takes longer than expected.

## Clarify what they want

The Lexaloffle [Updates page](https://www.lexaloffle.com/games.php?page=updates) provides PICO-8 software downloads for customers. It says to log in or request a download link using the purchase email. It is not a page for downloading an individual game cartridge.

If the user does not own PICO-8 yet, ask if they are ready to get started. When they say yes, ask if they are ready to visit Lexaloffle and purchase a PICO-8 key. If they confirm, guide them to the official [PICO-8 page](https://www.lexaloffle.com/pico-8.php) and let them complete the purchase themselves. After they say they have purchased it or received their key, guide them through redeeming or accessing the download, then installing and starting PICO-8. Do not imply they need to buy a separate key for a game cartridge.

If their request does not make this clear, ask whether they want to download the PICO-8 application or a particular game cartridge. Ask which game if they mean a cartridge. Before any file download or save, ask which folder on their computer they want to use. If their operating system is unknown, ask whether they use Windows, macOS, or Linux.

## Guide the workflow

- Give one or two concrete steps at a time and wait for the user to report what they see before moving past sign-in, install prompts, or errors.
- For the PICO-8 application, direct them to the official Updates page. Explain the customer login or purchase-email requirement plainly. Use the download for their operating system and save it to the folder they chose. Then guide them through extracting or installing it and launching PICO-8 using the steps appropriate to that operating system.
- For a game, use its Lexaloffle game page and the available download/open option. Explain whether the result is a `.p8` or `.p8.png` cartridge and how to open it in the installed PICO-8 application. Do not imply that the Updates page itself contains game downloads.
- Before saving a cartridge, confirm its filename and the destination folder with the user. PICO-8's `SAVE name` writes to its current virtual-drive folder and adds `.p8`; it does not ask for an arbitrary host-computer folder. To find that folder, the user can enter `FOLDER` at the PICO-8 prompt. If they requested another computer folder, guide them through moving or copying the saved file there in the operating system's file manager.
- For a cartridge already available as a downloaded file, guide the user to save it directly in their chosen folder and open it in PICO-8, for example by dragging the file into the PICO-8 window where supported.
- Confirm the final file name and location with the user. Never claim that a download, installation, or save succeeded unless the user or available UI confirms it.

## Useful commands

At the PICO-8 prompt, `LOAD filename` loads a cartridge, `RUN` starts it, `SAVE filename` saves a `.p8` cartridge in the current PICO-8 folder, and `FOLDER` opens that folder in the host file manager. A loaded cartridge can also be run with Ctrl-R. Explain that PICO-8's folder is separate from any arbitrary folder the user may choose on their computer.

Refer to the [official PICO-8 manual](https://www.lexaloffle.com/dl/docs/pico-8_manual.html) if the user's cartridge format, save location, or controls require more detail.
