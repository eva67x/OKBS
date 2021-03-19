# Open Kaboom Bot Standard
This standard covers bots running on:
* play.kaboom.pw
* raccoon.pw
* "Clones" of play.kaboom.pw
using:
* JavaScript
* TypeScript
* Java

## Section I: Minecraft Version
Bots should *only* be on one of the following Minecraft versions.
* 1.16.5
* 1.16.4

## Section II: Malicious Intent

### Section II, Part 1: Server
Bots CAN NOT be used to do any of the following.
* Lag Servers
* Crash Servers
* Otherwise Harm Servers
* Send out DoS or DDoS attacks to the servers and their hosts.

### Section II, Part 2: Playerbase
Bots CAN NOT be used to do any of the following:
* Discourage the growth of the community by:
  * Autolocking players unless the player has repeatedly shown malicious intent.
  * Autocrashing players.
  * Crashing players unless the player has repeatedly shown malicious intent.
  * No-OPing players unless the player has repeatedly shown malicious intent.
* Discourage bot developers by:
  * Autolocking or autocrashing any bots that have not violated any guidelines in section II.
  * Auto-NoOPing/Auto-DeOPing/Auto-Muting any bots that have not violated any guidelines in section II.

### Section II, Part 3: Real-world malicious intent
Bots CAN NOT be used to:
* Dox any person.
* DDoS/DoS any person.
* Infect any person with a computer virus.
* Leak any person's passwords, emails, or social media accounts/handles without consent.

## Section III: Development

### Section III, Part 1: Directory Structure
IF the bot is using java these shall be packages named `reverse-domain.bot-name.package`
Bots MUST include the following directories as long as the bot includes COMMANDS.
* commands
OR
* cmds
Bots MUST include the following directories as long as the bot includes NON-COMMAND-MODULES:
* modules
OR
* mods
Bots MUST include the following directories as long as it has PLUGIN SUPPORT:
* plugins
OR
* plugs
Bots MUST include the following directories as long as the bot includes DISCORD COMMANDS.
* discordcommands
OR
* dccmds

### Section III, Part 2: Main File
The MAIN file of the bot MUST be titled either `index.js`, `bot.js`, `index.ts`, `bot.ts`, `Main.java`, or `Bot.java`

### Section III, Part 3: Code Conventions
Bots must use the
```
    function() {

    }

    function() {

    }
```
OR
```
    function() 
    {

    }

    function() 
    {

    }
```

style.

### Section III, Part 4: Security
In the interest of security the following things are NOT allowed:
* Using eval() with arguments DIRECTLY supplied by users.
* Making web connections using user arguments.
* Allowing code to be run by the public playerbase on the hosts hardware/software via the JavaScript eval() function or other functions in different coding languages.

Making web connections using user arguments.

### Section III, Part 5: Integrations
Bots may integrate with the following services provided their conditions are met.

**Discord**
* The bot can only be used for a chatbridge. NOT to run any commands OR Direct Message users.
* The bot can have a SEPARATE set of commands for Discord.



===

Standard originally made by TFTWPhoenix.
Contributors:
* saxnbt
