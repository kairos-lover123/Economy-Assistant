# Economy Assistant Privacy Policy

**Effective Date:** August 21, 2026

This Privacy Policy explains how **Economy Assistant** ("the Bot") processes and stores information in connection with the **/r/TheSpikeGame Discord server** ("the Server").

Economy Assistant is a private Discord bot intended exclusively for use within the Server.

## 1. Information Economy Assistant Processes

Economy Assistant uses Discord's message-content functionality in order to identify supported message-based UnbelievaBoat give commands.

The Bot may process message content to determine whether a message begins with:

* `!give`
* `!money-give`
* `!pay`
* `!donate-money`
* `!give-money`

This processing is used to determine whether an applicable economy cooldown should begin or whether a user is already subject to an active cooldown.

Ordinary message content processed for this purpose is not automatically added to a permanent message database by the cooldown system.

## 2. Persistent Bot Configuration and Cooldown Data

Economy Assistant stores certain operational information in a local state file so that settings and active cooldowns can survive Bot restarts.

This may include:

* Discord user IDs of members granted command access.
* Discord role IDs granted command access.
* Discord role IDs with configured cooldowns.
* Configured cooldown durations.
* Discord user IDs currently subject to a cooldown.
* The Discord server ID associated with an active cooldown.
* The timestamp at which an active cooldown expires.
* The configured maximum give amount.

This data is used to operate and restore Economy Assistant's configuration and cooldown system.

## 3. Channel Export Data

Economy Assistant includes an administrative feature that allows an authorized user to create a database containing the accessible message history of a selected Discord text channel.

When an export is requested, the Bot may process and include:

### User information

* Discord user ID
* Username
* Display name
* Discord discriminator, where applicable
* Avatar identifier

### Message information

* Message ID
* Message content
* Message timestamp
* Edit timestamp
* Sender ID
* Reply relationships
* Embed contents
* Reactions and reaction counts

### Attachment information

* Attachment ID
* Filename
* Content type
* Discord/CDN URL
* File size
* Image width and height, where available

The current export system records attachment information and URLs. It does not intentionally download and store attachment file contents as part of the normal export process.

### Server and channel information

* Discord server ID
* Server name
* Server icon identifier
* Channel ID
* Channel name
* Channel category or parent information
* Channel position
* Channel topic
* Whether Discord reports the channel as NSFW

The exact contents of an export depend on the messages and metadata available through Discord at the time it is created.

## 4. How Channel Exports Work

Channel exports are created **only when an authorized user runs the export command**.

Economy Assistant does not continuously maintain a permanent database containing every message in the Server.

When an export is requested, the Bot reads the existing accessible history of the selected channel and creates a temporary DHT database.

The resulting database is then sent through Discord to the location where the command response is delivered.

An authorized user may cancel an export. In that case, Economy Assistant saves the messages already processed and sends the resulting partial database.

## 5. Temporary Export Storage

During an export, Economy Assistant temporarily stores the generated DHT database on the system hosting the Bot.

The Bot is designed to delete this temporary local file after the export attempt finishes.

Once the database has been uploaded to Discord, however, the copy sent through Discord is subject to Discord's storage systems, the permissions of the channel in which it was sent, and any copies subsequently downloaded or redistributed by users.

The Bot operator cannot automatically delete copies independently saved by other users.

## 6. Purposes of Processing

Economy Assistant processes information for purposes including:

* Enforcing Server economy cooldowns.
* Maintaining cooldowns across Bot restarts.
* Managing authorized Bot access.
* Creating requested channel-history exports.
* Auditing economy activity.
* Investigating suspicious or abusive economy activity.
* Resolving economy disputes.
* Moderating and administering the Server.
* Generating economy statistics or analysis.
* Balancing the Server economy.
* Debugging and maintaining Economy Assistant.
* Protecting the Bot and Server from abuse.

Economy Assistant is not intended to use collected information for advertising or commercial profiling.

## 7. Who Can Access Economy Assistant Commands

Economy Assistant's administrative functionality is restricted to Server administrators and roles or members that administrators explicitly authorize.

The command that grants additional users or roles access to Economy Assistant is restricted to administrators.

Access permissions may be modified or revoked by Server administration.

## 8. Who May Receive Exported Data

A generated channel export is sent through Discord in response to the authorized command that created it.

Depending on where that command is used, other users with access to the response channel may also be able to access the exported file.

Server staff are responsible for using the export feature only in appropriate channels and for controlling access to exported databases.

Exported information should not be shared with unauthorized third parties except where reasonably necessary for legitimate Server administration, security, enforcement, or legal obligations.

Economy Assistant does not sell personal information.

## 9. Data Retention

Different categories of information are retained differently.

### Cooldown and configuration data

Configuration information may remain stored for as long as it remains configured.

Active cooldown records are normally removed when the relevant cooldown expires.

User or role IDs explicitly granted command access may remain stored until the Bot's configuration is changed or the data is otherwise removed.

### Temporary exports

The Bot's temporary local DHT export file is designed to be deleted after the export process finishes.

### Copies sent through Discord

A DHT file uploaded to Discord may remain available according to Discord's retention practices and actions taken by Server staff or other authorized users.

Additional downloaded copies are outside Economy Assistant's direct control.

## 10. Message Deletion and Exported Copies

Deleting or editing a Discord message does not automatically modify a DHT database that was previously generated.

An export is a snapshot of the channel information available when the export occurred.

As a result, previously exported databases may contain information that has subsequently been edited or deleted from Discord.

## 11. Data Security

Reasonable efforts should be made to restrict access to Economy Assistant's hosting environment, configuration files, administrative commands, and generated databases.

However, no electronic system can be guaranteed to be completely secure.

Authorized users are expected to protect exported databases from unauthorized access or redistribution.

## 12. Data Deletion and Privacy Requests

Users may contact the **/r/TheSpikeGame Discord server administration** regarding questions or requests concerning information processed through Economy Assistant.

Depending on the type of information involved:

* Active Bot state may be corrected or removed where appropriate.
* A temporary export may already have been automatically deleted from the Bot's hosting system.
* Copies previously sent through Discord or downloaded by authorized users may need to be handled separately.

Some information may be retained where reasonably necessary for Server security, moderation, dispute resolution, abuse prevention, or compliance with applicable obligations.

Nothing in this section limits rights that a user may have under applicable data-protection law.

## 13. Sensitive Personal Information

Economy Assistant is not designed for the purpose of collecting real names, home addresses, passwords, payment-card details, government identification, or similar sensitive personal information.

However, because authorized channel exports contain message content, an export could contain personal information that a Discord user voluntarily posted in the exported channel.

Users should therefore avoid posting sensitive personal information in Discord channels where it is unnecessary.

## 14. Children's Privacy

Economy Assistant is not designed to specifically collect information about children.

Use of the Server and Discord remains subject to Discord's applicable age requirements and policies.

## 15. Third-Party Services

Economy Assistant operates through Discord and interacts with UnbelievaBoat.

Discord and UnbelievaBoat are independent services with their own terms, privacy practices, and data-processing activities.

Economy Assistant is not affiliated with or operated by either service.

## 16. Server Scope

Economy Assistant is intended for use only within the **/r/TheSpikeGame Discord server**.

Its information processing is intended to support administration of that Server and its virtual economy.

## 17. Changes to This Privacy Policy

This Privacy Policy may be updated if Economy Assistant's functionality, storage practices, permissions, or data-processing behavior changes.

The effective date at the top of this policy identifies the current version.

## 18. Contact

Questions, concerns, privacy requests, or requests relating to Economy Assistant data should be directed to the **/r/TheSpikeGame Discord server administration**.
