---
title: Components
has_toc: false
---

# Component Status

## Technology Overview

| Technology | Platform(s) |
|:-----------|:------------|
| <img src="https://avatars.githubusercontent.com/u/14101776?s=200&v=4" alt="Flutter" width="24" style="vertical-align:middle;"/> **Flutter** | iOS, Android   |
| <img src="https://developer.apple.com/assets/elements/icons/swiftui/swiftui-96x96_2x.png" alt="SwiftUI" width="24" style="vertical-align:middle;"/> **SwiftUI** | iOS            |
| <img src="https://logo.svgcdn.com/d/jetpackcompose-original-8x.png" alt="Jetpack Compose" width="24" style="vertical-align:middle;"/> **Jetpack Compose** | Android        |
| <img src="https://plugins.jetbrains.com/files/15596/564707/icon/default.png" alt="Stencil" width="24" style="vertical-align:middle;"/> **StencilJS** | Web            |

## Atoms

| Atom        | Design | Flutter | iOS  | Android | Web |
|:-----------------|:------:|:-------:|:----:|:-------:|:---:|
| [Avatar]         |   ✅   |   ➖    |  ➖  |   ➖    |  ➖  |
| [Button]         |   ✅   |   ✅    |  🔜  |   🔜    |  ➖  |
| [Checkbox]       |   ✅   |   ➖    |  ➖  |   ➖    |  ➖  |
| [Chip]           |   ✅   |   ✅    |  ➖  |   ➖    |  ➖  |
| [Divider]        |   ✅   |   ✅    |  🔜  |   🔜    |  ➖  |
| [Drawer]         |   ✅   |   ➖    |  ➖  |   ➖    |  ➖  |
| [Dropdown]       |   ✅   |   ➖    |  ➖  |   ➖    |  ➖  |
| [Icon]           |   ✅   |   ✅    |  🔜  |   🔜    |  ➖  |
| [Icon Button]    |   ✅   |   ✅    |  🔜  |   🔜    |  ➖  |
| [Icon With Background]       |   ✅   |   ✅    |  🔜  |   🔜    |  ➖  |
| [Image]          |   ✅   |   ✅    |  🔜  |   🔜    |  ➖  |
| [Loading Spinner]  |   ➖   |   ➖    |  ➖  |   ➖    |  ➖  |
| [Lottie]         |   ✅   |   ✅    |  🔜  |   🔜    |  ➖  |
| [Modal]            |   ➖   |   ➖    |  ➖  |   ➖    |  ➖  |
| [Radio Button]   |   ✅   |   ➖    |  ➖  |   ➖    |  ➖  |
| [Stepper]        |   ✅   |   ➖    |  ➖  |   ➖    |  ➖  |
| [Surface]        |   ✅   |   ✅    |  🔜  |   🔜    |  ➖  |
| [Text]           |   ✅   |   ✅    |  🔜  |   🔜    |  ➖  |
| [Text Field]     |   ✅   |   ➖    |  🔜  |   🔜    |  ➖  |
| [Text Link]      |   ✅   |   ✅    |  🔜  |   🔜    |  ➖  |
| [Tile Button]    |   ✅   |   ✅    |  ➖  |   ➖    |  ➖  |
| [Toggle]           |   ✅   |   🔜    |  ➖  |   ➖    |  ➖  |

| Molecule                   | Design | Flutter | iOS  | Android | Web |
|:---------------------------|:------:|:-------:|:----:|:-------:|:---:|
| Avatar Group               |   ➖   |   ➖    |  ➖  |   ➖    |  ➖  |
| Avatar with Label          |   ➖   |   ➖    |  ➖  |   ➖    |  ➖  |
| Badge                      |   ✅   |   ✅    |  ➖  |   ➖    |  ➖  |
| Button Bar                 |   ✅   |   🚧    |  ➖  |   ➖    |  ➖  |
| Checkbox with Label        |   ➖   |   ➖    |  ➖  |   ➖    |  ➖  |
| Chip Group                 |   ✅   |   🔜    |  ➖  |   ➖    |  ➖  |
| Inline Message             |   ➖   |   ➖    |  ➖  |   ➖    |  ➖  |
| Loading Spinner with Label |   ➖   |   ➖    |  ➖  |   ➖    |  ➖  |
| Page Footer                |   ➖   |   ➖    |  ➖  |   ➖    |  ➖  |
| Page Header                |   ✅   |   🚧    |  ➖  |   ➖    |  ➖  |
| Page-Wide Message          |   ✅   |   ✅    |  ➖  |   ➖    |  ➖  |
| Radio Button with Label    |   ➖   |   ➖    |  ➖  |   ➖    |  ➖  |
| Toast                      |   ✅   |   ✅    |  ➖  |   ➖    |  ➖  |
| Toggle with Label          |   ➖   |   ➖    |  ➖  |   ➖    |  ➖  |

| Organism                   | Design | Flutter | iOS  | Android | Web |
|:---------------------------|:------:|:-------:|:----:|:-------:|:---:|
| Card Footer                |   🚧   |   🔜    |  ➖  |   ➖    |  ➖  |
| Large Card                 |   🚧   |   🔜    |  ➖  |   ➖    |  ➖  |
| Medium Card                |   🚧   |   🔜    |  ➖  |   ➖    |  ➖  |
| Micro Card                 |   🚧   |   🔜    |  ➖  |   ➖    |  ➖  |
| Small Card                 |   🚧   |   🔜    |  ➖  |   ➖    |  ➖  |

{% assign atom_path = 'docs/components/atoms/' %}
[Button]: {% link {{ atom_path }}button.md %}
[Text]: {% link {{ atom_path }}text.md %}
[Divider]: {% link {{ atom_path }}divider.md %}
[Surface]: {% link {{ atom_path }}surface.md %}
[Icon Button]: {% link {{ atom_path }}icon-button.md %}
[Icon With Background]: {% link {{ atom_path }}icon-with-background.md %}
[Text Link]: {% link {{ atom_path }}text-link.md %}
[Chip]: {% link {{ atom_path }}chip.md %}
[Checkbox]: {% link {{ atom_path }}checkbox.md %}
[Drawer]: {% link {{ atom_path }}drawer.md %}
[Dropdown]: {% link {{ atom_path }}dropdown.md %}
[Radio Button]: {% link {{ atom_path }}radio-button.md %}
[Stepper]: {% link {{ atom_path }}stepper.md %}
[Text Field]: {% link {{ atom_path }}text-field.md %}
[Toggle]: {% link {{ atom_path }}toggle.md %}
[Image]: {% link {{ atom_path }}image.md %}
[Lottie]: {% link {{ atom_path }}lottie.md %}
[Modal]: {% link {{ atom_path }}modal.md %}
[Avatar]: {% link {{ atom_path }}avatar.md %}
[Tile Button]: {% link {{ atom_path }}tile-button.md %}
[Loading Spinner]: {% link {{ atom_path }}loading-spinner.md %}
[Icon]: {% link {{ atom_path }}icon.md %}
