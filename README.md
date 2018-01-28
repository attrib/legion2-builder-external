# Legion TD2 Builder (external)

This is a testing repo to use [legion2-builder](https://github.com/attrib/legion2-builder) in an external lib.

See [index.html](index.html) how this could be used.

http://localhost:8088/ needs to be replaced with [https://attrib.github.io](https://attrib.github.io) as this is also 
the repository to test before releasing new stuff.

For issues or more settings please create issues at [legion2-builder/issues](https://github.com/attrib/legion2-builder/issues)

## LegionTD2Builder object

In the LegionTD2Builder object some settings can be changed.

    <script type="application/javascript">
        var LegionTD2Builder = {
            containerId: 'someId',
            gaId: 'google-analytics-id'
        };
    </script> 


### containerId

The id of the div where the builder should be added.

### gaID

Can be empty or add your google analytics id, if you want to track page changes.
The gaID usually has the format like UA-xxxxxxxx-x
