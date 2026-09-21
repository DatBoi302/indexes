# Projects Compendium

Personal project tracker — project entries, descriptions, information, locations, and more...

## PROJECTS

| | | |
|---|---|---|
| [Star UI](#star-ui) | [Image Tools](#image-tools) | [Global ReShade Injection Library](#global-reshade-injection-library) |
| [Various Steam Plugins](#various-steam-plugins) | [Faraday](#faraday) | [Various Browser Mods / Extensions](#various-browser-mods--extensions) |
| [Refine / Modify Existing Applications](#refine--modify-existing-applications) | [CSS WebRipper](#css-webripper) | [Prism (Gemini .CSS)](#prism-gemini-css) |
| [Windows Terminal Tweaker](#windows-terminal-tweaker) | [Deconstructing Gemini Extensions](#deconstructing-gemini-extensions) | [Free AI Tools / APIs / Accounts / Software — Bundle](#free-ai-tools--apis--accounts--software--bundle) |
| [VSCode Custom CSS and JS](#vscode-custom-css-and-js) | [Path Scripts](#path-scripts) | [Bandcamp Tagger](#bandcamp-tagger) |
| [Docs-CLI](#docs-cli) | [Joplin Theme Switcher](#joplin-theme-switcher) | [Setup-Project](#setup-project) |
| [Context-Menu (Shell Switcher)](#context-menu-shell-switcher) | [IDE Sync](#ide-sync) | [Nilesoft Shell GUI](#nilesoft-shell-gui) |
| [Claude Profile Manager](#claude-profile-manager) | [Extension Groups](#extension-groups) | [Shortcut Centralizer](#shortcut-centralizer) |
| [Cursor Theme Animations](#cursor-theme-animations) | [C Drive Cleanup](#c-drive-cleanup) | [Game Page Enhancer](#game-page-enhancer) |
| [listnr](#listnr) | [Music - WACUP Plugin](#music---wacup-plugin) | [Music Suite](#music-suite) |
| [Typora Tint](#typora-tint) | [One Commander - Themes](#one-commander---themes) | [HLSL Converter](#hlsl-converter) |
| [HLSL Normalizer](#hlsl-normalizer) | [CustomTkinter Asset Library](#customtkinter-asset-library) | [- PY Bat Compilers](#--py-bat-compilers) |
| [TUI Layout Designer](#tui-layout-designer) | [AnyZip to 7z Converter](#anyzip-to-7z-converter) | [ASCII](#ascii) |
| [Folder Flattener](#folder-flattener) | [No Overwrite Mover](#no-overwrite-mover) | [Sea Power - Mod Renamer](#sea-power---mod-renamer) |
| [Start11 Start Menu Repair](#start11-start-menu-repair) | [TXT to JSON](#txt-to-json) | [E Terminal Gift](#e-terminal-gift) |
| [Browser Launcher](#browser-launcher) | [Print-Packages](#print-packages) | [VS Code Theme Bundler](#vs-code-theme-bundler) |

## BROAD-SCOPE

- [Improve / Discover AI Workflow](#improve--discover-ai-workflow)
- [Windows 10 Customization](#windows-10-customization)
- [Windows Terminal / CMD / PowerShell](#windows-terminal--cmd--powershell)

## Project Status Key

Exactly status used by all projects, five statuses:

| Status | Meaning |
|---|---|
| NOT STARTED | Idea captured — no work has begun. |
| IN PROGRESS | Actively being built or reworked. |
| NEARING COMPLETION | Core work is done — polish, optimization, or final tasks remain. |
| COMPLETE | Shippable / done. May still get an optional revisit — see Remaining. |
| ONGOING | No defined end — maintained or expanded indefinitely. |

## Type Key

Exactly one Type per project, eight fixed types — pick the closest match, don't invent a new one:

| Type | Meaning |
|---|---|
| GUI App | A standalone application with a graphical interface. |
| CLI / Script | A command-line tool, automation script, or background job. |
| Browser Mod/Ext | A browser extension, userscript, or browser-level modification. |
| App Plugin | A plugin/extension for an existing non-browser application. |
| Game Mod | Modding content built for a specific game. |
| Styling / Theme | CSS or a theme pack restyling an existing app or site. |
| Library / Asset Collection | A reusable asset or reference collection, not a deliverable on its own. |
| Research & Setup | Exploratory work or setup with no single shippable deliverable yet. |

Tags: free-form, lowercase, hyphenated — stack, language, or domain keywords (`#python`, `#tauri`, `#css`, `#game-mod`). As many as are useful, comma-separated. Skip the line if none are known yet — don't guess.

Location(s): one line per path — DIR: for a local folder/file, WEB: for a URL.

Reusable Parts: short note on what could be extracted and reused elsewhere — a GUI shell, a function, a pattern.

Tip: WEB: URLs render as clickable links automatically. DIR: paths are plain text for local reference. Commit at natural checkpoints (end of a session, a real milestone) rather than after every small edit — keeps history readable across agents.

---

## Projects

Concrete builds — apps, scripts, mods — each with a clear deliverable.

### Template

Copy this block (through Reusable Parts) and paste it below your last entry to log a new project.

**\<Project Name\>**
<one-line description of the project>

- **Status:** <use key above>
- **Type:** <use key above>
- **Tags:** <stack/domain keywords, or omit the line>
- **Remaining:** <what's left to do>
- **Issues:** <known bugs / blockers, or —>
- **Notes:** <context, decisions, links>
- **Location(s):** <DIR: D:\path\to\project\ | WEB: https://... — one per line, as many as needed>
- **Reusable Parts:** <piece(s) worth reusing elsewhere — GUI shell, function, pattern>

---

### Star UI
Comprehensive UI modding GUI tool for Starsector.

- **Status:** NEARING COMPLETION
- **Type:** GUI App
- **Tags:** #game-mod, #starsector
- **Remaining:** Optimization pass / various small tweaks, enhancements & features.
- **Issues:** —
- **Notes:** Image handling has a limited amount of changes that can be made to it, for optimization or otherwise, due to a convoluted solution being the only fix found for artifacting on transparent .png UI assets.
- **Location(s):** DIR: [D:\Code Projects\Star UI\](file:///D:/Code%20Projects/Star%20UI/)
- **Reusable Parts:** —

### Image Tools
Refining, expanding, and eventually combining image editing tools into a lightweight GUI. (See Path Scripts.)

- **Status:** NOT STARTED
- **Type:** CLI / Script
- **Tags:** #python, #image-processing
- **Remaining:** Refine Python scripts, options, functions, etc. Build a GUI.
- **Issues:** —
- **Notes:** Considering a different language for the GUI, since it'll be small and lightweight — only meant to ease running the .py scripts.
- **Location(s):** DIR: [D:\Code Projects\Image Color Layer Seperator\](file:///D:/Code%20Projects/Image%20Color%20Layer%20Seperator/) | DIR: [D:\Code Projects\Image Grid Maker\](file:///D:/Code%20Projects/Image%20Grid%20Maker/) | DIR: [D:\Code Projects\Image Recolor and Converter\](file:///D:/Code%20Projects/Image%20Recolor%20and%20Converter/) | DIR: [D:\Code Projects\Depth Mapper 2D\](file:///D:/Code%20Projects/Depth%20Mapper%202D/) | DIR: [D:\Code Projects\Paint.NET Layer Renamer\](file:///D:/Code%20Projects/Paint.NET%20Layer%20Renamer/)
- **Reusable Parts:** —

### Global ReShade Injection Library
GUI tool that manages a single ReShade library, injects it into games, handles updates, and can modify injected shaders for game compatibility.

- **Status:** IN PROGRESS
- **Type:** GUI App
- **Tags:** #game-mod, #reshade
- **Remaining:** A new method of tracking and injecting specific ReShade shaders into the application.
- **Issues:** —
- **Notes:** Came about after finding the global shader library doesn't work well with certain applications — e.g. games running on DirectX9.
- **Location(s):** DIR: [D:\Code Projects\Global Reshade Library\](file:///D:/Code%20Projects/Global%20Reshade%20Library/)
- **Reusable Parts:** —

### Various Steam Plugins
Improve existing plugins and finish new ones for Millennium.

- **Status:** ONGOING
- **Type:** App Plugin
- **Tags:** #steam, #millennium
- **Remaining:** Add a settings menu to CsRin_Plus; complete a working version of Steam_Linker.
- **Issues:** —
- **Notes:** CsRin_Plus: adds buttons to the Steam store linking to browser game deal/release sites. Steam_Linker: adds the UI bar under native Steam games in the library to non-Steam shortcut games.
- **Location(s):** DIR: [D:\Code Projects\Steam Plugins\Cs.Rin.Ru External\](file:///D:/Code%20Projects/Steam%20Plugins/Cs.Rin.Ru%20External/) (CsRin_Plus) | DIR: [D:\Code Projects\Steam Plugins\non-steam-linker\](file:///D:/Code%20Projects/Steam%20Plugins/non-steam-linker/) (Steam_Linker)
- **Reusable Parts:** —

### Faraday
Sandboxie-based GUI that captures an application's folder and keeps all related AppData and Documents files inside it.

- **Status:** COMPLETE
- **Type:** GUI App
- **Tags:** #sandboxie
- **Remaining:** (If desired) a second pass on all GUI elements and application functions.
- **Issues:** Possible functionality loss — e.g. Faraday-redirected LibreOffice opens Zen Browser outside the user's default Zen profile, breaking Google Docs sync.
- **Notes:** Test whether it affects an application's performance.
- **Location(s):** DIR: [D:\Code Projects\Application Data Redirect GUI\Faraday\](file:///D:/Code%20Projects/Application%20Data%20Redirect%20GUI/Faraday/)
- **Reusable Parts:** —

### Various Browser Mods / Extensions
Modding Zen, Firefox, and Thorium to better suit the user's needs — mods, extensions, launch commands, and portable multi-install setups.

- **Status:** ONGOING
- **Type:** Browser Mod/Ext
- **Tags:** #zen, #firefox, #thorium, #tampermonkey
- **Remaining:** None currently.
- **Issues:** —
- **Notes:** Completed: custom Thorium build for Gemini-only use | Zen tab right/left-side switcher + graphics/CPU acceleration toggle | Thorium "Zen_Link" extension routing clicked links and highlighted-text searches to Zen instead of Thorium.
- **Location(s):** DIR: [D:\Code Projects\Zen Browser Mods\](file:///D:/Code%20Projects/Zen%20Browser%20Mods/) | DIR: [D:\Code Projects\Browser Devtools\Chrome-Gruvbox\](file:///D:/Code%20Projects/Browser%20Devtools/Chrome-Gruvbox/) | DIR: [D:\Code Projects\Tamper Monkey\AutoPager Translated\](file:///D:/Code%20Projects/Tamper%20Monkey/AutoPager%20Translated/)
- **Reusable Parts:** —

### Refine / Modify Existing Applications
Refine or modify commonly used applications using sources like GitHub (e.g. PhotoGimp for GIMP).

- **Status:** ONGOING
- **Type:** Research & Setup
- **Remaining:** Pick applications; discuss improvements, alternatives, modifications.
- **Issues:** —
- **Notes:** —
- **Location(s):** —
- **Reusable Parts:** —

### CSS WebRipper
Custom portable Firefox build for .css styling, plus a Python/Node CLI that rips and cleans a page's .css for easy reading and Stylus styling.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Tags:** #css, #python, #nodejs, #firefox
- **Remaining:** —
- **Issues:** —
- **Notes:** Perhaps integrate some sort of application version of Stylus.
- **Location(s):** DIR: [C:\SystemEdits\Scripts\Web-Ripper-Monolith.bat](file:///C:/SystemEdits/Scripts/Web-Ripper-Monolith.bat) | DIR: [C:\SystemEdits\Scripts\Web-Ripper-SingleFile.bat](file:///C:/SystemEdits/Scripts/Web-Ripper-SingleFile.bat) | DIR: [C:\SystemEdits\Scripts\utils\Monolith_Ripper_CLI.ps1](file:///C:/SystemEdits/Scripts/utils/Monolith_Ripper_CLI.ps1) | DIR: [C:\SystemEdits\Scripts\utils\SingleFile_Ripper_CLI.ps1](file:///C:/SystemEdits/Scripts/utils/SingleFile_Ripper_CLI.ps1)
- **Reusable Parts:** —

### Prism (Gemini .CSS)
Comprehensive CSS styling and effects Chrome extension for the Gemini website — documented and implemented via Stylus early on, now a full extension.

- **Status:** NEARING COMPLETION
- **Type:** Browser Mod/Ext
- **Tags:** #css, #chrome-extension, #gemini, #nodejs
- **Remaining:** Complete the MV3 extension restructure (manifest.json and associated files started, not finished at last checkpoint); finish documenting the Gemini stylesheet's remaining properties; update the Thorium Gemini launcher's profile path to the new `Config\BrowserProfiles\<Browser>\<ProfileName>\` convention.
- **Issues:** —
- **Notes:** Began as Stylus + Tampermonkey, restructured into an MV3 unpacked extension for per-element control and to avoid CSP conflicts. Reached a milestone: a finalized, audited CSS effects library (~251 named effects across two volumes, 52 keyframes) with a complete trigger-state system (data-fx-trigger, --fx-on/--fx-play-state; Always/Hover/Active/Focus/Toggle modes). CSS selector library covers ~400–492 selectors across 22 sections with a JSON prop schema. A four-phase automated DOM extraction pipeline (DevTools snippet → Python merger → Anthropic API batch describer → manifest/markdown output) keeps the selector library current as Gemini's Angular DOM evolves. Also referred to as "Gemini Prism." Includes a working Gemini Sidebar Dock (AHK-docked Thorium sidebar with a local hub page: clock, theme switcher, notes, bookmarks, extension launcher).
- **Location(s):** DIR: [D:\Code Projects\Gemini\Gemini Prism\](file:///D:/Code%20Projects/Gemini/Gemini%20Prism/)
- **Reusable Parts:** The trigger-state effect system (251 effects / 52 keyframes, 5 trigger modes) is a reusable framework for styling any site. The DOM manifest scrape → classify → index pipeline (prism-clean.js → prism-reclassify.js → prism-area-classify.js → prism-index.js, run against an ~80MB/~9,632-entry manifest) is reusable for other large DOM-styling projects.

### Windows Terminal Tweaker
GUI for customizing Windows Terminal — downloading plugins and converting shaders.

- **Status:** IN PROGRESS
- **Type:** GUI App
- **Tags:** #windows-terminal, #hlsl
- **Remaining:** —
- **Issues:** —
- **Notes:** Bundles packaged copies of HLSL Converter and HLSL Normalizer (see their own entries) for its shader-conversion feature.
- **Location(s):** DIR: [D:\Code Projects\WindowsTerminalTweaker\](file:///D:/Code%20Projects/WindowsTerminalTweaker/)
- **Reusable Parts:** —

### Deconstructing Gemini Extensions
Deconstruct favorite Gemini extensions and rebuild them to spec.

- **Status:** ONGOING
- **Type:** Browser Mod/Ext
- **Tags:** #gemini
- **Remaining:** —
- **Issues:** —
- **Notes:** —
- **Location(s):** —
- **Reusable Parts:** —

### Free AI Tools / APIs / Accounts / Software — Bundle
Accumulate free AI software, tools, CLIs, and APIs to maximize free usage and credits at no cost.

- **Status:** ONGOING
- **Type:** Research & Setup
- **Tags:** #ollama, #litellm, #aider, #cline
- **Remaining:** —
- **Issues:** —
- **Notes:** Includes local Ollama models plus Aider, Cline, and LiteLLM wired into a custom CLI launcher.
- **Location(s):** DIR: [D:\Code Projects\LiteLLM\](file:///D:/Code%20Projects/LiteLLM/)
- **Reusable Parts:** —

### VSCode Custom CSS and JS
Compile as many custom CSS/JS VS Code extensions as possible into one installable package, with as few components as possible.

- **Status:** IN PROGRESS
- **Type:** Styling / Theme
- **Tags:** #vscode, #css, #js
- **Remaining:** —
- **Issues:** —
- **Notes:** Injected via the `be5invis.vscode-custom-css` loader extension. 7 versioned iterations kept (v11–v17) plus an "Alt CSS Versions" folder; also has its own logger/deeplogger JS for debugging. Likely has a Cursor counterpart (`.cursor` or its AppData) — not yet confirmed, worth checking.
- **Location(s):** DIR: [C:\Users\John Hudock\.vscode\css\](file:///C:/Users/John%20Hudock/.vscode/css/)
- **Reusable Parts:** —

### Path Scripts
Port existing scripts into the global Path Scripts folder so they're callable from anywhere in the terminal; style them as proper CLIs.

- **Status:** ONGOING
- **Type:** CLI / Script
- **Tags:** #python
- **Remaining:** —
- **Issues:** —
- **Notes:** Notable Python imports for this task: InquirerPy, prompt_toolkit, questionary, rich, argparse, click, blessed, Textual, colorama, termcolor, tqdm, urwid.
- **Location(s):** DIR: [C:\SystemEdits\Scripts\](file:///C:/SystemEdits/Scripts/) | DIR: [C:\SystemEdits\Scripts\utils\](file:///C:/SystemEdits/Scripts/utils/)
- **Reusable Parts:** —

### Bandcamp Tagger
Bandcamp music auto-tagging CLI workflow, replacing a manual MusicBrainz Picard process.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Tags:** #python, #music, #bandcamp
- **Remaining:** — (status recalled from memory, not this doc — confirm/correct)
- **Issues:** —
- **Notes:** Built on beets, beetcamp, yt-dlp, and mutagen. Features a Rich UI, progress bars, and color-coded summary tables. Being folded into the new Music Suite unified CLI (see its own entry).
- **Location(s):** DIR: [D:\Code Projects\Music Suite\bandcamp-tagger.py](file:///D:/Code%20Projects/Music%20Suite/bandcamp-tagger.py) | DIR: [C:\SystemEdits\Scripts\bandcamp-tagger.bat](file:///C:/SystemEdits/Scripts/bandcamp-tagger.bat)
- **Reusable Parts:** The Rich progress-bar + color-coded summary-table pattern is reusable in any CLI that processes a batch of items.

### Docs-CLI
CLI documentation management tool — pulls GitHub repo docs, hosts them, and indexes them in Cursor.

- **Status:** ONGOING
- **Type:** CLI / Script
- **Tags:** #python, #repomix, #cursor
- **Remaining:** — (status recalled from memory, not this doc — confirm/correct)
- **Issues:** —
- **Notes:** Automates pulling GitHub repo docs via Repomix, hosting them on Surge.sh, and indexing them in Cursor IDE's "Index Docs" feature. Interactive Rich/InquirerPy interface with dashboard stats and per-repo Repomix flag management.
- **Location(s):** DIR: [C:\SystemEdits\Scripts\Docs.bat](file:///C:/SystemEdits/Scripts/Docs.bat) | DIR: [C:\SystemEdits\Scripts\utils\Docs-CLI.py](file:///C:/SystemEdits/Scripts/utils/Docs-CLI.py) | DIR: [C:\Users\John Hudock\Config\Agent-Docs\Docs-CLI-Config.json](file:///C:/Users/John%20Hudock/Config/Agent-Docs/Docs-CLI-Config.json) | WEB: cursor-index-docs.surge.sh
- **Reusable Parts:** The Repomix → Surge.sh hosting → Cursor Index Docs pipeline is reusable for any "pull external docs and index them locally" need. The Rich/InquirerPy dashboard shell is a reusable CLI-dashboard template.

### Joplin Theme Switcher
Custom CSS theme switcher plugin for the Joplin markdown editor.

- **Status:** IN PROGRESS
- **Type:** App Plugin
- **Tags:** #joplin, #css
- **Remaining:** — (status recalled from memory, not this doc — confirm/correct)
- **Issues:** —
- **Notes:** Resolved sandbox limitations around path operations and shell APIs inside Joplin's plugin sandbox.
- **Location(s):** DIR: [C:\Users\John Hudock\AppData\Roaming\Joplin\Plugins-Custom\Theme-Switcher\](file:///C:/Users/John%20Hudock/AppData/Roaming/Joplin/Plugins-Custom/Theme-Switcher/)
- **Reusable Parts:** The sandbox path/shell-API workaround may be reusable for other Joplin (or similarly sandboxed) plugin work.

### Setup-Project
Python CLI scaffolding tool with a custom prompt_toolkit TUI picker.

- **Status:** IN PROGRESS
- **Type:** CLI / Script
- **Tags:** #python
- **Remaining:** — (status recalled from memory, not this doc — confirm/correct)
- **Issues:** —
- **Notes:** Split-pane checkbox + live-preview picker built with Rich, InquirerPy, pyfiglet, and a custom prompt_toolkit split-pane layout. Launches in Windows Terminal at a 106x38 size.
- **Location(s):** DIR: [D:\Code Projects\Command Line Scripts\Setup Project\](file:///D:/Code%20Projects/Command%20Line%20Scripts/Setup%20Project/) | DIR: [C:\SystemEdits\Scripts\Setup-Project.bat](file:///C:/SystemEdits/Scripts/Setup-Project.bat) | DIR: [C:\SystemEdits\Scripts\utils\Setup_Project.py](file:///C:/SystemEdits/Scripts/utils/Setup_Project.py)
- **Reusable Parts:** The prompt_toolkit split-pane checkbox+preview picker is a strong standalone reusable component — a natural fit for the "reusable-parts" idea itself.

### Context-Menu (Shell Switcher)
CLI to radio-switch Windows context-menu shells (Nilesoft/Breeze/IMA/native) and toggle independent shell-tweak tools (WindowFX/TranslucentFlyouts).

- **Status:** IN PROGRESS
- **Type:** CLI / Script
- **Tags:** #python, #nilesoft-shell
- **Remaining:** Resolve the Breeze crash/half-inject behavior when switched via the CLI (currently only works via Breeze's own GUI re-injection). Resume the paused WindowFX/TranslucentFlyouts toggle work.
- **Issues:** Breeze caused a crash/half-injected state when switched via the CLI — explorer auto-restarted, then Breeze started working; fixed manually via Breeze's GUI (Inject All → Disabled → High Priority → Inject All).
- **Notes:** Renamed from shellctl to Context-Menu (prog name context-menu, config context-menu.json/context-menu.state.json under ~/.context-menu/). Nilesoft Shell and IMA Menu switches confirmed live-tested and working.
- **Location(s):** DIR: [C:\SystemEdits\Scripts\Context-Menu.bat](file:///C:/SystemEdits/Scripts/Context-Menu.bat) | DIR: [C:\SystemEdits\Scripts\utils\Context-Menu.py](file:///C:/SystemEdits/Scripts/utils/Context-Menu.py)
- **Reusable Parts:** —

### IDE Sync
Tauri (Rust + React/TS) GUI to symlink/sync config (extensions, MCP servers, settings) across VS Code, Cursor, Windsurf, and Antigravity.

- **Status:** IN PROGRESS
- **Type:** GUI App
- **Tags:** #tauri, #rust, #react-ts
- **Remaining:** Extension-linking approach (per-extension junctions vs. whole-folder) needs a final pass; UI polish (animations for tab switches, disclosure expand/collapse, button feedback) still open.
- **Issues:** —
- **Notes:** VS Code is the source of truth. Owns a dedicated canonical config store rather than picking one real IDE as truth. Ships safety features: timestamped backups before destructive ops, unlink-without-blanking, and MCP conflict diff/merge. Styled in an industrial-brutalist "Tactical Telemetry" theme.
- **Location(s):** DIR: [D:\Code Projects\IDE Sync\](file:///D:/Code%20Projects/IDE%20Sync/)
- **Reusable Parts:** The canonical-store + backup/diff-merge pattern is reusable for any cross-tool config-sync problem.

### Nilesoft Shell GUI
Tauri (Rust + React/TS) GUI to generate and manage Nilesoft Shell's `shell.nss`/`theme.nss` context-menu configs.

- **Status:** NEARING COMPLETION
- **Type:** GUI App
- **Tags:** #tauri, #rust, #react-ts, #nilesoft-shell
- **Remaining:** Theme background-gradient rendering edge cases; Rust/Tauri backend still not build-verified in the dev sandbox (frontend fully verified).
- **Issues:** —
- **Notes:** Feature-complete no-code menu editor: item add/remove/reorder, icons (with Shell's own bundled glyph set, docs-cross-checked), conditions builder, custom command templates, theme editor with live preview (dark/light, blur/acrylic, gradients), import manager, "Remove Built-ins" tab, raw editor with syntax sanity checks. 79/79 tests passing.
- **Location(s):** DIR: [D:\Code Projects\Nilesoft Shell GUI\](file:///D:/Code%20Projects/Nilesoft%20Shell%20GUI/)
- **Reusable Parts:** The popover color+alpha picker and the docs-verified glyph picker are both reusable standalone components.

### Claude Profile Manager
PowerShell + WPF GUI that launches multiple isolated Claude Desktop profiles (separate login sessions) with a Sync-Sources system equalizing MCP extensions/settings/skills across profiles.

- **Status:** NEARING COMPLETION
- **Type:** GUI App
- **Tags:** #powershell, #wpf
- **Remaining:** Compile into an .exe, pick an icon, then archive the project. MCP configuration equalization across profiles is a pending follow-up.
- **Issues:** Chats with locally-cached file artifacts opened in a different `userData` context can crash the renderer (`404 not_found_error` on artifact resolution) — affects the Main profile; root cause identified, no fix implemented yet.
- **Notes:** Fully built and deployed across three profiles: `Claude-WebExt`, `personal`, and `work` (separate Anthropic account). Two-tier Sync-Sources (global bucket for extensions/settings, per-account bucket for Skills) via directory junctions/symlinks. WPF UI is borderless, warm clay/terracotta palette, 460×760 portrait, staggered animations. Custom icon.ico created (clay palette, overlapping-card motif, 4-point sparkle) at seven Windows sizes.
- **Location(s):** DIR: [D:\Code Projects\Claude Profile Manager\](file:///D:/Code%20Projects/Claude%20Profile%20Manager/) | DIR: [C:\Users\John Hudock\Config\Claude-Profiles\](file:///C:/Users/John%20Hudock/Config/Claude-Profiles/)
- **Reusable Parts:** —

### Extension Groups
Custom VS Code extension ("ext-groups") to organize installed extensions into searchable, taggable, toggleable, multi-membership groups, across VS Code and its forks (Cursor, Windsurf).

- **Status:** IN PROGRESS
- **Type:** App Plugin
- **Tags:** #vscode
- **Remaining:** Full build; distribution stays private (.vsix, not published to Marketplace).
- **Issues:** —
- **Notes:** Built because Hayden's Extension Pack Manager, Quick Extension Manager, BILALMRN's Manage Extensions, and installed-extensions-manage-status all fell short. Wants tags (e.g. Code Language) and an "unassigned" filter view.
- **Location(s):** — (own source location not yet found; drop location once you spot the folder)
- **Reusable Parts:** —

### Shortcut Centralizer
Portable PySide6 GUI app — single source of truth for shortcut (.lnk) definitions, pushed out to every discovered copy on the system.

- **Status:** NEARING COMPLETION
- **Type:** GUI App
- **Tags:** #python, #pyside6
- **Remaining:** —
- **Issues:** —
- **Notes:** Manages target/args/working-dir/icon/hotkey for shortcuts stored centrally in `data/shortcuts.json`; likely the tool behind the large set of `.lnk` shortcuts under Config. Extensive test suite (11 test files across core + GUI).
- **Location(s):** DIR: [D:\Code Projects\Shortcut Centralizer\](file:///D:/Code%20Projects/Shortcut%20Centralizer/)
- **Reusable Parts:** —

### Cursor Theme Animations
"Cinder" — a custom obsidian/ember color theme + motion pack for Cursor's Agent panel only (editor theme untouched).

- **Status:** ONGOING
- **Type:** Styling / Theme
- **Tags:** #cursor, #css, #js
- **Remaining:** —
- **Issues:** —
- **Notes:** Covers checkboxes/radios/switches, sidebar rows, dropdowns/popovers, tooltips, diff blocks, focus rings, and hover/press motion — scoped to `.agent-panel` so the rest of the IDE stays untouched. Companion `cinder-agent-motion.js` handles new-message fade-in.
- **Location(s):** DIR: [D:\Code Projects\Cursor Theme Animations\](file:///D:/Code%20Projects/Cursor%20Theme%20Animations/)
- **Reusable Parts:** —

### C Drive Cleanup
Recurring C-drive space-optimization sweeps using WizTree scan exports and full admin PC access.

- **Status:** ONGOING
- **Type:** CLI / Script
- **Tags:** #powershell, #wiztree
- **Remaining:** —
- **Issues:** —
- **Notes:** WizTree scan exports (whole-drive + duplicates CSV, matching .db/.sql) kept under Config\SQLite-Databases. Includes a standalone script to trim/compact the Docker Desktop WSL2 vhdx used by MetaMCP, since it never shrinks on its own.
- **Location(s):** DIR: [D:\Code Projects\C Drive Cleanup\](file:///D:/Code%20Projects/C%20Drive%20Cleanup/) | DIR: [C:\Users\John Hudock\Config\SQLite-Databases\](file:///C:/Users/John%20Hudock/Config/SQLite-Databases/)
- **Reusable Parts:** —

### Game Page Enhancer
Two Millennium (Steam Client Homebrew) plugins: native-style store/community/discussion/guide buttons for non-Steam library entries, plus a separate quick-link button panel ("Custom Link Buttons").

- **Status:** IN PROGRESS
- **Type:** App Plugin
- **Tags:** #steam, #millennium, #lua
- **Remaining:** AppID-guessing's Lua `http` module dependency is unconfirmed; "Custom Link Buttons" panel built but not yet live-tested.
- **Issues:** —
- **Notes:** game-page-enhancer confirmed live and theme-compatible. notes-enhancer/"Custom Link Buttons" started as links injected into the Notes preview, but that made editing a note nearly impossible (the preview doubles as the click-to-edit target) — reverted and rebuilt as its own DOM-injected button panel with 3 built-in presets (SteamDB, PCGamingWiki, Nexus Mods). Internal plugin id (`dev.hudock.notesenhancer`) kept as-is to avoid orphaning installed data despite the user-facing rename. Scaffolded from SteamClientHomebrew/PluginTemplate.
- **Location(s):** DIR: [D:\Code Projects\Steam Plugins\Game Page Enhancer\](file:///D:/Code%20Projects/Steam%20Plugins/Game%20Page%20Enhancer/)
- **Reusable Parts:** The DOM-injection pattern used for both the button row and the link-button panel is reusable for any future Millennium plugin needing a native-style injected UI section.

### listnr
Modern, modular terminal-based music player written in Go.

- **Status:** IN PROGRESS
- **Type:** CLI / Script
- **Tags:** #go, #music, #tui
- **Remaining:** —
- **Issues:** —
- **Notes:** Supports MP3/WAV/FLAC/OGG/M4A, directory-based library browsing, vim-inspired keybinds, audio visualizer. Modular internal layout (audio/library/config/events/ui).
- **Location(s):** DIR: [D:\Code Projects\listnr\](file:///D:/Code%20Projects/listnr/)
- **Reusable Parts:** —

### Music - WACUP Plugin
Winamp/WACUP visualization plugin patch work (vis_pablo3.dll) plus a custom AquaSkin variant.

- **Status:** IN PROGRESS
- **Type:** App Plugin
- **Tags:** #winamp, #wacup
- **Remaining:** —
- **Issues:** —
- **Notes:** Findings from live testing and a patch handoff doc are both kept alongside the binary; backup of the original unmodified .dll and .ini are retained.
- **Location(s):** DIR: [D:\Code Projects\Music - WACUP Plugin\](file:///D:/Code%20Projects/Music%20-%20WACUP%20Plugin/)
- **Reusable Parts:** —

### Music Suite
Unified CLI consolidating all of John's music scripts (Bandcamp Tagger, ytas, stas) into one tool, with room to scale.

- **Status:** IN PROGRESS
- **Type:** CLI / Script
- **Tags:** #python, #powershell, #music
- **Remaining:** Fix `ytas`'s broken yt-dlp auto-updater (pip-installed yt-dlp needs `pip`-based updates, not the built-in updater); move the GitHub API key into an environment variable to stop hitting the unauthenticated rate limit (403) on version checks.
- **Issues:** yt-dlp update-checker errors (see Remaining) — downloads themselves still succeed.
- **Notes:** Consolidates bandcamp-tagger.py, ytas.ps1/.cmd, and stas.ps1 under one roof.
- **Location(s):** DIR: [D:\Code Projects\Music Suite\](file:///D:/Code%20Projects/Music%20Suite/)
- **Reusable Parts:** —

### Typora Tint
Comprehensive editable theme suite for Typora, with plugin support, a visual customizer editor, and inter-theme compatibility.

- **Status:** IN PROGRESS
- **Type:** Styling / Theme
- **Tags:** #typora, #css
- **Remaining:** See Issues.md and Task-Effects.md for the live punch list.
- **Issues:** —
- **Notes:** Four themes so far (bauhaus-brutalism, ember-void, industrial-neu, swiss-boldnewsprint), each with its own effects/palette folders, built against a customizer.html editor tool.
- **Location(s):** DIR: [D:\Code Projects\Typora Tint\](file:///D:/Code%20Projects/Typora%20Tint/)
- **Reusable Parts:** The customizer.html editor shell is reusable across future themes.

### One Commander - Themes
Gruvbox-family theme variants (Better Dark, Custom, Dark, Dark Hard, Vibrant) plus a blank theme template for the One Commander file manager.

- **Status:** COMPLETE
- **Type:** Styling / Theme
- **Tags:** #one-commander, #xaml
- **Remaining:** —
- **Issues:** —
- **Notes:** —
- **Location(s):** DIR: [D:\Code Projects\One Commander - Themes\](file:///D:/Code%20Projects/One%20Commander%20-%20Themes/)
- **Reusable Parts:** The Theme Template.xaml is a reusable starting point for any future One Commander theme.

### HLSL Converter
Python CLI + packaged .exe that converts GLSL shaders to HLSL for use in Windows Terminal.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Tags:** #python, #hlsl, #glsl
- **Remaining:** —
- **Issues:** —
- **Notes:** Has a documented spec, full pytest suite (function mapping, include resolution, template injection, type mapping), and a PyInstaller build. Feeds Windows Terminal Tweaker's shader-conversion feature.
- **Location(s):** DIR: [D:\Code Projects\HLSL Converter\](file:///D:/Code%20Projects/HLSL%20Converter/)
- **Reusable Parts:** —

### HLSL Normalizer
Python tool (packaged as a standalone .exe) that normalizes/cleans up HLSL shader scripts via regex parsing, for Windows Terminal use.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Tags:** #python, #hlsl
- **Remaining:** —
- **Issues:** —
- **Notes:** Companion to HLSL Converter; also bundled into Windows Terminal Tweaker.
- **Location(s):** DIR: [D:\Code Projects\HLSL Normalizer\](file:///D:/Code%20Projects/HLSL%20Normalizer/)
- **Reusable Parts:** —

### CustomTkinter Asset Library
Reference collection of CustomTkinter (CTk) widgets, theme packs, and GUI editors/builders for building Python Tkinter-based apps.

- **Status:** ONGOING
- **Type:** Library / Asset Collection
- **Tags:** #python, #customtkinter
- **Remaining:** —
- **Issues:** —
- **Notes:** Downloaded reference material (CTkThemesPack, CTkWindow, CTkEasyEditor, Custom Tkinter Builder, hPyT, VisualTK.Studio, etc.) rather than original work — kept as a library to draw on for future CTk-based GUI projects.
- **Location(s):** DIR: [D:\Code Projects\CustomTinkiter\](file:///D:/Code%20Projects/CustomTinkiter/)
- **Reusable Parts:** The whole point of this folder — themes/widgets pulled from here as needed.

### - PY Bat Compilers
Shared batch-file build scripts (dev/release builds, CTK variants, cache-clearing) reused across several of the Python GUI projects above.

- **Status:** ONGOING
- **Type:** Library / Asset Collection
- **Tags:** #pyinstaller, #batch
- **Remaining:** —
- **Issues:** —
- **Notes:** —
- **Location(s):** DIR: [D:\Code Projects\- PY Bat Compilers\](file:///D:/Code%20Projects/-%20PY%20Bat%20Compilers/)
- **Reusable Parts:** The whole folder is reusable build tooling for any new PyInstaller-based project.

### TUI Layout Designer
Textual-based visual pane-layout tool for terminal multiplexers (tmux, Zellij, WezTerm).

- **Status:** ONGOING
- **Type:** CLI / Script
- **Tags:** #python, #textual, #tui
- **Remaining:** —
- **Issues:** —
- **Notes:** Part of the modular "System AI" toolchain. Rewritten to fix absolute-positioning bugs and add a context-aware ADD/EDIT PANE sidebar, d-pad movement, grid snap, keyboard/button resize, and a pane strip navigator. Styled Gruvbox Dark Hard with a four-tier typography hierarchy.
- **Location(s):** DIR: [C:\Users\John Hudock\.System_AI\](file:///C:/Users/John%20Hudock/.System_AI/)
- **Reusable Parts:** —

### AnyZip to 7z Converter
Single-script converter that repacks zip archives as 7z.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Remaining:** —
- **Issues:** —
- **Notes:** —
- **Location(s):** DIR: [D:\Code Projects\AnyZip to 7z Converter\](file:///D:/Code%20Projects/AnyZip%20to%207z%20Converter/)
- **Reusable Parts:** —

### ASCII
Figlet/pyfiglet font cataloguing and sampling scripts.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Tags:** #python, #pyfiglet
- **Remaining:** —
- **Issues:** —
- **Notes:** Generates a full sample catalogue of every figlet font.
- **Location(s):** DIR: [D:\Code Projects\ASCII\](file:///D:/Code%20Projects/ASCII/)
- **Reusable Parts:** —

### Folder Flattener
Script that extracts and flattens nested folder structures into one level.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Tags:** #python
- **Remaining:** —
- **Issues:** —
- **Notes:** Also mirrored into the global Path Scripts CLI set.
- **Location(s):** DIR: [D:\Code Projects\Folder Flattener\](file:///D:/Code%20Projects/Folder%20Flattener/) | DIR: [C:\SystemEdits\Scripts\flatten.bat](file:///C:/SystemEdits/Scripts/flatten.bat) | DIR: [C:\SystemEdits\Scripts\utils\folder_flattener.py](file:///C:/SystemEdits/Scripts/utils/folder_flattener.py)
- **Reusable Parts:** —

### No Overwrite Mover
PowerShell script that moves files without overwriting existing files of the same name.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Tags:** #powershell
- **Remaining:** —
- **Issues:** —
- **Notes:** —
- **Location(s):** DIR: [D:\Code Projects\No Overwrite Mover\](file:///D:/Code%20Projects/No%20Overwrite%20Mover/)
- **Reusable Parts:** —

### Sea Power - Mod Renamer
Script for batch-renaming mods for the game Sea Power.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Tags:** #game-mod, #sea-power
- **Remaining:** —
- **Issues:** —
- **Notes:** —
- **Location(s):** DIR: [D:\Code Projects\Sea Power - Mod Renamer\](file:///D:/Code%20Projects/Sea%20Power%20-%20Mod%20Renamer/)
- **Reusable Parts:** —

### Start11 Start Menu Repair
Registry fix + layout export/repair tooling for a broken Start11 Start Menu setup.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Tags:** #start11, #registry
- **Remaining:** —
- **Issues:** —
- **Notes:** —
- **Location(s):** DIR: [D:\Code Projects\Start11 Start Menu Repair\](file:///D:/Code%20Projects/Start11%20Start%20Menu%20Repair/)
- **Reusable Parts:** —

### TXT to JSON
Simple converter script from plain text to JSON.

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Remaining:** —
- **Issues:** —
- **Notes:** —
- **Location(s):** DIR: [D:\Code Projects\TXT to JSON\](file:///D:/Code%20Projects/TXT%20to%20JSON/)
- **Reusable Parts:** —

### E Terminal Gift
A one-off packaged terminal-themed gift for a friend (Eowyn).

- **Status:** COMPLETE
- **Type:** CLI / Script
- **Remaining:** —
- **Issues:** —
- **Notes:** —
- **Location(s):** DIR: [D:\Code Projects\E Terminal Gift\](file:///D:/Code%20Projects/E%20Terminal%20Gift/)
- **Reusable Parts:** —

### Browser Launcher
Compiled AHK2 launcher (`Browser-Launcher.exe`) plus a PowerShell `WScript.Shell` COM script, eliminating the terminal-window flash when launching Chrome/Firefox/Thorium/Vivaldi profiles from `.bat` files.

- **Status:** COMPLETE
- **Type:** GUI App
- **Tags:** #ahk2, #powershell
- **Remaining:** —
- **Issues:** —
- **Notes:** The COM script bulk-rewrites `.lnk` shortcuts while preserving their icons.
- **Location(s):** DIR: [C:\Users\John Hudock\Config\Browser-Profiles\Browser Launcher\](file:///C:/Users/John%20Hudock/Config/Browser-Profiles/Browser%20Launcher/)
- **Reusable Parts:** The AHK2 launcher pattern is reusable anywhere a `.bat`-launched GUI app needs to hide its console flash.

### Print-Packages
PowerShell 7 script cataloguing hundreds of installed software/package entries across the registry, Scoop, Chocolatey, Winget, pip, npm, cargo, and PowerShell modules.

- **Status:** ONGOING
- **Type:** CLI / Script
- **Tags:** #powershell
- **Remaining:** Run periodically to regenerate; feeds the Packages index file.
- **Issues:** —
- **Notes:** Renamed from Software-Catalogue.ps1. Output switched from a dated .md to a single Packages.csv with a Meta row carrying the generation timestamp.
- **Location(s):** DIR: [C:\SystemEdits\Scripts\Print-Packages.ps1](file:///C:/SystemEdits/Scripts/Print-Packages.ps1)
- **Reusable Parts:** The animated Gruvbox gradient sweep bar it prints during each scan is a standalone, reusable loading-bar pattern for any PowerShell CLI.

### VS Code Theme Bundler
Python tool that bundles multiple installed theme extensions into one, to eliminate the bloat of hoarding many separate theme extensions.

- **Status:** IN PROGRESS
- **Type:** CLI / Script
- **Tags:** #python, #vscode
- **Remaining:** —
- **Issues:** —
- **Notes:** Working folders: Pre_Bundle_Sources, Staging_Area, Custom_Themes, Builds, Cache_Backups.
- **Location(s):** DIR: [C:\Users\John Hudock\.vscode\Theme_Bundler\](file:///C:/Users/John%20Hudock/.vscode/Theme_Bundler/)
- **Reusable Parts:** —

---

## Comprehensive / Broad-Scope Projects

For initiatives too broad or continuous to resolve into a single deliverable — exploratory research, workflow tuning, and system-wide configuration spanning many small, related tasks rather than one build.

### Template

Copy this block and paste it below your last entry to log a new initiative.

**\<Project Name\>**
<one-line description of the project>

- <open thread / discussion point>
- <open thread / discussion point>

---

### Improve / Discover AI Workflow
Track and improve day-to-day AI usage — new models, workflow integrations, and productivity mods across tools.

- Discuss new solutions, alternatives, mods, extensions, tools.
- Large emphasis on speeding up the workflow and increasing output.
- Currently running Gemini CLI — want to refine it further.
- Currently running VS Code — want to refine it further.
- Cursor launch/update/kill/patch script suite in place (`C:\SystemEdits\Scripts\Launch-Cursor.ps1`, `Update-Cursor.ps1`, `Kill-Cursor.ps1`, `Patch-Cursor.ps1`) — patches Cursor's marketplace to point at the real MS Marketplace; being generalized into the IDE Sync tool's launch-watcher (see Active Projects).
- Migrating Cursor's agent rules to a four-file `.cursor/rules/*.mdc` architecture (`000-always.mdc`, `010-mcp-protocol.mdc`, `020-css-selectors.mdc`, `030-architecture.mdc`), moving off the old `.cursorrules` format.
- MCP servers set up in Cursor: JCodeMunch, Codesight, Context7, WarpGrep, Deepcon — with ongoing token-efficiency tuning.

### Windows 10 Customization
Establish a safe way to back up current system settings, then overhaul the OS visually and functionally with tools like WindowFX, WinPalletter, etc.

- Find a solid revert solution — more comprehensive than a Windows Restore Point.
- Find the optimal application to overhaul Windows 10 fully, using as few apps as possible to avoid conflicts.
- WinPalletter has a large option set worth investigating.
- Revert-solution work already started: `C:\SystemEdits\Scripts\Export-PATH.ps1`, `Export-Registry.ps1`, `Export-Start11.ps1`.

### Windows Terminal / CMD / PowerShell
Build real command-line fluency and a more capable, better-documented terminal setup.

- Learn to use the terminal more effectively.
- Find a way to easily surface available commands.
- Customize Terminal (currently uses Windows Terminal with BTOP++ installed).
- Learn how package installs work — install locations, why certain paths are required, etc.

---

## Other Modifications & Practices

A running log of miscellaneous system tweaks and working practices that aren't scoped enough to be their own project — capture first, formalize later. Each line leads with a `[Category]` tag so the log stays filterable even as it grows.

### Template

- <[Category] short note — tweak, script, or practice worth remembering>
- [Environment] Uses the C:/SystemEdits folder to store system-wide scripts and core adjustments.
- [Automation] SystemEdits adjustments include: custom AHK keybinds (e.g. replacing the Windows PowerToys Text Extractor with Normcap); a custom .vbs script that replaces default Windows Notepad with the MS Store app "Notepads"; a custom .bat (run via Task Scheduler) that kills AHK when launching Steam games that flag it as a cheat, then re-enables it on close. [This list is not comprehensive]
- [Launch Scripts] Often uses custom .bat files to launch certain programs with command arguments.
