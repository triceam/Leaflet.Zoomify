# HTML Zoomify

Use this template to export zoomified images with an HTML renderer directly from Photoshop. Detailed instructions and samples available at:
http://www.tricedesigns.com/2013/10/17/photoshop-zoomify-in-html-powered-by-leaflet/

Just add the following files to the "Presets/Zoomify" directory inside of your Photoshop installation, and then restart Photoshop.  On OS X, with the default configuration, these files should be located in /Applications/Adobe Photoshop CC/Presets/Zoomify

Files to be copied:
* L.TileLayer.Zoomify.js
* Zoomify Leaflet HTML.zvt
* leaflet.css
* leaflet.js   

Once you have restarted Photoshop, just open the file that you want to export, then go to File->Export->Zoomify, and select the "Zoomify Leaflet HTML" template.   You'll need to select an output location, enter a base name, and specify the image quality for the tiles, however you can ignore the "Browser Options" width and height.  The Leaflet template is configured to take 100% width and 100% height of the available viewport of the HTML page.

This HTML template is based upon the open source Leaflet map rendering library, which is very good at rendering image tiles, especially on mobile devices.   We don't need the full GIS APIs, however it handles all of the touch, mouse, and keyboard interactivity that we need.

## Sources

This zoomify template uses the following open source projects:

* [Leaflet map engine](http://leafletjs.com/) 
* [Leaflet.Zoomify](https://github.com/turban/Leaflet.Zoomify) - A tile layer to display Zoomify-style image tiles within the leaflet web mapping engine


