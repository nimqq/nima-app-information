# Nima — Privacy Notice

Effective: October 29, 2026  
Discord application: **1547312805215211682**  
Operator: **cyy** ([GitHub](https://github.com/nimqq))

## What Nima does

Nima is a privately installed Discord companion for selected game-development conversations and work. Its operator uses it to catch up on discussions, retrieve relevant references, answer questions, and prepare explicitly requested work records and game-data changes. Proposed changes are shown for confirmation before being applied.

## Data processed

In the server channels selected by its operator, Nima can process message text, author/display names and Discord identifiers, timestamps, links, and attachment/embed information. Relevant text may be included in conversation context, summaries, work records, and source references. The bot's access is governed by Discord's permissions and its configured application scope. It is not a public service that anyone can install.

## Storage and AI processing

Selected information is processed and stored outside Discord on operator-controlled systems. Relevant conversation context may be sent to AI service providers to generate answers and summaries. Application data may also be retained as source material for later retrieval. This inference and retrieval is distinct from training or fine-tuning model weights; Nima does not operate a model-weight training or fine-tuning workflow.

AI providers process requests under their own applicable service terms and data-handling settings. This notice does not promise zero provider retention. Discord message data is not offered for sale or used for advertising.

## Retention

Retention differs by purpose. The communications digest clears its cached message text and chat names after 30 days, and on the same schedule deletes its per-conversation summaries and clears the text of its rendered digests. Its live digest view is rebuilt only from the last 3 days. Records kept by Nima's work assistant (conversation context, saved work/source records and operational receipts) support ongoing work and record continuity and currently have no fixed automatic expiry. This notice therefore does **not** promise that all related information is erased after 30 days.

## Controls, questions and deletion requests

There is currently no automated per-user opt-out or account-deletion command. Server administrators can remove Nima from a server or restrict its channel access through Discord's permissions. Contact the operator to request that a source stop being processed, to ask what data is held about you, or to request correction or deletion. Requests are reviewed manually, including identity, affected records and any applicable retention requirements; removal from Discord alone does not establish deletion of an earlier saved record.

For private contact, use the [operator's Discord profile](https://discord.com/users/989011386929664091), or ask an administrator in the server where Nima is installed to contact the operator. If you cannot reach the operator there, leave a contact request in this repository's Issues; do **not** post private messages, identifying documents, credentials or other sensitive information in a public issue.

## Security and changes

Stored Discord message data, including digests, summaries, conversation context, logs and backups, is encrypted at rest on the operator's server (AES-256, Linux filesystem encryption). The decryption key is held separately from the data folders and readable only by the server's administrator account; it resides on the same server. One known exception: the server's swap space is not yet encrypted, so fragments of in-memory data can temporarily appear there; encrypted swap is planned for the next scheduled restart. Off-site backups are separately encrypted. Access to the operator's stored records and connected services is restricted. No system can guarantee absolute security. Material changes to these practices will be reflected in this notice.

This notice concerns Nima's Discord application data. Discord itself handles platform data under [Discord's Privacy Policy](https://discord.com/privacy).
