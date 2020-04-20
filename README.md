# micekeys

Buttons layout for my programmable mice (not robots).


## Redragon Legend M990

### Description
- 16 side buttons
- Price: usual ~$35, max discount ~$24
- Supported OS: Windows

### Side buttons Layout
| Row \| Column | Front                       | Front-Mid     | Back-Mid          | Back                        |
| ------------- | --------------------------- | ------------- | ----------------- | --------------------------- |
| Top           | `Ctrl-W`                    | `Alt-Right`   | `Alt-Left`        | `Ctrl-Shift-T`              |
| Upper-Mid     | `Ctrl-F5`                   | `Ctrl-PageUp` | `Ctrl-PageDown`   | `Alt-F4`                    |
| Lower-Mid     | `Alt`                       | `Shift`       | `Ctrl`            | `Alt-Space N`<sup>(1)</sup> |
| Bottom        | `Alt-Space X`<sup>(1)</sup> | `Alt-Tab`     | `Win-Shift-Right` | `Win-Down`                  |

_Outdated Layout_

<img alt="outdated_preview" src="./imgs/redragon_legend_config_outdated.PNG" width="600" align="middle">

### Usage

#### Top Row
- Mostly for interacting with a tab (in explorer, browser, IDE)
- Middle 2 keys = Backward vs. Forward
- Front vs. Back = Close tab vs. Reopen closed tab

#### Upper-Mid Row
- Mostly for moving between tabs (in browser, IDE)
- Middle 2 keys = Next vs. Previous tab position-wise<sup>(2)</sup>
- Front-most = reload browser tab (refresh cache)
- ~~Back-most = Window task view~~
- **EXPERIMENTAL** Back = Close program, _Alt-F4 feels rather dangerous bc can't be easily undo-ed, but this button seems very rarely used so far (even with previous combo) and also a bit hard to reach, probably worth trying esp. for Surface Book where F-keys are a hassle_

#### Lower-Mid Row
- Supplementary keys
- Middle 2 keys = Shift vs. Ctrl, to combo with Mouse Wheel (Shift-Scroll = Horizontal scrolling, Ctrl-Scroll = Zoom in/out)
- ~~Front vs. Back = Full screen vs. Fully-minimize window~~
- **EXPERIMENTAL** Front = Alt, _not too sure what to combo with but sometimes I felt I might as well have Alt together with Ctrl & Shift in this row_

#### Bottom Row
- Mostly for manipulating screens
- Front vs. Back: Maximize vs. Restore down (Minimize) window
- Front-Mid: Switch between windows (2 most recently active)
- Back-Mid: Move window to another screen/monitor

## Redragon Impact M908

### Description
- 12 side buttons
- Price: usual ~$30, max discount ~$20
- Supported OS: Windows

### Side buttons Layout
| Row \| Column | Front                       | Front-Mid     | Back-Mid          | Back                        |
| ------------- | --------------------------- | ------------- | ----------------- | --------------------------- |
| Top           | `Ctrl-W`                    | `Alt-Right`   | `Alt-Left`        | `Ctrl-Shift-T`              |
| Mid           | `Ctrl-F5`                   | `Ctrl-PageUp` | `Ctrl-PageDown`   | `Alt-Space N`<sup>(1)</sup> |
| Bottom        | `Alt-Space X`<sup>(1)</sup> | `Alt-Tab`     | `Win-Shift-Right` | `Win-Down`                  |


_Outdated Layout_

<img alt="outdated_preview" src="./imgs/redragon_impact_config_outdated.PNG" width="600" align="middle">

### Usage

#### Top Row
- Mostly for interacting with a tab (in explorer, browser, IDE)
- Middle 2 keys = Backward vs. Forward
- Front vs. Back = Close tab vs. Reopen closed tab

#### Mid Row
- Mostly for moving between tabs (in browser, IDE)
- Middle 2 keys = Next vs. Previous tab position-wise<sup>(2)</sup>
- Front-most = reload browser tab (refresh cache)
- Back-most = Fully-minimize window

#### Bottom Row
- Mostly for alternating windows/monitors
- Front vs. Back: Fully-maximize vs. Minimize window
- Front-Mid: Switch between windows (most recently active)
- Back-Mid: Move window to another screen/monitor

## Footnotes

- (2) I prefer Ctrl-PageUp/Down (strictly position-wise) over Ctrl-(Shift)-Tab (chronological order in VSCode & Sublime Text, positional order in web browsers)
- (1) [Max|Min]imize Macro: ↓Alt-0ms-↓Space-0ms-↑Alt-0ms-↑Space-200ms-↓[X|N]-0ms-↑[X|N]

## Tudu

- Experiment with Double click key
- Experiment with DPI keys (hardly ever change DPI)
