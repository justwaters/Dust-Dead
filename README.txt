DUST & DEAD v13

Changes:
- SPACE now fires (same as left click). Both can be held down to
  auto-fire as soon as the 0.3s cooldown clears.
- Added a score system: zombies 100, skeletons 150, witches 200,
  the bison boss 1000. Current score shows in the HUD; your best
  score is saved locally and shown on the level-complete/death/win
  screens.
- Added pause: P or Esc pauses/resumes and stops the music.
- Added a mute toggle: M key or click the speaker icon in the HUD.
  Mutes music and all sound effects.
- Enemy fire rate is randomized from 1 to 3 seconds (2 seconds
  average) instead of a fixed 0.3s, so firefights breathe.
- At exactly 1 HP, a flashing red danger overlay appears again, and
  getting hit adds a bit of screen shake.
- witchCast/witchHit fall back to the general hit sound (sound/hit.m4a)
  until a dedicated witch sample is dropped into sound/ (see
  sound/PUT_WITCH_HIT_SOUND_HERE.txt). The boss no longer replays the
  full boss_battle.mp3 track as a hit sound on every punch.
- Restarting (Enter or the Restart button) now goes through one
  shared startGame() path, so score/music reset consistently either
  way.
