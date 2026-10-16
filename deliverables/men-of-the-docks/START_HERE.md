# Men of the Docks — Premiere picture edit v3

This package contains an authored 1080p picture timeline: **14 image shots, 19 provisional narration markers, animated framing, opening and closing titles, black fades, and the complete voice-over**. Duration: **00:03:03:04 at true 30 fps** (about 3 minutes 3 seconds).

The two images are visible in the chat but were not exposed as downloadable media to this workspace. Their image clips are therefore **offline references** to the originals on your computer. No painting or gallery image has been regenerated or substituted. This is an importable edit for review, not a rendered film or a native `.prproj`.

## Open it in Premiere Pro 2026

1. Extract the entire ZIP to a permanent folder. Keep the `Media` folder and the WAV with it.
2. In Premiere, open or create a project and choose **File → Import**. Import `Men_of_the_Docks_PICTURE_EDIT_v3.xml`.
3. If Premiere asks for media, locate the bundled WAV and the files inside the extracted `Media` folder. Enable automatic relinking of other media where available.
4. For `PAINTING_ORIGINAL_5935x4226.jpg`, locate **your original painting file at 5935 × 4226**. Its actual name and extension can differ; relax filename/extension matching if necessary. Use the full-resolution original, not the 1280-pixel planning copy.
5. For `GALLERY_MOCKUP_1672x940.png`, locate your gallery image. Its **1672 × 940** size is confirmed. Premiere scales this source inside the **1920 × 1080 sequence**; the gallery's dimensions do not determine the sequence size.
6. Open the sequence named **Men of the Docks - PICTURE EDIT v3 - RELINK TWO IMAGES** and save the project as a native Premiere project.

The image names above are references, not bundled placeholder pictures. You do not have to rename or modify your originals.

## Check the import

- Sequence: **1920 × 1080**, progressive, square pixels, **30.00 fps**, non-drop-frame. Set/check **Rec.709** in Premiere; this minimal interchange file does not establish color-management settings.
- V1 is the charcoal matte; V2 is the image edit; V3 contains transparent title movies; V4 contains the opening and closing black fades. A1 is the narration.
- Narration begins at **00:00:01:15**. Its frame-rounded clip ends at **00:03:01:04**. The sequence ends at **00:03:03:04**.
- **Do not apply Set to Frame Size or Scale to Frame Size to the authored image clips.** Their Scale and Position keyframes are already calculated for the declared source dimensions.
- Keep the painting's Motion Anchor Point centered at **2967.5, 2113**. For the expected gallery source it is **836, 470**.
- Check that the mono narration plays centered. The audio was converted to 48 kHz/24-bit WAV without deliberate gain changes or processing.
- The title movies and black fades are ProRes 4444 with alpha. If a title shows a black rectangle, check its alpha interpretation: the files contain straight alpha and a transparent background.
- Listen at every narration marker and adjust the picture cut or emphasis as needed. These cue points came from automatic forced alignment of the supplied script; they have not received a human listening review.

If XML transfer changes the motion, `PREMIERE_MOTION_KEYFRAMES.csv` contains every authored keyframe as native Premiere **Scale %, Position X/Y in pixels, centered Anchor Point, and sequence timecode**. `PICTURE_SETTINGS.md` gives a shorter shot summary. The animation uses sampled gentle easing to avoid reliance on importer-specific Bezier controls.

## Confirmed dimensions

**Sequence and export: 1920 × 1080.** Painting original: 5935 × 4226. Gallery source: 1672 × 940. Both source sizes were confirmed by the user. Scale and Position are authored for those source sizes within the 1080p sequence. Do not resize or recompress your originals to match the sequence or reference names.

## What is included

- `Men_of_the_Docks_PICTURE_EDIT_v3.xml`: 14-shot animated picture edit, titles, fades, voice-over, and 19 cue markers.
- `VO_48k_24bit.wav`: the complete decoded narration, about 179.632 seconds.
- `Media/`: transparent opening/closing title movies, black fade movies, charcoal matte, and an editable vector title layout.
- `SHOT_PLAN.md`: direction linked to the supplied narration.
- `CUE_SHEET.md` / `.csv`: provisional source-audio and sequence cue times.
- `PICTURE_SETTINGS.md` / `PREMIERE_MOTION_KEYFRAMES.csv`: authored framing and Motion settings.
- `NARRATION.txt`: the user-supplied script, preserved verbatim.

No music is required or included. The close credit uses “Commentary · James Darcy” to distinguish that attribution from “George Bellows · 1912”; confirm the desired credit wording before delivery. The gallery mockup is a visual setting and is not identified as the painting's real museum.

## Validation and finishing

Verified here: the XML explicitly declares a 1920 × 1080 sequence; sequence continuity; 14 shots and 19 markers; authored crop bounds; source resolution for artwork details; native Motion math; XML structure and media references; title/fade frame counts and alpha transparency; and archive integrity. Artwork detail crops retain at least 3145 source pixels across, exceeding the 1920-pixel output width. The gallery receives a modest upscale from its confirmed source resolution.

Not verified here: native Premiere import and keyframe interpretation, playback against the local original images, human confirmation of every narration cue, and the final rendered film. The actual image media is not included, so a representative picture render could not be made here. Review all subject positions, painting edges, transitions, title placement, and audio in Premiere before export.

For a review export, use H.264 at 1920 × 1080/30 fps, approximately 15–20 Mbps, AAC at 48 kHz, and high-quality scaling. Watch the exported file in real time before delivery.
