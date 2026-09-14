DUST & DEAD v12

Changes:
- Enemy fire rate is randomized from 1 to 3 seconds (2 seconds average).
- Player fire cooldown is 0.3 seconds.
- Player/enemy projectiles and particles render at exactly 2x2 pixels.
- Every zombie, skeleton, and witch hit calls its corresponding sound:
  Zombie: sound/Zombie_hit.m4a
  Skeleton: sound/Skeleton_hit.m4a
  Witch: sound/witch_hit.m4a
- Enemy shots use the general shooting sound quietly:
  sound/hit.m4a
- Player hits create a short generated buzz and stronger screen shake.
- At exactly 1 HP, a flashing red danger overlay appears.
