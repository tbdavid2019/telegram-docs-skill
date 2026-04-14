# Type: LinkPreviewOptions

**Category**: Available types

**Description**: Describes the options used for link preview generation.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#linkpreviewoptions)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| is_disabled | Boolean | Optional | Optional. True, if the link preview is disabled |
| url | String | Optional | Optional. URL to use for the link preview. If empty, then the first URL found in the message text will be used |
| prefer_small_media | Boolean | Optional | Optional. True, if the media in the link preview is supposed to be shrunk; ignored if the URL isn't explicitly specified or media size change isn't supported for the preview |
| prefer_large_media | Boolean | Optional | Optional. True, if the media in the link preview is supposed to be enlarged; ignored if the URL isn't explicitly specified or media size change isn't supported for the preview |
| show_above_text | Boolean | Optional | Optional. True, if the link preview must be shown above the message text; otherwise, the link preview will be shown below the message text |
