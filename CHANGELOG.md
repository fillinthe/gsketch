# Changelog

Downloads for every version are on the [releases page](https://github.com/fillinthe/gsketch/releases).

## 0.1.27 (2026-11-22)

- **Your data, your choice**: GSketch now says what it sends to get better (which features get used and short problem reports, with your account when you're signed in; never your models or file names). Settings › Help improve GSketch turns it off, and Delete my data removes what was sent.

## 0.1.26 (2026-11-20)

- **Help opens the user manual**: Help › User Manual opens gsketch.app/docs/ in your language. The How Do I… box is gone.
- **Big 3D files open**: STL, OBJ, glTF and COLLADA files with up to 600,000 triangles open as they are; bigger ones open simplified to fit and the status line says so. Files over 2 million triangles and too-big SketchUp models say what to do.
- **Send problem reports**: Settings › Send problem reports turns off the automatic reports. When on and signed in, they carry your account, never file names.

## 0.1.25 (2026-11-17)

- **Four more languages**: Korean, Dutch, Polish and Turkish join Spanish, German, Japanese, French, Brazilian Portuguese, Italian and Simplified Chinese (Settings › Language; picked by itself from your computer's language).
- The right-click menu and the account, report and colour boxes are translated in every language now.

## 0.1.24 (2026-11-16)

- **Hide ♥ Donate**: the × beside ♥ Donate in the top bar puts it away. Settings › "Show ♥ Donate in the top bar" brings it back, and Donate stays in the Help menu.

## 0.1.23 (2026-11-16)

**Your work stays yours**
- A save to your account that is still on its way can no longer land on another model (New, Sample or a closed tab in between could put an empty or different model over the saved one).
- "Save changes? › Save" on an account model saves to the account. A failed or signed-out save is shown in red and autosave tries again.
- Paint, textures and tags stay on when you make a group, copy with Move or explode. Edges softened by hand stay soft.
- Backspace while moving something no longer deletes it. A cancelled Import no longer turns the next model you open into a component.
- An edit that fails no longer empties Redo.

**Right results**
- Variables in millimetre and feet projects: `w / 2` and `2*t` were scaled wrong.
- Follow Me beside other geometry faces out. Mirrored parts from COLLADA and glTF come in right side out.
- Arrays can be typed as /5, x5 or *5, and a variable's name can start a typed value.
- Clicks on empty space land on the ground in parallel views.

**Harder to break**
- Damaged or hand-made .skp, .gsk, glTF, COLLADA and STL files are refused instead of crashing or freezing the app.
- Fixed crashes on a crossing selection box over an emptied group and on Delete in the middle of Offset.

**Windows and Linux**
- Hints, the welcome card and How Do I…? name the keys your computer has (Alt, Ctrl).
- Windows: `install.cmd` in the download adds GSketch to the Start menu and desktop (`install.cmd remove` takes it out). On a PC or virtual machine without OpenGL 2, the 64-bit build starts by itself on a bundled software renderer (Mesa), and updates work there too. If no renderer works, a message says why.
- Linux: the menu entry, launcher and taskbar show the GSketch icon, and .gsk files open with GSketch.

The Cabinet box, welcome card and more messages are translated.

## 0.1.22 (2026-11-10)

**AI assistants can drive GSketch.** Settings › Let AI agents control GSketch starts an MCP server on this computer only (http://127.0.0.1:7807/mcp; off by default). AI assistants can read the model, add boxes and cabinets, set variables, select and move groups, run any menu command and take a screenshot. Each action is one undo step.

**Safer saving**
- "Save changes?" asks every time: it could skip the question after one Save, or skip a second unsaved tab when quitting.
- A save to your account no longer marks edits made during the upload as saved.
- Pasting groups copied from another model, or placing a component inside itself, can no longer damage the file or freeze the app.
- Fixed a crash on Delete after undoing a dimension.

**Easier to read**
- Short windows show every tool in two columns.
- The Cut List gives sizes in inches (34 1/2") and square feet, and scrolls sideways in narrow windows.
- The Cabinet box sits top right, off the cabinet it builds.
- The paint box folds its colour editor away.
- The Instructor shows one line, with More for the rest.

**Updates:** the Mac update checks it is signed by GSketch's maker; restart after an update works on Linux; a failed update can be tried again.

## 0.1.21 (2026-10-29)

GSketch 0.1.21

- **Updates install themselves**: when a new version is out, Help › Update available › Install update downloads it and puts it in place of the one you have; Restart now opens the new version. Your models and settings stay. If it can't install there, the download page opens instead. (This takes effect from the next release on: 0.1.20 and older still download the file for you to install.)

Free for personal and commercial use. Mac: open the .dmg and drag GSketch onto Applications. Windows: unzip and run GSketch.exe. Linux: untar and run ./gsketch.

## 0.1.20 (2026-10-29)

GSketch 0.1.20

- **Stamp, Drape and Flip Edge for terrains**: Draw › Stamp cuts a level pad the shape of a face into a terrain with a slope round it; Draw › Drape lays edges (a path) onto a terrain; Draw › Flip Edge turns the edge between two terrain triangles.
- **Dimension styles**: Model Info › Dimensions picks the end marks (ticks, arrows, dots or none) and the text size, on screen and on printed drawings.
- **Leader text**: select a text note to give it a dot, an arrow or no leader line.

Free for personal and commercial use. Mac: open the .dmg and drag GSketch onto Applications. Windows: unzip and run GSketch.exe. Linux: untar and run ./gsketch.

## 0.1.19 (2026-10-29)

GSketch 0.1.19

- **Parts library**: Components › Library has 2×4s, 2×6s, posts, boards, plywood sheets and a table leg at their real sizes; right-click any group › Add to Library to keep your own parts for every model.
- **Dado joints**: put a shelf against a side, select both, Edit › Joinery › Cut Dado: the side gets the slot, the shelf grows into it, and the Cut List has the real length.
- **Texture position**: move, turn or size a face's picture in Entity Info › Texture position.

Free for personal and commercial use. Mac: open the .dmg and drag GSketch onto Applications. Windows: unzip and run GSketch.exe. Linux: untar and run ./gsketch.

## 0.1.18 (2026-10-29)

GSketch 0.1.18

- **Scaled drawings (PDF)**: File › Export Scaled Drawing (PDF) prints the model as the view shows it, straight on with hidden edges left out, at the biggest standard scale that fits Letter, Tabloid, A4 or A3, with your dimensions and notes.
- **SketchUp export keeps groups and components**: File › Export SketchUp (.skp) writes groups and components as SketchUp groups and components, nested and named.
- **Update notices for apps left open**: the app looks for a newer version every 6 hours, not only at start.

Free for personal and commercial use. Mac: open the .dmg and drag GSketch onto Applications. Windows: unzip and run GSketch.exe. Linux: untar and run ./gsketch.

## 0.1.17 (2026-10-28)

**New**
- **Mac menu bar**: on a Mac, File, Edit, View and the other menus are in the Mac's own menu bar at the top of the screen, with the usual GSketch menu (About, Check for Updates, Settings ⌘,, Hide, Quit ⌘Q). Windows and Linux keep them in the window.

**Notes**
- The Mac app is signed and notarized by Apple: it opens with a double-click.
- Macs: Apple silicon, and Intel Macs from macOS 10.12 on. Windows: x64 for 64-bit Windows 10 / 11; win7 files for Windows 7 / 8 and any 32-bit Windows 7, 8 or 10.
- In 0.1.4 and later, Help › Check for Updates › Update now installs it.
- The Windows files are not code-signed yet (see the README for the first start).

## 0.1.16 (2026-10-28)

**New**
- **Easier Mac install**: the Mac download opens on a window that shows where to drag GSketch (onto the Applications folder).

**Notes**
- The Mac app is signed and notarized by Apple: it opens with a double-click.
- Macs: Apple silicon, and Intel Macs from macOS 10.12 on. Windows: x64 for 64-bit Windows 10 / 11; win7 files for Windows 7 / 8 and any 32-bit Windows 7, 8 or 10.
- In 0.1.4 and later, Help › Check for Updates › Update now installs it.
- The Windows files are not code-signed yet (see the README for the first start).

## 0.1.15 (2026-10-27)

**New**
- **Translations finished**: messages with numbers, cabinet part names, hardware, materials, the Cut List headings, snap labels and mouse-style tips now come in all seven languages (Edit › Settings › Language: Español, Deutsch, 日本語, Français, Português (Brasil), Italiano, 简体中文).

**Notes**
- The Mac app is signed and notarized by Apple: it opens with a double-click.
- Macs: Apple silicon, and Intel Macs from macOS 10.12 on. Windows: x64 for 64-bit Windows 10 / 11; win7 files for Windows 7 / 8 and any 32-bit Windows 7, 8 or 10.
- In 0.1.4 and later, Help › Check for Updates › Update now installs it.
- The Windows files are not code-signed yet (see the README for the first start).

## 0.1.14 (2026-10-27)

**New**
- **Seven languages**: Edit › Settings › Language switches GSketch to Español, Deutsch, 日本語, Français, Português (Brasil), Italiano or 简体中文. It starts in your computer's language when it is one of them. Menus, tools, dialogs, messages and the How Do I… guide are translated.

**Notes**
- 0.1.13 (earlier today) added tabs, radius and angle dimensions, Trim and Split, rulers, Edge Extensions, Terrain, Match Photo, Export SketchUp (.skp), Nest by shape and accessibility settings.
- The Mac app is signed and notarized by Apple: it opens with a double-click.
- Macs: Apple silicon, and Intel Macs from macOS 10.12 on. Windows: x64 for 64-bit Windows 10 / 11; win7 files for Windows 7 / 8 and any 32-bit Windows 7, 8 or 10.
- In 0.1.4 and later, Help › Check for Updates › Update now installs it.
- The Windows files are not code-signed yet (see the README for the first start).

## 0.1.13 (2026-10-27)

**New**
- **Tabs**: several models open at once (File › New Tab ⌘T); an empty model shows a Start card.
- **Dimensions**: diameter or radius of circles and arcs, and Tools › Angle Dimension.
- **Solid Tools › Trim and Split.**
- **Rulers** in straight-on views (Perspective off): drag guides out of them.
- **View › Edge Extensions** (with Profiles: SketchUp's sketched look).
- **Terrain**: Draw › Terrain from Face / from Contours, and Tools › Smoove.
- **Match Photo**: model over a photo with its camera.
- **File › Export SketchUp (.skp)**: faces, colours and lines (2017 format).
- **Scenes** from SketchUp 2013–2020 files.
- **Cut List › Nest by shape (CNC)**: parts nested by their true outline.
- **Cabinets**: drawer slide room, box sides and bottom thickness; hardware follows a scaled cabinet.
- **Settings › Accessibility**: large text, high contrast, large snap marks and grips (all off by default).

**Notes**
- The Mac app is signed and notarized by Apple: it opens with a double-click.
- Macs: Apple silicon, and Intel Macs from macOS 10.12 on. Windows: x64 for 64-bit Windows 10 / 11; win7 files for Windows 7 / 8 and any 32-bit Windows 7, 8 or 10.
- In 0.1.4 and later, Help › Check for Updates › Update now installs it.
- The Windows files are not code-signed yet (see the README for the first start).

## 0.1.12 (2026-10-26)

**New**
- **The right app icon** on Mac, Windows and Linux (0.1.10 and 0.1.11 showed a black square with a chevron).
- **View › Profiles**: the model's outline drawn thicker, as SketchUp's default style does.
- **Dimensions and text notes from older SketchUp files** (2013 to 2020) come in too.

**Notes**
- The Mac app is signed and notarized by Apple: it opens with a double-click.
- Macs: Apple silicon, and Intel Macs from macOS 10.12 on. Windows: x64 for 64-bit Windows 10 / 11; win7 files for Windows 7 / 8 and any 32-bit Windows 7, 8 or 10.
- In 0.1.4 and later, Help › Check for Updates › Update now installs it.
- The Windows files are not code-signed yet (see the README for the first start).

## 0.1.11 (2026-10-26)

**New**
- **Dimensions come in from SketchUp files** (SketchUp 2021 and later): every linear dimension lands where it was, on the wall or part it measures, in each copy of a component.

**Notes**
- The Mac app is signed and notarized by Apple: it opens with a double-click.
- Macs: Apple silicon, and Intel Macs from macOS 10.12 on. Windows: x64 for 64-bit Windows 10 / 11; win7 files for Windows 7 / 8 and any 32-bit Windows 7, 8 or 10.
- In 0.1.4 and later, Help › Check for Updates › Update now installs it.
- The Windows files are not code-signed yet (see the README for the first start).

## 0.1.10 (2026-10-26)

**New**
- **The Mac app is signed and notarized by Apple**: it opens with a double-click, no "unidentified developer" warning.
- **Report a problem in one click**: error messages come with a Report… link that opens the report form already filled in; after an unexpected close the app offers to send a report at the next start.
- **Circles and arcs are one piece**: click any edge of one to select it all, and type a new Radius in Entity Info.
- **Safer opening**: dropping a file or opening one from your account asks to save unsaved changes first, and a file opened after an account model no longer saves over that model.

**Notes**
- Macs: Apple silicon, and Intel Macs from macOS 10.12 on. Windows: x64 for 64-bit Windows 10 / 11; win7 files for Windows 7 / 8 and any 32-bit Windows 7, 8 or 10.
- In 0.1.4 and later, Help › Check for Updates › Update now installs it.
- The Windows files are not code-signed yet (see the README for the first start).

## 0.1.9 (2026-10-22)

**New**
- **Save changes?** Closing the window, New or Open with unsaved changes now asks first: Don't Save, Cancel or Save.

**Notes**
- Same features as 0.1.8, rebuilt so the files carry no build-machine paths. Older downloads were removed.
- Macs: Apple silicon, and Intel Macs from macOS 10.12 on. Windows: x64 for 64-bit Windows 10 / 11; win7 files for Windows 7 / 8 and any 32-bit Windows 7, 8 or 10.
- In 0.1.4 and later, Help › Check for Updates › Update now installs it.
- The macOS app is not notarized and the Windows files are not code-signed yet (see the README for the first start).

