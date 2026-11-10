# Privacy Policy

**Last updated:** November 11, 2026

This Privacy Policy explains how Sicae ("we", "us", "our") collects, uses, and shares information when you use the Sicae Discord bot (the "Bot") and its related support server (together, the "Service").

By adding the Bot to a server or interacting with it, you agree to this policy. If you do not agree, remove the Bot from your server and stop using it.

## 1. What the Bot Does

The Bot offers embed and webhook message builders, buttons, select menus and message layouts, server tag rewards, welcome, goodbye and boost messages, auto roles, booster roles, VoiceMaster temporary voice channels, an autoresponder, automatic reactions, snipe, emoji and sticker tools, info commands, and a per-server bot profile. It only runs in servers we have approved, and it uses slash commands only.

## 2. Information We Receive but Do Not Store

The Bot receives this from Discord and uses it while working, without saving it to its database:

- **Messages:** the Bot receives messages in channels it can see, so it can compare them to the autoresponder and reaction triggers set up in that server. Message text is not saved to the database, snipe below is the only feature that keeps it for a short time, in memory.
- **Member details:** usernames, display names, avatars, roles, join dates, account age, boost status, and server tag status, used for features and commands such as rewards, auto roles, variables, and `/info`.
- **Voice activity:** which voice channel members are in, used for VoiceMaster. The Bot never joins voice and never receives audio.
- **Snipe:** only in servers where staff turn snipe on, the Bot keeps recently deleted and edited messages in memory so members can view them with `/snipe`: the author, the text (up to 2,000 characters), attachment names, and when the message was sent, edited or deleted. If staff turn on image previews, it also keeps a small copy of the first image. If staff turn on showing who deleted a message, it reads that from Discord's audit log. None of this is written to the database. It's dropped after 1 hour, when the Bot restarts, when snipe is turned off or a channel is ignored, and when staff use `/snipe clear`. Staff can also filter out invites, links, images, files, music and chosen words, and limit snipe to certain roles.
- **Message links:** when someone gives a message link to the emoji and sticker tools, the Bot reads that one message to find its emojis or stickers, and doesn't keep it.

The Bot does not use Discord presence data, so it does not see online status or activities. It does not receive or send direct messages. We do not collect passwords or payment details.

## 3. Information We Store

**Set up by server staff**

- Saved embeds, webhook messages, and welcome, goodbye and boost messages
- Webhook URLs and tokens, and the channel and message IDs of posts the Bot sent
- Rules and settings for server tag rewards, auto roles, the autoresponder, reactions, VoiceMaster, snipe, and booster roles, including snipe's filters, blocked words, ignored channels and allowed roles, and the booster role name filter
- Buttons, select menus, layouts and page sets made with `/components`
- Pictures uploaded for the VoiceMaster interface and webhook
- The Bot's bio for that server

**About members**

- The user ID of whoever created, changed, or sent one of the items above
- Server tag rewards: whether a member wears the tag, since when, and which roles the Bot gave them
- Auto roles: join roles waiting on a delay or on rules screening
- VoiceMaster: a member's saved channel name, user limit, lock and hide settings, their permit list, and who owns each open temporary channel
- Booster triggers: the word, emoji or response a booster added, and who owns it
- Booster roles: which member owns each booster role, and who it's shared with
- Booster bans: who was banned from booster triggers, their username at the time, by whom, and when

Anything typed into an embed, message, or trigger is stored as written, so please do not put private information in them.

**About servers we manage**

- Approved servers: the server ID, a note, who added it, and when
- Servers the Bot refused: the server's name and ID, its owner's user ID, member count, number of attempts, and last attempt. Only the 50 most recent are kept.

**Logs and statistics**

- Logs record each command used, with the username, user ID, and server, along with errors, role changes made by server tag rewards, and role changes other features couldn't make. Message text is not logged.
- Each command has a total use and error count, which is not linked to any user.

## 4. How We Use Information

We use information to:

- Operate the Bot and carry out the commands and features you or your server staff request
- Store each server's settings so the Bot behaves consistently
- Prevent abuse and enforce our Terms of Service
- Diagnose errors and improve the Bot
- Respond to support requests
- Comply with legal obligations and Discord's requirements

## 5. How We Share Information

We do not sell your personal information, and we do not use it for advertising. The Bot only connects to Discord.

We may share information only:

- **With Discord,** because the Bot operates through Discord's platform and is subject to Discord's own policies
- **With GitHub,** which holds a private backup of the Bot's database (see Section 6)
- **When required by law,** or to protect the rights, safety, and security of our users or the Service
- **With your server's staff,** where a feature shows who owns something, such as booster triggers and bans

## 6. Storage and Backups

Data is stored on the developer's own devices, and a copy of the database is kept as a backup in a private GitHub repository. Older backup copies can remain there after data is deleted. Logs and snipe's in-memory messages stay on the developer's own devices and are never backed up.

## 7. Data Retention and Deletion

There is no automatic time limit on stored data, except as listed here.

**When the Bot leaves a server:** that server's data stays stored and is not deleted automatically. If you want it deleted, ask us (see Section 9).

**When a member leaves a server:**

- VoiceMaster data, server tag data, and waiting auto role jobs are deleted straight away. The member is also removed from other people's permit lists.
- Booster roles they own are deleted, and they're removed from roles others shared with them. A member who stops boosting also loses the booster roles they own, unless they're an admin or the server owner.
- Booster triggers are paused and stay until staff or the booster removes them.
- Booster bans stay until server staff remove them.
- The user ID on items someone created stays with those items.

**Logs** have no fixed time limit. They have a total size limit, and the oldest entries are overwritten as the logs fill up.

## 8. Who Can Delete What

- **Server staff** can delete saved embeds, webhooks, webhook messages, reward rules, triggers, booster bans, and event messages, using the matching commands and panels. VoiceMaster's Reset clears its design, `/snipe clear` forgets sniped messages in a channel or the whole server, `/components` deletes buttons, menus, layouts and page sets, and the booster role panel deletes booster roles.
- **Members** can reset their own VoiceMaster settings, remove their own booster triggers, and delete or leave booster roles.
- **We** handle everything else on request, including server data after the Bot has left, and logs.

## 9. Your Rights and Choices

Depending on where you live, you may have the right to access, correct, delete, or get a copy of your personal data, object to or restrict certain processing, and withdraw consent.

To make a request, contact us on Discord at https://discord.gg/sicae. We handle requests by hand, and we may need to verify that the account making the request is yours, for example by asking you to message us from that Discord account.

You can also:

- Ask server staff to remove the Bot from your server, or to limit which channels it can see
- Stop using the Bot's commands and features
- Manage what data Discord shares with apps through your Discord privacy settings

## 10. Security

We use reasonable measures to protect the data we hold, such as access controls and keeping secrets out of public code. No method of storage or transmission is completely secure, so we cannot guarantee absolute security.

## 11. Discord and Third-Party Services

The Bot runs on Discord. Discord's own Terms of Service and Privacy Policy apply to your use of Discord, and we are not responsible for how Discord handles your data. Links and images that server staff add to messages may lead to third-party sites with their own policies.

## 12. Children's Privacy

Discord requires users to be at least 13 years old (or the minimum age in their country). The Service is not intended for anyone younger. We do not knowingly collect personal information from children under 13. If you believe a child has provided us information, contact us and we will delete it.

## 13. International Users

The Bot and its data may be in a different country from yours.

## 14. Changes to This Policy

We may update this policy from time to time. We will post the new version in this repository and update the "Last updated" date. For material changes, we will announce them in our support server. Continued use of the Bot after changes means you accept the updated policy.

## 15. Contact Us

Sicae
Discord: https://discord.gg/sicae
