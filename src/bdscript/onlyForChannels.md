# $onlyForChannels
The command can only be executed in the provided channels.

## Usage
```
$onlyForChannels[channelIDs;...;errorMessage]
```

### Parameters 
- `channelIDs` `(Type: Snowflake || Flag: Emptiable)`: The channels that the command can be executed in. Separate the IDs using `;`.
- `errorMessage` `(Type: String || Flag: Emptiable)`: The message that is returned when the command is used in a non-whitelisted channel.
