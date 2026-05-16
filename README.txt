Threadbound - Recall Prototype

>> https://joenasriani.github.io/threadbound-game/


Contents:
- index.html
- assets/threadbound_actor.glb

Notes:
- The GLB actor is a local original segmented low-poly 3D model included for replacement testing.
- The code also includes a procedural fallback character if the GLB fails to load.
- The game uses Three.js from unpkg, so it should be tested from HTTPS, localhost, or an itch.io HTML upload with internet access.
- Level 3 has been removed. This build includes Level 1 and Level 2 only.

Core rules preserved:
- No automatic ghost summon.
- Recall appears only when standing on a trigger.
- Ghost starts from recorded segment start.
- Ghost does not move during apparition.
- Obstacles open only while trigger is physically held.
- Level 2 is longer than Level 1.
