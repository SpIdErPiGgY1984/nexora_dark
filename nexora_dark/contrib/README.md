# Nexora Dark 1.0.3

Nexora Dark is a dark phpBB 3.3.x style by Spiderpiggy, based on prosilver and the Lucid Lime style by Melvin García.

## Requirements

- phpBB 3.3.19
- Parent style: prosilver

## Design

Nexora Dark combines compact sizing and typography with an obsidian, ultraviolet and amber colour system.

## Changes in 1.0.3

- Restyled all standard UCP and MCP pages to match the Nexora Dark palette.
- Added compact tabs and side navigation with subtle borders and clearer active states.
- Improved panel spacing and aligned section heading bars.
- Refined settings forms with slightly smaller text, lighter labels and consistent input styling.
- Updated subscriptions, bookmarks, drafts, attachments, notifications, groups and friends/foes lists.
- Styled private-message folders, message views and moderation tools consistently.
- Added horizontal scrolling for wide tables and stacked settings fields on small screens.
- Restyled advanced search, recent searches and topic/post search results with compact Nexora panels.
- Refined the posting editor, smiley panel, options, attachments, polls and message previews.
- Preserved existing Nexora customizations, phpBB template events, form controls and security tokens.
- Replaced fixed Dutch member-list headings with the standard phpBB profile language key.
- Removed the fixed Dutch FAQ introduction.
- Organized documentation and license information under `contrib/`.

See [CHANGELOG.md](CHANGELOG.md) for the version history.

## Changes in 1.0.2

- Corrected alternating post backgrounds, with a darker secondary shade that remains visually distinct.
- Added complete, subtle borders and rounded corners to statistics, online-user and forum-permission panels.
- Improved panel padding so text no longer touches the edges.
- Aligned heading bars with their panels.
- Added spacing before additional headings inserted by extensions to prevent overlap with preceding content.
- Adjusted panel padding and heading spacing for mobile screens.

## Compatibility

The style preserves phpBB template events, form tokens, standard WHOIS behaviour, ACP/UCP/MCP functionality and prosilver parent inheritance. It contains no external Spiderpiggy-only WHOIS overlay dependency.

Extensions using standard `.stat-block` containers inherit the panel styling.

## Nexora SVG status icons

The forum/topic status image set uses custom 30×30 SVG artwork designed for Nexora Dark. The phpBB read/unread, hot, mine, locked, sticky, announcement, moved and forum-link states remain unchanged functionally.

## Updating

Replace the existing style files, purge the phpBB cache and refresh your browser cache.

## Copyright and license

Copyright © 2026 Spiderpiggy. Based on Lucid Lime by Melvin García and prosilver/phpBB. Licensed under the GNU General Public License, version 2 (GPL-2.0-only). See `license.txt`.
