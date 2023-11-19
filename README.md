# Yabai i3bar

[Übersicht](https://github.com/felixhageloh/uebersicht) widget of [i3bar](https://i3wm.org/i3bar/manpage.html) (i3 status bar and tabs bar) for [yabai](https://github.com/koekeishiya/yabai).

## Installation

Clone to widgets repository.

```bash
git clone https://github.com/behaviorism/yabai-i3bar $HOME/Library/Application\ Support/Übersicht/widgets/yabai-i3bar
```

## Usage

### Send Widget to Background

Press on the Übersicht icon, hover over the widget "yabai-i3bar-index-jsx" and press the button "Send to background". This will prevent the tabs bar from covering windows. Tabs bar is still visibile even when not not in stacked mode in order to not leave an empty space when re-rendering the widget after switching to a stacked workspace.

### Add Tabs Bar Padding

```bash
# Add Tabs Bar Padding (adjust padding based on preference and borders)
# We need to use padding instead of the external_bar because only padding can be adjusted
yabai -m config top_padding 18
```
