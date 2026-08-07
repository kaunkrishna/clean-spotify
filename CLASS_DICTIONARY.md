# Class Dictionary

> [!WARNING]
> Spotify uses dynamic class names - the userstyle may break after updates.

<br>

## Global

**Scope:** Site-wide

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Various Buttons** | `.encore-text-body-small-bold` | Hides buttons globally. |
| **Filter Pills** | `.g8bL3bGxc63nO5u9gY7g` | Hides the filter pills on the UI. |
| **Global Scrollbar** | `.os-scrollbar-vertical` | Hides the vertical scrollbar globally. |
| **Main Footer** | `.main-view-container__mh-footer-container` | Hides the main Spotify footer container. |
| **Liking Buttons** | `.UmC7B1blaToOXizU button` | **[Override]** Forces the liking/action buttons to display. |

<br>

## Profile Menu

**Selector:** `[data-testid="user-widget-menu"]`

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Upgrade to Premium** | `& ul > li:nth-child(4)` | Hides the premium upgrade option in the dropdown menu. |
| **Divider Line** | `.TC38nBQRHCYnwoEsmMZZ` | Hides the divider line in the dropdown menu. |
| **Your Updates** | `.aut5NpEEkS68T8ZrggVU` | Hides the "Your Updates" section in the menu. |

<br>

## Home Page

**Selector:** `[data-testid="home-page"]`

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Home Container** | `(Parent Container)` | Adds top padding to the home view. |
| **Recommendations** | `[data-shelf="carousel"]` | Hides carousel-style recommendations. |
| **The Reels** | `[data-testid="component-shelf"]` | Hides component shelves/reels. |
| **Small Text Buttons** | `.encore-text-body-small-bold` | **[Override]** Forces the smaller text buttons to display on the home page. |

<br>

## Artist Page

**Selector:** `[data-testid="artist-page"]`

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Other Shelves** | `.Shelf` | Hides all other music shelves on the artist page. |
| **On Tour** | `.contentSpacing > div:nth-child(4)` | Hides the tour dates section. |
| **About Section** | `.contentSpacing > div:nth-child(5)` | Hides the artist biography/about section. |
| **Discography** | `.contentSpacing > .Shelf:nth-child(2)` | **[Override]** Keeps the main discography row visible. |
| **"Show All" Button** | `.encore-text-body-small-bold` | **[Override]** Keeps this specific button visible on artist pages. |

<br>

## Media Pages (Album, Playlist, Track)

**Selector:** `:is([data-testid="album-page"], [data-testid="playlist-page"], [data-testid="track-page"])`

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **General Shelves** | `.Shelf` | Hides card-style recommendations. |
| **List Recommendations 1** | `.Ld0s4rBe_x0Ke84Q` | Hides list-style recommendations. |
| **List Recommendations 2** | `.kgkMCZPpmzc5dRXd` | Hides additional list-style recommendations. |

<br>

---

<p align="center">
  <i>Making it worse before it gets better.</i>
</p>
