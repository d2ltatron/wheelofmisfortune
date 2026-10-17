# wheel of misfortune: recode edition

## usage

paste this into your executor:

```lua
getgenv().challenge_mode = 1
getgenv().challenge_timer = 20
-- challenge mode 1: changes every gamemode 
-- challenge mode 2: changes every role change
-- challenge mode 3: changes on a timer based on the 'challenge_timer' variable

getgenv().global_sync = false
-- global sync DISABLED: challenges are randomized and unique to you only
-- global sync ENABLED: challenges are based on unix time, and be the same as other players

loadstring(game:HttpGet("https://raw.githubusercontent.com/d2ltatron/wheelofmisfortune/refs/heads/main/script.lua"))()
```

## credits

- **your_iucky & 1imag**: original challenge mode script this is based on
- **n0x**: rank icons used for difficulty icons
