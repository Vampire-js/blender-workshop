![alt text](banner.png)
# GDU Blender Workshop
Blender is a free, open-source application for 3D modeling, animation, rendering,
and more. This guide helps you install it and learn the most useful shortcuts.

## Install Blender

1. Check the [system requirements](https://www.blender.org/download/requirements/)
   and update your graphics drivers if needed.
2. Visit the [official download page](https://www.blender.org/download/) and choose
   the download for your operating system. Use a stable release, or the
   [Long-Term Support (LTS) release](https://www.blender.org/download/lts/) if your
   course requires it. Match your instructor's version when possible.
3. Install using the steps below.
4. Launch Blender. If the first-run setup appears, choose the **Blender** keymap
   and **Left** mouse selection to match this cheatsheet, then save the setup.

| Operating system | Basic installation steps | Official guide |
|---|---|---|
| Windows | Download the installer, open it, and follow the installation prompts. Launch Blender from the Start menu. | [Windows installation](https://docs.blender.org/manual/en/latest/getting_started/installing/windows.html) |
| macOS | Download the disk image for your Mac's processor (Apple Silicon or Intel, if supported). Open the `.dmg`, drag Blender into Applications, then launch it. | [macOS installation](https://docs.blender.org/manual/en/latest/getting_started/installing/macos.html) |
| Linux | Download the `.tar.xz` archive and extract it into a folder you own. Open the extracted folder and run the `blender` executable; no system-wide installation is needed. | [Linux installation](https://docs.blender.org/manual/en/latest/getting_started/installing/linux.html) |

**First project:** Use **File > Save As** to save a `.blend` file in your project
folder. Save regularly while working.

## Shortcut Cheatsheet

These shortcuts use the **default Blender keymap**, not Industry Compatible.
Keep your pointer over the **3D Viewport** for viewport and modeling shortcuts.
Some shortcuts depend on the active editor, object type, or mode.

### View and Navigate

| Action | Shortcut |
|---|---|
| Orbit the view | Middle mouse button + drag |
| Pan the view | Shift + middle mouse button + drag |
| Zoom | Mouse wheel, or Ctrl + middle mouse button + drag |
| Front / right / top view | Numpad 1 / 3 / 7 |
| Opposite view (back / left / bottom) | Ctrl + Numpad 1 / 3 / 7 |
| Toggle perspective / orthographic view | Numpad 5 |
| Look through the active camera | Numpad 0 |
| Frame selected objects | Numpad `.` (decimal key) |
| Frame all objects | Home |
| Open the view navigation pie menu | Backtick (grave accent key) |
| Open the viewport shading pie menu | Z |

**Laptop tip:** Without a numpad, use the viewport's **View** menu or navigation
pie menu. You can also enable **Edit > Preferences > Input > Emulate Numpad**,
but this repurposes the top-row number keys, including the mesh selection
shortcuts below. **Emulate 3 Button Mouse** lets Alt + left-drag emulate
middle-drag; it can conflict with other Alt + mouse actions.

### Select and Transform

| Action | Shortcut |
|---|---|
| Select an object or mesh element | Left-click |
| Add to / remove from selection | Shift + left-click |
| Select all / deselect all | A / Alt + A |
| Box select / circle select | B / C |
| Move / rotate / scale | G / R / S |
| Constrain a transform to an axis | Press X, Y, or Z after G, R, or S |
| Enter an exact transform value | Type a number after starting the transform |
| Confirm / cancel a transform | Enter or left-click / Esc or right-click |
| Duplicate | Shift + D, then move and confirm |
| Delete with confirmation | X |
| Hide selected / reveal hidden | H / Alt + H |
| Add an object | Shift + A (Object Mode) |
| Rename the active object | F2 |

**Example:** Press `G`, then `X`, then `2`, then `Enter` to move the selection
2 units along the X axis. Press `R`, `Z`, `90`, `Enter` to rotate it 90 degrees
around Z.

### Mesh Modeling

**Object Mode** works on whole objects. **Edit Mode** changes the geometry
inside the active mesh object.

| Action | Shortcut |
|---|---|
| Toggle Object / Edit Mode | Tab |
| Vertex / edge / face selection | Top-row 1 / 2 / 3 (mesh Edit Mode) |
| Extrude selected geometry | E (Edit Mode) |
| Inset selected faces | I (Edit Mode) |
| Bevel selected edges | Ctrl + B (Edit Mode) |
| Add a loop cut | Ctrl + R (Edit Mode); click to place, then confirm the slide |
| Merge selected vertices | M (Edit Mode) |
| Recalculate normals outside | Shift + N (Edit Mode) |
| Toggle X-Ray selection | Alt + Z |

### Save, Undo, and Render

| Action | Shortcut |
|---|---|
| Save / Save As | Ctrl + S / Ctrl + Shift + S |
| Open a file | Ctrl + O |
| Undo / redo | Ctrl + Z / Ctrl + Shift + Z |
| Search for a command | F3 |
| Adjust the last operation | F9 |
| Toggle toolbar / sidebar | T / N |
| Maximize / restore the current editor | Ctrl + Space |
| Render the current frame | F12 |
| Show / hide the render window | F11 |
| Play / pause animation | Space (default Spacebar Action) |

**macOS:** Cmd can replace Ctrl for many shortcuts, but not all. Laptop function
keys may require Fn to use F3, F9, F11, or F12.

## Practice in Five Minutes

1. Select the default cube and try moving, rotating, and scaling it.
2. Press Tab to enter Edit Mode, then press top-row 3 for face selection.
3. Select a face and press E to extrude it. Confirm with Enter.
4. Press Tab to return to Object Mode, then save your work with Ctrl + S.
5. Press F12 to render using the scene's camera and light. Viewport navigation
   does not move the camera, so your render may show a different view.

## Useful Learning Links

- [Official Blender Manual](https://docs.blender.org/manual/en/latest/) -
  searchable reference for tools and workflows.
- [Getting Started](https://docs.blender.org/manual/en/latest/getting_started/index.html) -
  installation, configuration, and introductory concepts.
- [Default Keymap Reference](https://docs.blender.org/manual/en/latest/interface/keymap/blender_default.html) -
  official shortcut reference.
- [Blender Tutorials](https://www.blender.org/support/tutorials/) -
  learning resources linked by Blender.
- [Blender Fundamentals](https://www.youtube.com/playlist?list=PLa1F2ddGya_8acrgoQr1fTeIuQtkSd6BW) -
  official introductory videos; older lessons may show a different interface.
- [Blender Support](https://www.blender.org/support/) -
  community help and troubleshooting resources.
