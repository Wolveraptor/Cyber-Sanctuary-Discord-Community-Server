<!-- omit from toc -->
# Cyber Sanctuary | Automations
* `Cyber Sanctuary` Discord community server `MEE6` `Automations`.

<!-- omit from toc -->
## Cyber Sanctuary | About Automations
* This README.md serves as documentation and changelog for the `MEE6` plug-in `Automations` for the `Cyber Sanctuary` Discord community server.

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
### Cyber Sanctuary | Automations | Table of Contents
* [Cyber Sanctuary | Automations | Loses a Role - Agreed to Rules - 05/18/25 – 12:30 PM EST](#cyber-sanctuary--automations--loses-a-role---agreed-to-rules---051825--1230-pm-est)
* [Cyber Sanctuary | Automations | Loses a Role - Agreed to Rules - 05/24/25 – 9:58 PM EST](#cyber-sanctuary--automations--loses-a-role---agreed-to-rules---052425--958-pm-est)

#### Cyber Sanctuary | Automations | Loses a Role - Agreed to Rules - 05/18/25 – 12:30 PM EST
* When Someone:
    * Trigger
        * Loses a role
* Conditions:
    * If:
        * The user lost one of these roles
            * Roles: `Agreed to Rules`
* Do This:
    * Take these roles from the user
        * Roles: `Ashes of Creation`, `Last Epoch`, `Pantheon: Rise of the Fallen`, `Satisfactory`, `MacOS`, `Ubuntu`, and `Windows`.
    * Send a message
        * Channel: `📖・mee6-automations-loses-a-role-logs`
        * Message:
            ```
            The user {user.mention} with Username *{user.name}* and User ID *{user.id}* has either removed the <@&1191876960771641364> role themselves or had it removed from them by an <@&1191873182471303168>.

            As a result of the <@&1191876960771641364> role being removed, they have had all other assigned roles removed as well.

            If they wish to re-gain access, they must read the server rules which can be found in the https://discord.com/channels/1190406648259432448/1195548408182743161 channel [here](https://discord.com/channels/1190406648259432448/1195548408182743161/1195548746574991400) and click the `✅ I agree` button to unlock the https://discord.com/channels/1190406648259432448/1191837535849168957 channel to assign themselves roles.
            ```

#### Cyber Sanctuary | Automations | Loses a Role - Agreed to Rules - 05/24/25 – 9:58 PM EST
* When Someone:
    * Trigger
        * Loses a role
* Conditions:
    * If:
        * The user has one of these roles
            * Roles: `Ashes of Creation`, `Last Epoch`, `Pantheon: Rise of the Fallen`, `Satisfactory`, `MacOS`, `Ubuntu`, or `Windows`.
    * And:
        * The user lost one of these roles
            * Roles: `Agreed to Rules`
* Do This:
    * Take these roles from the user
        * Roles: `Ashes of Creation`, `Last Epoch`, `Pantheon: Rise of the Fallen`, `Satisfactory`, `MacOS`, `Ubuntu`, and `Windows`.
    * Send a message
        * Channel: `📖・mee6-automations-loses-a-role-logs`
        * Message:
            ```
            The user {user.mention} with Username *{user.name}* and User ID *{user.id}* has either removed the <@&1191876960771641364> role themselves or had it removed from them by an <@&1191873182471303168>.

            As a result of the <@&1191876960771641364> role being removed, they have had all other assigned roles removed as well.

            If they wish to re-gain access, they must read the server rules which can be found in the https://discord.com/channels/1190406648259432448/1195548408182743161 channel [here](https://discord.com/channels/1190406648259432448/1195548408182743161/1195548746574991400) and click the `✅ I agree` button to unlock the https://discord.com/channels/1190406648259432448/1191837535849168957 channel to assign themselves roles.
            ```