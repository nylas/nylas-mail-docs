# How do I increase the font size in Nylas Mail?

Nylas Mail doesn't officially support changing the font size. However, for some displays and Linux machines, it's necessary to increase the scale of the UI to make Nylas Mail more usable.

You can scale up the entire interface of Nylas Mail by opening your config file at ~/.nylas/config.json, and adding a value greater than 1 for `core.workspace.interfaceZoom` (1.2 = 120%, 1.4 = 140%, etc.), like this:  

    {

      "*": {

        "env": "production",

        "core": {

          "workspace": {

              "interfaceZoom": 1.2

          },

          "themes": [

            "ui-light"

          ],

          .....

You can also do a global search and replace for .snippet-and-labels .snippet and make it .snippet-and-labels .snippet {\n font-size: 16px;...

That's because I noticed one of the tags I needed to change was "snippet" or "snippet-and-labels". This changed all the compile-cache files. 

In thread.less you can also make this change:

.participants,
.timestamp {
font-size: 16px;
}
.subject {
color: [#000000](/agent/tickets/000000);
font-size: 16px;


