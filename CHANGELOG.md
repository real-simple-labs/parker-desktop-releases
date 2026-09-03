# Parker Desktop changelog

What changed in each version, newest first.

## 0.7.2 - 2026-09-02

- A folder note's full line shows in the app's own tooltip, not a browser title
- A summary rewrite shows that it is happening, and how it went
- The wand's words are the folder's at once, and the box steps aside while it looks

## 0.7.1 - 2026-09-02

- Files that are nobody's reading stay out of every listing
- The chat's files column can be dragged again
- The agent menu hangs where the caret is, and its check is drawn as one

## 0.7.0 - 2026-09-02

- Latest edits: the chip names the brain
- An HTML file shows as the page it is, with Source a click away
- The slash menu works for Codex too
- A document shows the pictures and videos it points at
- A wand beside the folder description box suggests the line
- Search inside files, not only their names
- The Recent changes toggle wears the tab bar's sidebar glyph, mirrored for the right
- The Work on this caret opens a menu of the app's own, not a native one
- Boot paints from last launch's org and brand list
- A folder's name is never cut; its note gives way and carries the whole line
- A missing agent CLI gets the install guide, not a bare npm line
- Chat: a message typed mid-answer waits under the log, and joins it when it is sent
- The Overview's Recent changes folds to a strip at the right
- Latest edits says "Not summarized yet." and nothing about hours
- The sidebar's panel caret points down while open and right while folded
- Empty places say what belongs in them
- No describe pencil on or inside Parker's system folder
- Chat: the files a session touched, with a preview beside the log
- History shows an HTML file as the page, with its changes marked
- Orgs & Brands is a folder too, listing every org and how much of it syncs
- Chat: the untrusted-folder warning is a note with a Trust button, not an error
- The Chats panel is there from the first paint, and files get a quick chat icon
- Chat composer: one card with the footer row inside, like Claude's
- Brand tabs read the disk from the first paint: the clone map is remembered
- The org tab is the org folder, browsed like any other; every folder takes a description
- Home feed: the newest commits wait in one Latest edits block until summarized
- Chat: slash menu for skills, and a sign-in button when Claude is signed out
- An empty root keeps the Set Up Parker Brain button
- The debug console shows causes, not only effects
- Icons view: folders first, then files
- The org tab shows the organization's shared space

## 0.6.5 - 2026-09-02

- Chat footer: model left, status and a grey square stop at right; a faint spinner while summaries are asked for
- Managed remotes are the server's to choose: the clone gate covers any https remote, and an existing clone follows a changed cloneUrl

## 0.6.4 - 2026-09-02

- Set up Parker Brain provisions the repo from the app
- Six fixes from a code and UI review: sync state, chat processes, offline boot, layout

## 0.6.3 - 2026-09-01

- Chat pane: the model in the footer, the last brand's brain, and a bell for approvals

## 0.6.2 - 2026-09-01

- Chat pane: tool calls in plain words, a message queue, and the brain as the CLI's folder
- The chat log stops totalling each answer in seconds and dollars

## 0.6.1 - 2026-09-01

- An empty Chats section hides itself, and History is renamed to Chats
- A machine without git says so instead of 'git failed'
- About gains a "How does it work?" button beside the icon's secret
- Intro tour: the machine noun follows the platform, and Work on this reads as a button

## 0.6.0 - 2026-09-01

- A brain left at its old address stops syncing beside its twin
- MCP detection reads every shape an install takes, and the Claude app's own config
- overview: let the Recent Changes sidebar breathe on wide screens
- Only the user's own Parker publishes the workspace pointer
- The workspace root has a fixed address other tools can read

## 0.5.7 - 2026-08-31

- Native dialogs center again, and the template dialog's foot right-aligns

## 0.5.6 - 2026-08-28

- Windows installer builds itself when a release is published

## 0.5.5 - 2026-08-28

- ⌘F reaches a search from anywhere, and the Overview has one to reach

## 0.5.4 - 2026-08-28

- Stop electron-builder publishing itself in CI: --publish never lives in the dist scripts
- An agent session runs in a tab again

## 0.5.3 - 2026-08-28

- parker://open: refuse drive-qualified paths, and decide what Share copies once

## 0.5.2 - 2026-08-28

- Small fixes and improvements.

## 0.5.1 - 2026-08-28

- Share button copies a parker://open link, and that link opens the file or folder
- Every rule reads the theme through a token, and a test keeps it that way
- The blank tab can open the Parker web app in itself

## 0.5.0 - 2026-08-28

- Work-on-this: the brands' own marks, and the brain's name at a brain's root
- The chat handoff button becomes "Work on this", wearing its agent's mark
- Windows support: platform copy, tray and menu behavior, CLI spawning, NSIS build

## 0.4.0 - 2026-08-27

- pnpm release <version> bumps package.json and pushes the bump to main
- the remaining modals become native <dialog>s + showModal()
- No em-dashes in user-facing text: replace with ' - ', add the hard rule to CLAUDE.md and AGENTS.md
- Feed: Markdown summaries, one tree per person per hour, Cmd+double-click regenerate
- Release flow: package.json carries the real version
- Onboarding copy: no need for GitHub - the brain tracks everything for you
- feed blocks + template dialog: hover, chevron direction, self-diagnosing load errors
- feed blocks: real icons - Lucide gear, the panels' caret on the right
- Feed blocks and template dialog: accessibility fixes from #188's review
- A settings gear on feed posts: edit the brain's summary template
- Sign in through the default browser (parker:// hand-off)
- Feed rework: hourly Brain summaries as expandable blocks, and an Overview activity sidebar
- A welcome card opens the intro tour, and the cards grow a little
- Faint version stamp on the boot splash
- feat: search box on the Selective sync tree
- feat: default to the Overview, darken the chat CTA

## 0.3.3 - 2026-08-25

- fix: prevent read-only path aliases from writing
- refactor: let React own browser guests
- fix: dismiss menus for closed windows
- refactor: render app regions directly
- refactor: let React own the app frame
- fix: contain native dialog failures
- fix: render drag hover from React state
- refactor: make the React root static
- refactor: let React own native view hosts
- refactor: let React own pane hosts
- fix: dismiss chat menu for closed windows
- fix: ignore late native menu responses
- fix: contain logout lifecycle failures
- fix: contain dock reveal lifecycle failures
- test: wait for remounted view controls
- fix: contain background update check failures
- refactor: derive signed-out layout from React
- fix: ignore stale embedded login failures
- fix: confine privileged renderer navigation
- refactor: render empty pane with React
- refactor: handle file search shortcut in React
- refactor: remove legacy file drag wiring
- refactor: remove DOM-driven modal dismissal
- refactor: render About window with React
- refactor: move sidebar lifecycle into React
- refactor: remove hidden selection controls
- refactor: render browser toolbar with React
- refactor: render the tab bar with React
- refactor: render tooltips with React
- refactor: render name prompts with React

## 0.3.0 - 2026-08-25

- Re-mint the git device token when the server re-maps a repo dir
- refactor: render debug console with React
- refactor: render hub previews with React
- refactor: render chat with React
- refactor: render files with React
- fix: mount React before restoring tabs
- perf: start the Home digest fetch at boot, under the splash
- fix: omit unreported ad values
- refactor: render native ads with React
- fix: margin on home
- Home digest: brand names to the server, markdown card, as-of stamp, dismiss X
- refactor: render native shells with React
- fix: serialize read-only sync changes
- fix: move workspaces atomically
- fix: reject incomplete git credentials
- fix: keep failed conflict handoffs open
- fix: contain update restart failures
- fix: await Codex handoff launches
- fix: contain file operation failures
- fix: keep sync status current
- fix: contain chat picker failures
- fix: contain native ad load failures
- fix: serialize MCP installs per agent
- fix: serialize MCP settings work
- fix: contain background clone failures
- fix: contain README load failures
- pnpm start points at the dev web app
- fix: keep grid previews current
- fix: settle Electron shell launches
- fix: contain stale settings requests

## 0.2.6 - 2026-08-25

- Small fixes and improvements.

## 0.2.5 - 2026-08-25

- chore: copy
- fix: ignore superseded history loads
- Review follow-up: the org view stops overclaiming
- Settings: the claude.ai connector becomes Claude's first door
- fix: contain Electron navigation failures
- fix: replay update state after renderer startup
- The Home feed opens with a digest of recent work

## 0.2.4 - 2026-08-25

- The org view: an org's name opens a tab, and a chat that spans it
- fix: stop retired sync engines
- fix: the server's brain status wins over an empty clone
- Signposts for agents at the workspace root and orgs/
- perf: render refreshed files from one read
- fix: hold clones that have no git token yet
- fix: suppress stale conflict dialogs
- fix: clear stale account access state
- fix: let React own the Brain Info dialog

## 0.2.3 - 2026-08-24

- The brain info dialog reads the brand's own roster
- fix: keep app menu commands on the main window
- docs: the tab embeds are gone from the imperative-leaves list
- fix: clear native view state on teardown
- fix: keep stale activity out of Home
- Drop the tab-embed subsystem the native wizard orphaned
- The setup wizard is Parker Desktop's own screen

## 0.2.2 - 2026-08-22

- fix: ignore stale browser reloads
- fix: route deep links to the main window
- fix: route setup links outside Electron
- fix: prevent orphaned setup embeds after tab close
- fix: confine repo file operations to the clone
- perf: move local tree scans off the main thread
- fix: clean up grid resizing on unmount
- fix: protect unsaved edits when closing tabs
- fix: open Markdown links outside Parker
- Read-only mode, per brand or per org, from Selective sync
- The download link stops moving: a fixed DMG name
- The brain info dialog lists who holds the brand, not the org

## 0.2.1 - 2026-08-21

- chore: copy
- Double-clicking the About icon replays the intro tour
- A first launch gets a four-card tour
- The chat opener speaks in relative paths

## 0.2.0 - 2026-08-20

- A short README shows whole, and READMEs follow the disk
- FOLDERS goes home, and history rows stop jumping
- CLI detection asks the user's shell, then looks where installers put things
- Fix TypeScript project binding and eliminate 104 of 107 any values
- The app points at production
- The open file follows the disk, and the Chat button holds its line
- The dock icon actually leaves with the window
- The universal merge learns to accept node-pty's prebuilds
- The mac build goes universal again
- MCP detection reads every Claude Code scope, and says which Claude

## 0.1.25 - 2026-08-20

- Every Chat button gets the caret

## 0.1.24 - 2026-08-20

- The DMG comes back to the release
- Parker's MCP offers itself to the agents, once

## 0.1.22 - 2026-08-20

- Chat buttons say where they go

## 0.1.21 - 2026-08-20

- parker:// grows codex and chat, and the Chat button owns the choice
- Repaints stop refetching badges

## 0.1.20 - 2026-08-19

- The comments stop saying island
- The word island leaves the tree
- The last island falls, and island.ts with it
- The browser tab becomes a component
- Per-tab surfaces join the one tree, starting with Home
- The app-level islands become one React tree
- refreshBadges becomes three named jobs
- The Home tab moves out, and CLAUDE.md tells the truth again
- The file browser becomes a module
- Three shell subsystems out of the entry file
- The account model leaves the entry file
- The hover preview owns its timing
- Nothing unused survives the compiler now
- The toolbar gets an island, like every other view
- One git process per repo at a time
- Embedded pages hide under React dialogs again
- renderer.tsx drops below 2,000 lines
- Four more out, and a per-tab bug the extractions had introduced
- The native screens move out
- The smoke-test debug handle moves out
- The brain-info dialog and the setup wizard move out
- Three more subsystems out of the file browser
- The sidebar becomes one component instead of three islands
- Home becomes React, and its labels become a module
- The clone pass moves out, and owns where brains live
- The file browser's toolbar becomes React
- All four file-browser views become one React island
- Three of the file browser's four views become React
- Every icon in one place, and two more pieces out of the file browser
- renderer.ts becomes renderer.tsx, and the boot screens become React
- Ask the server what this account can see, without a restart
- Stop the smoke suites putting Parker on screen
- Move the tab bar to React, and the tab decisions out of the renderer
- Move the switched-off panes out, and tidy the island helper
- Move the history fetching out of the file browser too
- Fix the four smoke suites the React migration left broken
- Move the history screens and the sync countdown to React
- Move both dialogs to React, and give the components a structure
- Split the thread history sidebar into modules and components
- The team list becomes a table, and stops showing admins to everyone
- Stop the smoke suites flaking on an Electron segfault, and keep their windows off screen
- Move the sidebar navigation and the sync tree to React
- Start the React migration: islands, and the first two components
- Split three shell subsystems out of the renderer
- The member list asks the endpoint that knows people's names
- Split the ad view and the diff renderer out of the renderer
- An old address is a name, not an identity
- Brand brains live under their organization, and move themselves there
- Split the chat pane out of the renderer, and unit-test it
- Split nine modules out of the renderer, and unit-test the plain ones
- Bundle the renderer, and start splitting it into modules
- Selective sync gets Select all and Unselect all
- Convert the project to pnpm and TypeScript

## 0.1.17 - 2026-08-19

- File manager, the icon view's return, and the brain info dialog
- Local releases read their credentials from .env
- Review fixes: overview rows join the unsynced pass
- Overview view: the README leads, contents follow in two columns
- Release script: survive macOS's bash 3.2
- Releases move off GitHub Actions and onto a Mac
- CI runs again, plus the review findings from #5–#9
- Preview view: one plain list, folders open on click

## 0.1.16 - 2026-08-18

- The third view becomes Preview: collapsed hub cards + the preview pane
- Logging that answers questions: engine lifecycle, updater phases, selection mapping

## 0.1.15 - 2026-08-18

- Icons view: glyphs drawn for the size, and a draggable split

## 0.1.14 - 2026-08-18

- Selective sync replaces favorites; hub default; revert to any version

## 0.1.13 - 2026-08-18

- Tabs get a right-click menu: Close Tab and Close Other Tabs
- Experimental hub view: Notion-style clusters behind a switch

## 0.1.12 - 2026-08-18

- Brain history, rendered markdown diffs, codex handoff, sidebar polish

## 0.1.11 - 2026-08-18

- Centered reading, gray no-brain dots, and a sync countdown

## 0.1.10 - 2026-08-18

- Picking a brand slides the panel away; favorites filter the feed

## 0.1.9 - 2026-08-18

- Back/forward, sidebar scale tools, and the parker-system submodule

## 0.1.8 - 2026-08-18

- Home feed cards offer the whole-brain chat handoff

## 0.1.7 - 2026-08-17

- A remote that answers 404 is an error, not a merge conflict

## 0.1.6 - 2026-08-17

- About shows the signed-in email again (the endpoint exists now)

## 0.1.5 - 2026-08-17

- Give the editor's name its own column; keep the conflict helper reachable
- Enable notarization for signed builds

## 0.1.4 - 2026-08-17

- Show real download progress for updates instead of a fire-and-forget dialog
- History diffs use the name the file had at each commit

## 0.1.3 - 2026-08-17

- Search files and folders from the sidebar; fix feed-opened tab titles

## 0.1.2 - 2026-08-17

- In-page overlays hide the embedded page instead of losing to it
- Auto-update reads a public releases mirror
- Tell renamed, moved, and moved+renamed apart in history and the feed
- The Home feed can scroll
- Home feed: day headings, org · brand chips, file trees that open history
- Closing the last tab returns to Home instead of closing the window
- Smoke suites live in the repo now, with a runner and CI
- Home: a time-sorted feed of changes across every brain
- CI: unset empty signing env vars before the build

## 0.1.1 - 2026-08-15

- Small fixes and improvements.

## 0.1.0 - 2026-08-15

- The first release.
