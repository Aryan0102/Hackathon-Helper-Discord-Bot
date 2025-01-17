# Discord Hackathon Bot

A feature-rich bot designed for managing hackathon-related activities within a Discord server. This bot includes a wide range of functionalities, including clearing messages, timezone conversion, sending reminders, language translation, and user identity management.

## Features

### 1. **Clearing Messages**
- `clear`: Clears the 5 latest messages in the channel.
- `clearall`: Clears all messages in the channel.
- `clearmember (Member)`: Clears messages from a specific member.
- `clearself`: Clears messages from the invoking user.

### 2. **Timezone Management**
- `timezones`: Displays a list of available timezones.
- `convertTZ (time, starting timezone, ending timezone)`: Converts a given time to a specific timezone.

### 3. **User Identity Management**
- `createID`: Collects and generates a shareable identity card for the user based on their information.
- `loadID`: Loads the identity card for the user.
- `editInfo`: Admin command for modifying message content displayed on the identity card.

### 4. **Message Export**
- `export`: Creates a `.txt` file of all messages in the channel and sends it as an attachment.

### 5. **Timers and Reminders**
- `timer (time in minutes)`: Sets a timer for a specified number of minutes.
- `remind (time in minutes, message, user)`: Sends a timed reminder message to a user.

### 6. **Language Translation**
- `translate (targetlanguage, message)`: Translates a message into the specified language.
- `translationlist`: Displays all supported languages for translation.

### 7. **Miscellaneous Commands**
- `defaultchannel`: Sets the default channel for bot messages (Admin only).
- `DM`: Sends a direct message to a specified user.
- `on_member_join`: Announces when a new member joins the server.
- `on_member_remove`: Announces when a member leaves the server.
