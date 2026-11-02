# Economy Assistant Privacy Policy

**Effective Date:** November 2, 2026  
**Last Updated:** November 2, 2026

This Privacy Policy explains how **Economy Assistant** ("the Bot," "we," or "our") collects, processes, stores, and uses information in connection with the **The Spike Cross Discord server** ("the Server").

Economy Assistant is a private, multifunctional Discord bot intended exclusively for use within the Server. Its features include a multiplayer Mafia game, player progression, virtual economy management, moderation tools, role management, automated AFK notifications, and administrative utilities.

By interacting with the Bot or participating in Server activities involving its features, users may have relevant Discord information processed as described below.

## 1. Information We Process

Economy Assistant processes information provided through Discord's API and information generated through users' interactions with the Bot.

Depending on the functionality involved, this may include:

### Discord account and membership information

- Discord user IDs
- Usernames and global display names
- Server-specific display names and nicknames
- Profile pictures and avatar identifiers
- Server IDs and names
- Role IDs and role assignments
- Server membership information
- Account creation and server joining timestamps, where applicable

This information is used to identify members, enforce permissions, manage gameplay, display profiles, and operate community features.

### Message information

The Bot may access:

- Message IDs and author IDs
- Message content
- Message timestamps
- Message edits, where relevant
- Mentions and reply relationships
- Attachments and embedded content
- Reactions and associated metadata

Message content is processed for supported commands, automated notifications, virtual economy enforcement, gameplay activity, moderation, and authorized administrative functions.

**The Bot does not continuously maintain a permanent database of every message in the Server.** However, specific messages, user submissions, gameplay events, and authorized channel exports may be stored as described in this policy.

## 2. Message Content Processing

Economy Assistant uses Discord's Message Content functionality to support features requiring traditional message-based commands or automated responses.

### Supported commands

The Bot processes text commands, including its own supported commands and relevant commands from integrated third-party bots.

For virtual economy management, the Bot may recognize commands such as:

- `!give`
- `!money-give`
- `!pay`
- `!donate-money`
- `!give-money`

This processing determines whether economy restrictions or cooldowns apply.

### Automated message detection

The Bot also examines relevant message activity to:

- Detect when AFK members are mentioned or replied to.
- Determine when an AFK member returns.
- Process relevant Mafia discussion activity.
- Identify supported command requests.
- Detect qualifying virtual economy transactions.
- Support authorized moderation functions.

Ordinary messages inspected for these purposes are not automatically archived in a permanent message database solely because they were processed.

## 3. Multiplayer Mafia Game

Economy Assistant provides a custom multiplayer social deduction game.

Players may join hosted games, receive hidden roles, perform actions, participate in discussions, vote, complete objectives, and earn rewards.

To operate the game, the Bot processes and may store:

- Participating players' Discord IDs
- Server display names
- Lobby participation and hosting information
- Assigned roles and factions
- Player movement and room selections
- Ability usage, targets, and cooldowns
- Voting decisions and elimination information
- Game phases and timestamps
- Game results and victory conditions
- Player inactivity and gameplay restrictions
- Game events and activity logs

### Private gameplay information

Certain information, such as hidden roles, player actions, and ability results, is delivered through Discord direct messages or other restricted interactions.

The Bot maintains internal game state to correctly resolve player actions and determine outcomes.

Authorized administrators may have access to additional gameplay information through administrative tools or stored game records.

### Gameplay logs

The Bot may generate persistent records of completed or interrupted games, including participants, role assignments, gameplay events, timestamps, and results.

These records support debugging, dispute resolution, gameplay administration, and investigation of technical problems or misconduct.

## 4. Player Statistics and Progression

Economy Assistant maintains persistent player progression information.

This may include:

- Total games played
- Wins, losses, and other outcomes
- Elo ratings and ranking information
- Experience points and levels
- Gameplay performance statistics
- Achievements and progression milestones
- Daily and weekly quest progress
- Gameplay inactivity records
- Participation restrictions and penalties
- Historical game information

These records are associated with Discord user IDs to preserve player progression across games and Bot restarts.

Certain statistics may be displayed publicly through player profiles, rankings, leaderboards, and game-result interfaces.

Other information remains available only through authorized administrative functions.

## 5. Player Profiles, Cosmetics, and Inventories

The Bot supports customizable Mafia player profiles, cosmetic rewards, and virtual inventories.

To operate these systems, it may store:

- Discord user IDs
- Owned virtual items
- Equipped cosmetics
- Profile backgrounds and decorations
- Selected colors, gradients, and visual settings
- Profile titles and display preferences
- Virtual item purchases
- Vouchers and consumable items
- Customization requests and transaction records

Player avatars and display names may be retrieved from Discord to generate profile images and gameplay-related visual content.

Generated images may be delivered through Discord and remain subject to Discord's message and attachment storage practices.

This information is used exclusively for profile customization, virtual inventory management, rewards, and related gameplay features.

## 6. Virtual Economy and UnbelievaBoat Integration

Economy Assistant integrates with UnbelievaBoat to support the Server's virtual economy.

The Bot may process relevant economy commands, transaction confirmations, virtual currency amounts, and member identifiers.

### Economy cooldowns

The Bot maintains persistent cooldown and restriction information, including:

- Discord user IDs subject to cooldowns
- Associated Server IDs
- Cooldown start and expiration timestamps
- Role-based cooldown configurations
- Maximum permitted transfer amounts
- Authorized members and roles
- Applicable channel restrictions

This information is used to enforce Server economy rules and prevent members from avoiding restrictions through Bot restarts or leaving and rejoining the Server.

### Virtual currency transactions

Where supported, the Bot may communicate with UnbelievaBoat's API to retrieve economy information or perform authorized virtual currency operations.

Relevant Discord identifiers, transaction amounts, and transaction-related information may be exchanged as necessary to perform those operations.

These features concern virtual Server currency rather than bank accounts, payment cards, or real-world financial transactions.

## 7. Automated AFK System

Economy Assistant provides an optional automated away-from-keyboard system.

Members may activate AFK using the `-afk` command, optionally including a custom message.

When activated, the Bot may store:

- Discord user ID
- Server ID
- AFK activation timestamp
- Custom AFK message
- Previous server nickname
- Temporary AFK nickname
- Members requesting return notifications
- Messages left for the AFK member

### AFK notifications

When another member mentions or replies to an AFK member, the Bot may send that person a private notification.

The notification may contain the AFK member's server display name, custom message, AFK duration, and Server name.

### Messages left for AFK members

Members may voluntarily leave messages for absent users through interactive Bot controls.

These messages may be stored until delivery and can include:

- Sender's Discord ID
- Sender's server display name
- Message content
- Submission timestamp

Messages are delivered privately when the absent member returns.

If delivery fails, undelivered messages may remain stored for later delivery attempts.

### AFK expiration

AFK status automatically ends when the member sends a regular message in the Server.

The Bot then removes the active AFK record, attempts to restore the member's previous nickname, delivers waiting messages, and sends requested return notifications.

AFK information is persisted across Bot restarts to maintain functionality.

This system does not require monitoring members' Discord online, idle, or offline presence statuses.

## 8. Role Management and Permissions

The Bot includes features for managing member permissions and role appearance.

These include role showcase functionality, command access restrictions, and automated restoration of role configurations.

Information processed may include:

- Member Discord IDs
- Current role assignments
- Selected showcase roles
- Temporarily adjusted roles
- Previously held roles required for restoration
- Access permissions and eligibility information
- Relevant membership or role changes

The Bot uses this information to manage supported role features and maintain configured permissions.

Role configuration data may persist across Bot restarts.

## 9. Moderation and Player Reporting

Economy Assistant provides moderation and reporting utilities for authorized Server staff.

### Player reports

Following Mafia games, participants may voluntarily submit reports about other participants.

A report may contain:

- Reporter Discord ID
- Reported member's Discord ID
- Associated game identifier
- Selected report reason
- Written explanation
- Submission timestamp
- Evidence links
- Screenshots or other supporting attachments

Reports are maintained in a restricted moderation system intended for authorized staff.

Some submitted evidence may be copied into a private Discord evidence channel for review.

### Report retention

Post-game reporting invitations are time-limited, normally expiring after one hour.

Open reports remain stored while awaiting review.

When a report is marked completed, its record is removed from the active reporting database, and the Bot attempts to delete associated evidence messages that it archived in the designated evidence channel.

Original messages, externally hosted evidence, or separately downloaded copies may remain available outside the Bot's direct control.

### Other moderation records

The Bot may also store member restrictions, hosting bans, gameplay penalties, economy blacklists, and administrative access configurations.

These records support Server safety, rule enforcement, and abuse prevention.

## 10. Administrative Channel Exports

Economy Assistant includes a restricted administrative feature for exporting accessible message history from a specifically configured Discord channel.

**Channel exports are created only when an authorized administrator explicitly requests them.**

The Bot does not continuously export or archive all Server conversations.

### User information included in exports

An export may contain:

- Discord user IDs
- Usernames and display names
- Discord discriminators, where applicable
- Avatar identifiers

### Message information included in exports

An export may contain:

- Message IDs and content
- Message timestamps
- Edit timestamps
- Sender IDs
- Reply relationships
- Embeds
- Reactions and reaction counts

### Attachment information included in exports

An export may contain:

- Attachment IDs
- Filenames and content types
- Discord/CDN URLs
- File sizes
- Image dimensions, where available

The normal export process records attachment metadata and URLs rather than intentionally downloading attachment file contents.

### Server and channel information included in exports

An export may contain:

- Server ID and name
- Server icon identifier
- Channel ID and name
- Channel category or parent
- Channel position and topic
- Channel NSFW classification

The specific information included depends on what Discord makes accessible when the export is generated.

## 11. Export Storage and Distribution

Requested channel exports are generated as temporary DHT database files.

The Bot temporarily stores these files on its hosting system during processing.

Temporary local export files are designed to be deleted after the export attempt finishes.

Administrators may cancel an ongoing export, in which case the Bot may provide a partial export containing information processed before cancellation.

Completed or partial exports are delivered through Discord.

Depending on the destination and its permissions, other members may be able to access the exported database.

Server administrators are responsible for requesting exports only when appropriate and ensuring they are delivered to appropriately restricted destinations.

### Previously exported information

Editing or deleting a Discord message does not automatically update a previously generated export.

Exports represent snapshots of the accessible channel history at the time of processing.

Copies downloaded or redistributed by authorized users may exist independently of the Bot.

## 12. Purposes of Information Processing

Economy Assistant processes information for legitimate Server functionality, including:

- Operating multiplayer Mafia games.
- Assigning roles and resolving gameplay actions.
- Recording player statistics and rankings.
- Maintaining experience, quests, and rewards.
- Managing profiles, inventories, and cosmetics.
- Enforcing virtual economy rules and cooldowns.
- Providing automated AFK notifications.
- Delivering messages left for absent members.
- Managing Server roles and command permissions.
- Processing player reports.
- Investigating misconduct and resolving disputes.
- Maintaining gameplay logs and administrative records.
- Generating authorized channel-history exports.
- Preventing abuse and unauthorized use.
- Debugging errors and maintaining Bot functionality.

The Bot is not intended to process Discord information for advertising, commercial profiling, or the sale of personal information.

Where applicable data-protection law requires a lawful basis, processing is generally undertaken for legitimate interests in operating and protecting the Server and providing its community features. Optional, user-initiated features are processed to fulfill the requested functionality. Other legal bases may apply where required by law.

## 13. Who Can Access Information

Access depends on the category of information and the relevant feature.

### Members

Members may access their own player information, inventories, and progression records through supported Bot commands.

Other members may see information intended to be public, such as leaderboards, visible profiles, and game results.

### Authorized staff

Server administrators and appropriately authorized staff may access information necessary for moderation, Bot administration, gameplay oversight, and technical troubleshooting.

This may include moderation reports, gameplay logs, configuration records, and authorized channel exports.

### Bot operators

Persons responsible for operating and maintaining the Bot may require access to locally stored files, databases, and technical records.

Access should be limited to individuals responsible for maintaining the service and performing authorized administrative functions.

## 14. Third-Party Services and Data Sharing

Economy Assistant operates through Discord and integrates with UnbelievaBoat.

### Discord

Discord provides the messaging, interaction, account, and server infrastructure required for the Bot.

Information sent through Discord, including direct messages, generated images, reports, and exported databases, is subject to Discord's own storage and privacy practices.

Discord's Privacy Policy is available at:

https://discord.com/privacy

### UnbelievaBoat

The Bot interacts with UnbelievaBoat for supported virtual economy functions.

UnbelievaBoat is an independent third-party service with its own data-handling practices.

### Hosting providers

The Bot's hosting infrastructure may process or store operational data necessary for the application to function.

Any hosting provider used for this purpose should be subject to appropriate data-protection and security arrangements.

### Other disclosures

Information may be disclosed where required by applicable law or where users expressly direct an authorized disclosure, subject to applicable requirements.

**Economy Assistant does not sell personal information.**

The Bot is independently operated and is not affiliated with or operated by Discord or UnbelievaBoat.

## 15. Data Storage and Retention

The Bot uses persistent storage, including local configuration files, JSON data files, and SQLite databases, to maintain operational information.

Retention varies according to the purpose of each category.

### Gameplay and progression data

Player statistics, rankings, experience, inventories, customization settings, and gameplay records may remain stored while needed for continued gameplay, administration, or dispute resolution.

Completed game logs may also persist for technical analysis and gameplay auditing.

These records do not necessarily expire automatically.

### Economy data

Cooldown information is maintained while applicable.

Expired cooldown records may be cleared automatically or during subsequent state maintenance.

Configuration records and access permissions may remain until changed or removed.

### AFK data

Active AFK information is stored until the member returns or the record is otherwise removed.

Queued messages are retained until delivered or removed. Failed delivery attempts may result in continued storage.

Return-notification subscriptions are cleared when the associated AFK status ends.

### Role management information

Saved role configurations may remain stored while necessary for role restoration and related functions.

### Moderation information

Open reports remain stored until processed.

Completed reports are removed from the active reporting database, with associated archived evidence deletion attempted.

Other restrictions and administrative records may remain for as long as necessary for their intended purposes, subject to applicable deletion requirements.

### Temporary channel exports

Temporary local export databases are designed to be deleted following the export attempt.

Copies transmitted through Discord or downloaded separately are subject to their respective storage and retention arrangements.

### Deletion and retention limitations

Information is retained only insofar as necessary for the Bot's permitted functions, security, legal obligations, or other lawful purposes.

Users may request deletion of their personal data as described below.

## 16. Data Deletion and Privacy Requests

Users may contact the **The Spike Cross Discord server administration** regarding information processed by Economy Assistant.

Depending on the request and the information involved, administrators may:

- Review stored information associated with a Discord account.
- Correct inaccurate records.
- Remove eligible account-associated Bot data.
- Remove or adjust applicable configuration records.
- Review outstanding moderation information.
- Delete locally controlled information that is no longer required.
- Investigate previously generated exports within their control.

Deletion of certain information, such as player progression, may affect the user's ability to retain previously earned rewards or statistics.

### Exported copies

Information included in a previously generated export may require separate handling.

Deleting original Discord messages or Bot records does not automatically delete independently stored exports.

Administrators will assess deletion requests relating to copies within their control.

### Legal rights

Where applicable, users may have rights to access, correct, erase, restrict, or object to the processing of their personal information, and to request portability.

Users covered by the GDPR may also have the right to lodge a complaint with their relevant data-protection supervisory authority.

Requests will be assessed in accordance with applicable law and Discord's Developer Terms.

## 17. Data Security

The Bot's operator is responsible for taking appropriate technical and organizational measures to protect information processed by Economy Assistant.

These measures should include:

- Restricting access to hosting systems.
- Protecting Bot credentials and API tokens.
- Limiting administrative command access.
- Restricting moderation evidence channels.
- Controlling access to stored databases and configuration files.
- Protecting stored information against unauthorized access.
- Securing data during transmission and storage.
- Removing data when it is no longer required.
- Investigating and responding to security incidents.

The Bot also relies on Discord's permission system to control access to relevant channels, messages, interactions, and administrative commands.

No electronic system can be guaranteed to be completely secure.

Users should avoid submitting sensitive information unnecessarily through commands, reports, or other Bot interactions.

## 18. Sensitive Personal Information

Economy Assistant is not designed to intentionally collect:

- Passwords or authentication credentials
- Government identification documents
- Payment-card information
- Bank account details
- Home addresses
- Medical records
- Other sensitive personal information unrelated to Bot functionality

However, voluntarily submitted messages, reports, screenshots, or exported channel histories may contain personal information posted by Discord users.

Users should avoid including unnecessary sensitive information in AFK messages, reporting evidence, or other interactions.

Administrators should handle such information carefully and remove unnecessary copies when appropriate.

## 19. Children's Privacy

Economy Assistant is not specifically designed to collect personal information from children.

The Bot operates within Discord and is subject to Discord's applicable age requirements and platform policies.

The Bot does not independently verify users' ages.

If a parent, guardian, or user believes that personal information has been processed inappropriately, they may contact the Server administration.

## 20. Server Scope

Economy Assistant is intended exclusively for use within the **The Spike Cross Discord server**.

Its processing activities are intended to support the Server's gameplay systems, community features, virtual economy, moderation, and administration.

The Bot is not intended to harvest information from unrelated Discord communities or maintain external member directories.

## 21. Changes to This Privacy Policy

This Privacy Policy may be updated when Economy Assistant's features, data collection practices, storage systems, or relevant legal requirements change.

Changes may include the introduction of new gameplay systems, moderation features, integrations, or administrative utilities.

The effective date at the beginning of this document identifies the current version.

Where required, users will be informed of material changes.

## 22. Contact

Questions, concerns, access requests, correction requests, and deletion requests relating to Economy Assistant should be directed to the **The Spike Cross Discord server administration**.

Server page:

https://discord.com/servers/the-spike-cross-915792826929913926

Users may contact the Server's administration through Discord to request assistance concerning information processed by the Bot.

Requests will be reviewed in accordance with applicable data-protection obligations and Discord's developer requirements.
