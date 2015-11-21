note: apiNG is under development and not ready for public usage

# apiNG

apiNG is an AngularJS directive for receiving and displaying data from different REST API's'.

## how does it work?

apiNG works as plugin platform.
 - **`plugins`**: receive some data (from REST API's) and convert this to any `model` and send the result to **apiNG**
 - **`designs`**: receive the result from **apiNG** and display the `model's` data

everybody can create `plugins`, `models` and `designs`

## current status

### plugins (sources/platforms)
 - [x] **Youtube** ([apiNG-plugin-youtube](https://github.com/JohnnyTheTank/apiNG-plugin-youtube))
    - converts results to this models: `social`, `video`
 - [x] **Instagram** ([apiNG-plugin-instagram](https://github.com/JohnnyTheTank/apiNG-plugin-instagram))
    - converts results to this models: `social`, `video`, `image`
 - [x] **Facebook** ([apiNG-plugin-facebook](https://github.com/JohnnyTheTank/apiNG-plugin-facebook))
    - converts results to this models: `social`, `video`, `image`, `event`
 - [ ] Twitter
 - [ ] Google+
 - [ ] Flickr
 - [ ] Vimeo
 - [ ] Tumblr
 - [ ] Vine
 - [ ] Spotify
 - [ ] GitHub
 - [ ] BandsInTown
 - maybe: EventFul (http://api.eventful.com/docs/formats)
 - maybe: Gigulate (http://gigulate.com/api/)
 - maybe: OpenLigaDB (http://www.openligadb.de/Help)
 - and much more coming soon ...
    
### models
 - [x] **social**
 - [x] **video**
 - [x] **image**
 - [x] **event**
 - [ ] post
 - [ ] news
 - [ ] product
 - [ ] activity
 - [ ] match
 - [ ] rank
 - and much more coming soon ...
    
### designs
 - [x] **[default](https://github.com/JohnnyTheTank/apiNG-design-default)**
 - [x] **[deadwood](https://github.com/JohnnyTheTank/apiNG-design-deadwood)** (youtube video design)
 - much more coming ...
 
## samples
create your own `plugin` or `design` from this samples:
- [apiNG-plugin-sample](https://github.com/JohnnyTheTank/apiNG-plugin-sample)
- [apiNG-design-sample](https://github.com/JohnnyTheTank/apiNG-design-sample)

# Contributors
- Jonathan Hornung ([JohnnyTheTank](https://github.com/JohnnyTheTank))
    - core system
