# Discord Bot Skeleton - By TeraBytes
This is a skeleton code with all the common code I (like to) use for Discord Bots. It includes
* Command/Event Handler
* Extended Client structure (for Intellisense and more organization)
* Necessary, ready-to-fill config files
* A colors.json file with a **lot** of color HEX values
* `message` and `ready` events
* `ping`, `help` and `eval` commands

## Installation
I will be sharing compressed artifacts of new releases every now and then, make sure to get those by going [https://github.com/TeraBaito/discord-bot-skeleton/releases]

1. Unzip the file (you can safely remove `README.md` and `LICENSE.md`)
1. Run `npm init` (`npm init -y` to skip prompts)
1. Run `npm i ascii-table beautify chalk common-tags discord.js dotenv`
1. Fill in the `DISCORD_TOKEN=` parameter on `.env` file
1. Go to config.json, and fill in the properties accordingly

Then it's all yours!

Made by TeraBytes, 2021, MIT License