# vote-kogecoin-netlify
serverless proposal send + recieve

## snapshot
Here is an example of event object:
{
  id: 'proposal/QmZ21uS8tVucpaNq2LZCbZUmHhYYXunC1ZS2gPDNWwPWD9',
  event: 'proposal/created',
  space: 'yam.eth',
  expire: 1620947058
}
Here are the possible events:
1) proposal/created 
When a new proposal is created
2) proposal/start 
When the voting period for a proposal start.
3) proposal/end 
When the voting period for a proposal end.
4) proposal/deleted  
When a proposal is deleted by the author or an admin of the space.

## request snapshot webhooks in discord

## Telegram

WebhookInfo
Contains information about the current status of a webhook.

Field	Type	Description
url	String	Webhook URL, may be empty if webhook is not set up
has_custom_certificate	Boolean	True, if a custom certificate was provided for webhook certificate checks
pending_update_count	Integer	Number of updates awaiting delivery
ip_address	String	Optional. Currently used webhook IP address
last_error_date	Integer	Optional. Unix time for the most recent error that happened when trying to deliver an update via webhook
last_error_message	String	Optional. Error message in human-readable format for the most recent error that happened when trying to deliver an update via webhook
max_connections	Integer	Optional. Maximum allowed number of simultaneous HTTPS connections to the webhook for update delivery
allowed_updates	Array of String	Optional. A list of update types the bot is subscribed to. Defaults to all update types except chat_member

## getWebhookInfo

Use this method to get current webhook status. Requires no parameters. On success, returns a WebhookInfo object. If the bot is using getUpdates, will return an object with the url field empty.

WebhookInfo
Contains information about the current status of a webhook.

Field	Type	Description
url	String	Webhook URL, may be empty if webhook is not set up
has_custom_certificate	Boolean	True, if a custom certificate was provided for webhook certificate checks
pending_update_count	Integer	Number of updates awaiting delivery
ip_address	String	Optional. Currently used webhook IP address
last_error_date	Integer	Optional. Unix time for the most recent error that happened when trying to deliver an update via webhook
last_error_message	String	Optional. Error message in human-readable format for the most recent error that happened when trying to deliver an update via webhook
max_connections	Integer	Optional. Maximum allowed number of simultaneous HTTPS connections to the webhook for update delivery
allowed_updates	Array of String	Optional. A list of update types the bot is subscribed to. Defaults to all update types except chat_member

# bot setup

