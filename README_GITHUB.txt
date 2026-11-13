MCB V56.4 — MP4 custom player integration test

Upload all THREE HTML files to the root of your new GitHub Pages test repository, replacing the existing files. Keep filenames exactly as supplied.

This version reuses the V55 original custom player for MP4 as well as MP3; only the media routing/bridge was modified. The file original-v55-audio.html keeps its old filename to avoid breaking existing deployments, but now handles both audio and video.

TEST: MP3 first, then MP4 waveform, scrub, Shift-drag, loop, speed, fullscreen, float. YouTube still uses basic embedded playback; no changes to its player.

Local media still needs relinking after browser/session or storage changes. Persistence is a separate planned improvement.

JavaScript syntax checked; playback not verified in a real browser. Keep V56.3.1 ZIP as a rollback.
