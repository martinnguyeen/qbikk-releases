# E by QBIKK Beta 0.2.0-beta.3: for testers

This is what comes next in E by QBIKK, a few days to weeks before everyone gets it. Expect rough edges, and tell
us about them. Martin, the QBIKK team and invited testers use it.

E by QBIKK Beta is a separate app. It installs next to E by QBIKK, has its own icon (with a BETA band) and keeps
its own recordings, settings and saved keys, so nothing you do in the beta touches the stable app on this
computer. You sign in to the same QBIKK account in both.

| Your computer | Download | Needs |
| --- | --- | --- |
| Mac with Apple silicon (M1 or newer) | [QBIKK-E-Beta-mac-arm64.dmg](https://github.com/martinnguyeen/qbikk-releases/releases/download/e-v0.2.0-beta.3/QBIKK-E-Beta-mac-arm64.dmg) | macOS 14 Sonoma or newer |
| Mac with an Intel processor | [QBIKK-E-Beta-mac-x64.dmg](https://github.com/martinnguyeen/qbikk-releases/releases/download/e-v0.2.0-beta.3/QBIKK-E-Beta-mac-x64.dmg) | macOS 14 Sonoma or newer |
| Windows PC | [QBIKK-E-Beta-win-x64.exe](https://github.com/martinnguyeen/qbikk-releases/releases/download/e-v0.2.0-beta.3/QBIKK-E-Beta-win-x64.exe) | Windows 10 or 11, 64-bit |

Which Mac do you have? Apple menu ▸ About This Mac: "Chip: Apple M…" is Apple silicon, "Processor: … Intel" is Intel.

**First open on a Mac.** Open the DMG and drag E by QBIKK Beta into Applications, then open it from there. It is not
notarized by Apple yet, so the first time macOS will not open it ("Apple could not verify…" or "cannot verify the
developer"). Click Done, open System Settings ▸ Privacy & Security, scroll down to the message about E by QBIKK Beta,
click Open Anyway and confirm. On macOS 14 you can instead Control-click E by QBIKK Beta in Applications and choose Open.
You do this once; updates open without asking.

**First open on Windows.** The installer is not signed yet, so Windows SmartScreen says "Windows protected your
PC". Click More info, then Run anyway. If your browser warns about the download, choose Keep. It installs for your
user only (no administrator needed) and starts by itself.

**Updates arrive by themselves.** E by QBIKK Beta checks once a day, downloads a new version in the background and
installs it when you quit. To check now: Settings ▸ About ▸ Check for Updates… (on a Mac also E by QBIKK Beta ▸ Check for
Updates… in the menu bar). If macOS asks for the microphone again after an update, allow it again.

E by QBIKK Beta only ever updates to a newer beta; it never turns into E by QBIKK.

**Found a bug?** Settings ▸ About shows "Beta" and the version: put that, what you did and what happened in an
issue at https://gitlab.com/qbikk/QBIKK-SW/-/issues (start the title with "Beta:"), or send it to Martin. On Windows, attach
`%APPDATA%\QBIKK E Beta\logs\updates.log` if the bug is about updating.

**Leaving the beta.** Quit E by QBIKK Beta. Mac: drag it from Applications to the Trash. Windows: Settings ▸ Apps ▸
Installed apps ▸ E by QBIKK Beta ▸ Uninstall. Then install E by QBIKK from the QBIKK-SW README, or keep using it
if you have it. Recordings made in the beta stay in the beta's own folder (Mac:
`~/Library/Application Support/QBIKK E Beta/Recordings`, Windows: `%APPDATA%\QBIKK E Beta\Recordings`); copy
any you want to keep before you delete that folder.

Release notes: https://github.com/martinnguyeen/qbikk-releases/releases/tag/e-v0.2.0-beta.3
