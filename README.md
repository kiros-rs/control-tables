# Robotis control tables
This repository contains every control table available on the [Robotis E-Manual](https://emanual.robotis.com/), scraped by the [dynamixel-scraper](https://github.com/kiros-rs/dynamixel-scraper) tool. If there is an issue with the tables, please [open a ticket in the dynamixel-scraper repository](https://github.com/kiros-rs/dynamixel-scraper/issues/new). If there is an issue with the library itself, please [open a ticket on this repository](https://github.com/kiros-rs/control-tables/issues/new).

If you would like to download the tables in a particular format, please see the artifacts under the latest [daily action](https://github.com/kiros-rs/control-tables/actions/workflows/daily.yml) workflow run.
Currently supported formats:
- CSV
- [RON](https://github.com/ron-rs/ron) ([see the `ControlTableData` struct](https://github.com/kiros-rs/dynamixel-scraper/blob/main/src/serialize.rs))

Hopefully this helps you when working with Dynamixel actuators!
