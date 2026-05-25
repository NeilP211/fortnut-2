# FORTNUT 2 🌰🔥

> Top 1 game of all time

[![▶ Play on GameJolt](https://img.shields.io/badge/▶%20Play%20on-GameJolt-CCFF00?style=for-the-badge)](https://gamejolt.com/games/fortnut2/551302)
&nbsp;
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white)

<p align="center">
  <img src=".github/media/fortnut2-hero.jpg" alt="Fortnut 2 banner art" width="680">
</p>

**Fortnut 2** is a first-person shooter I designed, coded, modeled, and published on my own. 
Custom-modeled skins and lots of easter eggs you will find. It started as me messing
around in Unity and I ended up working on it for fun.


## 🎮 Play it

▶ **[Download on GameJolt](https://gamejolt.com/games/fortnut2/551302)**. It's a standalone **Windows** build (no Unity install needed).

## 🛠️ Under the hood

- **First-person movement & camera:** WASD movement, mouse look, and jumping (`Player_Controller`, `Camera_Controller`).
- **Weapons & shooting:** projectile/clone spawning, weapon switching, and a dedicated Uzi spawner (`Instantiate*`, `Change`, `clonespam`).
- **Health & damage:** a health model wired to an on-screen health bar (`Health`, `HealthBar`), plus shoot-to-destroy targets (`destroyedwhenshot`, `bloodsplatter`).
- **Movement toys:** jump pads (`JumpBoost`), a fly/noclip mode (`Fly`), and kill-plane plus fall logic for respawning (`DeathPlane`, `fall`).
- **Secrets & scoring:** a hidden door (`HiddenDoor`), enemy head-tracking (`HeadTurn`), and a card-based score system (`FNCARD`, `fncardscore`).

## 🎨 Built end-to-end, solo

- **Code:** all gameplay scripting in **C#** inside **Unity**.
- **3D art:** custom characters **Blender** (characters you might recognize: `Omega.blend` and `Fishstick.blend`).
- **Ship:** packaged and **published to GameJolt** so anyone could download and play.


## 🚀 Run it from source

```bash
git clone https://github.com/NeilP211/fortnut-2.git
```

1. Open the folder in **Unity Hub** (open with a matching LTS version; let it resolve packages).
2. Load `Assets/Scenes/SampleScene.unity` (or `Assets/QS/Scenes/main.unity`).
3. Press **Play**.

> **Heads up:** this repo ships its full asset library (skyboxes, weapon packs, `.blend` files), so it's a chunky clone. 
