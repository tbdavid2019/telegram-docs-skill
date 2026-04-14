# Type: ChosenInlineResult

**Category**: Inline mode

**Description**: Represents a result of an inline query that was chosen by the user and sent to their chat partner.
Note: It is necessary to enable inline feedback via @BotFather in order to receive these objects in updates.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#choseninlineresult)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| result_id | String | Yes | The unique identifier for the result that was chosen |
| from | User | Yes | The user that chose the result |
| location | Location | Optional | Optional. Sender location, only for bots that require user location |
| inline_message_id | String | Optional | Optional. Identifier of the sent inline message. Available only if there is an inline keyboard attached to the message. Will be also received in callback queries and can be used to edit the message. |
| query | String | Yes | The query that was used to obtain the result |
