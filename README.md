# FacebookAlbumToHTML
`FacebookAlbumToHTML.py` makes an html page out of a facebook album (capturing tags and captions).  Instructions are in comments. Visit https://developers.facebook.com/tools/explorer/ to get an access token. Guide to facebook-sdk for python at http://facebook-sdk.readthedocs.io/en/latest/api.html

Note that the script is designed to accommodate the default behavior of facebook albums:  jpgs download  with filename corresponding to index number + 1, with leading zeros to fill four digits (e.g., first element is 0001.jpg) 

The limit is set to 200 - if your album has more than 200 photos youll need to increase it.
