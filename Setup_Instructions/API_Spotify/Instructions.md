# Installation instructions for API's, webscraping...
prepared by **Florian Titze**

What we need:

- **BeautifulSoup**, a powerful webscraping library. Install it into your conda environment with ```conda install -c anaconda beautifulsoup4```

- **requests**, a library to send HTTP requests. Install it with ```conda install -c anaconda requests```

- **spotipy**, an API wrapper library to conveniently access the Spotify API in Python. We need that towards middle of the week. Install via ```conda install -c conda-forge spotipy```

- **A spotify account**. Not a paid one. A free one will be just fine. Although you can use your existing one, if you already have one. Nontheless, It is better to have seperate spotify developer account and not using your normal spotify account.

In order to get access to the Spotify API (on Wednesday I think), we need to get our own ```client_id``` and ```client_secret``` (never share these with anyone and don't upload it to github. You can reset the secret though, if you have accidentally published it). To get it, go to [developer.spotify](https://developer.spotify.com/dashboard/login) , login with your account credentials, accept the terms of conditions. In the following click on "create an app". Give it a name, check that you understand the TOS. That green rectangle that now appears is your app (see screenshots). Click it, and in there you need to copy your client_id and client_secret.

In a Jupyter Notebook or in any Python file, you can connect to the API using the spotipy wrapper via

```
import spotipy
from spotipy.oauth2 import SpotifyClientCredentials


c_id = "your client id goes here"
c_se ="your client secret goes here"

sp = spotipy.Spotify(auth_manager=SpotifyClientCredentials(client_id=c_id, client_secret=c_se))
```

then the world of Spotify data is all yours, if you operate on that ```sp``` variable grinning - well, within the API limitations haha.
Check here for the [Spotipy documentation](https://spotipy.readthedocs.io/en/2.19.0/#module-spotipy.client) and/or the [Getting started section](https://spotipy.readthedocs.io/en/2.19.0/#getting-started).

```Note: check the screenshots in the folder```
