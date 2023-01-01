# 🤝 Trystero

**Serverless WebRTC matchmaking for painless P2P: make any site multiplayer in a
few lines**

Making a project and want all the js stored locally, instead of opaquely accessing a CDN every time?

Well , me too.  After eleventy hours of tracking down what was downloading what and from where, and changing the import statements in the modules to point to the right files, I arrived at this.

To use, just clone this repo, and start the `<script>` tag in your html like so:

```
<script type='module'>

import {joinRoom} from "/lib/trystero/torrent.js"
import {s as selfId} from "/lib/common/crypto.js"
```

From then on out, everything is identical to having used the CDN.
