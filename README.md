Youtube-Playlist-Manager
========================

**This project is no longer in development**  
An advanced playlist manager for Youtube that lets you perform various batch actions.

**Open source under the [MIT](http://opensource.org/licenses/MIT) or [CC-BY-SA](https://creativecommons.org/licenses/by-sa/2.0/) license.**  
**Live Demo: [http://apps.elias.media/Youtube-Playlist-Manager](http://apps.elias.media/Youtube-Playlist-Manager)**

#####Features (implemented):

* Export playlists
* Remove duplicates
* Remove deleted videos

#####Features (planned):

* Sort playlists by date added
* Sort by tags

#####Dependencies:
* jQuery
* Underscore.js
* Backbone.js
* RequireJS
* Youtube API v3

##### Screenshot

![](https://i.imgur.com/SoBrgUo.png)

---

If you want to host this application yourself, you need to create your own API project [here](https://code.google.com/apis/console/)  
(also enable the Youtube API v3) and then replace the `client_id` with yours [here](https://github.com/elias-schuett/Youtube-Playlist-Manager/blob/master/js/utils.js#L11).
