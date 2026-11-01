# Abhiram Krishna

I build machines that sense and react. These are the code repositories of my projects.

## 1. FTC Team Orbit #28831 – DECODE 2025–26 (team project)
🔗 [Orbit_Internationals](https://github.com/Unbeatable171/Orbit_Internationals)

I was captain and **lead programmer**, and I wrote this codebase.

**Key files:**
- **Shooter calculator:** `ShooterCalculatorRed.java` / `ShooterCalculatorBlue.java`. Projectile-motion model: fixed entry angle → hood angle, quadratic velocity-to-RPM regression, shoot-while-moving compensation.
- **Flywheel control:** `SUBSYSTEMS/FlyWheelSubsystem.java`. Dual-zone PIDF with voltage compensation.
- **Autonomous:** `AutoRedClose.java` / `AutoBlueClose.java` (21-ball), `AutoRedFar3.java`. State-machine routines using Pedro Pathing.

**Others' contributions:** Aryan Goyal and Arav Bahuguna (whom I trained) tuned autonomous and position values. Mentor Shaadab and Aarav Dewan wrote a turret controller (`TurretSubsystemAaravDewan.java`) that we did not use. Commits by Cal Kestis / Craig MacFarlane are from the official FIRST SDK this project is built on.

**Note:** when I couldn't be at the Dubai lab, teammates sometimes committed my code from their computers, so some commits under their names contain my work.

**Libraries:** FTC SDK, Pedro Pathing, SolversLib, FTCLib, FTC Dashboard, goBILDA Pinpoint.
**AI use:** for V2, I designed the logic and Claude helped me turn it into Java while I learned; for V3, I modified the code myself and used Claude and Codex to cross-check logic and debug.
