# ZMK config for Tornblue keyboard

A ZMK module/config repo that attempts to update [the ZMK definition](https://github.com/rtitmuss/zmk/tree/tornblue_r1/app/boards/arm/tornblue) for the [Tornblue keyboard](https://github.com/rtitmuss/tornblue) in order to get it working with latest ZMK.

Not tested, but in theory supports keys, underglow, and both left and right encoders. The layer indicator LEDs are not supported.

## Usage

You can either fork this repo and edit `config/tornblue.*` files, or create a new blank config repo and refer to this repo as a Zephyr module in your `config/west.yml`.
In the latter case you won't have to keep a copy of the board definition in your repo.
