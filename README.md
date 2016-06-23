# Google Map Showing Multi Kml Layer

There is a limit on the number of KML Layers that can be displayed on a single Google Map. If you exceed this limit, none of your layers will appear on the map. The limit is based on a combination of the number of KMLLayer classes created and the total length of all the URLs used to create those layers. Each new KMLLayer you create will take up a portion of the limit for the layer and a further portion of the limit depending on the length of the URL where the KML file was loaded from. Consequently, the number of layers you can add will vary by application; on average, you should be able to load between 10 and 20 layers without hitting the limit.
# Demo URL
  - https://appdevexpress.firebaseapp.com/
