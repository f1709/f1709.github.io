# KillCounter+∞ for OBS

OBS Lua script to display a kill counter with support for + and ∞ symbols.

## Features
- Increase / Decrease counter
- Toggle + symbol
- Toggle ∞ symbol
- Hotkey support with save/load
- Start Number / Step Number support (새로 추가됨)

## Usage
1. Save `killcounter.lua`
2. Load in OBS via Tools → Scripts
3. Add a Text(GDI+) source named **KillCounter**
4. Configure hotkeys in OBS Settings → Hotkeys
5. Set **Start Number** and **Step Number** in script properties
   - Start Number: 카운터 시작 값
   - Step Number: 증가/감소 단위
