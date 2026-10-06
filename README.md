# VersionControlSystem

Student ID: 20243007028  
COMPX202 Practical 3

Cloned [the provided project](https://github.com/jibrilmuhammadadam/Practical3_GitHub.git) using HTTPS. The original Commit 001 (`85bd8ad`) is preserved. This repository was created empty, then `origin` was changed to this repository before pushing the existing history.

## Changes

| Commit | Change | Screenshot |
| --- | --- | --- |
| 001 | Original login screen | [View](screenshots/commit-001.png) |
| 002 | Centered the title | [View](screenshots/commit-002.png) |
| 003 | Added Cancel beside Log In | [View](screenshots/commit-003.png) |
| 004 | Changed both buttons to black | [View](screenshots/commit-004.png) |

Commit 004 was made on `feature-button-background-color`. The branch was pushed, then merged into `master`. Both branches are kept on GitHub. The merge has its own commit so it is visible in `git log --graph --all --oneline`.

## Running

Open this folder in Android Studio, let Gradle sync, and run `app` on an emulator. The project uses the starter's Gradle 9.6.0, Android Gradle Plugin 9.4.1 and SDK 37 settings. Its Gradle daemon configuration uses JDK 25.

Each UI stage was built and run on Pixel 7 (API 36). The screenshots above were captured from the emulator. The final build, Lint check and the starter's unit test passed.

For Windows with a Chinese user folder, the unit test command used was:

```powershell
.\gradlew.bat --no-daemon '-Dorg.gradle.jvmargs=-Xmx2048m -Dfile.encoding=COMPAT' testDebugUnitTest lintDebug
```

`local.properties` and build outputs are ignored by Git.

## Reflection

Small commits make it easier to locate a bug and recover an earlier version. Branches let developers try a change without changing the main version. Pulling and merging bring work together, while a remote repository gives the team a shared history to review.
