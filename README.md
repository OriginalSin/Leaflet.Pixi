Allows a Leaflet TileLayer to delegate and interacte with a pixi.js scene.

There is a [demo](http://todo] available, which shows x/y/z

Current state of the project: Incomplete! All work in the develop branch until something is working will be available in master.

# Dependencies

Attempting to be compatible with either or both Leaflet 0.7 or 1.0-beta. TBD.

# Usage

The plugin extends the core `L.TileLayer` class.


```
var pixiTileLayer = L.TileLayer.pixiTileLayer({option: 1, option 2}); 
```

Options available are as follows:

* `option1`: set to true in order to enable the cache. This option must be set at initialization time.

Additional `L.TileLayer` events available are as follows:

* `event1`
* `event2`

# Credits / Inspiration

* [Displaying WebGL on Bing Maps (using Pixi.js)](http://build-failed.blogspot.com/2015/01/displaying-webgl-on-bing-maps-using.html)