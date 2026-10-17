# Ungroup & reorder taskbar windows (Windhawk mod)

A [Windhawk](https://windhawk.net) mod that gives every window its own taskbar
button, so you can drag them to re-arrange them, including several windows of
the same app (for example three Brave windows), which the stock taskbar doesn't
allow.

- Already-open windows are ungrouped when the mod is enabled and regrouped when
  it's disabled (their buttons are briefly re-created, which resets their order
  once). Store apps are left alone and must be reopened.
- New windows can be placed next to their app's existing buttons.
- Choose how pinned items behave, and exclude programs that should keep the
  normal grouping.

For icon-only buttons that stay uncombined, set *Settings > Personalization >
Taskbar > Taskbar behaviors > Combine taskbar buttons and hide labels* to
**Always**.

Don't enable it together with the "Disable grouping on the taskbar" mod, as
both hook the same taskbar functions.

## Install

1. In Windhawk, click **Create a new mod**.
2. Replace the template with the contents of
   [`taskbar-ungroup-reorder.wh.cpp`](taskbar-ungroup-reorder.wh.cpp).
3. Press **Ctrl+B** to compile, then exit the editing mode.

Supports Windows 10 64-bit and Windows 11.

## Credits

Based on [Disable grouping on the taskbar](https://windhawk.net/mods/taskbar-grouping)
by m417z. I made this version for personal use, to have ungrouping, reordering
and applying to already-open windows together in one mod. Developed with the
assistance of Claude (Anthropic).

Licensed under the [GNU General Public License v3.0](LICENSE).
