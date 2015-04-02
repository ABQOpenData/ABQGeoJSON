# ABQGeoJSON
GeoJSON files for ABQ Data. 
##Intent
The intent of this repo is to provide GeoJSON for Albuquerque Data that is not available as a REST Endpoint. But please feel free to add GeoJSON that is available because GitHub will automatically map the data and users who may not be able to map with code could benifit.

##Embed a Map in your Webpage
You can embed any of the maps here in your webpage using the code below. Just change the .geojson file name to the one you want to use.

```html
<html><head><title>GitHub GeoJSON as IFrame</title>
</head>
<body>
<h1>My Super Awesome Modern Minimalist Website</h1>
<p>It has some content here.
<script src="https://embed.github.com/view/geojson/ABQOpenData/ABQGeoJSON/master/cityparks_fromesrijson.geojson?height=600&width=1000"></script>
</body>
</html>
```
