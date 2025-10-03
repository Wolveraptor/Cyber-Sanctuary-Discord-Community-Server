<!-- omit from toc -->
# Cyber Sanctuary | Levels
* `Cyber Sanctuary` Discord community server `MEE6` `Levels`.

<!-- omit from toc -->
## Cyber Sanctuary | About Levels
* This README.md serves as documentation and changelog for the `MEE6` plug-in `Levels` for the `Cyber Sanctuary` Discord community server.

![Cyber Sanctuary Discord Community Server Logo](https://forgejo.cybersanctuary.xyz/ssimon/Cyber-Sanctuary-Discord-Community-Server/raw/branch/main/Images/Server%20Icons/Cyber%20Sanctuary%20-%20Server%20Icons%20-%20512x512%20-%20Earth%20from%20Space%201%20-%20Cyber%20Sanctuary.png "Cyber Sanctuary Discord Community Server Logo")

<!-- omit from toc -->
### Cyber Sanctuary | Table of Contents
* [Cyber Sanctuary Discord Community Server - README.md](/ssimon/Homelab/src/branch/main/README.md)
* [Automations - README.md](/ssimon/Homelab/src/branch/main/Automations/README.md)
* [Bad Words - README.md](/ssimon/Homelab/src/branch/main/Bad%20Words/README.md)
* [Categories and Channels - README.md](/ssimon/Homelab/src/branch/main/Categories%20and%20Channels/README.md)
* [Community Roles - README.md](/ssimon/Homelab/src/branch/main/Community%20Roles/README.md)
* [Community Rules - README.md](/ssimon/Homelab/src/branch/main/Community%20Rules/README.md)
* [Economy - README.md](/ssimon/Homelab/src/branch/main/Economy/README.md)
* [Embedded Messages - README.md](/ssimon/Homelab/src/branch/main/Embedded%20Messages/README.md)
* [Help - README.md](/ssimon/Homelab/src/branch/main/Help/README.md)
* [Images](/ssimon/Homelab/src/branch/main/Images/)
* [Levels - README.md](/ssimon/Homelab/src/branch/main/Levels/README.md)
* [Moderator - README.md](/ssimon/Homelab/src/branch/main/Moderator/README.md)
* [Reaction Roles - README.md](/ssimon/Homelab/src/branch/main/Reaction%20Roles/README.md)
* [Welcome & Goodbye - README.md](/ssimon/Homelab/src/branch/main/Welcome%20&%20Goodbye/README.md)

<!-- omit from toc -->
### Cyber Sanctuary | Levels | Table of Contents
* [Cyber Sanctuary | Levels | 05/18/25 – 1:05 PM EST](#cyber-sanctuary--levels--051825--105-pm-est)
* [Cyber Sanctuary | Levels | 05/18/25 – 1:15 PM EST](#cyber-sanctuary--levels--051825--115-pm-est)

#### Cyber Sanctuary | Levels | 05/18/25 – 1:05 PM EST
* Leveling Up
    * Level up announcement: `Custom Channel`
    * Announcement Channel: `📊・mee6-levels`
    * Level Up Announcement Message:
        ```
        GG {player}, you just advanced to level {level}!
        ```
* Role rewards configuration
    * Role rewards type: `Stack previous rewards`
    * Role Rewards: `N/A`
    * Remove role weard after member loses XP: `Enabled`
* Default server rank card
    * Customized to use `Earth from Space - 1 - 3840x2160.png` as the background.
* XP Rate
    * Slider: `x1`
    * Do not give extra XP to MEE6 Pro subscribers: `Enabled`
* No-XP Roles
    * Allow all roles to gain XP, except: `Enabled` with no roles selected.
* No-XP Channels
    * Deny for all channels except: `Enabled`
        * Channels:
            * 💬・general-text
            * 🔊・General Voice
            * 💬・staff-text
            * 🔊・Staff Voice
            * 💬・ashes-of-creation
            * 🔊・Ashes of Creation
            * 💬・last-epoch
            * 🔊・Last Epoch
            * 💬・pantheon-rise-of-the-fallen
            * 🔊・Pantheon: Rise of the Fallen
            * 💬・satisfactory
            * 🔊・Satisfactory
* Commands
    * `/give-xp`: `Enabled`
    * `/levels`: `Enabled`
    * `/rank`: `Enabled`
    * `/remove-xp`: `Enabled`

#### Cyber Sanctuary | Levels | 05/18/25 – 1:15 PM EST
* Leveling Up
    * Level up announcement: `Custom Channel`
    * Announcement Channel: `📊・mee6-levels`
    * Level Up Announcement Message:
        ```
        Congratulations, {user.mention}! You advanced to level {level}!
        ```
* Role rewards configuration
    * Role rewards type: `Stack previous rewards`
    * Role Rewards: `N/A`
    * Remove role weard after member loses XP: `Enabled`
* Default server rank card
    * Customized to use `Earth from Space - 1 - 3840x2160.png` as the background.
* XP Rate
    * Slider: `x1`
    * Do not give extra XP to MEE6 Pro subscribers: `Enabled`
* No-XP Roles
    * Allow all roles to gain XP, except: `Enabled` with no roles selected.
* No-XP Channels
    * Deny for all channels except: `Enabled`
        * Channels:
            * 💬・general-text
            * 🔊・General Voice
            * 💬・staff-text
            * 🔊・Staff Voice
            * 💬・ashes-of-creation
            * 🔊・Ashes of Creation
            * 💬・last-epoch
            * 🔊・Last Epoch
            * 💬・pantheon-rise-of-the-fallen
            * 🔊・Pantheon: Rise of the Fallen
            * 💬・satisfactory
            * 🔊・Satisfactory
* Commands
    * `/give-xp` - `Give XP to a member`: `Enabled`
        * Permissions
            * Role permissions
                * Deny for all roles except: `Enabled`
                    * Roles: `Owner`, `Administrator`, and `Moderator`
            * Channel permissions
                * Deny for all channels except: `Enabled`
                    * Channels:
                        * `🤖・general-bot-spam` in `╭・👋  General`
                        * `🤖・staff-bot-spam` in `╭・💼  Staff`
            * Additional settings
                * Cooldown: `None`
                * Send private response: `Disabled`
                * Deleted command usage: `Enabled`
                * Do not reply to command: `Disabled`
    * `/levels` - `Get a link to the leaderboard`: `Enabled`
        * Permissions
            * Role permissions
                * Allow for all roles except: `Enabled`
            * Channel permissions
                * Deny for all channels except: `Enabled`
                    * Channels:
                        * `🤖・general-bot-spam` in `╭・👋  General`
                        * `🤖・staff-bot-spam` in `╭・💼  Staff`
            * Additional settings
                * Cooldown: `None`
                * Send private response: `Disabled`
                * Deleted command usage: `Enabled`
                * Do not reply to command: `Disabled`
    * `/rank`: - `Get your rank or another member's rank`: `Enabled`
        * Permissions
            * Role permissions
                * Allow for all roles except: `Enabled`
            * Channel permissions
                * Deny for all channels except: `Enabled`
                    * Channels:
                        * `🤖・general-bot-spam` in `╭・👋  General`
                        * `🤖・staff-bot-spam` in `╭・💼  Staff`
            * Additional settings
                * Cooldown: `None`
                * Send private response: `Disabled`
                * Deleted command usage: `Enabled`
                * Do not reply to command: `Disabled`
    * `/remove-xp` - `Remove XP from a member`: `Enabled`
        * Permissions
            * Role permissions
                * Allow for all roles except: `Enabled`
            * Channel permissions
                * Deny for all channels except: `Enabled`
                    * Channels:
                        * `🤖・general-bot-spam` in `╭・👋  General`
                        * `🤖・staff-bot-spam` in `╭・💼  Staff`
            * Additional settings
                * Cooldown: `None`
                * Send private response: `Disabled`
                * Deleted command usage: `Enabled`
                * Do not reply to command: `Disabled`