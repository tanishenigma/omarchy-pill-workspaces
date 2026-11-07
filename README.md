# Pill Workspaces for Omarchy

A bar widget for the Omarchy shell. The active workspace shows as a wide pill and the other workspaces as small ring dots. The pill animates between them as you switch.

![Pill Workspaces demo](assets/demo.gif)

![Pill Workspaces screenshot](assets/screenshot.png)

- Follows your Omarchy theme colors
- Hover expands a dot into a pill
- Urgent workspaces turn red
- Click a dot to focus it; click the active pill to cycle the layout (tile, scroll, float)
- Scroll over the widget to move between workspaces
- Works on horizontal and vertical bars, with multi-monitor workspace blocks

## Install

```bash
omarchy plugin add https://github.com/tanishenigma/omarchy-pill-workspaces --enable
```

Then swap it in for the stock widget:

```bash
omarchy plugin disable omarchy.workspaces
```

## Remove

```bash
omarchy plugin remove tanishenigma.pill-workspaces
omarchy plugin enable omarchy.workspaces
```

## Dependencies

None beyond Omarchy itself (Omarchy shell on Hyprland). The plugin doesn't edit any of your config files; it only adds itself to the bar when you enable it.

## License

MIT, see [LICENSE](LICENSE).

## Credit

Based on the stock `omarchy.workspaces` widget from [Omarchy](https://omarchy.org).
