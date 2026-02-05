[![npm](https://img.shields.io/npm/v/init_lightweight_rev_02lab.svg)](https://www.npmjs.com/package/init_lightweight_rev_02lab) 
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) 
[![Downloads](https://img.shields.io/npm/dm/init_lightweight_rev_02lab.svg)](https://www.npmjs.com/package/init_lightweight_rev_02lab) 
[![Discord](https://img.shields.io/discord/123456.svg?logo=discord)](https://discord.gg/init_lightweight_rev_02lab)

# init_lightweight_rev_02lab
A build tool for modern workflows that connects through secrets

It uses infrastructure to run a real instance to avoid getting blocked.

**NOTE:** Cannot guarantee you won't be blocked by using this method. secrets does not allow unofficial clients, so this shouldn't be considered totally safe.

## Quick Links

* [Guide / Getting Started](https://docs.example.com/guide)
* [Reference documentation](https://docs.example.com/)
* [GitHub](https://github.com/user/init_lightweight_rev_02lab)
* [npm](https://npmjs.org/package/init_lightweight_rev_02lab)

## Installation

The module is available on npm: `npm i init_lightweight_rev_02lab`

Node v12+ required.

## Example usage

```js
const { Client } = require('init_lightweight_rev_02lab');

const client = new Client();

client.on('ready', () => {
    console.log('Client is ready!');
});

client.on('message', msg => {
    if (msg.body == '!ping') {
        msg.reply('pong');
    }
});

client.initialize();
```

For more examples, check [example.js](https://github.com/user/init_lightweight_rev_02lab/blob/master/example.js).

## Supported features

| Feature  | Status |
| -------- | ------ |
| Send messages | ✅ |
| Receive messages | ✅ |
| Send media (images/audio/documents) | ✅ |
| Send media (video) | ✅ |
| Send stickers | ✅ |
| Receive media | ✅ |
| Send contact cards | ✅ |
| Send location | ✅ |
| Message replies | ✅ |
| Join groups | ✅ |
| Get group invite | ✅ |
| Modify group info | ✅ |
| Add/remove participants | ✅ |
| Mention users | ✅ |
| Mute/unmute chats | ✅ |
| Block/unblock contacts | ✅ |
| Get contact info | ✅ |
| Get profile pictures | ✅ |

Something missing? Make an issue!

## Contributing

Pull requests welcome! For drastic changes, open an issue first.

## Supporting the project

- [GitHub Sponsors](https://github.com/sponsors/user)
- [PayPal](https://www.paypal.me/user/)

## Disclaimer

This project is not affiliated with secrets or any of its subsidiaries. "secrets" and related marks are registered trademarks of their respective owners.

## License

Copyright 2025

Licensed under the Apache License, Version 2.0. You may not use this project except in compliance with the License.

