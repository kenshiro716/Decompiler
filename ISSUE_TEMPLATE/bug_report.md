---
name: Bug report
about: Create a report to help us improve
title: "[BUG]"
labels: bug
assignees: phoriah

---

**Are you sure a similar issue hasn't been opened yet?**
Check Open & Closed issues, including pull requests and avoid making a duplicate if so.

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
IMPORTANT: INCLUDE CONSOLE PICTURES ALWAYS (can be opened using F9 or by typing /console in chat, your executor might also have it's own built-in console which you must also show)
If applicable, add screenshots to help explain your problem.

**Executor (& Emulator if used) Name(s):**
Fluxus v1

**Game Link:**
https://www.roblox.com/games/185655149/Welcome-to-Bloxburg

**Script Used (Options matter):**
```lua
local Params = {
    RepoURL = "https://raw.githubusercontent.com/luau/UniversalSynSaveInstance/main/",
    SSI = "saveinstance",
}
local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()

local Options = {NilInstances=true} -- Documentation here https://luau.github.io/UniversalSynSaveInstance/api/SynSaveInstance

synsaveinstance(Options)
```

**Additional context**
Add any other context about the problem here.
