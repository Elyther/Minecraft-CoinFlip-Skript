# 🪙 CoinFlip Skript

A fully GUI-based Minecraft CoinFlip system created with Skript.

Challenge other players or play against the Bot, place your bet, watch the spinning animation, and let the CoinFlip decide the winner.

## ✨ Features

- 🪙 PvP CoinFlip
- 🤖 Bot CoinFlip
- 💰 Custom bet amounts
- 📊 Active games list
- 🎰 Animated CoinFlip system
- 🏆 Automatic winner selection
- 💵 Economy integration
- 🔢 Supports K, M, B and T amounts
- 🔊 Custom sounds and effects
- ❌ Cancel active games
- 🖥️ GUI-based interface
- ⚡ Lightweight and easy to customize

## 🎮 Commands

| Command | Description |
|---------|-------------|
| `/coinflip` | Opens the CoinFlip menu |
| `/cf` | Alias for `/coinflip` |
| `/cf menu` | Opens the CoinFlip menu |
| `/cf bot` | Play CoinFlip against the Bot |
| `/cf pvpcreate` | Create a PvP CoinFlip game |
| `/cf list` | View active PvP games |
| `/cf cancel` | Cancel your active game |

## 💰 Bet Format

The system supports normal numbers and shortened formats:

- `1000`
- `1.5k`
- `2m`
- `5b`
- `1t`

### Examples

```text
1000 = $1,000
1.5k = $1,500
2m = $2,000,000
5b = $5,000,000,000
1t = $1,000,000,000,000

🎯 Minimum Bet

The default minimum bet is:
100$
You can change it in the options:
min-bet: 100

🪙 PvP Mode

Players can create their own CoinFlip game.
	1.	Use /cf pvpcreate
	2.	Enter the bet amount in chat.
	3.	Your bet is taken from your balance.
	4.	Other players can use /cf list.
	5.	Another player joins your game.
	6.	The CoinFlip animation starts.
	7.	One player wins the total pot.

🤖 Bot Mode

Players can also play against the Bot.
Use:
/cf bot

Then enter the amount you want to bet.

The Bot has a configurable chance of winning.

🎰 CoinFlip Animation

The script includes a custom spinning GUI animation with:
	•	Player skulls
	•	Bot skull
	•	Colored glass panes
	•	Winner indicators
	•	Click sounds
	•	Victory sounds
	•	Loss sounds
	•	Animated spinning sequence

💵 Economy

The script uses the player’s balance to handle bets and rewards.

When a player wins, the total pot is added to their balance.

Make sure your server has a compatible economy system.

📋 Installation

1. Install Skript

Install the Skript plugin on your Minecraft server.

2. Create the Script
Go to:
plugins/Skript/scripts/
Create a file called:
coinflip.sk

3. Add the Code

Paste the CoinFlip Skript into:
coinflip.sk

4. Reload the Script

Run:
/sk reload coinflip

⚙️ Configuration

At the top of the script you can customize:
options:
    prefix: &8[&6CoinFlip&8] &7
    min-bet: 100
    menu-list: &8&lActive Games
    menu-spin: &8&lCoinFlip Spinning...

You can change the prefix, minimum bet and GUI names to match your server.

📌 Notes

The script is designed to work with a Minecraft economy system and uses GUI menus for the CoinFlip experience.

Make sure your economy setup is working correctly before using the script on a live server.

🛠️ Customization

The Skript can be modified to change:
	•	Minimum bet
	•	Messages
	•	GUI titles
	•	Animation speed
	•	Sounds
	•	Bot win chance
	•	Visual effects
	•	Bet formatting

👤 Created By

Elyther

Minecraft Skript Developer