# Type: WebhookInfo

**Category**: Getting updates

**Description**: Describes the current status of a webhook.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#webhookinfo)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| url | String | Yes | Webhook URL, may be empty if webhook is not set up |
| has_custom_certificate | Boolean | Yes | True, if a custom certificate was provided for webhook certificate checks |
| pending_update_count | Integer | Yes | Number of updates awaiting delivery |
| ip_address | String | Optional | Optional. Currently used webhook IP address |
| last_error_date | Integer | Optional | Optional. Unix time for the most recent error that happened when trying to deliver an update via webhook |
| last_error_message | String | Optional | Optional. Error message in human-readable format for the most recent error that happened when trying to deliver an update via webhook |
| last_synchronization_error_date | Integer | Optional | Optional. Unix time of the most recent error that happened when trying to synchronize available updates with Telegram datacenters |
| max_connections | Integer | Optional | Optional. The maximum allowed number of simultaneous HTTPS connections to the webhook for update delivery |
| allowed_updates | Array of String | Optional | Optional. A list of update types the bot is subscribed to. Defaults to all update types except chat_member |
