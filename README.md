#ProjectDenis Web App v.1.2
========================================================================================
#ProjectDenis explores the repertoire of the Sliabh Luachra music legend, fiddle player Denis Murphy (1910–1974).

Join fiddle player Anton Zille and other Friends of Sliabh Luachra in a quest to uncover hidden gems in archival, historical and other previously unexplored recordings of Denis Murphy. Use this app to guide you to the tapes and tunes as they are being studied and organised from sources scattered across dozens of online and offline collections. Contribute to the volunteer project and the spreading of Denis Murphy's legacy by setting off on your own personal research journey or by simply learning some great tunes!

**December 2025 update:**

Progressive Web App improvements for better offline and cross-platform experience.

**November 2024 update:** 

#ProjectDenis: ITMA Blog Edition has been released! Anton Zille's blog _Stories Told by Cards & Tapes: Uncovering Denis Murphy Materials at ITMA_ is a project done in cooperation with Irish Traditional Music Archive (ITMA). It features original research and some 40 previously unpublished recordings. The blog and the newly published materials can be accessed on ITMA's website:

https://www.itma.ie/collections/denis-murphy/

Use #ProjectDenis app to see the full extent of archival materials cited in the blog and explore a total of 10 Denis Murphy collections available for research at ITMA.

**July 2024 update:**

#ProjectDenis Prototype officially released!

https://sliabhluachra.github.io/ProjectDenis/

## App Overview

### Start Menu Sections:

Section Name | Description |
| --- | --- |
| **Start Exploring** | Get the latest #ProjectDenis database and launch the app by pressing this button |
| **App Helper** | Little Denis Helper will offer to to begin a detailed Guide Help Tour of the app |

### Main Menu Sections:

Section Name | Description |
| --- | --- |
| **#Search** | Search through 700+ database items for Denis Murphy tunes, albums or track details |
| **#Explore** | Explore Tracklist, Tunelist and list of Collections presented in interactive table format |
| **#Discover** | Discover sources & tools used in #ProjectDenis tune research and identification process |

NB: This is the Client version of the app. For Toolkit version with Tune DB tools and complete version history see [#ProjectDenis Toolkit](https://github.com/anton-bregolas/ProjectDenisToolkit).

## Version History

**PWA Improvements**

v.1.2.1

+ Update Tune DB to 2025-12-12 (Fix tunes with reflinks containing commas)

v.1.2.0

+ Refactor service worker logic for robust offline functionality
+ Service worker now correctly serves assets on reload while offline
+ Add asset categories to service worker, lazy-load images and fonts
+ Add fallback service worker methods for handling specific type of assets while offline
+ Update app.webmanifest: Add id and screenshot links
+ Add wide and narrow form-factor screenshots for PWA install menu
+ Add new primary app font (Lato) for consistent app display across platforms
+ Add auto-update-version scripts fine-tuned for app and toolkit
+ Add fallback background-color for The Star above the Garter theme
+ Fix JSON Splitter incorrectly parsing tune reflinks containing comma; Space between links is now required

<details>
  <summary>Version History Archive</summary>

v.1.1.4

+ Update Tune DB to 2025-11-01 (Fix tracks, add link for 12000)

v.1.1.3
 
+ Update Tune DB to 2025-10-25 (Add ITI link for 1000)

v.1.1.2

+ Fix links to Bill Black's ABCs & source naming logic in wake of BB website update
+ Add ITMA links to collections featured in 2024 Denis Murphy blog
+ Add underline styles to popover grid links for clarity
+ Fix Alt + F3 focus behavior, scrollIntoView is now instant
+ Update Tune DB to 2025-10-08

v.1.1.1

+ Custom line break marker added to account for song lyrics in track details.
+ Annotations added and fixed in BB collections.
+ Annotations added and fixed in HD35.
+ Tune DB updated to 2024-12-02.

v.1.1.0

**ITMA Blog Edition**

+ Major Tune DB update with 8 new catalogued ITMA collections (10 in total).
+ Default colour scheme changed to The Paps of Anu.
+ Tracklist items now follow a unified naming standard: 
+ * Tune Title for tune names provided in source;
+ * [Tune Title] for tune names supplied by editor.
+ Keyboard shortcuts added:
+ * Alt + F1 = Launch Helper;
+ * Alt + F2 = Launch Navigation Menu;
+ * Alt + F3 = Focus on Search Input.
+ Minor improvements made to Search Engine.
+ Navigation Menu behaviour improved for keyboard users.
+ Help button launching Helper added to Navigation Menu.
+ Helper guided tour menu updated, keyboard navigation improved.
+ Notification banner shown first time new edition loads added to app.
+ Donation links added.
+ Tune DB updated to 2024-11-27.

v.1.0.7
+ Tune DB links updated to separate the test (Toolkit) DB version from live (Client) DB version.

v.1.0.6
+ Added GoatCounter, a privacy-oriented analytics app, to check on basic visitor stats.

v.1.0.5
+ Tune DB updated to 2024-08-13.

v.1.0.4
+ Tweaks to UI elements after tests in more browsers.

v.1.0.3
+ Tune DB updated to 2024-07-27.

v.1.0.2
+ Popover card tweaks to improve mobile experience.

v.1.0.1

+ Progressive Web App.
+ Minor UI/UX tweaks.

v.1.0.0

+ Initial commit as a separate Client version from #ProjectDenis Toolkit v.3.1
+ Modules included: App Launcher, App Helper, Modal Lists Generator, Popovers Generator, Tracklist Generator, Search Engine.
+ Tune DB version 2024-07-23.
</details>