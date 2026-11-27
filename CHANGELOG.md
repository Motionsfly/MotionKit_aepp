# MotionKit - Change log

Every MotionKit (After Effects + Premiere Pro) release. **Update:** open your [Gumroad library](https://app.gumroad.com/library), download the new zip and run the installer again - settings and license stay.

## v2.59.2 - 2026-11-27 - Photoshop fixes: shapes on any resolution, vector icons, guides & mockups
- **Fix:** Photoshop: shapes from the Create tab and the Elements tab are the right size and in the right place on 300 ppi (and any non-72 ppi) documents
- **Fix:** Photoshop: safe-zone guides, device mockups and PNG icons are placed pixel for pixel on any document resolution
- **New:** Photoshop: Icons tab > Shape makes real editable vector shape layers (fill and outline icons, grouped) - if Photoshop refuses, the PNG is added instead
- **Fix:** Photoshop: New document with black background is really black; Social sizes keeps your background colour; Layers to PNG exports hidden layers too
- **Improved:** Photoshop: Safe Guide Remove also finds guides inside groups; Editor > Media button reads 'Add to document'

## v2.59.1 - 2026-11-27 - Photoshop Color Studio fix, AI Mode + Elements in Photoshop, comment automation
- **Fix:** Photoshop: Color Studio now works on every layer type - text, shape, pixel, smart object, fill layers, the locked Background and locked layers (it unlocks what it must, turns layer effects on, and the panel reloads its Photoshop script after an update, so no 'Unknown color tool')
- **New:** Photoshop: AI Mode tab with Direct Chat, BG Remove, AI Enhancer and Create Image - chat edits run as Photoshop scripts on your document (one Undo), generated images go in as layers
- **New:** Photoshop: Elements tab - 349 premade editable elements in 9 groups (Sale & Badges, Buttons, Arrows, Icons, Social, Labels, Frames, Posters, Backgrounds), each in several colour styles; built as a group of vector shape layers, live text and layer styles
- **New:** Elements > Automation: 14 comment automation animations - reel and YouTube comment -> auto reply -> DM in a phone mockup, comment flood with auto replies, comment keyword -> DM, DM inbox auto replies (dark, light, purple, green)
- **Improved:** Photoshop: API Keys section is visible in Settings so AI Mode keys can be added

## v2.59.0 - 2026-11-27 - Photoshop round trip, Color Studio, Automation elements, Cursor effects
- **New:** After Effects: one Photoshop button in the Quick tab (next to Snapshot, Import, Export) - the comp at the playhead goes to Photoshop as editable layers: text = editable text, solids and simple shapes = editable shape layers, images = Smart Objects, drop shadow / glow / stroke / colour overlay = editable layer styles
- **New:** Photoshop: Send to After Effects button (Layers tab) - the document comes into After Effects as an editable comp
- **New:** Photoshop: Color Studio - solid or gradient Color Overlay, gradient / solid Stroke, fill layers, 18 colours, 16 gradients, blend mode, opacity, angle, scale, reverse - on every selected layer
- **New:** Photoshop: Image Download - paste links from Google Images, Instagram, Pinterest, X, Reddit, Unsplash, Pexels or any website; images only, straight into Photoshop
- **New:** Elements: new Automation tab - 49 animations (workflow nodes, IF branches, checklists, CI/CD, gears, toasts, email, schedule, API, data sync, switch, counters, bots, conveyor)
- **New:** Theme: Cursor effects - 14 animations that follow the mouse in the panel (glow, ring, sparkles, comet, ribbon, bubbles, embers, snow, confetti, pixels, hearts, ripples, orbit, electric) with On / Off, amount, size and colour
- **New:** Guides: "My profile" - Reels, TikTok, Shorts, Stories, YouTube and Pinterest guides show the Motionsfly profile (avatar, name, verified badge, likes, comments, caption, audio)
- **Improved:** Captions upgraded to CaptionKit 2.3: every language gets a font that has its letters, right-to-left languages, better offline Whisper on Mac, shared API key vault
- **Fix:** Comp Saver / Library (AE + Premiere): the category row no longer lists every sub-folder - only folders with saved items, the rest in a Folders menu
- **Improved:** Photoshop: the Download section is images only (no video / audio)

## v2.58.1 - 2026-11-25 - Photoshop import, paste & export folder, Text Plate
- **New:** Photoshop: Import button - images, PSD, AI / PDF / SVG, RAW and video come in as layers (or Open as new documents)
- **New:** Photoshop: Paste Image - copy any image in the browser (right-click > Copy image) or a screenshot and paste it straight into Photoshop; Paste New makes a document from the clipboard
- **New:** Photoshop: choose your own export folder (Save Copy, To Folder, Layers PNG, Social sizes)
- **New:** Quick Tools > Layer: Text Plate replaces Text Box - box, pill, outline, underline or marker that follows the text, with grow-in animation
- **Fix:** After Effects: To Photoshop / From Photoshop buttons work (they showed "Tool not loaded")
- **Fix:** Photoshop: Send to AE / Get from AE really send the document now
- **Fix:** Photoshop: new direct connection - no more "MK_NOT_LOADED"; if scripts can't load, a banner shows the reason
- **Fix:** Photoshop: Select Subject, Remove BG and Stamp work when a hidden layer, group or text layer is selected; clear message instead of "General Photoshop error"
- **Improved:** Removed the 2.57 tools Click Pointer, Dot Burst, Dot Wipe and Smart Reveal
- **Improved:** Photoshop CC 2017 (18.0) and newer can open the panel

## v2.57.1 - 2026-11-24 - Fix update
- **Fix:** 2.57.0 build could stop MotionKit from working in After Effects, Premiere Pro and Photoshop - 2.57.1 uses the normal code again
- **Fix:** FX Search window: no more lock / "files were changed" message after updating

## v2.57.0 - 2026-11-23 - Click Pointer, Dot Burst, Dot Wipe, Smart Reveal
- **New:** Quick Tools > Tools: Click Pointer - a mouse pointer travels to the selected layers and clicks them (6 styles, press, ripple, 3D lift, trail, clicked layer reacts)
- **New:** Quick Tools > Tools: Dot Burst - halftone dot shockwave from a layer with glow (1-5 waves, dots or pixels)
- **New:** Quick Tools > Tools: Dot Wipe - transition through growing dots or pixels from 7 directions
- **New:** Quick Tools > Tools: Smart Reveal - 10 reveal looks (Soft Wipe, Blur In, Flicker, Spiral, Glitch, Pixelate, Blinds, Vortex, Zoom In, Light Burn) on one slider
- **Improved:** Text Box rebuilt: a box layer under the text that follows the text, with padding, corner, colour and opacity
- **Improved:** Photoshop opens its own MotionKit page - no After Effects / Premiere code runs in Photoshop
- **Fix:** Captions: "Host script error" fixed; offline Whisper engine built in on Mac (no Homebrew)
- **Fix:** Captions Gemini key can no longer be overwritten by AI Mode

## v2.54.1 - 2026-11-18 - Captions hotfix
- **Fix:** Captions: fixed "Host script error (ck_sources / ck_ppPrepare / ck_ppPlace)" - the Captions host functions now always load in After Effects and Premiere Pro, and any real error now shows its reason

## v2.54.0 - 2026-11-18 - New Captions tab (CaptionKit 2.2), offline Whisper, ElevenLabs multi-key
- **New:** Captions tab rebuilt with CaptionKit 2.2 (AE + Premiere Pro): 121 caption styles with live previews, Word / Phrase / Sentence / Smart caption modes, 80+ languages, Hinglish, translation, emoji and swear censor
- **New:** Captions: right-click any style to customize it - fonts, colours, size, position (drag it in the preview), glow, drop shadow, animation - with your own frame as the preview
- **New:** Captions: Whisper (offline) engine - free captions on your own computer, no key and nothing uploaded (engine built in on Windows; Mac via Homebrew)
- **New:** Text to Speech: Google Gemini voices + ElevenLabs with several API keys, credits shown for every key and auto-switch when a key runs out
- **Improved:** Settings > API Keys > Captions & Text to Speech: one place for the Gemini key, ElevenLabs keys, Whisper, caption AI model, voice AI and ffmpeg - stays in sync with the Captions tab
- **Improved:** Premiere Pro: captions go to a Caption track or a Video track; AE captions are editable text layers
- **Fix:** Version label + update checker now show the real version; Map 3D camera layer and 3D Toolkit layer order fixes are included

## v2.53.0 - 2026-11-14 - 3D Toolkit, Parallax, Putty, 3D Maps
- **New:** Editor Mode > 3D Toolkit (AE): one-click camera rig, 24 camera moves, Target (layer to layer), 16 shakes, Layout (Z / X / Y / grid / circle / random), Depth of Field + auto focus, Depth Fade, Overlap
- **New:** 3D Toolkit > Parallax (AE): give every layer a depth without the picture jumping (scale compensation) + 12 parallax camera moves
- **New:** Viral > Putty (AE): bend any layer with a cage - drag the points on the preview, 15 shape presets, 12 living presets (jelly, sway, flag, melt ...), keyframe it or drive it with nulls
- **New:** Map: search any place, 3D tilted maps with heading / orbit, sky + haze, extruded countries, Tour camera, drop pins / flags, car / ship / train travellers
- **New:** Grid Reveal: 33 new premade presets (incl. Text Reveal)
- **Improved:** Every new tool: settings in the right slide drawer + mouse control in the live preview (orbit, dolly, pan, zoom)
- **Fix:** Light leaks: your own light leak videos show up by themselves - no more Scan again; the empty footage box is gone

## v2.52.0 - 2026-11-13 - Text Behind (BETA), TypePlay flicker + 3D
- **New:** Tracker > Text Behind (BETA, AE + Premiere): text behind the people in a video or image - people found every frame, edge detail, settings drawer, all installed fonts
- **New:** TypePlay: 8 reveal directions in one row under the tabs, preview plays on every preset click, hover = animated thumbnail
- **New:** TypePlay: Flicker (10) and 3D (14) text presets

## v2.51.0 - 2026-11-09 - BG Generator styles, Map preview, Premiere popups
- **New:** BG Generator: 14 new looks (dashed grid, zebra marble, watercolor, pinstripes, squiggles, sunburst, crumpled paper, polka, checker, glow curve, plasma, topographic)
- **New:** Map: mouse wheel zoom + drag in the preview, maps app look, everything goes in as a precomp
- **New:** TypePlay: fixed preview while presets scroll, reveal direction arrows, 8 bounce presets
- **New:** Mask Splitter: zoom / pan preview, cut-out with your own masks, different animation per part
- **Improved:** Premiere: Separate Audio / Auto Duck / Scene Detect / Vertical each in its own popup, better voice detection in Auto Duck
- **Improved:** Premiere Graph tab rebuilt: clean bezier graph, handles never hide
- **Fix:** Premiere SFX tab: top buttons visible on narrow panels; light leak files found anywhere in the MotionKit folder
- **Removed:** MotionKit AI tab removed; Generate Video removed from Premiere AI Mode

## v2.50.0 - 2026-11-09 - Map, Quick Tools, Light Leaks, Photoshop
- **New:** Editor Mode > Map (AE): animated world maps - highlight countries, routes between cities, camera fly-ins
- **New:** Quick Tools: TypePlay text animator + BG Generator
- **New:** 24 real light leak videos in Transitions > Light Leaks
- **New:** Premiere Project tab: Separate Audio, Auto Duck, Scene Detect, Vertical
- **New:** Photoshop version of MotionKit
- **Improved:** Resizable compact settings drawers; Mask Splitter v2; Generate Video accepts any code

## v2.48.0 - 2026-11-09 - Grid Reveal studio, Mask Splitter, Client Review links
- **New:** Viral > Grid Reveal studio with visual presets and a settings drawer
- **New:** Editor Mode > Mask Splitter: every part of an image becomes its own animated layer
- **New:** Connect > Client Review links: send a watch-only link, comments come back
- **Improved:** Split Screen: real pictures in the preview, settings drawer

## v2.46.0 - 2026-11-08 - MotionKit Connect + theme presets
- **New:** Editor Mode > Connect: phone live preview + remote control, Wireless Import, shortcuts, annotations (local Wi-Fi + remote)
- **New:** Theme presets: accent + background + buttons in one click

## v2.45.0 - 2026-11-08 - Mockups as precomps
- **New:** Mockups are added as one precomp, screen footage replaceable, 2D / 3D switch

## v2.44.0 - 2026-11-07 - Tracker + Graph presets
- **New:** Editor Mode > Tracker (AE + Premiere): track & attach any layer / clip, stabilize, zoomable preview
- **Improved:** Graph: presets drawer, multi-key graph; Premiere Smooth Graph

## v2.43.0 - 2026-10-29 - Grid Focus, Split Screen mouse control, Align shortcuts, FX slots
- **New:** Grid Focus (multiple images), Split Screen mouse control, Align shortcuts, FX slots, Purge

## v2.37.0 - 2026-10-22 - Editor templates + update checker
- **New:** 28 editor timeline templates (Elements > Timeline): render bar green / red, render queue, trim in / out, split layer, drag file to timeline, pre-compose, pick whip, markers, time remap, audio waveform, expression error, missing footage, timecode, RAM preview loop and more
- **New:** 27 editor UI templates (Elements > UI Animation): error + warning dialogs, render complete, render progress, out of memory, missing fonts, drag & drop import, effect search typing, effect controls, color picker, export format, undo history, context menu and more
- **New:** Update checker: MotionKit tells you when a new version is out (green Update button in the header + Settings > About > Updates)
- **New:** "What's new" window after every update

## v2.36.0 - 2026-10-21 - Money elements
- **New:** 243 money templates: Simple (32), Loops (31), Explosions (30), Paper Cut (30), Hand Drawn (30), Infographics (30), Timeline (30) and UI Animation (30)
- **New:** Coins, bills, money bags, piggy banks, wallets, cards, price tags, gold, charts, KPI cards, payment success, checkout, wallet balance, transaction list and more - currency symbol is editable ($, ₹, €, ₿ ...)

## v2.35.0 - 2026-10-21 - Viral tab redesign
- **Improved:** Grid Transition + Split Screen: presets / templates open in a side drawer with adjustable thumbnail size
- **Improved:** Cleaner settings: Grid / Animation / Timing and Panel / Layout / Style / Animation tabs
- **New:** Corner and box reveal grid animations (from all 4 corners, rings, zip, blinds, shutter, snake, rain) + 21 Reveal presets
- **New:** 40 editor timeline templates: color wheels, curves, scopes, node graph, mobile editor strips, trim, keyframes, graph editor, audio mixer, multicam
- **Fix:** Theme accent colors are perfect circles

## v2.34.0 - Viral tab: Grid Transition + Split Screen
- **New:** Editor Mode > Viral: Grid Transition (12 styles, 15 patterns, 20 presets) for After Effects and Premiere Pro
- **New:** Split Screen Studio: 36 layouts, borders, rounded corners, background, panel animations
- **Improved:** AI Mode tabs use a compact layout; Captions & Voice keys in Settings > API Keys
- **Fix:** Gradient lock now stays with the shape when it moves or scales

## v2.33.0 - Create Image + API keys
- **New:** AI Mode > Create Image: aspect ratio, resolution, count, style and 7 image engines
- **Improved:** Settings > API Keys: sections for Direct Chat, BG Remove, AI Enhancer and Create Image with auto-detect, show / hide and more than one key
- **Improved:** Smoother, lighter panel (less CPU while idle)

## v2.32.0 - Transitions, cursors and more
- **New:** 60 transitions, animated cursors, Explosions / Arcs / Blow Ups packs
- **New:** 46 slider templates in Elements > Timeline: video / music players, story bars, progress bars, editor tracks, waveforms
- **New:** Chat animation tab, FX Search palette, screen color picker
- **Improved:** Timeline sliders, graph Value / Speed switch, Remove Silence closes gaps, multi-layer create, Repeater X / Y / Z, comp duplicate with copies
- **Fix:** Panel freeze fix and gradient lock

## v2.31.0 - AI Mode (BETA)
- **New:** AI Mode (BETA) for AE + PP: Direct Chat, BG Remove and AI Enhancer
- **New:** New Elements > Timeline tab: timeline, progress and process animation templates
- **New:** More Premiere Pro carousel templates
- **Improved:** Faster loading, no more freezing; Social Media and Cards layout fixes
