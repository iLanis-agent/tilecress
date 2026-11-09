# Tilecress 1.0 TEST
Native Android Tilepaint whole-tile line-total deduction puzzle. Android 8+ (min26), target35. Package com.gg007.tilecress. Twelve original unique boards on a compact 4x4 grid.

## Rules
Tilepaint deduction on a 4x4 grid. Tap any cell to shade or clear its whole outlined tile. All cells of a tile must share one color. Top clues give dark-cell totals for columns; left clues give dark-cell totals for rows. Labels show current/target. Count cells, not tiles and not consecutive runs. This edition has no internal clue blocks, only full-row and full-column totals. No connectivity, separation or solid-square restriction. Twelve original abstract tile layouts and unique shadings, not guaranteed picture silhouettes. Unlimited whole-tile undo/reset, next and level selection. Saved palette and optional dark cell marks. No timer, score or drag controls.

## Download and status
https://mega.co.nz/#!tdkBAaQY!uMnXzTdzaxhAAhefeXkDbFYeyXaPyT6PDyMN9ntUw70
APK SHA256 dfec45ae6ac82f6c81cabfb92a2b00c23ee45b060495ffa9100c10c1e1f8289d; 16878 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
Independent coordinate row/column counters and sets of room colors versus production bit counts and pairwise uniformity passed 786,432 complete board masks and 524,288 individual line counts. Each of twelve original 4x4 seven-tile boards has exactly one shading, and all twelve shadings differ. Tests cover multi-line tile coupling, zero/full line targets, bounds, undo, reset and solved lock. Portable generator seed 540609 reproduces twelve distinct layouts in 14 attempts. Actual drawing-adapter taps solve all twelve boards; solve/undo/replay, next, levels, menu, privacy and saved palette/dark marks pass. Six drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 185 prior studio descriptions and targeted functional terms across 803 web registry records. Paintcress also flips entire rooms, but uses local dark-neighbor cell clues, dark connectivity and both-color 2x2 bans. Tilecress instead solves eight global line totals coupled by irregular tiles; it has none of those adjacency or connectivity rules. Weightwake uses position-weighted sums and independent cells; Tilecress uses unweighted cell counts and whole-tile choices, so one choice changes several line constraints. Inkgrove uses ordered run lengths, not full-line totals plus pre-outlined uniform tiles. No Tilepaint match found in the reviewed corpus; repository corpus remains partial. Known Tilepaint adaptation with original abstract boards, code and visuals; no copied layouts, code or art. Full-line edge clues are this edition, not internal segmented clues or promised pictures.
Rules https://www.nikoli.co.jp/en/puzzles/tilepaint/ ; independent rules https://www.cross-plus-a.com/html/cros7crpv.htm .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/tilecress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.tilecress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Tilecress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, dark cell marks and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 186-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/aemqvjs1u5w1-tilecress-source-archive . Repository https://github.com/iLanis-agent/tilecress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
