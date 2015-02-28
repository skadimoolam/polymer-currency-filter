# polymer-currency-filter

### Currency Filter is plugin for Polymer Library to format Numbers in Currency format.

### Installation:

> Bower install polymer-currency-filter


### Usage:
`<link rel="import" href="[components]/polymer-currency-filter/polymer-currency-filter.html">`

### Examples

    {{ 169535.216 | currency }}

> $169535.22

    {{ 169535.216 | currency('USD$') }}

> USD$169535.22

    {{ 169535.216 | currency('USD$', 4) }}

> USD$169535.2160
