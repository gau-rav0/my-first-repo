# Interaction checks

Verified in the managed Chrome preview:

- Root opens locked with the classic water-droplet wallpaper.
- Slider keyboard End unlocks the phone.
- App navigation works after unlocking at desktop and 390px widths.
- Auto wallpaper rotation advances from Classic to Beach after unlocking.
- Manual Mountains selection disables rotation.
- Reloading resets the wallpaper to Classic.
- Settings can relock the phone.
- Camera roll opens photo details; Next advances to the next image.

Native range dragging and gallery swiping use browser pointer interactions; the automated checks exercised keyboard unlocking and photo buttons. Reduced-motion preferences disable decorative animations and crossfades. The lock screen is a visual interaction, not an authentication boundary.

## Centered interface update

Verified in desktop Chrome and a 390px responsive frame: natural-language sports and contact searches, Enter-to-open a result, recent apps, double-click Home, project list/detail/back, and Notes tab navigation. The core scripts pass `node --check`. Search uses a local keyword/intent index with factual, predefined results.
