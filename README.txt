FINAL SINGLE-FILE LUA - OPTIMIZATION REVISION 2026.11.14.1

1.lua is the ONE complete source and phone file: configuration + login + channel + HUD + all features. No split Lua modules or build step are required.

Phone path:
/storage/emulated/0/Android/data/com.pubg.imobile/files/MEOW/1.lua

The current top configuration is your supplied Offline Free entry, version 1.0.0. Server authentication/branding/status still requires internet; feature code stays local.

For Online Paid/Free updates: upload THIS SAME full 1.lua into the selected Online entry in Lua Manager. The existing panel recognizes it, replaces its login prefix for that selected entry and preserves the optimized feature body. For this saved-session update, download that entry's new starter once after deploying the website; then reuse it for compatible feature updates. Do not replace the online starter with this Offline Free configured file.

Editing: change link/version/key type in the first configuration block. Find features by the // FEATURE NAME // separator. Performance settings are in PERFORMANCE SETTINGS / SHARED CACHE, immediately after login. See docs/SOURCE-INDEX.json for exact section line numbers.

Overlay line/ESP2 refresh defaults to 30 Hz; this does not cap game FPS. All existing named feature functions are retained. No forced GC, CPU-frequency tweak or game-quality reduction was added.

Implementation, syntax, mocked runtime and operation-count checks passed. Actual phone FPS/CPU/thermal improvement and complete all-options gameplay acceptance remain for your later test. Previous source and development-only fragments are backed up privately outside this folder.

2026-11-14 saved-session update: manual key entry once; successful key saved in MEOW/SuperPakUserKey.txt and auto-validated after restart. Server status checks remain silent every 120 seconds. Temporary connectivity pauses features and retries automatically, while signed disable/block/expiry shows a notice. New generated website starters contain the same behavior. Update/download online starters after deploying the website; old starters do not self-update.
