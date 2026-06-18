# Type: PollMedia

**Category**: Available types

**Description**: At most one of the optional fields can be present in any given object.

**Link**: [Official Documentation](https://core.telegram.org/bots/api#pollmedia)

### Fields

| Field | Type | Required | Description |
|---|---|---|---|
| animation | Animation | Optional | Optional. Media is an animation, information about the animation |
| audio | Audio | Optional | Optional. Media is an audio file, information about the file; currently, can't be received in a poll option |
| document | Document | Optional | Optional. Media is a general file, information about the file; currently, can't be received in a poll option |
| link | Link | Optional | Optional. The HTTP link attached to the poll option |
| live_photo | LivePhoto | Optional | Optional. Media is a live photo, information about the live photo |
| location | Location | Optional | Optional. Media is a shared location, information about the location |
| photo | Array of PhotoSize | Optional | Optional. Media is a photo, available sizes of the photo |
| sticker | Sticker | Optional | Optional. Media is a sticker, information about the sticker; currently, for poll options only |
| venue | Venue | Optional | Optional. Media is a venue, information about the venue |
| video | Video | Optional | Optional. Media is a video, information about the video |
