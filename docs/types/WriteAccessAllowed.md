# Type: WriteAccessAllowed

**Category**: Available types

**Description**: This object represents a service message about a user allowing a bot to write messages after adding it to the attachment menu, launching a Web App from a link, or accepting an explicit request from a Web App sent by the method requestWriteAccess.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#writeaccessallowed)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| from_request | Boolean | Optional | Optional. True, if the access was granted after the user accepted an explicit request from a Web App sent by the method requestWriteAccess |
| web_app_name | String | Optional | Optional. Name of the Web App, if the access was granted when the Web App was launched from a link |
| from_attachment_menu | Boolean | Optional | Optional. True, if the access was granted when the bot was added to the attachment or side menu |
