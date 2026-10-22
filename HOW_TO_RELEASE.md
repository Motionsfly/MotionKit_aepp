# How to publish a MotionKit update

1. **Build the update** and upload the new files / installers to Gumroad (all three editions: AE+PP, AE, PP).
2. **Edit `update.json`** in this repo:
   - `latest` -> the new version, for example `"2.38.0"` (must match the version inside the plugin)
   - `date` -> release date (`YYYY-MM-DD`)
   - `message` -> one short line shown at the top of the update window
   - add a new block at the **top** of `history`:
     ```json
     {
       "version": "2.38.0",
       "date": "2026-11-01",
       "title": "Short title",
       "changes": [
         { "type": "new", "text": "What is new" },
         { "type": "fix", "text": "What was fixed" },
         { "type": "improved", "text": "What got better" }
       ]
     }
     ```
     `type` can be `new`, `fix`, `improved` or `removed`.
   - `critical: true` -> the update window opens by itself (use it only for important fixes). Optional `critical_text`.
   - `downloads` -> link per edition (`aepp`, `ae`, `pp`). Default: Gumroad.
3. **Add the same notes to `CHANGELOG.md`.**
4. **Commit to `main`.** Users see the update within a few minutes (the plugin checks on start and every 6 hours; "Check for updates" in Settings > About checks right away).

### Optional: one time announcement
```json
"announcement": { "id": "black-friday-2026", "title": "Black Friday", "text": "50% off all Motionsfly plugins", "url": "https://officialmotionsfly.gumroad.com", "button": "Open store" }
```
Each `id` is shown once per user. Set it back to `null` to remove it.

### Check the JSON before you commit
Paste `update.json` into https://jsonlint.com - a broken JSON means the plugin cannot read the feed.
