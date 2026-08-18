# breezewiki-quay

A [BreezeWiki](https://gitdab.com/cadence/breezewiki) image, on Quay.

[Quay page](https://quay.io/repository/pussthecatorg/breezewiki) | [GitHub page](https://github.com/PussTheCat-org/docker-breezewiki-quay)

This image mostly exist for the [PussTheCat.org](https://pussthecat.org/) [instance](https://breezewiki.pussthecat.org/), but others are free to use it.

## Usage:

- Download (or copy the content of) the [`docker-compose.yml`](./docker-compose.yml). 
- Download (or copy the content of) the [`config.ini` from this repository](./config.ini).
- Customize the [config.ini file](https://docs.breezewiki.com/Configuration.html#(part._.Example)) how you want. You may also use [environment variables](https://docs.breezewiki.com/Configuration.html#(part._.Environment_variables)).
- Move both files to the folder you want.
- `docker-compose up -d`
