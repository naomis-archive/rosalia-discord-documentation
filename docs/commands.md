# Commands

This page shows a list of all available commands.

## `/adventure` Commands

The `/adventure` commands allow you to explore an area, plunder a dungeon, or see what areas you've unlocked.

| Command              | Parameters     | Description                                                                                                                         |
| -------------------- | -------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| `/adventure dungeon` | `area: string` | Visits the dungeon named `area`, provided you have unlocked it. Takes 4 hours.                                                      |
| `/adventure explore` | `area: string` | Visits the exploration zone named `area`, provided you have unlocked it. Takes 1 hour.                                              |
| `/adventure map`     | `null`         | Shows the list of exploration zones and dungeons you have unlocked.                                                                 |
| `/adventure rest`    | `room: Option` | Rest for 8 hours, recovering some mana and health. The recovery rate is determined by the room you choose, some of which will cost. |

## `/character` Commands

These commands handle your character sheet.

| Command                | Parameters                                                                  | Description                                      |
| ---------------------- | --------------------------------------------------------------------------- | ------------------------------------------------ |
| `/character create`    | `name: string`, `race: string`, `gender: string`, `description: string`     | Creates your character.                          |
| `/character equipment` | `null`                                                                      | Shows your character's currently equipped items. |
| `/character update`    | `name?: string`, `race?: string`, `gender?: string`, `description?: string` | Update your character's descriptive text.        |
| `/character view`      | `null`                                                                      | View your character's stats and description.     |

## `/inventory` Commands

These commands help manage your inventory.

| Command              | Parameters     | Description                                                                      |
| -------------------- | -------------- | -------------------------------------------------------------------------------- |
| `/inventory details` | `item: string` | Returns information about the provided `item`.                                   |
| `/inventory sell`    | `item: string` | Sells the named `item`, removing it from your inventory in exchange for gold.    |
| `/inventory use`     | `item: string` | Uses the named `item`, removing it from your inventory and applying its effects. |
| `/inventory view`    | `null`         | Shows your inventory.                                                            |

## `/market` Commands

These commands allow you to view and purchase items in the market.

| Command            | Parameters         | Description                                                          |
| ------------------ | ------------------ | -------------------------------------------------------------------- |
| `/market purchase` | `item: string`     | Purchase the named `item` from the market.                           |
| `/market visit`    | `location: Choice` | Visit the named `location` in the market. Shows the items available. |

## `/rosalia` Commands

| Commands           | Paramaters | Description                                                                 |
| ------------------ | ---------- | --------------------------------------------------------------------------- |
| `/rosalia about`   | `null`     | Provides information about the bot.                                         |
| /`rosalia art`     | `null`     | Provides a random art depicting Rosalia.                                    |
| `/rosalia beta`    | `null`     | Provides a thank you for the wonderful beta testers.                        |
| `/rosalia contact` | `null`     | Provides links to contact the development team.                             |
| `/rosalia donate`  | `null`     | Provides links to the methods to financially support the bot's development. |
| `/rosalia help`    | `null`     | Provides instructions for using the bot.                                    |
| `/rosalia ping`    | `null`     | Provides the bot's response time.                                           |
| `/rosalia profile` | `null`     | Provides a link to Rosalia's profile.                                       |
| `/rosalia updates` | `null`     | Provides an embed with the changelog for the latest release.                |
