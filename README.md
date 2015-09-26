# s4-slack

This module is to be used as a sender/receiver connector for [s4 core.](https://github.com/studentrnd/s4-core)

## Initializing

```javascript
var SlackConnector = require('s4-slack'),
    slack = new SlackConnector(bot, "YOUR-SLACK-KEY");

// then attach the `slack` variable or whatever you named it to the bot.
```
