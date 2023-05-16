
### Disable Snowsgiving Button
- (bugged) hides links in chat...
```
/* Disable Snowsgiving Button */
.anchorUnderlineOnHover-2qPutX{display:none}
```

### Disable Ping Icons
```
/* Disable Ping Icons */
.lowerBadge-3WTshO{display:none}
```

### Remove Channel Icons
```
/* Remove Channel Icons */
.icon-2W8DHg {display: none}
```

### Hide Friends Activity on Home
```
/* Hide Friends Activity on Home */
*[class^='nowPlayingColumn']{

display: none;

}
```

### Transparent Call Background
```
/* Transparent Call Background */
.wrapper-1gVUIN, .minimum-fXpVNc, .callContainer-HtHELf {
background: none!important;
}
```

### Change Discord Font
```
/* Change Font */
::placeholder, body, button, input, select, textarea {
font-family: "gabriola";

text-rendering: optimizeLegibility;

}
```

### Remove Offline Users
```
/* Remove Offline Users */
.offline-22aM7E{display:none}
```

### Remove Offline User gray-out
```
/* Remove Offline User gray-out */ /* Default opacity; .3 */
.offline-22aM7E {
    opacity: 1;
}
```

### Inset Messages
```
/* Inset Messages */
.message-2CShn3 {
	border: 1.5px inset #202225;
}
```

### Edit Users/Servers
##### (Should work with any image url.)
- Replace Profile Picture
```
[src^="https://cdn.discordapp.com/avatars/USER_ID/"] {
    content: url(URL_TO_IMAGE);
}
```
- Replace Server Icon
```
[src^="https://cdn.discordapp.com/icons/SERVER_ID/"] {
    content: url(URL_TO_IMAGE);
}
```
- Replace Emoji
```
[src^="https://cdn.discordapp.com/emojis/EMOJI_ID/"] {
    content: url(URL_TO_IMAGE);
}
```
