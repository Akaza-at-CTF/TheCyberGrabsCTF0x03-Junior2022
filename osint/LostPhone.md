# Lost Phone

> I lost my phone, this is the last tower id \nMCC: 404\nMNC: 56\nLAC: 391\nCID: 64284 \nit sent to my server, could you tell the location ? flag{x,y} up to 2 decimal places".

Search for the cell ID using [this site](https://www.opencellid.org/) with the given information.

- MCC: 404
- MNC: 56
- LAC: 391
- CID: 64281

The latitude and longitude values appear in the url. Truncate them to 2 decimal places (no rounding). The flag is `flag{28.41,77.58}`
