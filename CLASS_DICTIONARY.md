# Clean Spotify - Class Dictionary

> [!WARNING]
> Spotify uses dynamic class names - the userstyle may break after updates.

### Global & Overrides

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Global Scrollbar** | `.os-scrollbar-vertical` | Hides the vertical scrollbar globally. |
| **Main Footer** | `.main-view-container__mh-footer-container` | Hides the main Spotify footer container. |

### Top Header

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Header Container** | `.YsP3Gj4aJDYsaOC5` | Forces the header to full-width and spaces elements. |
| **Home Button Spacing** | `.qPaMr9Jzt0_Doy3C ._Bg_zSvFrEutyacG` | Adds margin space left of the Home (house) icon. |
| **Spotify Logo** | `.Cafs_YTh_Qg9Jk7m` | Hides the Spotify logo in the top-left corner. |
| **Right Side Buttons** | `.encore-text-body-small-bold` | Hides buttons like "Explore Premium". *(Note: This is overridden later to show the "Show All" button).* |

### Search Bar

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Search Container** | `.eu6ObgEHE5owtzi_` | Centers and resizes the search input field. |
| **Hover Shortcuts**| `.WsYez2D10Mop_rOw` | Hides the keyboard shortcut hints in the search bar. |
| **Filter Pills** | `.x_HLN829yDsvJDgl` | Hides the "All", "Music", and "Podcast" filter pills. |

### Profile Menu

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Hover Underline**| `.kaFcDUSEXPonEYJm:after`, `.ESQKhiBFqQIFO1qu:after` | Removes the green active/hover underline on profile items. |
| **Progress Bar** | `.ESQKhiBFqQIFO1qu` | Hides the "Getting Started" progress bar entirely. |
| **Upgrade to Premium** | `.glp7Ah4Cywoy2Q6n > li:nth-child(4)` | Hides the upgrade option in the dropdown menu. |
| **Divider Line** | `.noRWQA3grBYNT5QG` | Hides the divider line in the dropdown menu. |
| **Your Updates** | `.wwh7lpPwfhcu8qTg` | Hides the "Your Updates" bell/section. |

### Home Page

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Home Container** | `[data-testid="home-page"]` | Adds top padding to offset the custom header. |
| **Jump Back In** | `[data-testid="home-page"] .aKzLj1l9YnIwouCc` | Hides the "Jump back in" section. |
| **Recommendations** | `[data-testid="home-page"] .l3tPikCftuELMOzz` | Hides general recommendations. |
| **Made For You** | `[data-testid="home-page"] .YR7WOlf_lck48w4l` | Hides the "Made for you" section. |
| **Getting Started** | `[data-testid="home-page"] .C8qLX8lOHwAx63FP` | Hides introductory cards. |
| **Promo Cards** | `[data-testid="home-page"] :is(.re6tIyfoHvgJCQod, .k2lmpygysqwv8ES4)`| Hides promotional music and tour cards. |

### Artist Page

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Discography** | `[data-testid="artist-page"] .contentSpacing > .Shelf:nth-child(2)` | Keeps the main discography row visible. |
| **"Show All" Button** | `[data-testid="artist-page"] .encore-text-body-small-bold` | Overrides the global hide to keep this button visible. |
| **Other Shelves** | `[data-testid="artist-page"] .Shelf` | Hides all other music shelves on the artist page. |
| **On Tour** | `[data-testid="artist-page"] .contentSpacing > div:nth-child(4)` | Hides the tour dates section. |
| **About Section** | `[data-testid="artist-page"] .contentSpacing > div:nth-child(5)` | Hides the artist biography/about section. |

### Media Pages (Album, Playlist, Track)

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **General Shelves** | `:is([data-testid="album-page"], [data-testid="playlist-page"], [data-testid="track-page"]) .Shelf` | Hides card-style recommendations on media pages. |
| **List Recommendations**| `:is([data-testid="album-page"], [data-testid="playlist-page"], [data-testid="track-page"]) :is(.Ld0s4rBe_x0Ke84Q, .kgkMCZPpmzc5dRXd)` | Hides list-style recommendations. |

### Now Playing (Right Sidebar)

| UI Element | Current Class Hash / Selector | Action |
| :--- | :--- | :--- |
| **Artist Info** | `.ax9CMxA763c25wSn` | Hides artist info and credits in the Now Playing sidebar. |
| **Bottom Fade** | `.aOBAWy97nIgISCgo` | Removes the bottom gradient overlay in the sidebar. |

<br>

<p align="center">
  <i>Making it worse before it gets better.</i>
</p>
