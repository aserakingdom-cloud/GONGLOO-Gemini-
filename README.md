# GONGLOO — Code. Create. Command.

A new, standalone native Android application. It is separate from NOORI Companion and ASERA-STITCH.

- Application ID: `com.aserakingdom.gongloo`
- UI framework in this foundation: Android platform Views in Java. This keeps the first shell build configuration free of uncached Compose dependencies.
- Android SDK: local SDK platform 35, configured for this Termux device in `local.properties`.
- Android Gradle Plugin: 8.13.0.
- Intended Gradle: 8.13, available locally at `/data/data/com.termux/files/home/downloads/noori-companion/gradle-8.13/bin/gradle`.
- Java source/target: 17; the installed JDK is 21.

The current screen is a local UI shell. Dashboard navigation works between local status screens. Terminal, project operations, editor, Codex, packages, server controls, GitHub, and file operations are marked unavailable/planned. No shell command execution, network request, or project mutation is implemented.

No Gradle wrapper is included yet. The current Gradle distribution and SDK are local device resources; make the build fully portable with an approved project-owned wrapper/toolchain plan before distributing the project. This project has not been built or tested in this implementation step.
# GONGLOO-Gemini-
# GONGLOO-Gemini-
