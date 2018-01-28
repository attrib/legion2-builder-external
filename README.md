# Legion TD2 Builder (external)

This is a testing repo to use [legion2-builder](https://github.com/attrib/legion2-builder) in an external lib.

See [index.html](index.html) how this could be used.

For issues or more settings please create issues at [legion2-builder/issues](https://github.com/attrib/legion2-builder/issues)

## LegionTD2Builder object

In the LegionTD2Builder object some settings can be changed.

    <script type="application/javascript">
        var LegionTD2Builder = {
            containerId: 'someId',
            basePath: '/builder',
            gaId: 'google-analytics-id'
        };
    </script> 


### containerId

The id of the div where the builder should be added.

### gaID (optional)

Can be empty or add your google analytics id, if you want to track page changes.
The gaID usually has the format like UA-xxxxxxxx-x

### basePath (optional)

Set a basePath if the builder is not running on the main page. Defaults to "/".

### iconsPath (optional)

Set the path of the Icons folder, e.g. "images/Icons". Defaults to "/Icons".