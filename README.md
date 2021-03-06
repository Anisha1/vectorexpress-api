<img alt="Logo" src="onlight.png" width=300>

# Vector Express - Free Vector Converting API
### Update 2019 - Now SSL secured

https://vector.express

Vector Express is a free website and API for converting vector files. Made with love by [@Smidyo](https://twitter.com/smidyo)

Runs a combination of Inkscape, SVGO and a custom made Autocad converter under the hood.

## API

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/0f29a3f11f39cae080da)

You can use our free API in your projects.

Useage is simple, just provide your file in the form field `file` and your desired extension in the querystring `toextension` The API will return a file.

Examples:

POST `https://vector.express/api/public/vectorconvert?toextension=optimizedsvg`

POST `https://vector.express/api/public/vectorconvert?toextension=svg`

POST `https://vector.express/api/public/vectorconvert?toextension=eps`

POST `https://vector.express/api/public/vectorconvert?toextension=pdf`


### Limits

Max filesize is 10MB and the hourly limit is 20 files. We reserve the right to change this at any point.


### Supported formats

At the moment we can convert from these formats:

- svg
- pdf
- ai
- cdr
- eps
- ps
- hpgl
- plt
- dxf
- dwg

..to these formats

- svg
- optimizedsvg (svg that is optimized with SVGO)
- eps
- pdf

## Feedback

Feel free to open up an issue, or just tweet at us. Or mail us! frank@smidyo.com  
