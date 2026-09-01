# Amiga Workbench 1.3 for Obsidian

**A blue screen, ivory windows and an orange highlight. The flattest, boldest and most compact of the three.**

> **This is an independent, unofficial, fan-made theme.**
> It is **not affiliated with, endorsed by, sponsored by, approved by, or connected to**
> Amiga Corporation, Amiga Inc., Cloanto, Hyperion Entertainment, the former Commodore
> International, or any other present or former owner of the Amiga, Commodore, Kickstart
> or Workbench trademarks. Nothing here is official. The developer has no relationship
> with any of those parties. The theme is *inspired by* a remembered visual style — it is
> not a reproduction of one, and it ships no original Amiga assets of any kind.

---

<p align="center">
  <img src="https://raw.githubusercontent.com/anthonyfitzpatrick/obsidian-theme-inspired-by-amiga-workbench-1.3/main/screenshot.png" alt="Amiga Workbench 1.3" width="900">
</p>

<p align="center"><em>Workbench 1.3 in light mode. The saturated blue desktop sits behind pale windows, title strips are white carrying dark text, and orange marks the one thing that is selected — here the open scene in the file tree and its tab above.</em></p>

## What this is

Workbench 1.3 is the one people picture when they picture an Amiga. Boot an A500 in
1988 and this is what filled the screen: a saturated blue desktop, hard white window
frames, black text, and a single warm orange used sparingly to mean *this one*. Four
colours, and not one of them wasted.

That constraint is the whole character. There is no shading here, no soft edges and no
gradients — the three-dimensional gadget had not been invented yet, and would not arrive
until Workbench 2.0 two years later. Everything is drawn with flat fills and hard
one-pixel outlines, relieved by no more than a single pixel of highlight and shade. Controls are compact and square. The interface does
not try to look like a physical object; it looks like what it is, which is pixels
arranged with conviction.

This theme takes that language and applies it to a modern writing application. The blue
sits behind your panes, the windows are light and calm, the title strips are white with
dark text, and orange marks whatever is currently selected — the active tab, the open
note, the highlighted command. Nothing else is orange, which is precisely why it works.

<p align="center">
  <img src="https://raw.githubusercontent.com/anthonyfitzpatrick/obsidian-theme-inspired-by-amiga-workbench-1.3/main/docs/images/02-workspace-dark.png" alt="Amiga Workbench 1.3 in dark mode" width="900">
</p>

<p align="center"><em>The same workspace in dark mode. Workbench 1.3 never had one, so this is an invention rather than a reconstruction: the screen drops to deep navy and windows become dark blue, but the orange still marks selection and nothing else, exactly as it does in light.</em></p>

## Why you might choose this one

**If you are choosing between the three, pick 1.3 when you want the strongest
character.** It is by far the flattest, the only one with a coloured screen, and
the only one that uses orange. Beside 2.04 and 3.1 — which are both grey, bevelled and
descended from the same 1990 redesign — it looks like a different machine, because it
was.

## The palette

Every colour below is stated plainly so you can see exactly what the theme does. Nothing
is hidden behind a gradient or an image.

| Role | Value | Notes |
| --- | --- | --- |
| Screen | `#0055aa` | The blue behind every pane, and the one colour you see before anything else |
| Windows | `#ebf1f8` | The writing surface. The screen white, dithered with a little of the screen blue |
| Panels | `#c7daec` | Explorer, sidebars and the ribbon, so the chrome sits back from the page |
| Title strips | `#ffffff` | White with dark text, as Workbench 1.3 drew them |
| Highlight | `#ff8800` | Selection and active state. Used sparingly and never decoratively |
| Ink | `#000022` | Text and outlines |

## The geometry

| Property | Value | Notes |
| --- | --- | --- |
| Relief | 1px, minimal | A single-pixel highlight and shade, never 2.0's full relief |
| Border width | 1px | Hard, square, single-pixel outlines |
| Corner radius | 0 | Nothing is rounded anywhere |
| Spacing unit | 0.25rem | The most compact of the three |
| Control height | 1.75rem | Small, dense gadgets |

<p align="center">
  <img src="https://raw.githubusercontent.com/anthonyfitzpatrick/obsidian-theme-inspired-by-amiga-workbench-1.3/main/docs/images/03-chrome-detail.png" alt="Ribbon and file explorer" width="400">
</p>

<p align="center"><em>The ribbon and the file tree at depth. Every nesting level drops a connector rail from beneath its parent's disclosure triangle, so folder and file labels stay aligned however deep the structure runs. The ribbon pictograms are original drawings, not Obsidian's default line icons.</em></p>

## What is covered

The theme styles the whole application, not just the editor:

- **Workspace shell** — ribbon, tab bar, view headers, status bar, pane dividers
- **File explorer** — indentation, disclosure triangles, connector rails, selection
- **Editor and reading view** — headings, lists, links, code, tables, callouts, quotes
- **Properties** — rebuilt as a Workbench-style requester with a keyed column
- **Command palette and quick switcher** — recessed entry field, square result rows,
  keyboard hints drawn as small raised gadgets
- **Menus, modals, notices and tooltips** — hard frames, title strips, solid selection
- **Canvas, graph, Bases and backlinks** — consistent surface and control treatment
- **Settings** — including when opened in its own window

<p align="center">
  <img src="https://raw.githubusercontent.com/anthonyfitzpatrick/obsidian-theme-inspired-by-amiga-workbench-1.3/main/docs/images/04-tab-strip.png" alt="Tab strip, breadcrumbs and toolbar" width="900">
</p>

<p align="center"><em>The tab strip, the breadcrumb path and the toolbar row beneath them. Tabs are drawn as attached rectangular selectors over the title bar, with the new-tab gadget sharing their top and bottom edges. The path is plain clickable text rather than a row of boxes, and the current note is the only bold segment.</em></p>

## Installation

### From Obsidian's Community Themes browser

1. Open **Settings → Appearance**.
2. Under **Themes**, choose **Manage**.
3. Search for **Amiga Workbench 1.3**.
4. Select it and choose **Use**.

### Manually

1. Download `theme.css` and `manifest.json` from this repository.
2. Place both in `YourVault/.obsidian/themes/Amiga Workbench 1.3/` — the folder name must match exactly.
3. In Obsidian, go to **Settings → Appearance → Themes** and select **Amiga Workbench 1.3**.
4. If it does not appear, close and reopen Obsidian.

## Light and dark

Both modes are designed, not generated. Switch with **Settings → Appearance → Base theme**.
No plugin is involved.

Workbench 1.3 never had a dark mode; the hardware barely had the colours for one.
This one is an invention, but a disciplined one: it keeps 1.3's signatures rather than
inverting into generic charcoal. The screen goes deep navy, windows become dark blue,
title strips stay light with dark text, and orange remains the highlight.

## Fonts

The theme follows *your* typography settings. Set **Settings → Appearance → Interface font,
Text font, Monospace font** and **Font size**, and the entire interface follows — including
the tab bar, view headers, file explorer and status bar.

Leave them unset and the theme's own stack applies. It never overrides a font you have
chosen.

## Requirements

- Obsidian **1.6.0** or later
- No plugins. The theme is plain CSS and works on its own.

## Accessibility

- Every text and background pair is contrast-checked in both light and dark modes
- Keyboard focus is always visible, with a dedicated focus colour
- `prefers-reduced-motion` is respected
- `prefers-contrast: more` strengthens frames and removes muted text
- Printing and PDF export drop the screen palette for black on white

## Documentation

- **[User Guide](USERGUIDE.md)** — a fuller walkthrough, including customisation and
  troubleshooting

## Building from source

This repository is self-contained. The CSS is authored as modules under `src/` and
`theme.css` is generated from them:

```sh
npm run build    # regenerate theme.css from src/
npm test         # verify packaging, isolation, tokens and contrast
```

There are no dependencies to install — the build is plain Node. `src/variants/` holds this
theme's light and dark palettes; `src/components/workbench-chrome.css` holds the shared
Workbench structure; `src/icons/` holds the ribbon pictograms, which are coloured from the
palette at build time so they can never drift from it.

`theme.css` is generated. Edit the modules under `src/` and rebuild rather than editing it
directly; the pre-commit hook enforces this if you enable it with
`git config core.hooksPath .githooks`.


## Trademarks, affiliation and intellectual property

Please read this section in full. It matters.

### No affiliation whatsoever

Amiga Workbench 1.3 for Obsidian is an **independent, unofficial, community-created theme**. The
developer is a private individual with **no relationship of any kind** to:

- Amiga Corporation, Amiga Inc., or any entity trading under the Amiga name
- Cloanto Corporation, holders of Commodore/Amiga ROM and Workbench copyrights
- Hyperion Entertainment, developers and rights-holders of later AmigaOS releases
- The former Commodore International, Commodore Business Machines, or their successors
- Haage & Partner, or any other historical Amiga software publisher
- Any present, former or claimed owner of the Amiga, Commodore, Kickstart, AmigaOS or
  Workbench trademarks, in any territory

There is **no endorsement, sponsorship, approval, licence, partnership, or association**,
express or implied. Nothing in this project should be read as suggesting otherwise. If
you have arrived here believing this is an official product, it is not.

### Why the name refers to Workbench at all

The name is **descriptive, not proprietary**. It tells you which remembered look the
palette and proportions are drawn from — the Workbench of the late 1980s — in the same way a paint colour might be
called "racing green" without any claim on a car manufacturer. This is nominative use:
naming a thing in order to describe a resemblance to it. It is not a claim of origin,
authorship or authority.

The project's own framing is **"Amiga Inspired"**. Inspired by. Not a port, not a
recreation, not a replica, not a continuation, and not a substitute for anything real.

### No original assets are used or distributed

This theme is **CSS only**. It contains no copyrighted material from any Amiga or
Commodore product. Specifically, it does **not** contain, embed, adapt, trace, or
redistribute:

- Workbench, AmigaOS or Kickstart ROM code, or any part of any operating system
- Original Workbench icons, or any icon set derived from them
- MagicWB, NewIcons, GlowIcons, or any other third-party Amiga icon set
- Topaz or any other Amiga bitmap font, or any digitisation of one
- Original wallpapers, backdrops, pointers, brand marks or logos
- Screenshots of any Amiga system, used as an asset or otherwise

Every graphic in this theme is an **original drawing**, authored for this project as
inline SVG, using ordinary geometry. Colour values are stated as plain numbers. Colours
themselves are not copyrightable, and no artwork has been copied.

### Trademark acknowledgement

Amiga, AmigaOS, Kickstart and Workbench are trademarks or registered trademarks of their
respective owners. Commodore is a trademark of its respective owner. All such marks are
acknowledged as the property of those owners, and are used here only descriptively, to
identify the historical visual style that inspired this work.

Obsidian is a trademark of Dynalist Inc. This theme is a community theme for Obsidian and
is not produced by, endorsed by, or affiliated with Dynalist Inc.

### If you are a rights-holder

If you represent any rights-holder and consider anything in this project to overstep,
please open an issue on the repository. The developer's intention is respectful homage
within the bounds of independent creative work, and any specific, good-faith concern will
be addressed promptly and without argument.

### Licence

This theme is released under the **MIT Licence**. See [LICENSE](LICENSE) for the full
text. The MIT Licence covers **only the original CSS and documentation in this
repository**. It does not, and cannot, grant any rights in any third party's trademarks
or copyrighted works, and confers no rights in anything owned by the parties named above.
