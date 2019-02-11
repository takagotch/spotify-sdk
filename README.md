### spotify-sdk
---
https://github.com/loverajoel/spotify-sdk

```js
user.me().then((myUser) => {
  myUser.playlists().then((playlistsCollection) => {
    playlistsCollection.first().tracks
    playlistsCollection.first().addTrack(trackEntity)
  });
});

import {Client, TrackHandler, PlaylistHandler} from 'spotify-sdk';

let client = Client.instance;
client.settings = {
  clientId: 'CLIENT_ID',
  secretId: 'SECRET_ID'
};

client.settings = {
  clientId: 'CLIENT_ID',
  secretId: 'SECRET_ID',
  scopes: [SCOPE, SCOPE2],
  redirect_uri: 'REDIRECT_URL'
};
client.token = 'TOKEN';
```

```
npm install
npm run watch
```

```
```

