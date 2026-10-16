# Men of the Docks — provisional cue sheet

The supplied script was aligned locally to the decoded audio using PocketSphinx 5.0.4. All 311 normalized words were covered in script order. This is forced alignment of the supplied text, not an independent transcription or human listening review. Three dictionary pronunciations were added for alignment: impasto, reprieved, and voyeurs. Every cut point remains provisional.

**Clock reference:** source times begin at the first sample of `VO_48k_24bit.wav`. Sequence timecode is true 30 fps, non-drop-frame, with a 45-frame (1.5-second) visual lead-in. Sequence markers use rounded source seconds × 30 + 45. Do not add an MP3 encoder-delay offset. A source time such as 80.74 seconds is not the same clock as the sequence timecode.

## Picture cues

| Cue | Audio seconds | Sequence TC | Visual direction |
| --- | ---: | --- | --- |
| GALLERY OPENING | — | 00:00:00:00 | Gallery wide with small title; proposed 1.5-second lead before narration. |
| FULL ARTWORK | 6.67 | 00:00:08:05 | Cut from gallery to complete painting; establish workers against vessel. |
| WINTER SETTING | 10.58 | 00:00:12:02 | Full composition, then a slight drift toward river and cold foreground. |
| FOREGROUND TEXTURE | 30.75 | 00:00:32:07 | Lower foreground; allow brushwork to read without over-enlargement. |
| BOLLARD AND WAITING | 37.45 | 00:00:38:29 | Frame bollard with workers visible; move gently toward the group. |
| BACK-FACING FIGURE | 48.89 | 00:00:50:12 | Back-facing central figure with surrounding workers; restrained push. |
| COATS AND POSTURE | 57.97 | 00:00:59:14 | Optional closer framing of clothing and posture if resolution allows. |
| LEFT FIGURE | 66.13 | 00:01:07:19 | Figure beside warehouse; keep shadow and empty space; mostly static. |
| MANHATTAN SKYLINE | 80.74 | 00:01:22:07 | Skyline with waterfront; small upward drift. |
| HORSES AND CITY | 87.67 | 00:01:29:05 | Optional wider cut reconnecting foreground horses with distant buildings. |
| GROUP CONTEXT | 94.69 | 00:01:36:06 | Show group before isolating the blue jumper. |
| BLUE JUMPER | 98.24 | 00:01:39:22 | Favor blue-clad figure while retaining surrounding dark coats. |
| LINER | 111.76 | 00:01:53:08 | Ship hull and superstructure together; gentle upward reveal. |
| RETURN TO WHOLE | 124.90 | 00:02:06:12 | Broad composition reconnecting workers, city, and ship. |
| REFLECTIVE HOLD | 141.97 | 00:02:23:14 | Complete artwork or modest wide view; let narration lead. |
| ATLANTIC PASSAGE | 149.35 | 00:02:30:25 | Continue a quiet full view; no map or additional imagery. |
| FINAL ARTWORK VIEW | 160.51 | 00:02:42:00 | Final unobstructed full view; workers remain readable. |
| GALLERY RETURN | 174.88 | 00:02:56:11 | Return to gallery for closing title and short final hold. |
| COMMENTARY CREDIT | 177.08 | 00:02:58:17 | Commentary: James Darcy; retain a distinct George Bellows painting credit. |

Some cues identify a change of emphasis within the same shot rather than requiring a cut. For example, hold the full view through the Atlantic passage if a second wide shot would feel repetitive. The ship cue is deliberately placed on “Liverpool,” the first content word of that sentence.

## Paragraph speech boundaries

These are aligned first-to-last word boundaries. They exclude the following pause and are not shot durations.

| Paragraph | First words | Source in (s) | Source out (s) | Sequence in | Sequence out |
| ---: | --- | ---: | ---: | --- | --- |
| 1 | There is no ambiguity in George Bellows’… | 0.39 | 10.17 | 00:00:01:27 | 00:00:11:20 |
| 2 | Before us lies a squalid New York… | 10.58 | 29.86 | 00:00:12:02 | 00:00:31:11 |
| 3 | In the foreground, impasto brown sludge marks… | 30.75 | 47.69 | 00:00:32:07 | 00:00:49:06 |
| 4 | Their foreman stands front and center. As… | 48.89 | 65.22 | 00:00:50:12 | 00:01:06:22 |
| 5 | To the left, a rejected figure walks… | 66.13 | 79.87 | 00:01:07:19 | 00:01:21:11 |
| 6 | Across the water, the newly built skyline… | 80.74 | 92.98 | 00:01:22:07 | 00:01:34:14 |
| 7 | In the gathered crowd of faceless lives,… | 94.69 | 110.87 | 00:01:36:06 | 00:01:52:11 |
| 8 | A Liverpool ship in the livery of… | 110.87 | 123.93 | 00:01:52:11 | 00:02:05:13 |
| 9 | Bellows captured the epitome of a biting… | 124.90 | 141.18 | 00:02:06:12 | 00:02:22:20 |
| 10 | Bellows painted on his own terms, with… | 141.97 | 159.65 | 00:02:23:14 | 00:02:41:05 |
| 11 | Men of the Docks stands as a… | 160.51 | 173.94 | 00:02:42:00 | 00:02:55:13 |
| 12 | Men of the Docks. By James Darcy.… | 174.88 | 178.31 | 00:02:56:11 | 00:02:59:24 |

## Premiere import checks

Relink the WAV if asked. Confirm 1920 × 1080 at true 30 fps and set/check Rec.709 in Premiere. Confirm the mono voice is centered in the output. Scrub each provisional marker while listening and move it as needed. Check that the audio begins at 00:00:01:15, the frame-rounded audio clip ends at 00:03:01:04, and the planned sequence finishes at 00:03:03:04. Blank video tracks and the final empty hold may be handled differently on import; restore them if needed. Native Premiere import has not been tested here.
