# Economy Assistant Terms of Service

**Effective Date:** August 21, 2026

These Terms of Service ("Terms") govern the use of **Economy Assistant** ("the Bot"), a private Discord bot intended for use exclusively within the **/r/TheSpikeGame Discord server** ("the Server").

By participating in Server features that interact with Economy Assistant, you agree to these Terms and the applicable rules of the Server.

## 1. Purpose

Economy Assistant is a moderation and administration utility for the Server's virtual economy.

The Bot provides functionality including:

* Applying role-based cooldowns to UnbelievaBoat give commands.
* Supporting the following message-based UnbelievaBoat give aliases:

  * `!give`
  * `!money-give`
  * `!pay`
  * `!donate-money`
  * `!give-money`
* Generating Discord AutoMod regex patterns that Server staff may use to limit the maximum amount transferable through supported message-based give commands.
* Exporting the existing message history of a selected Discord text channel into a DHT database.
* Allowing authorized users to stop an export and receive the partial database.
* Providing administrative configuration commands.

Economy Assistant is not affiliated with, endorsed by, or operated by Discord or UnbelievaBoat.

## 2. Server Availability

Economy Assistant is intended exclusively for the **/r/TheSpikeGame Discord server**.

The Bot is not offered as a public Discord bot or general-purpose service.

Unauthorized copying, redistribution, modification, hosting, or use of the Bot outside its authorized environment may be prohibited by the Bot operator.

## 3. Administrative Access

Most Economy Assistant commands are restricted to:

* Members with the Discord Administrator permission; or
* Roles or individual members explicitly granted Economy Assistant command access by an administrator.

The ability to grant additional command access is itself restricted to Server administrators.

Authorized access may be changed or revoked at any time.

## 4. Give Cooldowns

Server staff may configure cooldown periods for specific Discord roles.

When a member with a configured role uses a supported message-based give command, Economy Assistant may assign that member a designated cooldown role for the configured period.

If multiple configured roles apply to the same member, the Bot uses the shortest applicable cooldown.

Cooldown information may remain active across Bot restarts. If a cooldown expires while the Bot is offline, Economy Assistant may remove the cooldown role when it next becomes available.

Users must not intentionally bypass or evade economy cooldowns, including through alternate accounts, command variants, permission exploits, or other methods.

The effectiveness of a cooldown may also depend on the Server's Discord permissions, roles, AutoMod configuration, and UnbelievaBoat configuration.

## 5. Maximum Give Amount

Economy Assistant can generate Discord AutoMod regular expressions intended to block supported message-based give commands above a Server-defined amount, as well as transfers using `all`.

These regular expressions must be configured in Discord AutoMod by authorized Server staff.

Economy Assistant does not guarantee that an AutoMod pattern will intercept every possible command format.

Discord AutoMod cannot use these message regex patterns to restrict another bot's slash-command interactions. Therefore, this functionality does not itself restrict UnbelievaBoat's `/give` slash command.

## 6. Channel Exports

Authorized users may instruct Economy Assistant to export the existing history of a Discord text channel that the Bot is permitted to view.

An export may include the complete accessible message history of the selected channel at the time the export is performed.

Exports may contain:

* Message content
* Message IDs
* Discord user IDs
* Usernames and display names
* Message timestamps
* Edit timestamps
* Reply relationships
* Embeds
* Reactions
* Attachment information and URLs
* Channel information
* Server information
* Other metadata associated with exported Discord messages

Exports are generated on demand. Economy Assistant does not continuously add new messages to a previously generated export.

The Bot may temporarily create the database on the system hosting Economy Assistant and then send the resulting file through Discord.

## 7. Export Access and Responsibility

Channel exports may contain information that was visible only to members with access to the original channel.

Users with access to Economy Assistant's export functionality must use exported data only for legitimate Server administration, moderation, auditing, economy analysis, or other authorized purposes.

Authorized users must not:

* Publish private-channel exports without authorization.
* Distribute exported databases to unauthorized persons.
* Use exported information to harass, impersonate, dox, or target users.
* Use the export system to access information they are not authorized to access.
* Attempt to circumvent Discord channel permissions.

Once an exported file has been sent through Discord or separately downloaded or redistributed by an authorized user, Economy Assistant cannot control additional copies of that file.

## 8. Acceptable Use

Users must not:

* Attempt to bypass cooldowns or economy limits.
* Exploit bugs or unintended Bot behavior.
* Attempt to access administrative commands without authorization.
* Attempt to gain unauthorized access to Bot files, databases, credentials, or hosting systems.
* Intentionally interfere with the Bot's operation.
* Use alternate accounts or automation to evade economy restrictions.
* Abuse interactions between Economy Assistant, Discord, and UnbelievaBoat.

Violations may result in economy restrictions, loss of Bot access, moderation action, or other penalties under Server rules.

## 9. Virtual Economy

Economy Assistant interacts with a Discord-based virtual economy.

Unless separately stated by the Server, virtual currency, balances, items, roles, or similar economy features do not represent guaranteed real-world monetary value.

The Server administration may modify economy rules, cooldowns, limits, prices, balances, or other economy settings at any time.

## 10. Availability and Accuracy

Economy Assistant is provided on an **"as is"** and **"as available"** basis.

There is no guarantee that the Bot will:

* Remain online continuously.
* Detect every relevant command.
* Enforce every cooldown successfully.
* Generate perfect AutoMod rules.
* Export every message or piece of metadata.
* Remain compatible with future Discord or UnbelievaBoat updates.
* Operate without errors, interruptions, or data loss.

Bot records and exports should not be assumed to be infallible.

## 11. Third-Party Services

Economy Assistant depends on third-party services including Discord and interacts with UnbelievaBoat.

Changes, outages, restrictions, API changes, permission changes, or errors involving those services may affect the Bot.

Users remain subject to applicable Discord terms, policies, and Server rules.

## 12. Limitation of Liability

To the maximum extent permitted by applicable law, the Bot operator and /r/TheSpikeGame administration are not responsible for losses or damages resulting from:

* Bot downtime or errors
* Incorrect or missing cooldowns
* Failed or incorrectly configured AutoMod rules
* Incorrect, incomplete, or failed exports
* Loss of virtual currency or economy items
* Discord or UnbelievaBoat outages or changes
* Unauthorized redistribution of an export by another user
* Other unintended Bot behavior

Nothing in these Terms excludes liability that cannot legally be excluded.

## 13. Suspension or Termination

Access to Economy Assistant may be restricted or revoked at any time, including where a user:

* Violates these Terms.
* Violates Server rules.
* Abuses economy systems.
* Misuses exported information.
* Creates a security or operational risk.

Economy Assistant itself may be modified, suspended, replaced, or discontinued at any time.

## 14. Privacy

Use of Economy Assistant is also subject to the **Economy Assistant Privacy Policy**, which explains what information the Bot processes and stores.

## 15. Changes to These Terms

These Terms may be updated when Economy Assistant, the Server economy, Discord, or related systems change.

The effective date above identifies the current version.

Continued use of applicable Server features after updated Terms take effect constitutes acceptance of the revised Terms to the extent permitted by applicable law.

## 16. Contact

Questions about Economy Assistant or these Terms should be directed to the **/r/TheSpikeGame Discord server administration**.
