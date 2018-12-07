# Flag Images [![Build status](https://img.shields.io/circleci/project/Financial-Times/origami-flag-images.svg)](https://circleci.com/gh/Financial-Times/origami-flag-images)

An image set of world flags.

- [Usage](#usage)
- [Adding or modifying flags](#adding-or-modifying-flags)
- [Contact](#contact)
- [Licence](#licence)


## Usage

As with all image sets, these are available via the [Image Service](https://www.ft.com/__origami/service/image/v2).

To get a flag from the Image Service, use the following URL (replace the `product_source` with your product name and `flag_name` with the ISO ALPHA-2 country code for the place you want)

`https://www.ft.com/__origami/service/image/v2/images/raw/ftflag:{flag_name}?source={product_source}`

So to get Japan:
`https://www.ft.com/__origami/service/image/v2/images/raw/flag:jp?source=test`

### Getting these flags in a different format/size

The Image Service will convert these images on the fly if you pass in the right parameters. To find out more about this, please see the [Image Service documentation](https://www.ft.com/__origami/service/image/v2/docs/api)

## Adding or modifying flags

To keep flags consistent, please follow these guidelines:

- Flags must be SVG format
- Flags must be in a 4:3 aspect ratio
- Flags must be named according to their ISO ALPHA-2 country
- Flag names must be lower case
	- **good**: jp.svg, gb.svg
	- **bad**: japan.svg, JP.svg, jp

**Please do not delete flags without talking to the Origami team who will need to manage the deprecation process**

----

## Contact

If you have any questions or comments about this component, or need help using it, please either [raise an issue](https://github.com/Financial-Times/origami-flag-images/issues), visit [#ft-origami](https://financialtimes.slack.com/messages/ft-origami/) or email [Origami Support](mailto:origami-support@ft.com).

----

## Licence

This software is published by the Financial Times under the [MIT licence](http://opensource.org/licenses/MIT).

Icons in this repository are taken from [flag-icon-css](https://github.com/lipis/flag-icon-css), also published under the [MIT licence](src/flag-icon-LICENCE).
