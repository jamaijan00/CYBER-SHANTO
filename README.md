[
    {
        "key": "dbln",
        "value": "%7B%2261578094682569%22%3A%22QGl2arVv%22%7D",
        "domain": "facebook.com",
        "path": "/login/device-based/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "datr",
        "value": "vbmlaG22CWr4MkrqLP0Wyzel",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "sb",
        "value": "vbmlaDB2fI3FLURuHKWxXP5d",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "pas",
        "value": "61578094682569%3AobihGmt4yI",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "vpd",
        "value": "v1%3B663x360x2",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "ps_l",
        "value": "1",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "ps_n",
        "value": "1",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "c_user",
        "value": "61578094682569",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "xs",
        "value": "7%3AIgDD10dRZHUN2Q%3A2%3A1756890206%3A-1%3A-1",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "fr",
        "value": "0sH3ksKBeDMp1zWEh.AWe84wTy2mFOCQ0zatjuwDspK-IRzl-Me635KLF9extrEkYqk4c.Bopbm9..AAA.0.0.BouGD1.AWcH9WtZeB4wvwftnJwY1HX4FbU",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "locale",
        "value": "en_GB",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "fbl_st",
        "value": "100420939%3BT%3A29284822",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    },
    {
        "key": "wl_cbv",
        "value": "v2%3Bclient_version%3A2913%3Btimestamp%3A1757089341",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-09-05T16:23:22.251Z",
        "lastAccessed": "2025-09-05T16:23:22.251Z"
    }
]🔧 Custom console logging (see configs/console.js)
🚫 Spam prevention in ban system
💎 Premium-only commands (enable with premium: true in command config)

⚙️ CONFIGURATION

File	Description

IMRAN.js	Auto restart and pending message handler
config.json	Bot name, prefix, admins, operators, etc.
appstate.json	Facebook login/session state


🔐 BOX APPROVAL SYSTEM

Enable in config.json:

"approval": true

Usage examples:

approve list
approve box 1234567890
approve remove 1234567890

📥 HOW TO GET appstate.json

Use the FBState Exporter extension to export your Facebook login session:

Steps:

1. Download FBState Exporter here


2. Open with Kiwi Browser


3. Load as an Extension


4. Login to Facebook


5. Open the extension and click “Copy fbstate”


6. Paste the copied data into a file named appstate.json



🧠 ADDING A COMMAND

Example command template:

module.exports.config = {
  name: "example",
  version: "1.0.0",
  permission: 0,
  credits: "SAKIB VAI",
  description: "An example command",
  prefix: true,
  category: "utility",
  usages: "example [args]",
  cooldowns: 5,
  premium: false,
  dependencies: {}
};

module.exports.run = async ({ api, event, args }) => {
  api.sendMessage("Hello from example command!", event.threadID);
};

🧩 UPCOMING FEATURES

⏩ Command aliases
🔒 Encrypted state manager
📊 Dashboard system for logs and analytics

📁 RESOURCES

GitHub Repository: Sakib-ai

> 💬 Developed with care by Sakib Vai & Ryuko

Let me know if you want me to help with anything else!

