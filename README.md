# Alfred-JSON - Freifunk Routerliste

Requires - jQuery 1.7.2+ ( apt-get install jq )

1. - edit the cron/get_data.sh file to your needs

2. - just run the script in cronjob every 5minutes

....

![Screenshot](http://map.ff-en.de/alfred-json.png)

 

Build with
--------

- Columns jQuery Plugin

Copyright (c) 2014 Michael Eisenbraun (http://jquery.michaeleisenbraun.com)
Version: 1.0.0
Requires: jQuery 1.7.2+

The Columns is a jQuery plugin for taking JSON data and creating a table that is sortable, searchable, and paginated.

BASIC INVOCATION:

        $(document).ready(function() {

                var json = [{"col1":"row1", "col2":"row1", "col3":"row1"}, {"col1":"row2", "col2":"row2", "col3":"row2"}];

                $('#columns').columns({data:json});

        });

REQUIRED:

data - Must be an Array of Objects

OPTIONAL:

page - Which page to display onload (Default: 1)

query - A search query to filter data (Default: null)

reverse - If true, sort data in reverse, sortBy must be set (Default: false)

schema - Custom structure of data (Default: null)

size - Number of rows to display per page (Default: 5)

sortBy - The column id in which to sort data (Default: null)


FOR MORE INFORMATION AND EXAMPLES:

http://jquery.michaeleisenbraun.com/columns
