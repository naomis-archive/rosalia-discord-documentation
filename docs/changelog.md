# Changelog

Here you can see the changes made across each version of Rosalia.

[Version 1](#version-1) | [Beta](#beta)

## Version 1

### 1.2.1

- Patched an error with a missing button style in the `/rosalia about` command.

### 1.2.0

- Added link buttons to a few of the embeds.
- Added a step to sort the subcommands alphabetically.
- Added the `/rosalia contact` and `/rosalia updates` commands.

### 1.1.1

- Added developer avatar to donation CTA in embed footer for clearer branding.

### 1.1.0

- Added logging for guild join and leave events
- Added logging for new character creation
- Added total character count to the `/rosalia about` command.

### 1.0.1

- Added donation CTA to the embeds.

### 1.0.0

- Public release!
- Added `/rosalia beta` command.
- Added server with uptime monitoring endpoint.

## Beta

### 0.0.1-rc.4

- Added chance for monster to "wait" (do nothing) in battle.
- Added multiple descriptions for each data entry, to allow for variety.
- Expanded available content significantly.
- Added `/rosalia art` command.

### 0.0.1-rc.3

- Fixed error in database query for `/adventure rest` and `/adventure map`
- Added `/adventure search` to find new exploration areas
- Removed stat decrease on battle defeat
- Added more seed data
- Implemented the market system
  - `/market visit` to see what a specific shoppe offers
  - `/market purchase` to buy an item

### 0.0.1-rc.2

- Added author information to embeds
- Fixed issue where data wasn't saved properly on certain adventure results

### 0.0.1-rc.1

- Fixed issue in character database schema
- Fixed bug where inventory items were assigned to wrong slot
- Fixed bug where gold was not assigned on battle victory

### 0.0.1-rc.0

- Initial Release!
- Added `/rosalia` commands
  - `ping`
  - `about`
  - `profile`
  - `donate`
  - `help`
- Added `/character` commands
  - `create`
  - `view`
  - `update`
  - `equipment`
- Added initial seed data for:
  - Adventures
  - Monsters
  - Items
- Added `/inventory` commands
  - `details`
  - `sell`
  - `use`
- Added `/adventure` commands
  - `map`
  - `explore`
  - `dungeon`
  - `rest`
- Wrote battle system prototype
