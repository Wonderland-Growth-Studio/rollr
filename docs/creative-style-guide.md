# Rollr creative style guide: editing styles and caption styles seen so far

Audience: an editor (human or AI with ffmpeg and caption-rendering tools) who has no other context. Brand: Rollr, refillable luxury deodorant, UK, GBP 45. Agency: Wonderland. All facts below come from research notes dated 2026-11-11. Nothing was re-researched when this was written.

Labels used in this document (all coined here):

- **[F]** = the style was analysed from extracted video frames (contact sheets, scene-detect cut counts, close-up crops).
- **[C]** = only one cover/poster frame of the ad was seen (Meta). Cut rate, timing and animation are unknown.
- **[N]** = names, durations and folder structure only.
- **INFERRED** = the note author's reading, not something visible in a frame. The marking is carried through from the notes.
- **E1, E2...** = editing styles (section 3). **CA1, CA2...** = agency/brand caption styles. **CN1, CN2...** = creator-native caption styles (section 4).
- "Hook" = the first ~3 seconds. "Clean" = a version with no burned-in captions.
- Money: Trybe figures are **USD**. Meta account and Drive-sheet figures are **GBP**. They are never converted or added together here.

---

## 1. What this is and how far to trust it

### 1.1 Evidence table

| Source | What was actually inspected | Counts |
|---|---|---|
| **Trybe** (creator-submission platform; originals reachable by signed link) | Full-frame analysis: 1 fps or 1.5 fps contact sheets, scene-detect cut times, 450-540 px close-ups of caption text. For roughly half of the second batch only the first ~20 s plus crops were viewed; the rest is inferred from cut times and transcripts. Audio is only Trybe's transcript. Review comments read in full. | 79 submissions total: 47 approved (46 video, 1 static image), 18 pending, 14 revision-requested, 0 rejected. All 46 approved videos covered (4 are exact duplicates identified by identical duration and cut times, frames not re-read). 6 of the 14 revision-requested videos viewed; the other 8 are inferred from their comments. |
| **Meta Ads connector** (ads that ran) | **One cover frame per ad** (720-1080 px wide, sometimes 320 px). No source video was obtainable (`download_hd_url` was null for 31 of 31 videos requested) and thumbnail hosts were blocked by the sandbox proxy. Copy, spend, status and duration come from metadata. | First 100 ads by spend since April 2026 listed (more exist, unlisted). About 19 cover frames viewed. Several top ads returned no image (see section 9). |
| **Drive: small designed motion pieces** | Full-frame analysis, 1.5 fps sheets. These are designed/animated pieces, not UGC. | 6 distinct edits: SEARCH AD, We're Sorry, GEMSTONE, Awards Motion (4x5 only), EDU_T4 kinetic counter, AnimatedGemstone_Kive. Plus 1 UGC refill demo (Charlie, two files that share cut timestamps). |
| **Drive: statics** | Viewed as images. | About 27 viewed across notes (6 Top Ads, 20 across Approved / Top Ads / B11 reworks / Finished Ads / Demand Gen, 1 October rose-quartz); some overlap, exact distinct count not stated. |
| **Drive: docs** | Text read. No brand-guideline, caption spec, subtitle spec or editing guideline exists in the connected drives. The "Meta Primary Texts & Headlines" sheet holds only a header row. | 3 named docs read, plus the customer-segments doc and the 2023 motion-guidelines report. |
| **Drive: folder/file names** | Names only. Folder names are the briefs. | Months 04 to 11 mapped. Statics for May-Nov were not enumerated. |

### 1.2 The gap you must keep in mind

- **Agency-edited UGC masters could not be opened.** Drive's `download_file_content` fails above about 6 MB (the earlier METHOD note said 10 MB; a later test corrected this to about 6 MB: it succeeded at 5.88 MB and failed at 6.45 MB). Every agency UGC master is 20 to 340 MB. Unopened: Caz.mp4 (85 MB), Founder edits, all "With Subtitles" cuts, the whole Demand Gen Suggestions folder (7 videos, 45-336 MB), Finished Ads (21 videos, 45-157 MB), Customer Call, Laura, Selena, Cirqle, Twirl, ICON and DR Sensory Appeal videos.
- **So agency caption styles for UGC rest on a single Meta cover frame per ad.** That is decent evidence for how the text looks (font weight, colour, box, position) and none for word-by-word timing, animation or cut rhythm.
- **Creator-upload styles and the designed motion pieces rest on full frame analysis.**
- **Trybe holds the creator's upload**, i.e. what the brand reviewed. The ad that ran on Meta may have been re-cut or re-captioned by the agency. Only three Trybe items are brand/agency uploads (e0d8d384, 6c5dbb39, 90ea1855) and they are the best view of an in-house template.
- **No video was judged for audio or music** beyond Trybe's transcripts and a few file names.
- **"Approved" is a weak quality signal.** 47 Trybe submissions are approved, but only about 6 have meaningful spend. In Drive there is no approvals ledger; approval proxies (Approved folder, Demand Gen "approved launch videos" folder, Top Ads folder, launch-date sheet) are used instead.

---

## 2. Brand constants

### 2.1 Palette

Hex values are visual estimates from frames, marked "-ish" in the notes. They are not from a brand file; none exists.

| Colour | Value as recorded | Where |
|---|---|---|
| Deep plum / aubergine (primary) | `#42042F`-ish (end cards, kinetic counter canvas); `#3D0A2E`-ish (Founder caption boxes); `#3a0a2e`-ish (agency key-term pill) | End cards, caption boxes, headline text on cream, footer bars |
| Cream / off-white end card | `#FDF6EE` (this is the later correction: the EDU_T4 end card is cream, not pink) | EDU_T4 end card |
| Cream number/text on plum | `#FAE6DC`-ish | EDU_T4 counter |
| Newspaper cream | `#E9E2D0` | M11 newspaper static |
| Near-black | `#0F1114` | M10 Reddit static background |
| Pale pink / dusty lilac / blush | no hex | Pale pink caption-box variant (Founder_V3); earlier-read EDU_T4 end card was described as pale pink before the cream correction |
| Magenta / plum-magenta (creator caption colour that happens to be on-palette) | `#9B1B6B`-ish and `#8E0F6B`-ish | Frosted caption boxes (42099163, c7c2f01c) |
| Greige / cream / white | no hex | Backgrounds, translucent boxes, text |
| Yellow highlight | `#FFF200`-ish | **Creator tool look only (CapCut-style).** It is not a brand colour; no brand-made piece uses it. |
| Product colour accents | Magenta/plum shipper box ("purple/magenta mailer box", "plum Rollr box"); scent sachets: Mandarin (orange), Clary Sage (pink), Juniper (blue), Vetiver (green) | Throughout |
| Gemstone roller colours seen | rose quartz, green aventurine, blue sodalite/"demortierite" stone, jade-green, smoky | Product shots |

Overall: deep plum, cream/greige, white, pale-pink accent. Tactile real-world backdrops for photography (travertine, citrus, daisies, satin, marble, wood).

### 2.2 Typefaces (as observed)

- **Named in the notes:** "Kalice Trial", style Italic, appears as a text-layer font in the 2023 `Rollr_MotionGuidelines.aep` report (project by a third party, July 2023). That is the only font name in any document.
- **Matches by eye (INFERRED, not confirmed by any brand file):** designed copy and static headlines look like a light/regular high-contrast display serif with an italic emphasis word and curly-j/y italic swash (Kalice-like). The "Rollr" wordmark is a custom display serif with a ligature R with a flared foot. Body micro-copy is in the same serif or a plain humanist sans (Inter/Helvetica-like). UI mimics use a system sans (Roboto/Arial-like).
- **Creator-tool fonts (as described, none verified):** bold geometric sans (Montserrat/Poppins/Inter-Black look), extra-wide heavy sans for one-word caps, thin system sans for native subtitles, light Playfair-like serif, extended light geometric sans for instructions.

### 2.3 Wordmark usage

- "Rollr" in the display serif. White on plum or on photos; plum or cream on light grounds.
- Statics (rose-quartz series): white serif wordmark **bottom-left**. Handwriting static M24: white serif wordmark bottom-right.
- Motion end cards and templates: wordmark centred near the top of the plum card.
- Product also carries "Rollr" debossed/embossed on the bottle base and a black sphere cap; the box lid carries copy (section 2.8).
- Spelling is always **Rollr**: capital R, then o-l-l-r. See rules in section 7.

### 2.4 End-card system (designed motion pieces)

Plum background (`#42042F`-ish), white "Rollr" display-serif wordmark centre-top, a cream serif tagline (2 lines, fades in), optional full-width white **Trustpilot bar** ("Excellent", 5 green stars, Trustpilot logo; 4.5 stars in templates), then a white-fill rectangular **"SHOP NOW"** button (serif caps, plum text) which pops in last. Held about 3 to 4 seconds. Tagline examples: "Found: the beautiful way to quit plastic." (SEARCH AD), "We're only sorry you didn't find us sooner." (We're Sorry), "A deodorant you'll love applying - and love leaving on display." (Awards; no Trustpilot bar on this one). Static reworks use a plum "Shop Rollr" button (filled plum with white serif on light scenes; white button with plum serif on dark scenes).

Variant, EDU_T4 kinetic counter (later correction applied): cream `#FDF6EE` end card with a blue-ball glass bottle still, "22,000 times. Make every one of them Rollr." in dark plum serif (2 lines), the wordmark, and "SHOP ROLLR · ROLLR.CO.UK" in tiny grey sans caps. No button.

**No creator-uploaded video (46 approved Trybe videos) has an end card, logo, sticker, price badge or CTA graphic.** The CTA there is spoken or sits in the Meta ad's CTA button. The GBP 45 price appears as spoken or static copy only.

### 2.5 Standard CTA

Meta CTA button on every ad that has one: **SHOP_NOW**. On-screen: "SHOP NOW" button, or "SHOP ROLLR · ROLLR.CO.UK". Link seen once: `rollr.co.uk/products/starter-pack`. Trybe-sourced ads must carry `trybe=<trybe_id>` in the destination URL and at the end of the ad name or the creator is not paid (Trybe instruction; see section 2.7).

### 2.6 Aspect ratios and export pairs

- Videos are delivered as **9:16 (1080x1920)** and **4:5 (1080x1350)** from one master. Seen: SEARCH AD 4:5 is 1536x1920 hi-res; Awards 4x5 is 1080x1350; Trybe creator uploads range 1080x1920 to 2160x3840 (some 1440x2560, 720x1280).
- One brand-upload pair is confirmed from a single timeline: 6c5dbb39 (9:16, 10 cuts) and 90ea1855 (1080x1350, 13 cuts, captions in the same place relative to the frame). The 4:5 had three extra cuts, INFERRED to come from reframing.
- Statics are always a 4x5 + 9x16 pair.
- Some ads run 4:5 only (LoFi, Laura NewHooks, SplitScreen, ASMR banner, Heatwave).
- Shorts/YouTube: the Demand Gen guide says to repurpose the strongest vertical videos as Shorts under 60 s.

### 2.7 File-naming conventions

| Where | Pattern | Example |
|---|---|---|
| Drive deliverables | `YYMM_Rollr_<Concept>_<variant>_<ratio>` | `2604_Rollr_Brief4_1_9x16.mp4`, `2610_Rollr_TheQuietUpgrade_1A_4x5.jpg` |
| Drive folders | Folder name is the brief: `Brief N - <concept>`, `B<n> - <concept>`, creator folders (`Laura UGC`, `Cirqle - Emily`) | `07_July/Brief 23 Static to Motion` |
| Version / state suffixes (INFERRED meaning) | `_v1/_v2`, `-r1/-r2`, `Round 1/Round 2`, `Variant1/2`, `Hook 1/2/3`, `_Short`, `Audio1`, `_MusicOnly`, `_Slower_2/_Faster_2`; folders `UPLOADED` (went to Meta), `0LD`, `Archive`, `DO NOT UPLOAD`, `DO NOT LAUNCH`, `RAW - Do not upload` | `EDU_T4_05_..._9x16_MusicOnly` |
| Platform-native statics | `MDI_T1_Mxx` | M10 Reddit, M24 HandwritingPhoto |
| Caption pairs | `<name>_NoSubs` / `<name>_withSubs`, "Hook 1 (with captions)" / "(without captions)" | `BrookeM_NoSubs.mov` vs `BrookeMaunders_withSubs.mov` |
| Meta ad name (agency) | `[Creator/Format]_[Hook]_[Format: UGC/VID/IMG]_[Angle: Aspirational/Upgrader/Switcher/Ritualist/Price]_[Lever: COOL-GEM/VISUAL-STOP/PUNCHLINE/PAIN-MIRROR/GEM-PORTAL/TACTILE]_[hook-slug]_[NewConcept/Iteration]_[TOF/MOF/BOF]_[length]` | `UGC_Caz_Upgrader_Punchline_CanYouBelieve_NewConcept_MOF_75s` |
| Meta ad name (Trybe) | `VID_<Creator>_<date or hook>_..._trybe=<8-char id>` | `VID_BrookeMaunders_20261013_Aspirational_Upgrader_COOL-GEM_NewConcept_TOF_trybe=a638e2df` |
| Trybe creator upload | `rollr_<Creator>_<Hook title>_<Roll\|Refi>_<hash>`; `Roll` vs `Refi` is INFERRED to mean roller vs refill product | `rollr_BrookeM_Scent_First_Roll_88f8c84a.jpg` |

Funnel tags: TOF/MOF/BOF = top/middle/bottom of funnel. Trybe angle tags: The Quiet Upgrade (Finally enjoying deodorant); The ugliest thing in your bathroom; Scent First; The Sceptic (I didn't think it would work); Owned, not Explained.

### 2.8 Recurring product shots

- **Plum/magenta box** as colour anchor (about half of the 46 approved Trybe videos, where viewed). Lid copy is printed on the box, not overlaid: "For pleasure and planet.", "Permission to get sweaty." (one note records the printed text as "get sweasty", sic), "Deodorants really shouldn't be this beautiful.", "Damn, you smell good.", "Natural | Refillable | Vegan".
- **Refill ritual:** tear/cut a sachet (Mandarin with Cedarwood, Clary Sage, Juniper, Vetiver), powder into the glass bottle, warm water from tap or glass jug up to the neck, shake. In about two thirds of the creator demos.
- **Sachet held to the lens** (scent name legible), creator smelling the roller or sachet.
- **Gemstone roller macro** (rose quartz most common), cap off, roller turning in hand, roller under the arm, roller on bare skin.
- **Bottle shown among luxury items**: perfume shelf, skincare cabinet, hydrangea/candle/crystal styled shelf.
- **Closing hold or macro** of the capped bottle with "Rollr" on the base.
- **Bottle must be filled on camera** whenever it is smelled or rolled (rule, section 7).
- Studio/CGI hero: bottle with black sphere cap and debossed "Rollr" on a soft gradient; four bottles in a row differentiated by ball colour.
- Hands in frame are polished and the label is legible.

### 2.9 Tone of voice

From written sources and on-screen copy. Customer-segments doc (Sept 2026) avatar "The Elevated Everyday Groomer" (22-40, urban). Insight: "I upgraded my skincare, fragrance and grooming products. Why haven't I upgraded my deodorant?" Direction: should feel like it sits beside fragrance and skincare; "Not 'available in coconut'. Proper fragrance language"; "No fearmongering... more 'considered formulation' than 'conventional deodorant is poison'"; common denominator "I don't want to have to think about my deodorant."

Observed in designed copy (INFERRED characterisation): sentence case, full stops, short declaratives (3-9 words per line), triplet rhythm ("Swoony to smell. Sublime on skin. Stunning to look at."), one italicised emphasis word per headline, UK spelling and GBP, press/award logos as proof. Emoji never appear in designed pieces; they appear only in some hook captions on UGC/founder videos (section 4). Premium and scent-led, apologetic-wit ("We're sorry."), price confronted directly ("£45 for a deodorant?! We can explain").

Language note: the brief language appears to be "anti-odorant" (the Katie/Brooke French scripts and the "We're sorry" statics: "Rollr isn't a natural deodorant. It's an anti-odorant"). Creators who said "natural deodorant" were still approved (INFERRED, not tested).

---

## 3. Editing styles

Ordering: strongest approval/spend evidence first. The ranking mixes units (GBP Meta, USD Trybe) so it is indicative only. Within each entry, "Spend" is quoted in the unit of its source. Cross-cutting facts that apply to nearly every style follow the entries.

### E1. Agency UGC talking head, hook-first (the "Caz" format)  [C]
- **Use when:** raw footage is a creator speaking to camera and holding the bottle, phone-shot 9:16, warm natural light.
- **Structure:** INFERRED only. Creator holds the Rollr bottle up to camera (cap in the other hand) with a caption in the lower third; runtime 30 s to 100 s. No cut data. Hook text for the first 3 s was not seen.
- **Cuts:** unknown (not measured).
- **Overlays seen on the cover frame:** caption only (CA1: white bold sans, 2 lines, ~78% down, one emphasis word in the brand italic serif: "Not to mention how gorgeous it is!").
- **Look:** warm beige wall, cream/greige low-key grade.
- **Ending:** unknown.
- **Examples:** `UGC_Caz_Upgrader_Punchline_CanYouBelieve_NewConcept_MOF_75s` (69.0 s, 720x1280 cover), older copy and `VID_UGC_Caz_Hook:CanYouBelieveThisisADeodorant` (same frame); Caz WooWoo 99.6 s; Chloe_Shout_Hook2 (no image returned); Selena (SHARE post, no image).
- **Spend/approval:** the largest by far. Meta GBP 34,209 on the lead ad (window 2026-04-01 to 11-11), plus GBP 1,740 and 301 on older copies. Drive sheet "Top 4 Ads, Last 60D": UGC_Caz_Upgrader spend GBP 19,643.61, attributed purchase value GBP 13,984.40 (0.71). Caz.mp4 is in the "approved launch videos" folder and "Creator Ads with Launch Date" shows launch 05/12/2026, still live. Chloe_Shout_Hook2: GBP 14,791. Platform-attributed return is below 1 on the top four ads in that sheet.
- **Confidence warning:** this is the best-funded style and the one least visible. Do not infer its cut rhythm from the other styles.

### E2. Voiceover over hands-only demo / refill ritual  [F]
- **Use when:** raw footage is a bathroom/vanity/worktop demo of the box, bottle and refill, with a voiceover or no speech; creator face absent or only briefly shown.
- **Structure (a638e2df, best-spending creator ad, 36.7 s):** 0-3 s extreme close-up of the rose-quartz roller turning in hand with the hook headline (CN6, section 4) in the upper third; 2-7 s box-open sequence showing lid copy; 7-21 s one long hands-on shot (refill how-to); 21-29 s creator face appears at 23-25 s (smelling a sachet); burst of 5 cuts at 29.6-30.3 s; 31-36 s creator smelling the roller and smiling to camera. CTA spoken only.
- **Cuts and pace:** average shot 1.4 to 3.4 s across the family, hard cuts only; a638e2df has 12 cuts (avg ~2.8 s, lumpy). Fastest: e0890090 (10 cuts in 15.2 s, 1.4 s avg). Charlie UGC refill tutorial: 9 shots in 33 s (avg 3.7 s, range 1.7-10.2 s; one 10 s pour shot), handheld, packaging-first opening, ends on a ~5 s static hold of the capped bottle on a marble sink.
- **Overlays:** usually none beyond one hook headline (a638e2df, 6b7d074c, e0890090) or running native captions (fa4cab68, 020dc18c, a346d626, 4502ae23, 25d4700a, eac3fcdf). No logo, no end card, no stickers.
- **Look:** bright daylight, white/grey marble or white bathroom, plum box as the only saturated colour.
- **Ending:** creator smiling to camera, or bottle hold/windowsill/shelf; no card.
- **Examples:** a638e2df and 6b7145a6 (Brooke Maunders), fa4cab68 / 3631d6ba (Plyska Genova, bathroom-cabinet hook), 020dc18c / 9e4fef71 / 3e6b19bb (Brooke French: one master of 6 cuts with three scripts), 4502ae23 (Sifa Veli), a346d626 (Sophie Cranmer), eac3fcdf (Kate Allan), 6b7d074c and 4f40ef48 (duplicates), e0890090, 25d4700a (Sofie Raken, golden-hour wall, hands only), `CharlieUGCwithElevenaudioa1.mp4` and the "Ad - I never thought I'd call a deodorant beautiful..." file (same 8 cuts, 720x1280, no captions; Charlie's audio is an ElevenLabs voice per file name only).
- **Spend:** the family is 14 Trybe submissions, $3,414.29 (USD), of which a638e2df is $3,032.78 (platform ROAS 0.92, Trybe GMV $1,991) and the other 13 together $381.51. Meta shows the same ad at GBP 2,291 (a different unit and window from the Trybe figure; not added). fa4cab68 was weak: $187, ROAS 0.26, GMV $0.
- **Evidence:** [F] for Trybe items; Charlie [F].

### E3. Founder podcast clip  [C]
- **Use when:** footage is the founder speaking to a mic in a podcast-style set-up and the angle is the price objection.
- **Structure:** INFERRED. One speaker, 9:16 crop, one continuous clip, 30 to 50 s. Boxed serif caption in the upper third above the head (CA2).
- **Cuts:** unknown.
- **Variants:** same footage, caption box plum vs pale pink (A/B of box colour only).
- **Examples:** `VID_Founder_Upgrader_Punchline_Our-Deodorant-Expensive_Iteration_BOF_30s` (31.4 s): "We charge £45 for deodorant. Here's why.✨"; `VID_Founder_V3_Upgrader_Punchline_45-for-a-Deodorant-wecan-explain_Iteration_BOF_50s` (48.7 s): "£45 for a deodorant?! We can explain...💫". Folder `09_September/B1 - Founder Edit V3`; July "Brief 14 - Founder Reply".
- **Spend:** GBP 9,110 (+4,299 duplicate) and GBP 2,368 (+446). The Drive sheet's "VID_Founder_Upgrader" (GBP 7,543.64 spend, 0.72) maps to the Founder family by name only (INFERRED).

### E4. Aesthetic voiceover + b-roll, "ugly object" visual stop, and luxury product mashup  [C]
- **Use when:** there is mundane or cinematic b-roll (no face needed) and a voiceover, or CGI/studio product shots.
- **Structure (INFERRED from names and cover frames):** hook b-roll (a hand opening a drawer of everyday ugly objects; a man walking a sunlit street; a CGI bottle hero) with a text hook, then voiceover. Mashup variant: studio/CGI product shots with two caption layers (title box + subtitles), "fragrance-ad treatment".
- **Cuts:** unknown.
- **Examples:** `DR_Aesthetics_Hook3_VID_..._heres-what-noone-else-say` (56.4 s; "This is the ugliest thing you own!"), `Voiceover_Script_1_3_..._the-last-natural-deodorant` (43.3 s; cover has no text), `VID_Mashup_Hook3_Exclusivity_Fragrance_VISUAL-STOP_this-isnt-perfume` (44.4 s), `Skye_Brief17_..._how-much-of-your-day` (partner post, typographic full-screen text), `CherLaurens_Twirl_...`.
- **Spend:** GBP 8,522 (DR Aesthetics), 4,157 (Mashup), 971 + 218 (Voiceover_Script), 850 (Skye).

### E5. Kinetic talking head with prop cutaways (the "CapCut creator edit")  [F]
- **Use when:** footage is a creator, especially the male creator Dylan Dalton's set, talking to camera with products and competitor props to hand.
- **Structure:** a cut on every phrase. Example 82807831 (33.3 s, 17 cuts, avg ~1.85 s): 0-3 s he holds bottle and shaving brush to camera, cut to roll-on macro, cut to powder in bottle, holds a competitor can (green Mitchum) at ~2.7 s; then face, product macro, face. End: purple box on a table, spoken CTA ("link down below... before they sell out").
- **Cuts and pace:** hard cuts landing on spoken beats, avg 1.45 to 1.9 s (22 to 26 cuts in 33 to 47 s). The highest cut density in the set.
- **Overlays:** captions only (CN1). No stickers, no end card.
- **Look:** warm lamp light, plants, shallow depth of field, camera-grade 4K, varied rooms plus a bright white bathroom insert.
- **Examples:** 82807831 (Dylan Dalton); 3a2543f1 (47.1 s, 26 cuts); 1b3ad86b (33.3 s, 22 cuts, sweat-patch hook); 8823223f (37.5 s, 19 cuts, hook caption "what the f***", profanity censored by asterisks).
- **Spend:** 82807831 $1,229 (ROAS 0.73, GMV $786), Meta GBP 1,127. Family $1,237.70 total (4 submissions; the other three ran $8.74 or $0). The only repeated men's angle.

### E6. Silent / music-bed b-roll, no text  [F]
- **Use when:** footage is aesthetic b-roll with no voice. Also use as the clean master that the agency can caption.
- **Structure:** either a single continuous shot or 4 to 9 cuts, hands rotating/uncapping the bottle, roller to camera, sachet pour. eed69570 (11.8 s, 0 cuts, 2160x3840): hands uncap the bottle by a hydrangea, lamp and pumpkin shelf, tilt to show powder and liquid, roller to camera. b9844aab (12.2 s, 4 cuts at 3.6/5.8/7.9/10.2 s).
- **Overlays:** none (or one line). Soft overcast light; calm styled shelf.
- **Examples:** eed69570, 3e82b650 (6.0 s, 0 cuts), b9844aab, b2ffe364 (6.7 s, 0 cuts), 3ae539aa / 5b31f04f (crystal-collector ASMR, 20.3 s, 9 cuts with a cluster of 5 cuts 0.5 s apart at 4.8-7.3 s), 34afca37, c1c69172 (clean twin of the captioned 25d4700a), b34c4e4e, plus Tracy Lee's six no-text talking-head uploads.
- **Spend:** eed69570 $474 (ROAS 1.85, GMV $660), the best efficiency among sizeable spends; family $777.38 (eed69570 is 61% of it). The second-most-spent family and the one with the cleanest hand-off to captioning.

### E7. Captioned b-roll narration (text carries the message)  [F]
- **Use when:** the footage is silent or ambient b-roll and a line of text should tell the story.
- **Structure:** same b-roll cuts as E6, with text. 26a245ae is the captioned twin of b9844aab (same 12.2 s footage and cut times): sentences appear one at a time. 88e563a9 (14.2 s, 5 cuts) opens on the box lid and uses a typewriter line. 73b3b5eb (21.7 s, 5+ cuts) is the "Things I said "yes" to this year" trend. aaf7ea9e (34.8 s, 13 cuts) is a step-by-step refill tutorial where instruction text replaces subtitles.
- **Examples and spend:** 26a245ae $40.54 (ROAS 2.01); 88e563a9 $182.37 (ROAS 1.10, note "Excellent - launching it today"); 73b3b5eb $85.19 (ROAS 2.24, GMV $137); aaf7ea9e $0. Family $308.10.
- Pairs with its clean sibling (b9844aab) as an A/B.

### E8. Static-to-motion typographic piece (apology letter, gemstone)  [F for V2/V3; C for the Meta ad]
- **Use when:** you have designed copy and product stills/CGI and no footage.
- **Structure, We're Sorry (8.34 s, 1080x1920, 1 hard cut at ~5.0 s):** cream gradient, "We're sorry." fades in at top (plum serif); lines stack roughly every 0.7 s; a glass roll-on with green ball slides in at the bottom and three more bottles (rose, navy, bronze/black ball) slide in from the right to form a row of four; hard cut to the plum end card (3.3 s) with wordmark, "We're only sorry you didn't find us sooner.", Trustpilot bar, SHOP NOW.
- **Structure, GEMSTONE (5.02 s, 1080x1920, 0 cuts):** hand holding the bottle (green aventurine) against a leaf, slow push-in (~1.15x over 5 s); headline "Bring More Balance to your day" top with "your day" in italic; 0.7 s "Green Aventurine" and the micro-line; 1.3 s wordmark; 1.9 s SHOP NOW button and Trustpilot 4.5-star badge. No end card, CTA overlaid on the image.
- **Cuts:** 1 hard cut or none. Reveal pacing about 0.65 to 0.7 s per element. No zooms or transitions beyond the push-in.
- **Captions:** none; designed copy only (CA10).
- **Examples:** `We're Sorry - 9x16.mp4`, `GEMSTONE - 9x16.mp4`, `WeReSorry_Brief23_StaticToMotion_Fragrance_PUNCHLINE_WeReSorry_Iteration_BOF_10s` (8.3 s, GBP 312).
- **Spend/approval:** the static IMG_WeReSorry is the #4 ad in the Top 4 sheet (spend GBP 4,249.60, attributed value GBP 4,023.20, 0.95, the best of the four) and the "SORRY" story recurs across at least 5 approved or top assets. The motion version is small (GBP 312). The static "We're sorry" stills say "anti-odorant"; the motion V2 says "crafted by perfumers / four scents worth wearing" (different wording on purpose, noted in APPROVED_AND_TOP).

### E9. Customer call / interview  [C]
- **Use when:** footage is a handheld phone-call or interview with a customer or the founder.
- **Structure:** INFERRED. Kitchen footage; opens with a white rounded title card with an ALL-CAPS question and a "Part 2" tag; outlined subtitles below. 60 to 80 s.
- **Examples:** `CustomerCall_Vicky_HookB_VID_Founder_Switcher_GEM-PERSONAL_what-customers-love-rollr_NewConcept_BOF_60s_V1` (77.6 s; GBP 1,184 + 300 Elizabeth variant), `..._HookA_..._calling-sweatiest-customer_60s_V1` (79.5 s; GBP 308). Caption CA5.

### E10. Comment-reply / price objection  [C]
- **Use when:** you have macro product b-roll plus a creator reaction clip and the angle is "it's expensive".
- **Structure:** 4:5, 50 s. Fake comment card pinned top-left over macro hand/bottle b-roll; creator talking-head cut-out in a bottom-right corner (reaction picture-in-picture). Card text: "Almost £50? For deodorant? In this economy?"
- **Example and spend:** `Laura_NewHooks_1_UGC_Aspirational_Ritualist_GEM-PORTAL_ive-got-to-be-honest_Iteration_BOF_50s` (GBP 745, active). Caption CA7.

### E11. LoFi text-overlay b-roll  [C]
- **Use when:** footage is deliberately phone-quality and the creative should look native.
- **Structure:** 44.0 s, 4:5 (1284x1608), soft phone-shot bottle on a tray in a green-tiled bathroom with perfume bottles; native TikTok-classic text, lowercase, upper-middle.
- **Example and spend:** `LoFi_Text_Overlays_VID_Aspirational_Upgrader_COOL-GEM_prettiest-deodorant-there-is_NewConcept_BOF_45s` ("the prettiest deodorant there is"); GBP 1,144 and 689 on two creatives. Caption style CA1.

### E12. Talking head with product cutaways, hook-swapped masters  [F]
- **Use when:** footage is a talking head with a few product inserts.
- **Structure:** face on screen about half the time, cuts on sentence beats (avg 1.5 to 3.6 s); cutaways land on the sentence that mentions them. e0d8d384 (brand upload, 43.1 s, 11 cuts, avg 3.6 s): talking head (bedroom/wardrobe, warm beige light) with 3 product cutaways (macro bottle on vase, rose-quartz roller macro, bottle); ends on the creator smiling, last caption "the Christmas gift idea this year." and no end card. Hook-swap pairs: fa57f0fa vs e22456d0 (5 s talking-head hook, then b-roll; 21 cuts, avg 1.5 s); Tracy Lee's six uploads (three scripts, three different first shots, no text).
- **Examples:** e0d8d384 (Black Friday gifting script), 6c5dbb39 and 90ea1855 (towel/marble testimonial, one word at a time, 31.2 s), fa57f0fa, e22456d0, f54e20da / c091bc99 / eeaa2806.
- **Spend:** family $56.73 across 11 submissions; e0d8d384 not yet run. No performance verdict.

### E13. Templated brand frame (split-screen, ASMR banner, heatwave)  [C]
- **Use when:** you have a short product clip and want a branded layout; 4:5, 18 to 25 s.
- **Structure:** SplitScreen (18.8 s): top-half b-roll over a plum scalloped/wavy divider, bottom half a cream brand panel with the "Rollr" wordmark, italic tagline "A natural, refillable, deodorant", Trustpilot 4.5-star logo and a bottle cut-out. ASMR banner (23.9 s): plum header bar "As seen in" with VOGUE / THE TIMES / GQ / ELLE logos; left column of three line-icons with captions "Prevents odour-causing bacteria", "Reduces sweat", "Smells beautiful"; centre rounded video window; right column "Natural Refillable Deodorant" and "Deodorants really shouldn't be this beautiful."; plum footer "Excellent ★★★★½ Trustpilot"; cream background. Heatwave (24.1 s): top half water ripples over bottom half palm leaf with a centred product cut-out straddling the seam.
- **Examples/spend:** `SplitScreen_Brief23_..._such-gorgeous-summer-scents` (GBP 405 and 209), `ASMR_Brief16_..._natural-refillable-deodorand` (GBP 194), `Heatwave_Essential_..._your-pits-heatwave-essential` (GBP 244). Caption styles CA6, CA13 (template furniture) and CA15.

### E14. Long single-take talking head  [F]
- **Use when:** the raw is one long selfie take (31-111 s) and an offer or gift pitch must be kept intact.
- **Structure:** 1 to 4 cuts. 842671ca (45.3 s, 1 cut at 32.9 s): handheld selfie in a home office, ends holding the bottle. 42099163 (69.3 s, 12 cuts): talking head plus cutaways, ending on the offer line. c7c2f01c (110.9 s, 4 cuts): single selfie, hook is clapping hands with "as soon as November hits".
- **Spend and verdict:** $151.96 across the three, platform ROAS 0 to 0.35; 42099163 $118. The note author calls these poor value and "far too long" (INFERRED). Brand did not push back on length.

### E15. UI-mimic hook (search box)  [F]
- **Use when:** you have a macro product shot and want a "search-intent" hook.
- **Structure (`SEARCH AD - 4X5.mp4`, 7.27 s, 1536x1920, 1 hard cut at ~4.0 s):** macro of a glass roll-on with a rose-quartz ball on travertine in hard sun; a white search-box UI types "no" -> "non-pla" -> "non-plastic" at ~0.6 s per character, then suggestions "non-plastic roll-on deodorant" and "non-plastic refillable deodorant" fade in. Cut to plum end card: wordmark, "Found: the beautiful way to quit plastic.", Trustpilot bar slides in at 4.7 s, SHOP NOW pops at 5.3 s, held ~3 s.
- **Spend:** none recorded for the video. A "Search Ad Static" concept exists in June.

### E16. Proof / awards montage  [F]
- **Use when:** you have award and press cards to show.
- **Structure (`AwardsMotion_Brief3_4x5_Audio1.mp4`, 10.64 s, 1080x1350, 7 detected cuts):** seven poster cards on pastel studio backdrops, ~0.7 s each for the first cards (hard cuts, possibly a 3-frame dissolve), 1.4 s on the last two; each card has a publication/award logo, a product photo, a tiny sentence-case serif caption and a white "Rollr" wordmark beneath. 4 s plum end card with "A deodorant you'll love applying - and love leaving on display." and SHOP NOW (no Trustpilot bar).
- **Cards in order:** DIELINE "Best of Show and Sustainable Health, Body & Beauty, 2025"; GENTLEMAN'S JOURNAL "Best Up-and-Coming Brand, 2025"; The Drum Awards "Product Design - Consumer, 2024"; Campaign BIG Awards "Life Wisdom Award, 2024"; The Drum Awards "Brand Identity Design - Launch, 2025"; Design Intelligence Award "Life Wisdom Award, 2024"; The Fragrance Foundation UK "Responsible Design & Packaging - Finalist, 2026".
- **Spend:** none recorded. The 9x16 sibling (6.45 MB) could not be opened.

### E17. Kinetic-type counter on solid plum  [F]
- **Use when:** you have a statistic and no footage; platform-native feel.
- **Structure (`EDU_T4_05_VID_KineticType_Upgrader_WHY-IMPORTANT_22000-times_NewConcept_TOF_16s`, 16.00 s, 1080x1920, 30 fps, 0 cuts inside the canvas until the end-card cut at ~12.6-13 s):** plum canvas; a big light italic display-serif number in pale pink/cream sits about 20% from the top (not centred) and counts 2,536 (0 s), 15,675 (1 s), 20,974 (2 s), 21,995 (3 s), "22,000" (~3.5 s), ease-out. 4.0 s sub-line under it in two lines, small condensed serif: "That's how many times you use deodorant" / *in your life.* (italic), held to ~8 s. At 8 s it fades to "It should be *beautiful.*" (single line, cream serif, italic last word, mid-canvas, fades in from ~50%, out at ~12 s). At 13 s hard cut to the cream `#FDF6EE` end card (section 2.4). No product on screen until the end card.
- **Files:** plain (0.80 MB, no audio), `_9x16` (1.21 MB, audio present) and `_MusicOnly_9x16`, all in `09_September/Platform Native Concepts/Approved`. This is the only video in an "Approved" folder. Note: the first read of this file said "pink end card, centred number"; the later read corrected it to cream, upper third.

### E18. Split-screen two-persona comedy sketch  [F]
- **Use when:** a creator can play two characters in one frame.
- **Structure (727f445d, 61.3 s, 3 cuts at 42.0/52.7/56.0 s):** side-by-side frame for 0-42 s, two versions of Dylan ("Natural but Terrible" vs "Natural and Luxury") arguing; hard cut at 42 s to a single close-up pitch to camera with bottle and shaving brush. Top labels with emoji (pink soap emoji and a red 100 emoji) held through the whole split section. CN1 captions run underneath. Competitor products in the "terrible" Dylan's hand are pixel-blurred.
- **Spend:** $0, approved 11-10, no data. One example only.

### E19. AI product push-in (no text)  [F]
- `AnimatedGemstone_Kive.mp4`: 15.04 s, 720x1280, 24 fps, 0 cuts. Kive-generated continuous slow push-in on a bottle with a blue sodalite ball on blush-beige, hard raking light, from full bottle to extreme close-up of ball/collar at 12-15 s. No text, captions, overlays or end card. Final 2 s not viewed. Spend unknown.

### E20. Creator-native partnership posts (creator's own edit)  [C]
- **Use when:** boosting a creator's own post; the creator's own caption and cover are kept.
- **Seen:** Folklore (herb pots, text "Use code FOLKLORE10 for 10% off your first order"), Madishu (unedited phone photo cover, no overlay), JARV, ArinKaz, Skye (full-screen ALL-CAPS serif statement over shower b-roll), Fragrance Foundation (Juniper).
- **Spend (GBP):** Folklore 1,120; Skye 850; Madishu 839; JARV 636 (+535), WITH_ISSUES status; ArinKaz 302.

### Cross-cutting production facts
- **Hard cuts only** in everything viewed. No wipes, zooms-as-effects, speed ramps, stinger SFX, LUT changes, stickers (Trybe videos; some final seconds of ~10 videos not viewed). Exceptions: slow push-in in E8 GEMSTONE and E19; a possible 3-frame dissolve in E16.
- **Hook/script swaps on one master are the standard A/B method.** Only the first 3 to 5 seconds and the caption text change. Examples: Tracy Lee (3 hooks, 3 duplicates), Brooke French (same 6 cuts at 3.8/6.9/10.8/13.2/15.5/17.9 s, three scripts), Plyska Genova (fa4cab68 vs 3631d6ba; fa57f0fa vs e22456d0, groups "Hook 1/Hook 2 of Concept 1"), Sofie Raken (captioned 25d4700a vs clean c1c69172), Katie (four scripts per footage). Each variant is reviewed separately, so each needs its own proofread.
- **Clean + captioned pairs** are normal (Sofie Raken; BrookeM_NoSubs vs withSubs; Black Friday UGC "Hook 1 with/without captions").
- **Rhythm benchmark:** top ad a638e2df averages 2.8 s; Dylan averages 1.4 to 1.9 s; spend does not track cut rate by itself (Dylan $1.2k vs VO demos $3.4k).
- **Length:** approved up to 110.9 s but the high spenders are 33 to 37 s; the long ones had tiny spend. Brand never objected to length.
- **Hands-only shots:** polished nails, legible label, bottle always refilled on camera.
- Mirrored selfie footage reverses the box text (defect, section 7).

---

## 4. Caption styles

How to read sizes: the notes measure position as percentage of frame height and size as small/large relative to a 1080-wide frame; absolute font sizes were not recorded. Where a size is not given, only the look is recorded, and the editor must pick a size that stays legible on a phone (the revision notes say text about one third the size of the other revision videos, or under ~3% of frame, was a defect). Safe zone from the notes: 70-80% height, one line, 3-7 words, keep the top ~15% clear for platform UI.

### 4A. Agency / brand caption systems

**CA1. Native white bold sans, no box, with optional brand-serif italic emphasis word  [C]**
- Font: bold geometric sans (TikTok/CapCut-like); the emphasis word is set in the brand italic serif.
- Case/colour: sentence or lowercase, white. No box, no visible stroke, light shadow at most.
- Position: Caz, lower third (~78% down), centred, 2 lines. LoFi, upper-middle.
- Words per segment: whole phrase, 1-2 lines. Highlight behaviour: only the italic-serif word.
- Reveal/duration: not seen.
- Pairs with: E1, E11.
- Examples: Caz 75 s: "Not to mention how gorgeous it is!" (italic serif "gorgeous"); LoFi: "the prettiest deodorant there is".

**CA2. Brand serif boxed hook (the Rollr signature)  [C]**
- Font: white italic serif.
- Box: rounded rectangle hugging each line (not one big box), deep plum (`#3D0A2E`-ish) or pale pink fill (then plum italic serif text).
- Position: upper third, above the speaker's head, 2 lines. Trailing emoji ✨ or 💫.
- Reveal/duration: unknown.
- Pairs with: E3 (the two variants differ only by box colour).
- Examples: "We charge £45 for deodorant. Here's why.✨" (plum); "£45 for a deodorant?! We can explain...💫" (pale pink).
- Hard-cornered plum rectangle with regular (non-italic) white serif is the Mashup title variant (CA4).

**CA3. White pill with two-tone sans  [C]**
- Single white rounded pill (radius ~25 px), upper third, geometric bold sans, sentence case. First word dark plum bold, the rest muted lilac/mauve.
- Pairs with: E4. Example: "This is the ugliest thing you own!"

**CA4. Mashup: plum title rectangle + plain serif subtitles  [C]**
- Layer 1 (top title): solid plum rectangle with a small radius, white regular serif: "This isn't perfume."
- Layer 2 (lower subtitle): plain white serif, soft shadow, no box, phrase by phrase: "You'd swear".
- Pairs with: E4 (luxury product hero).

**CA5. Interview title card + outlined subtitles  [C]**
- Title card: white rounded rectangle, ALL-CAPS bold black sans, 2 lines: "WHAT DO OUR CUSTOMERS LOVE ABOUT ROLLR?" with "Part 2" under it in white bold sans with a dark outline.
- Subtitles: lower-middle, white bold sans with a thin black stroke, sentence case, full phrase, disfluencies kept verbatim ("The, the, the crystal.").
- Pairs with: E9.

**CA6. Translucent greige box, plum two-weight sans  [C]**
- Semi-transparent greige rounded box on the top-half seam; plum bold sans, 2 lines, line 1 darker/bolder, line 2 lighter: "It uses / pre and postbiotics". Pairs with: E13 (SplitScreen).

**CA7. Fake social UI  [C]**
- White comment card pinned top-left: avatar, name, "7w", like/dislike icons, Reply; text "Almost £50? For deodorant? In this economy?" Pairs with: E10.

**CA8. Agency pill with key-term tag (closest to a house template)  [F]**
- Main caption: white rounded pill (~8 px radius), bold geometric sans (Outfit/Poppins look), dark aubergine/black text, sentence case, one line of 3-6 words, centred at ~72-75% height. The pill resizes per line.
- Highlight behaviour: spoken words dark, upcoming words light grey, so the line "fills in" as she speaks.
- Second layer: a persistent aubergine (`#3a0a2e`-ish) rounded pill above the caption with white italic serif (Playfair/Cormorant italic look), shown ~6 s, used for key terms: "Gemstone rollerball", "4 gorgeous scents", "2 rollrs + 6 refills for £100" (lowercase "rollrs", plural, in the offer tag).
- Emoji: none.
- Pairs with: E12. Example: e0d8d384 (brand upload, Black Friday script, hook caption "Ever since I upgraded"; last caption "the Christmas gift idea this year.").

**CA9. One word at a time, ALL CAPS, Didone/serif  [F]**
- White Playfair/Bodoni-like high-contrast serif, no stroke, no box, very slight shadow, centred at ~72% height, ~0.5 s per word, no highlight, no emoji. First word "FOUND" at 1 s.
- Pairs with: E12 (brand upload). Examples: 6c5dbb39 (9:16), 90ea1855 (4:5, same placement relative to the frame). Spend $3.00 total. "Most luxury word-by-word look in the set."

**CA10. Designed-copy serif with one italic emphasis word  [F]**
- Light/regular high-contrast display serif, cream or white on plum or on photo (plum on cream for apology letter). Centred, sentence case, full stops, max 3-4 lines, one italic emphasis word per line group ("*beautiful.*", "*in your life.*", "*deodorant*", "*scents worth wearing*", "your day" in italic swash). Staggered line fades about 0.65 to 0.7 s apart; fade-in can start from ~40-50% opacity. No box, no stroke.
- Pairs with: E8, E17.

**CA11. UI-native text  [F]**
- Black sans (Roboto/Arial-like) on a white rounded card, sentence/lower case, left aligned, 1 line per suggestion, bold for the completion part; per-character typing at ~0.6 s steps. Pairs with: E15.

**CA12. Proof captions  [F]**
- Tiny sentence-case dark-grey serif inside a white poster card (Awards); pills with red x / green tick icons on the Us-vs-Them static. Pairs with: E16.

**CA13. Template furniture  [C]**
- Press-logo header bar (plum, "As seen in"), three line-icons in circles with serif captions, Trustpilot 4.5-star footer, wordmark + italic tagline, plum scalloped divider. Pairs with: E13.

**CA14. Full-screen ALL-CAPS serif statement  [C]**
- Large cream/off-white high-contrast serif, ~6 lines, very large, tight leading, centred, no box, no stroke: "HOW MUCH OF YOUR DAY DO YOU ACTUALLY ENJOY?" Over atmospheric b-roll (shower tiles). Pairs with: E4/E20.

**CA15. Lower-case serif minimal overlay  [C]**
- White lowercase serif, no box, text at top and bottom of the frame: "your pits' / heatwave essential". Pairs with: E13 (Heatwave).

### 4B. Creator-native caption styles (approved as uploaded; made in the creator's own app)

Many creators used CapCut/Reels/TikTok. All of the below were approved as uploaded; where noted the brand later asked for a clean version.

**CN1. CapCut kinetic yellow-keyword  [F]**
- Font: bold (italic in the Dylan videos) geometric sans (Poppins Bold Italic / Montserrat ExtraBold look).
- Case: lowercase / sentence case, proper nouns capitalised; profanity censored with asterisks ("f***").
- Colour: white fill, thick black outline plus drop shadow, no box. ONE key word per line flips to yellow (`#FFF200`-ish). A two-line label (e.g. "Premium Natural Deodorant") may put yellow on line 2.
- Position: centred, ~75-78% height. Segments of 1-3 words, 1 line (2 lines for 4+ words), follows speech word by word.
- Emoji: none in running captions; the split-sketch version adds top labels with emoji (soap, 100).
- Pairs with: E5, E18. Examples: 82807831, 3a2543f1, 1b3ad86b, 8823223f, 727f445d. n=5, $1,237.70.
- Also present in two revision-requested videos (4fd6e12b, f935a4cb), rejected for spelling/overlap, not for the look.

**CN2. One-word-pop ALL CAPS, extra-wide heavy sans  [F]**
- Extra-wide heavy sans (Montserrat/Gotham Black look), ALL CAPS, one word per frame (~3 words/s), white fill, soft dark shadow (25d4700a, no hard outline) or black soft shadow (eac3fcdf). Centred ~75-78% height, very large (a word often 35-80% of the frame width).
- Pairs with: E2. Examples: eac3fcdf (its auto-captions show recognition errors; the brand asked for a clean upload), 25d4700a. n=2, $79.65.

**CN3. Native Reels/TikTok subtitle, TOP third  [F]**
- Tiny thin white system sans, no stroke/box/highlight, shadow only, one line of 3-7 words at ~19-25% height, phrase at a time.
- Pairs with: E2, E12. Examples: fa4cab68, 3631d6ba, fa57f0fa, e22456d0. n=4, $244.78. Belongs to the weakest per-dollar results (fa4cab68 ROAS 0.26).

**CN4. Native subtitle, LOWER third  [F]**
- Small white bold or regular sans, soft shadow (sometimes thin dark outline), sentence case, 1-2 lines of 2-6 words, ~64-85% height, phrase at a time. The Instagram variant dims upcoming words (grey) so the line fills as spoken. a346d626's size is "very small" and its position moves between ~25% and ~64-70%.
- Pairs with: E2. Examples: 020dc18c, 9e4fef71, 3e6b19bb, a346d626, 4502ae23, 842671ca (running captions). n=6, $55.63.

**CN5. IG-story frosted box, magenta text  [F]**
- Translucent white rounded box (~40% white, radius ~14 px) with bold lowercase-ish sans (Proxima/Inter Bold) in plum-magenta (`#8E0F6B`-ish; the other file reads `#9B1B6B`-ish), 1-2 lines of 3-7 words, centred at ~75-80% height (72% at the end), phrase at a time, no highlight, no emoji.
- Pairs with: E14. Examples: 42099163, c7c2f01c. n=2, $122.26. On-palette colour but only on 69-111 s videos.

**CN6. Single hook headline, then clean video  [F]**
- One caption for the first ~3 s, then no running subtitles.
  - (a) a638e2df / 6b7145a6: two-line bold white TikTok-classic sans, centred, upper third, thin soft shadow, no box/stroke, sentence case: "Why does my deodorant look like a luxury beauty product?!" (the spoken hook is different: "Why does this deodorant look more expensive than my perfume?"). Visible through ~2.7 s, gone by 3.3 s.
  - (b) 6b7d074c / 4f40ef48: thin white sans, no stroke, centred ~50% height, 0-3 s: "A little reminder to slow down 🤍".
  - (c) e0890090: thin-ish white system sans, no stroke, centred ~40% height, 0-3 s: "Who said deodorant had to be boring?✨".
- Emoji only here (🤍 ✨). Pairs with: E2. n=5 (4 distinct), $3,089.11, includes the single biggest spender a638e2df ($3,032.78). Best evidence of scale among creator styles.

**CN7. Label hook: black serif on white pill  [F]**
- Bold serif (Merriweather/Source Serif look) in BLACK on a white rounded rectangle, centred ~75% height, sentence case with straight quotes, held ~1.5-2 s from 0: Things I said "yes" to this year. Pairs with: E7 (73b3b5eb, $85.19, ROAS 2.24).

**CN8. Editorial serif typewriter  [F]**
- Lowercase light Playfair/Didot-like white serif, 2 centred lines at ~25-30% height, no stroke/box, typewriter reveal ("the prett" > "the prettiest deodorant you'" > "the prettiest deodorant you've ever seen..."), held ~4 s then gone. Pairs with: E7 (88e563a9, $182.37, ROAS 1.10).

**CN9. Quiet narration serif  [F]**
- Small thin light serif or regular sans, white, no stroke/box, slight shadow, centred, lower third (~76-95% height), 1-3 lines, sentence case with full stops, whole sentence at a time: "I upgraded my skincare." / "My makeup. My home." / "But somehow not my deodorant." Pairs with: E7 (26a245ae, $40.54, ROAS 2.01). A small "AI" tag top-left at 0 s is in the footage itself.

**CN10. Instruction text in wide light sans  [F]**
- Extended/wide light geometric sans (Syne / Unbounded-Light look), white, no stroke/box, faint shadow, sentence case, narrow stacked column of 1-3 words per line, centred ~35-70% height; "This is not a perfume" stacked one word per line (5 lines). Each step ~2.5-3 s: "For pleasure and planet." / "Unscrew your Rollr" / "Add sachet contents to the bottle" / "Fill with warm water up to the neck of bottle" / "Reattach all parts of your Rollr". Pairs with: E7 (aaf7ea9e, $0).

**CN11. TikTok-classic headline plus running captions  [F]**
- A bold white sans headline (centred, mid-lower ~55-65% height, 2 lines, persistent ~7 s, e.g. "Finally a trend I can participate in!") with lighter, smaller white running captions below (2 lines, ~72-90% height, no box/stroke). Example: 842671ca. Pairs with: E14.

**CN12. No on-screen text at all (clean)  [F]**
- 15 of 46 approved Trybe videos (12 distinct, $805.93): eed69570, 3e82b650, b9844aab, b2ffe364, 3ae539aa, 5b31f04f, 34afca37, c1c69172, b34c4e4e, f54e20da, c091bc99, eeaa2806 and duplicates 67f83903, bbed595d, cfaa9b96. Intended for the agency to caption (INFERRED, from the feedback to Kate Allan).

**Emoji summary:** only in hook headlines (🤍 ✨ 🚨 on a revision video; ✨ 💫 on Founder boxes) and the sketch labels (soap, 100). None in running captions or designed pieces.

**Caption defects that triggered revision (not allowed):** see section 7.

---

## 5. Static ad styles

Statics always come as a 4x5 + 9x16 pair. Palette: plum, cream, white, pale pink; bottle on tactile backdrops. Serif headline with italic emphasis, plain sans for pills and small proof text, wordmark in the display serif, no stroke or shadow on the serif text.

| Style | Layout | Verbatim headline(s) / copy | Evidence |
|---|---|---|---|
| Press quote (The Times) | Full-bleed macro of rose-quartz ball on travertine (v2) or terracotta backdrop (v1); THE TIMES masthead + "LUXURY \| BEAUTY" above a hairline, five white stars, quote, small footer | "The world's most *beautiful* deodorant" / foot: "Deodorant doesn't get more luxurious than Rollr." | Top Ads 03/04 |
| Press quote (Vogue web card) | Split: left cream apology-letter panel, right blood-orange texture with a Vogue article card | "Deodorant doesn't get more luxurious than Rollr" (By Hannah Coates, Beauty & Wellness Editor) | Demand Gen `Press_Quotes_Brief1_P1_4x5` |
| Apology letter | Cream/peach gradient, centre-aligned plum serif, bottles lined up on a reflective surface (v2: single rose-quartz bottle) | "We're sorry." / "Natural deodorants have let you down before." / "But this isn't a *natural deodorant.*" / "It's an *anti-odorant.* It's pre- and probiotic. It's been four years in the making." / "Finally, there's one that works. It's Rollr." | Top Ads 05/06; top-spend family IMG_WeReSorry |
| Provocative statement | Full-bleed fruit flat lay (tangerine or orange slice), bottle top centre, white serif lower third | "A dabble with danger. From a deodorant?" / sub "A rush of orange. Then comes geranium. At last, cedarwood & patchouli." / v2: "Like perfume for your pits" | Top Ads 01/02; IMG_ProvocativeStatement #2 in the Top 4 sheet: spend GBP 8,842.38, value GBP 7,089.90 (0.80) |
| Benefit callout (27 million) | Product on pale studio on top, plum panel bottom; "As seen in" press logos row (VOGUE, THE TIMES, GQ, ELLE); variant with text right of bottle | "*27 Million* disposable deodorants will be binned today." / "Not this one." / "This one's glass and designed to keep forever." / "Natural refillable deodorant" | Top Ads 07; Finished Ads `27MillionStatic_1`, `Static_Formats_Brief25_2`; Meta GBP 8,935 (paused) |
| Us vs Them | Split cool-grey (white plastic roll-on) vs warm taupe (Rollr); red-X pills left, green-tick pills right; Trustpilot badge | "Still rolling on plastic?" / left: "Plastic roller ball", "Plastic bottle", "Used once, then binned", "Generic packaging", "Mindless daily task" / right: "Natural gemstone", "Refillable glass bottle", "Keep for life", "Actually beautiful", "An intentional daily ritual" | Top Ads 10; Meta GBP 1,870 + 788 + 629 |
| Triplet scent line | Satin-taupe liquid backdrop, bottle bottom-centre, italic on the last word of each line | "Swoony to *smell.* Sublime on *skin.* Stunning to *look at.*" / "The last deodorant you'll ever buy." | Top Ads 09 |
| Long review quote | Cream backdrop with daisies, black-ball bottle, centred serif quote, italic attribution | "Rollr is one of those rare products where idea, design and execution line up. It looks ridiculous in the best way - the kind of thing that makes you wonder why the category has been so boring for so long." (Ferg) | Top Ads 08 |
| Rose-quartz statics (October) | Full-bleed macro, plum high-contrast serif headline top-left, white wordmark bottom-left, no badge | "Every morning is occasion enough." Siblings: Save beautiful, Deserve the smallest things, Ordinary, ColdStone | `04_RoseQuartz_V1_OccasionEnough_4x5` (only one viewed) |
| Award-roundel reworks (B11) | Hero magenta shipper box + blue Juniper sachet + bottle; "Grooming Awards '25 / Best Up-and-Coming Brand" roundel; plum or white "Shop Rollr" button; light serif headline with italic second line | 01 "Most deodorants are designed to be hidden. *This one was designed to be seen.*" / 02 "*The last thing you'd expect on a perfume shelf?* Your new deodorant." / 03 "Gentleman's Journal named it Best Up-and-Coming Brand. *You'll notice the scent first.*" / 04 "Opens like a gift. *Refills like a ritual.*" / 06 "Fine fragrance scents. *A bottle you keep forever.*" / 08 "A deodorant, if you *insist* on calling it that." | `2609_StaticRework` 4x5 01,02,03,04,06,08 viewed |
| Platform-native: Reddit post | Near-black `#0F1114`, dark-grey Reddit card, bold white sans title, cut-out bottle with glow bottom-right | "PSA from a deodorant founder: we're sorry. Natural deodorants have let you down before." Body: "We know. The rash is the bicarbonate of soda. The white marks are the formula. The 3pm check is the failure." / "So we didn't make a natural deodorant. We made an *anti-odorant*: pre- and probiotic, no bicarb, four years and 40 formulations." | `MDI_T1_M10`, Approved folder |
| Platform-native: meme caption | Full-bleed UGC photo, TikTok-classic ALL-CAPS heavy rounded sans, white with thick black outline and soft shadow, centred, 4 lines top third + smaller 2 lines, no emoji | "ME EXPLAINING TO MY FLATMATE THAT 27 MILLION DEODORANTS GET BINNED A DAY" / "AND MINE IS GLASS AND REFILLS THROUGH THE LETTERBOX" | `MDI_T1_M04`. The only place a native-app caption look appears among approved designed assets |
| Platform-native: newspaper clipping | Cream `#E9E2D0`, rotated clipping, masthead "THE BATHROOM GAZETTE · THURSDAY 11 SEPTEMBER 2026 · PERSONAL CARE · 14" | "We're sorry." / "Natural deodorants have let you down before. A small British brand says this isn't one." / caption "The bottle: glass, gemstone roller, refilled by paper sachet." | `MDI_T1_M11` |
| Platform-native: Trustpilot card | Blurred lifestyle photo, white review card, 5 green stars, "✓ Verified" | "I'd given up on natural deodorants. Then this." | `MDI_T1_M12` |
| Platform-native: tweet card | White background, X-style post, plum "Rollr" avatar, founder tag, lowercase Inter-like sans | "our deodorant is £45. it's expensive. / but we're not really selling deodorant. we're selling a product that goes from the most boring object in your bathroom to the most beautiful. and you never have to bin it." | `MDI_T1_M17` |
| Platform-native: handwriting on UGC photo | UGC photo, top-left brush-script (Caveat-like) white, no stroke, 4 lines tilted about -5 degrees, last line smaller; white serif wordmark bottom-right | "yes it's £45. / yes it's a deodorant. / yes I'm keeping it forever. / (refills are £3.75 a month, calm down)" | `MDI_T1_M24` |
| Other concept names seen in Meta/Drive (not viewed) | Review (Brief 4), Letter ("EverydayRitual"), IG_Meme (Brief 28, "protect-me-from-what-want"), Carousel (ChooseYourStone, "four-rollers-four-moods"), Venn_Diagram_LoFi, GemstoneApplication, SearchAd, BeforeAfter_UsVsThem, IG-native Typewriter (Wine/Black), Quiet Upgrade (B2), Not A Natural Deodorant (B3) | n/a | [N] |

Reddit, newspaper, Trustpilot and apology-letter stories are all the same "We're sorry / anti-odorant" message, which is the most corroborated message across approved assets.

---

## 6. Copy bank (verbatim)

Spelling kept as in the source. Items marked **[typo]** are not for reuse; the correction is noted.

### 6.1 On-screen hooks, creator and agency videos
- "Why does my deodorant look like a luxury beauty product?!" (a638e2df, headline)
- "A little reminder to slow down 🤍" (6b7d074c)
- "Who said deodorant had to be boring?✨" (e0890090)
- "Things I said "yes" to this year" (73b3b5eb)
- "the prettiest deodorant you've ever seen..." (88e563a9, typewriter)
- "Finally a trend I can participate in!" (842671ca)
- "I've tried 8 different deodorants.... This is the only one I go back to:" (4fd6e12b, revision video)
- "I've never loved a deodorant so much!!" (f935a4cb, revision video)
- "Dilemma of the day:" (57673ce6, revision video)
- "Deodorant: but make it cute" (9a68fa58, revision video)
- "I've never LOVED a deodorant like this:" (6e3aa987, revision video)
- "pov you learn the TRUTH🚨" (4dae61cc, revision video)
- Caption openers: "Ever since I upgraded" (e0d8d384); "this is the" (3a2543f1); "sweat patches are" / "impossible to stop when you're using natural deodorants" / "unless you upgrade" (1b3ad86b); "what the f***" / "is this" / "an upgrade on your deodorant" (8823223f); "my deodorant's all" (727f445d); "I've always loved romanticising" (4502ae23); "My days are pretty full-on" (020dc18c); "I love perfume" (a346d626); "as soon as November hits" (c7c2f01c); "FOUND" (6c5dbb39); "UPGRADING" (eac3fcdf); "DEODORANT" (25d4700a).
- Question hooks in captions: "Why are we investing in / luxury skincare, but / overlooking the one product / we use every day?" (fa4cab68); "If you're upgrading your / skincare and fragrance / your deodorant too?" (3631d6ba); "If you've also given up / on natural deodorants / this might be the alternative / that you're looking for." (fa57f0fa).
- Narration: "I upgraded my skincare." / "My makeup. My home." / "But somehow not my deodorant." / "Rollr feels like one of those small upgrades that makes everyday routines nicer." (26a245ae)
- Split-sketch labels: "Natural but Terrible" / "Natural and Luxury" (727f445d).
- Key-term tags: "Gemstone rollerball", "4 gorgeous scents", "2 rollrs + 6 refills for £100" (e0d8d384).
- Instruction text: see CN10.

### 6.2 Founder, price and objection hooks
- "We charge £45 for deodorant. Here's why.✨"
- "£45 for a deodorant?! We can explain...💫"
- "Almost £50? For deodorant? In this economy?" (comment card)
- "WHAT DO OUR CUSTOMERS LOVE ABOUT ROLLR?" (title card)
- "yes it's £45. / yes it's a deodorant. / yes I'm keeping it forever. / (refills are £3.75 a month, calm down)"

### 6.3 Meta headlines (CTA SHOP_NOW on all that have one)
- "The Last Deodorant You'll Ever Buy" (most common)
- **[typo]** "The last deodorant you'll every buy." (live on some ads; correct to "ever")
- "We use deodorant 22,000 times in our lives."
- "Meet Your Forever Deodorant"
- "Deodorant shouldn't be this beautiful." (Trybe ads)
- "Who said deodorant has to be ordinary?" (old)
- **[stray default, not reusable]** "Create stunning ads in minutes!" (on two older Caz ads)
- Partnership and Instagram-post ads carry no headline.

### 6.4 Meta primary texts
- Agency standard: "Deodorant shouldn't be this beautiful.\n\nA shelf showstopper. Swoony to smell. Sublime on skin. And sustainable too." (variants without the blank line or without the final full stop)
- Trybe ads: "Most deodorants are made to be thrown away. Rollr is made to be kept.\n\nOne bottle with a gemstone roller and proper fragrance. When it runs low you mix in a concentrated refill and carry on. Clean formula, works all day. Pleasure and planet, in that order."
- Older 2025/26: "WARNING: This deodorant is ridiculously gorgeous! \nBut don't let its good looks fool you... it's also crazy effective at keeping you fresh all day. Try it now and see for yourself why beauty meets brawn in our latest creation!"
- Charlie ad copy (from a file name, truncated): "I never thought I'd call a deodorant beautiful... until this arrived. Meet my new bathroom-s[...]"
- Pattern: one body text and a rotating headline are reused across nearly all agency ads; the on-video caption does the persuading.

### 6.5 Creator-posted partnership captions (their own words)
- Folklore: "What herbs are you growing in your garden this year? 🌿 \n\nTo get 10% off your first order of @rollrdeo, use code FOLKLORE10 at checkout 🌞 ..."
- ArinKaz: "Honestly… deodorant has never looked this pretty 💜\n\nWould you try a powder-to-liquid deodorant? 💜✨"
- Madishu: "@rollrdeo and I didn't even mention how long this formula lasts and how nice it smells💜"
- Fragrance Foundation: "#NFW26 first impressions 👀\nExploring @rollrdeo's new scent, Juniper: soft, bittersweet, quietly soothing."
- Skye and JARV posts exist (long personal copy / "Anyone else tried @rollrdeo ?").

### 6.6 End-card and designed-motion lines
- "22,000" / "That's how many times you use deodorant" / *in your life.* / "It should be *beautiful.*" / "22,000 times. Make every one of them Rollr." / "SHOP ROLLR · ROLLR.CO.UK"
- "Found: the beautiful way to quit plastic." / "non-plastic roll-on deodorant" / "non-plastic refillable deodorant"
- "We're sorry." / "Deodorant has always smelled so obviously like a deodorant." / "But this isn't a deodorant. It's crafted by perfumers. It's four scents worth wearing." / "And none of them smell like deodorant." / "We're only sorry you didn't find us sooner."
- "Bring More Balance to your day" / "Green Aventurine" / "A crystal for balance, calm & optimism."
- "A deodorant you'll love applying - and love leaving on display."
- "A natural, refillable, deodorant" (tagline in the SplitScreen template)
- "Natural Refillable Deodorant" / "Deodorants really shouldn't be this beautiful." (ASMR template)
- "Excellent" + 5 green stars + Trustpilot; "SHOP NOW"; "Shop Rollr"

### 6.7 Offer and price lines
- Black Friday gifting (spoken in e0d8d384): "any pair of Rollrs plus six refills for £100 ... total of £50 off ... each refill lasts two months"; tag "2 rollrs + 6 refills for £100".
- Christmas (spoken in 42099163 and c7c2f01c): "buy two and you get 33% off"; "the offer's running through most of November". A Black Friday folder exists in Drive (B1 - Black Friday).
- "Use code FOLKLORE10 for 10% off your first order" (Folklore overlay, hand-drawn small caps).
- "refills are £3.75 a month"; "£45" appears in founder hooks and statics.
- Spoken scarcity close in Dylan videos: "link down below... before they sell out" (and "sold out four times this year", from a transcript summary).

### 6.8 Static headlines
See the table in section 5 (kept there to avoid duplication).

### 6.9 Known typos and inconsistencies (do not copy)
- "The last deodorant you'll every buy." (live Meta headline)
- "Anti-oderant" (group names), "ANTIODRANT," (4dae61cc caption, revision video), "natural-refillable-deodorand" (ad-name slug)
- "Permission to get sweasty." (as printed on the lid per one note) vs "Permission to get sweaty." (other notes). Unresolved which is on the pack; do not retype the lid copy, show the box itself.
- "Gentlemen's Journal" (B11 roundel) vs "GENTLEMAN'S JOURNAL" (Awards card). Unresolved; check against the real award before typing it.
- "Roller" instead of "Rollr" in auto-captions (rule in section 7).
- Claims flagged by the note author as risk (not by the reviewer; all were approved): "best natural deodorant I have ever used"/"worked in beauty for over 15 years" (6c5dbb39), "sweat patches are impossible to stop ... unless you upgrade to Rollr" (1b3ad86b), "I've tried 8 different deodorants.... only one I go back to" (unverifiable).

---

## 7. Rules

"Stated" = the brand's own review comment says it. "Inferred" = the note author's reading of frames, comments or patterns.

| # | Rule | Source | Status |
|---|---|---|---|
| 1 | Spell **Rollr** exactly (capital R, o-l-l-r) in every burned-in subtitle and on-screen text. Auto-captions write "Roller". 12 of 14 revision requests concern this, alone or in part. Proofread the whole caption track, not just the hook. | Comments on 4fd6e12b, 16b90ca0, 57673ce6, 11cf42f3, 8a9b7ffe, 9a68fa58, c46d8445, e1503e25, 6e3aa987 (and "same comment as previous" on 198d2db0, 689949dd, ef5d34bd). "Roller" seen in 4fd6e12b and f935a4cb ("across Roller"), 57673ce6 ("So this is my roller"), 9a68fa58 ("This is Roller"). | **Stated** (the "Roller" examples are SEEN in frames) |
| 2 | Captions must not overlap each other or other text. Keep one caption layer, one line at a time, in a clear zone, not on hands, mug or product. | f935a4cb "subtitles are overlapping"; frames show lines stacked inside one box on the chest/hands, and a caption on the mug in 4fd6e12b | The comment is **stated**; the "one layer, clear zone" guidance is **inferred** |
| 3 | If the bottle is shown being smelled or used, it must actually contain product. Fill it first, then film smelling/rolling. | 6e3aa987 "when you smell the bottle, there's no product in it" | **Stated** |
| 4 | Blur competitor logos. | 4dae61cc "blur out the Lynx logo on the bottle". Enforcement looks inconsistent: unblurred competitor cans appear in approved Dylan videos (3a2543f1, 1b3ad86b, 8823223f, Mitchum can in 82807831), while 727f445d pixel-blurred them. | The Lynx comment is **stated**; "blur on anything new" is **inferred** |
| 5 | Offer a clean, no-subtitle version. The brand asked one creator to upload a version without subtitles. The agency has its own caption template (brand uploads). 15 of 46 approved videos have no on-screen text. | eac3fcdf "Can you please upload a version without the subtitles?"; clean/captioned pairs exist | Request **stated**; generalising it is **inferred** |
| 6 | Burned-in captions that misrecognise words are a risk (examples: "ANTIODRANT," in 4dae61cc; eac3fcdf shows "ARE SOPHISTICATED" for the spoken "gemstone"). | Frames | **Inferred** |
| 7 | Avoid mirrored front-camera shots when the logo is in view (box text reads backwards). | Visible in 6e3aa987; no comment about it | **Inferred** |
| 8 | Caption size: not tiny, not low-contrast. Examples that were requested again or flagged: a thin light lavender/white serif with a faint glow over a busy scarf and purple box (57673ce6), captions about one third the size of the other revision videos (9a68fa58). | Frames; the written comment on 57673ce6 is only about spelling | **Inferred** (no comment mentions size or contrast) |
| 9 | Do not let captions cover the product or hands. | Frames of 4fd6e12b / f935a4cb | **Inferred** |
| 10 | Revision-video visual defects seen (none quoted in comments): no product on screen for the first 17 s (4fd6e12b); 0-3 cuts over 42-50 s of static selfie (f935a4cb, 57673ce6, 9a68fa58, 6e3aa987); dim low-contrast dark brown background (4fd6e12b); a third-party shirt logo ("HILFIGER 1985") visible through the whole video, extreme close-ups with the bottle blurred, hand over the lens, heavy handheld shake and a cluttered fur-throw/tufted-wall bedroom (4dae61cc); meme/comparison tone instead of "quiet luxury" (4dae61cc). | Frames of six revision videos | **Inferred**. These appear only in revision videos, so they are risk patterns, not confirmed rules |
| 11 | Not pushed back on in any comment (so not rules): length (approved up to 110.9 s), hook style, lighting, handheld shake, face or no face, profanity censored in a caption, sweat-patch and "best natural deodorant" claims, "natural deodorant" vs "anti-odorant" wording. | 5d of the Trybe note | **Inferred** |
| 12 | Trybe-sourced ads: destination URL must carry `trybe=<trybe_id>` and the ad name must end with it, or the ad is unattributed and the creator is unpaid. | Trybe tool instructions; ad names follow it | **Stated** (tool instruction) |
| 13 | Clean, tidy edits get fast approval: one headline or none, clear product reveal, bathroom/vanity/plum-box set. Positive comments: "Excellent - launching it today", "love this", "great stuff", "Amazing". | Comments on 6b7145a6, 88e563a9, aaf7ea9e, 6b7d074c, 26a245ae | Comments **stated**; the pattern is **inferred** |
| 14 | Deliver 9:16 and 4:5 from one master. | 6c5dbb39 / 90ea1855; statics always in pairs | **Inferred** from file pairs |
| 15 | No emoji, stickers or highlight colours in designed brand pieces; keep them to hook captions on UGC if used at all. | Designed pieces viewed contain none; scope limited to those pieces | **Inferred** |

---

## 8. Choosing a style for a new raw video

| Raw footage | Recommended editing style | Caption style | Why / how well supported |
|---|---|---|---|
| **Talking head to camera, holding the bottle, no cutaways** | E1 (default) | CA1 (white bold sans, lower third, one italic-serif emphasis word) | E1 is the top spender (GBP 34.2k lead ad). The evidence is a single cover frame, so cut rhythm is a guess. If the take is under ~60 s and has many cut points, E5 is the best-documented alternative. |
| **Talking head with a few product inserts** | E12 | CA8 (white pill, grey upcoming words, plus plum key-term pill for offers and features) | The only agency-made template with full frames (brand upload). $0 spend so far, so it is documentation-backed, not performance-backed. |
| **Male creator / many props and competitor cans** | E5 | CN1 (yellow keyword, lower third) | $1,229 on 82807831. The only CapCut-style that carries colour. Blur competitor logos (rule 4). |
| **Hands-only demo, no speech (or voiceover added)** | E2 | CN6: one hook headline in the first ~3 s, then nothing (default). Or deliver clean for captioning. | a638e2df used exactly this and is the best creator ad ($3,033). CN3 and CN4 running subtitles exist but the CN3 example was the weakest per dollar. |
| **Voiceover + b-roll** | E2 for hands/product footage, E4 for aesthetic or "ugly object" b-roll | CN4 (lower-third native) or CA3/CA4 plum-and-serif styles (cover frame only) | Voiceover demos in E2 are the strongest evidence; E4 has large GBP spends but cover-frame-only evidence. |
| **Silent aesthetic b-roll, no voice** | E6 as delivered (no text) | CN12 (none). Or E7 with CN9 (narration serif) for a story | E6 has the best ROAS among sizeable spends (1.85 on $474). E7 on the same footage (26a245ae) ran at ROAS 2.01 on $40, small sample. |
| **Silent step-by-step refill tutorial** | E7 | CN10 (wide light sans instruction text) | aaf7ea9e, approved, $0. Sparse evidence. |
| **Founder / podcast / mic clip** | E3 | CA2 (plum rounded boxes, white italic serif, top third, ✨ or 💫) | Two founder ads total GBP 11.5k+ spend (cover frames). |
| **Customer call / interview** | E9 | CA5 | Cover frames only. |
| **Price objection; creator reaction + b-roll** | E10 | CA7 (comment card) | Cover frame only, small spend. |
| **Product stills or CGI, no footage; apology/proof/message** | E8, E16 or E17 | CA10 (designed serif with one italic word) plus the end-card system (2.4) | Full-frame evidence, approved folder for E17; the apology message has the best value per spend among the top four statics. |
| **Short product clip needing a branded layout (4:5)** | E13 | CA13/CA6 | Cover frames, small spends. |
| **Long single-take selfie with an offer** | E14 | CN5 or CN4 (native lower third) | Brand never objected to length, but spend and ROAS were poor. Prefer cutting down. |
| **Raw Trybe creator upload, brand asks for clean** | Do not burn in captions; deliver clean (CN12) and a separate captioned cut | CA8 if the brand wants captions | Feedback to Kate Allan; agency has own template. |
| **Two-character comedy or sketch** | E18 | CN1 | One example, $0. |

If nothing in the table fits: use **E2 + CN6**, the best-documented high-spend creator combination; for anything with a face, use **E1 + CA1** on the strength of spend alone and check against section 9 as soon as a real master can be opened.

Always: spell Rollr correctly; fill the bottle before it is smelled; keep captions out of the top ~15% and off the product; export 9:16 and 4:5.

---

## 9. Open gaps (inspect once larger files are reachable)

High-value files named in the notes, all currently unopened. Two routes exist: a Drive route (API/rclone access or compressed proxies under ~5 MB) and a Trybe route (signed original links worked for all 40 creator downloads; Meta and Drive do not offer this).

1. **Caz UGC, the top spender (GBP 34k):** `Caz.mp4` (85.2 MB, id 1tQJXXNsWaRnanR2-X4EH-cRirc-Mopre, in `07_July/Demand Gen Suggestions` and `05_May/Client UGC/UPLOADED`), `Caz4x5.mp4` (84.2 MB). Needed: cut rate, hook, caption animation.
2. **Chloe_Shout_Hook2** (GBP 14.8k, #3 by spend; Meta returned no cover image because it is a SHARE/IG-post creative); folder `09_September/Chloe Shout UGC`.
3. **Founder edits:** `09_September/B1 - Founder Edit V3`, July `Brief 14 - Founder Reply` (>500 MB, Milo_ReplyToFounderAd), "FOUNDER AD REPLY- BRIEF 14 -r2".
4. **Demand Gen Suggestions** (the "approved launch videos" folder, 7 videos, 45-336 MB): why is rollr more expensive_music, Laura_May_Hook 3_9x16, Hook B - Customer Call - Vicky -9x16, V2.B_JAVR_RollrDeodorantWorthThePrice_UGC_9.1.mov, Rollr Selena 9x16, HOOK 3 - MASH UP ROLLR-9X16.
5. **Agency caption cuts:** the `UGC/With Subtitles` folder (14 files; smallest is `ClaireMartinez_UnnecessarilyGorgeos_Icon.mp4`, 8.08 MB, id 1SkaDaYnTPjfjL0iKeNU3fy-3zovYlSQj), `BrookeM_NoSubs.mov` (44.7 MB) vs `BrookeMaunders_withSubs.mov` (47.3 MB), `REECE_2V_SUBS.mov` (46.7 MB), and the Black Friday UGC "Hook 1 (with captions)" vs "(without captions)". These pairs would show the agency subtitle style directly.
6. **Finished Ads (6 Oct Update):** Nia, Karen, OliviaG, ChloeH, DR Self-Transcendence Hooks 1-3, B4 Open It Use It Refill It Mashup, B2 Quality UGC Mashup Hooks 1-4 (4:5 + 9:16, 45-157 MB). Treated by the notes as the clearest "final cut" signal for October.
7. **October concepts never viewed:** DR Sensory Appeal Hook 1-3, B5 The Forever Rollr (+ `_Short`), Proof Day UGC, Karen_HiddenVillan, Sam BuyingJourney, Nia GirlMath.
8. **Videos of 6.4-10 MB** that fail at the ~6 MB limit: Brief4_1 (4x5, 9x16), Brief5_1_9x16, Brief5_3 (4x5, 9x16), Press_Quotes_Brief1_P1 Animation1/2, Rollr_GemstoneVideo_Brief8_4x5, TheTimesPressAd_3 (4x5, 9x16), Tell Me About Yourself r2 9x16, AwardsMotion_Brief3_9x16_Audio1, UsVsThemAnimatedStaticBrief_1; plus the 2023 `ASSETS/rollr motion` references (mostly under 6 MB and downloadable, never analysed).
9. **Meta:** a next page of lower-spend ads is unlisted; cover frames missing for Chloe_Shout, Laura_Hook3, JARV, Selena, ArinKaz, Cher, Brief25 ScentFraming, Emily, Andreea, WooWoo, Girl Math, Laura V3; five video ids unresolved (1156965116588706, 961372743595908, 1688871249097071, 1626746798556545, 904737365615232).
10. **Trybe:** 8 revision videos not viewed (16b90ca0, 11cf42f3, 8a9b7ffe, c46d8445, e1503e25, 198d2db0, 689949dd, ef5d34bd); the second half of about 15 batch-2 videos; the last seconds of about 10 videos (possible missed end text); the approved image 88f8c84a. The final Meta ad may differ from the Trybe upload.
11. **Docs:** "Rollr Meta Primary Texts & Headlines" is header-only (no copy). Unread but named: "Rollr Budget", "UK Launch Early Numbers", the Demand Gen YouTube channel-setup doc, and the Wonderland video-brief template (a sibling-client "Holly template" doc exists). No audio or music analysis was done anywhere.
12. **Open factual questions:** the exact lid copy ("sweaty" vs "sweasty"); "Gentleman's/Gentlemen's Journal"; the meaning of `Roll`/`Refi`, `EDU_T4` and `r1/r2` suffixes (all inferred); how the Top 4 sheet's "VID_Founder_Upgrader" maps to the Founder ads (by name only).
