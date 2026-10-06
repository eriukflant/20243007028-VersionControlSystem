# VersionControlSystem

Student ID: 20243007028  
COMPX202 Practical 3

Started from [the provided project](https://github.com/jibrilmuhammadadam/Practical3_GitHub.git), cloned over HTTPS. Commit 001 (`85bd8ad`) is the original commit. This repository was created empty before changing `origin` and pushing the project.

## Changes

| Commit | Change | Screenshot |
| --- | --- | --- |
| 001 | Original login screen | [View](screenshots/commit-001.png) |
| 002 | Centered the title | [View](screenshots/commit-002.png) |
| 003 | Added Cancel beside Log In | [View](screenshots/commit-003.png) |
| 004 | Changed both buttons to black | [View](screenshots/commit-004.png) |

Commit 004 was made on `feature-button-background-color`, pushed, and merged into `master`. Both branches are on GitHub.

## Running

Open the project in Android Studio, sync Gradle, and run `app`. The starter uses Gradle 9.6.0, AGP 9.4.1, SDK 37 and JDK 25.

Tested each stage on Pixel 7 (API 36). Build, Lint and the included unit test passed.

On Windows, this command avoids an encoding error when the user folder has non-ASCII characters:

```powershell
.\gradlew.bat --no-daemon '-Dorg.gradle.jvmargs=-Xmx2048m -Dfile.encoding=COMPAT' testDebugUnitTest lintDebug
```

## Reflection

In a larger project, developers can work on separate branches and merge their changes after testing. Small commits help the team find where a bug started and restore an earlier version. A shared remote lets everyone pull the latest changes and review the same history.
