<!-- Title -->
<h1 align="center">License Manager</h1>
  <p align="center">
    This is an simple License manager for tech groups.
    <br />
</h1>

<!-- Getting Started -->

## 🛠 Getting Started

To get a local copy up and running follow these simple steps.
<br/>

<!-- Installation -->

### **Step 1:** Setup / Installation

1. Clone the repository

```sh
git clone https://github.com/IsEmil/license-manager.git
```

### **Step 2:** Setup / Installation

2. Install NPM packages

```sh
npm install
```

### Configurations

Edit the config.js file and insert your credentials

```js
module.exports = exports = {
    port: 8080,
    db: "", // Input your MongoDB URL.

    discord_token: "", // Input your Discord bot token.
    discord_secret: "", // Input your Discord bot secret token.

    guild_id: "", // Input the guild id of the server you want to use this bot on. (Slash Commands)
    guild_staff_id: "", // Input the guild id of the server you want to use for Logs and Purchase channel.
    purchase_channel: "",  // Input the purchase channel id.
    log_channel: "",   // Input the log channel id.
}
```

<br/>

<!-- License -->
## License

Copyright © 2022 Emil (hi@isemil.me)

Distributed under the MIT License. See `LICENSE` for more information.
