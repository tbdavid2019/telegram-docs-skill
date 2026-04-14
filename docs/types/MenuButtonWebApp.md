# Type: MenuButtonWebApp

**Category**: Available types

**Description**: Represents a menu button, which launches a Web App.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#menubuttonwebapp)

**Subtype of**: MenuButton

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| type | String | Yes | Type of the button, must be web_app |
| text | String | Yes | Text on the button |
| web_app | WebAppInfo | Yes | Description of the Web App that will be launched when the user presses the button. The Web App will be able to send an arbitrary message on behalf of the user using the method answerWebAppQuery. Alternatively, a t.me link to a Web App of the bot can be specified in the object instead of the Web App's URL, in which case the Web App will be opened as if the user pressed the link. |
