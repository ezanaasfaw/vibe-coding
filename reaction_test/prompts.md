# Project: Reaction Test

> - **Files:** reaction_test.html
> - **Dates:** 2026-11-04 → 2026-11-04
> - **Defaults:** Claude (claude.ai chat) · Sonnet 5.5
> - **Status:** prototype
> - **Use:** none yet
> - **Reusability:** artifact low · prompt pattern high
> - **Tags:** single-file-html, game, localStorage
> - **Takeaway:** Worked on the first try from a short, specific prompt.
> - **Story value:** none
> - **Surprises:** The app idea was chosen by me. It worked with no fixes needed.

# Prompt 1 (build the first version):

> - **Tool:** Claude (claude.ai chat) · Sonnet 5.5 · 2026-11-04
> - **Session:** fresh · attached: none
> - **Verified:** human-tested
> - **Human edits:** none

Build a single-file HTML reaction time game. A big pad starts blue; I click it, it turns red, and after a random 1.5 to 4 seconds it turns green. I click as fast as I can and it shows my time in milliseconds. If I click while it's red, tell me I was too soon. Show my last time, my average of the last five, and my all-time best, and remember my best in the browser. No external libraries.

## Output 1:

I built the Reaction Test app based on your prompt. I haven't run it myself, so you'll need to test it to make sure everything works correctly.
- Reaction Test (reaction_test) is a single-file HTML game that measures how quickly you react to a color change.
- Game Mechanics: The pad starts blue. When you click it, it turns red. After a random delay of 1.5 to 4 seconds, it turns green. Click as quickly as possible to measure your reaction time in milliseconds.
- Early Click Detection: If you click while the pad is still red, the game tells you that you clicked too soon.
- Performance Tracking: The app displays your last reaction time, your average reaction time over the last five successful attempts, and your all-time best.
- Best Score Storage: Your best reaction time is saved in the browser, so it remains available when you reopen the game.
- Design: The interface is simple and interactive, with a large color-changing pad and clearly displayed results.
Steps from here:
1. Unzip. Download reaction_test.zip, right-click it, and choose Extract All. You'll get a folder containing the HTML file and a prompts.md file.
2. Move it in. Drag the reaction_test folder into your vibe-coding folder.
3. Test the app yourself. Double-click the HTML file to open it in your browser and try the following:
   - Start the game: Click the blue pad and check that it turns red.
   - Random delay: Wait for the pad to turn green after 1.5 to 4 seconds.
   - Reaction time: Click the green pad as quickly as possible and verify that your time appears in milliseconds.
   - Early click: Start another round and click while the pad is red. Check that the game displays a "Too Soon" message.
   - Last time: Complete another round and verify that your most recent reaction time updates.
   - Average time: Play at least five rounds and check that the average reflects your last five successful attempts.
   - All-time best: Try to beat your fastest reaction time and verify that your best score updates.
   - Score storage: Refresh the browser and check that your all-time best is still saved.
Note: The game uses browser storage to remember your best score. Your last time and average may reset when you refresh the page, but your all-time best should remain saved.