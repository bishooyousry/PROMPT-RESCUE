# PROMPT RESCUE: The AI Emergency Room — Skills Bank | GitHub Pages

One file (`index.html`), no build, no keys, no backend. English / العربية (RTL). Target: 8–10 minutes, individual.

## Publish (GitHub Pages)
1. Create a **public** repo. Upload `index.html` and `.nojekyll` to the root.
2. Settings → Pages → Deploy from branch `main` / root. Wait ~1 minute.
3. Open `https://<user>.github.io/<repo>/` → **Trainer Dashboard** → PIN `2026`.
4. Always open the published link (not the file from your computer, not a preview window).

## The five phases
1. **System failure** — the weak prompt “Write a report.” goes to a (simulated) AI; alarm, glitch, flatline.
2. **Diagnostic scan** — scan 6 sensors (Context, Role, Action, Format, Tone + a false-alarm “Polite words”), then file a diagnosis: OK / WEAK / MISSING per sensor.
3. **Repair operation** — (a) black out private customer data in a sample sheet (name, account, phone) while keeping business numbers readable; (b) rewrite the prompt in an editor with a live **prompt health** meter, five ECG vitals, repair instruments (labels + the AI's question), an “attach clean data” tool, and a stability test.
4. **Before vs after** — original vs rewritten prompt, health and CRAFT parts side by side; a clearly labelled **simulated** demonstration; copy buttons for ChatGPT / Copilot / Gemini; real-test self-report; reflection.
5. **Rescue complete** — name, diagnostic accuracy, repair completion, final prompt, hints, coins, points, rank; leaderboard when the trainer reveals it.

## Trainer
5-character session code (auto). **+ New session** (up to 6 at once), **Reset** (new code), **Close**, session name, copy EN/AR link, **Projector view**, live table (phase, diagnosis ✓/✗ per sensor, health, hints, coins, score, progress), expandable rows (diagnosis vs correct, data-safety result, final prompt with CRAFT parts, reflection, real-test result), **Debrief panel** (first-filing accuracy per sensor + CRAFT parts present in final prompts), Reveal/Hide leaderboard, CSV export, backup import.

## Scoring (all rule-based; the player sees every rule)
| Part | Points |
|---|---|
| Diagnosis | 20 × correct sensors (6) = 120. First filing counts; a paid hint fills in a sensor |
| Data safety | +15 per private item hidden (4), −15 per business number hidden by mistake → 0–60. Sealing is final |
| Repair | 30 × CRAFT parts present (150) + 10 × key numbers included (max 3 = 30) + 20 reader mentioned + 20 safe prompt = 220 |
Max **400**. Coins: 250 at start, hint = 50 (max 5: scan 2, data 1, repair 2). Coins break ties. *Repair completion / prompt health* = 20% per CRAFT part present (Action counts 10% if there is a verb but the task is vague, so “Write a report.” = 10%). Ranks: ≥330 Chief Prompt Surgeon · ≥250 Prompt Doctor · ≥150 Resident · else Intern.

## Honest limits
- **The AI answers in the game are pre-written and labelled as simulated.** The game never calls a real AI model.
- **The checks are keyword rules**, not an AI. They measure completeness (is there a role? a format? the data?), not writing quality or meaning. A prompt can pass and still be weak; the real test is how an AI tool answers.
- **Not yet tested on real ntfy.sh or across real devices.** It was tested in a headless browser against a local relay that imitates ntfy (SSE, polling, retries, storage blocked, Arabic, mobile viewport, 61 checks). Run the two-device checklist before a live class.
- ntfy.sh free limits are per IP (publish limits, ~30 live streams). Players open the live stream from the “before vs after” phase on. Keep backup/import as the safety net.
- The `2026` PIN only hides the interface. The relay is public: players' prompts and reflections travel through it. All data in the game is fictional; tell participants never to paste confidential data.

## Two-device test checklist
1. Laptop: published link → Trainer Dashboard → PIN 2026. Note the 5-character code and `● LIVE`.
2. Phone (mobile data or another Wi-Fi): open the player link (or type the code) → name → **Enter the ER**.
3. Laptop: the player appears in seconds (toast + sound).
4. Phone: send the weak prompt, scan all sensors (try one wrong status and one hint), file the diagnosis. Laptop: phase, ✓/✗ chips and score update.
5. Phone: black out the private data (try over-redacting one number), seal. Edit the prompt, use an instrument, attach clean data, run the stability test, discharge.
6. Phone: show the demonstration, choose the real-test result, write the reflection, finish. Laptop: ✅ rescued; expand the row to read the diagnosis, data-safety result, final prompt, reflection.
7. Laptop: **Reveal leaderboard** → opens by itself on the phone; **Hide** closes it. Projector view shows the same.
8. Switch language on both (العربية / English); check RTL and that the prompt still scores.
9. Refresh the phone mid-mission → **Resume rescue** continues where it stopped.
10. Laptop: **Reset session** → new code. Switch the phone offline for one step: retry message appears; download the backup and import it on the laptop.
11. Check Sound ON/OFF and the page with “reduce motion” enabled on the device.
