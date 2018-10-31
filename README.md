# Navigation stats extension
This extension is based an example from MDN (https://github.com/mdn/webextensions-examples/tree/master/navigation-stats),
but I've tweaked it and added some features. Firstly, the original extension
only showed the top 5 most visited domains, so I added a button to see all the
domains visited. I also added protocol tracking (HTTP/HTTPS) and display this
information as a percentage of web pages visited that use HTTPS. I also added
some CSS just to make the popup look slightly nicer.

The purpose of developing this extension is to familiarise myself with the
extension ecosystem, specifically the web-extensions APIs.