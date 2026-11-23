# Malaw Roadmap

Malaw is an Android keyboard for the terminal and cybersecurity, based on HeliBoard.

## Phase 0: dictionary (done)
- [x] malaw-dictionary repository online
- [x] Three-level priority dictionary (basic commands, security tools, others)
- [x] Shell reserved words removed
- [x] Visual identity: signature and mockup
- [ ] build.sh script to regenerate the dictionary

## Phase 1: a fork that builds
- [ ] Fork HeliBoard as malaw-keyboard
- [ ] Enable GitHub Actions and run a first build
- [ ] Name, icon and applicationId
- [ ] Credit HeliBoard in the README

## Phase 2: Malaw identity
- [ ] Default theme: dark background, purple accent, Malaw signature
- [ ] Terminal key row: Ctrl, Esc, Tab, arrows, | ~ / -
- [ ] Automatic switch to Malaw in Termux
- [ ] Dictionary bundled in the APK

## Phase 3: smart suggestions
- [ ] Strict ranking: words starting with the typed letters first, then basic commands before tools
- [ ] Malaw Assist: correction of mistyped commands, with a switch and three levels (off, suggestions only, auto-correct)
- [ ] Options and subcommands (-sV, --script...), if the format allows it
- [ ] Short description of each command, for beginners

## Phase 4: release
- [ ] Full README with screenshots and a video
- [ ] First APK release on GitHub
- [ ] Announcement on X
