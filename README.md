# Abhiram Krishna

I build machines that sense and react. These are the code repositories for my MIT Maker Portfolio.

## 1. FTC Team Orbit #28831 – DECODE 2025–26 (team project)
🔗 [Orbit_Internationals](https://github.com/Unbeatable171/Orbit_Internationals)

I was captain and **lead programmer**, and I wrote this codebase.

**Key files:**
- **Shooter calculator:** `ShooterCalculatorRed.java` / `ShooterCalculatorBlue.java`. Projectile-motion model: fixed entry angle → hood angle, quadratic velocity-to-RPM regression, shoot-while-moving compensation.
- **Flywheel control:** `SUBSYSTEMS/FlyWheelSubsystemUpdated.java`. Dual-zone PIDF with voltage compensation.
- **Autonomous:** `AutoRedFar3.java`, `AutoBlueClose.java`. State-machine routines using Pedro Pathing.

**Others' contributions:** Aryan Goyal and Arav Bahuguna (whom I trained) tuned autonomous and position values. Mentor Shaadab and Aarav Dewan wrote a turret controller (`TurretSubsystemAaravDewan.java`) that we did not use. Commits by Cal Kestis / Craig MacFarlane are from the official FIRST SDK this project is built on.

**Libraries:** FTC SDK, Pedro Pathing, SolversLib, FTCLib, FTC Dashboard, goBILDA Pinpoint.
**AI use:** for V2, I designed the logic and Claude helped me turn it into Java while I learned; for V3, I modified the code myself and used Claude and Codex to cross-check logic and debug.
