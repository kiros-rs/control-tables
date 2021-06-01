# Robotis Dynamixel control tables
This repository contains every control table available on the [Robotis E-Manual](https://emanual.robotis.com/), scraped by the [dynamixel-scraper](https://github.com/kiros-rs/dynamixel-scraper) tool. If there is an issue with the tables, please [open a ticket in the dynamixel-scraper repository](https://github.com/kiros-rs/dynamixel-scraper/issues/new).

Currently used formats:
- CSV
- [RON](https://github.com/ron-rs/ron)

The RON tables are a serialized version of the [`ControlTableData` struct](https://github.com/kiros-rs/kiros/blob/master/movement/src/dynamixel/mod.rs) used by [KIROS](https://github.com/kiros-rs/kiros).

Hopefully this helps you when working with Dynamixel actuators!
