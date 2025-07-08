# What is badgeKit?
badgeKit is a collection of standards pertaining to electronic conference badges (i.e. DEF CON or Supercon) as well as SAOs (Shitty Add-Ons).

badgeKit's objective is to serve as a beginner-friendly toolkit for badgemakers, reducing time-to-implementation for common embedded device features and functions and making them more approachable, such that new makers don't have to dedicate large amounts of time to learning a particular technology to take part in the #badgelife community and get their first project across the finish line, with a result they can be proud of.

We believe you should only spend a week learning the intricacies of BLE and GATT characteristics if you want to! If you want to skip the fluff and get to the good stuff, and simply announce your device's presence to another device, you shouldn't have to.

# The Plan
## badgeKit\ID (Stage 1)
We will start by providing a standard language for badge and add-on identification and capabilities advertisement, called badgeKit\ID, with the intent of allowing common team and device identifiers to be used across the various badgeKit protocols. This will be necessary for the next stages of the project.

badgeKit\ID will provide an API via the https://badge[.]life website, where metadata describing a particular device can be registered and queried. The full database will also be able to be downloaded and embedded for quick and offline lookups, if necessary. This metadata will also be used to populate https://badge[,]life/archive, where we will host a historical archive of all #badgelife badges!

## Intercommunication (Stage 2)
Once badgeKit\ID is ratified, we will begin building out platform-specific libraries and code examples to make use of these IDs in a consistent manner over intercom protocols like I2C, BLE, WiFi, etc, across common MCU platforms like ESP8266, ESP32, RP2040 (Raspberry Pi Pico), STM32, and more.

## Modules (Stage 3)
Eventually, we will provide additional badgeKit "modules", providing instruction on best practices and continuing to simplify other advanced topics. These modules might include schematics, gerbers, footprints, 3d models, component recommendations, and/or documentation on best practices across different #badgelife use cases, such as..

badgeKit\SAO - Defining the SAO standard implementation specifics, as well as how to add proper SAO support to your badge
badgeKit\OTA - Secure OTA (Over-The-Air) firmware updating
badgeKit\coinCell - Considerations for designing a low-power device to run off a coin cell
badgeKit\usbC-PD - Schematics, footprints and a BOM for adding a USB-PD-compatible power supply to your project.

These badgeKit "modules" will serve as a proven set of building blocks you can utilize to base your project upon.

## Ownership and Contribution
#badgelife is a grassroots community phenomenon and is owned by no one. In the same vein as both #badgelife itself and webkit, badgeKit aims to serve as a hub for all #badgelife groups to contribute and iterate upon best practice code and standards and for common badge and add-on functions. All original badgeKit resources and code will always be open source and free to use in your projects. For any libraries badgeKit did not create but makes use of, please refer to that project's license documentation for usage rights.

badgeKit is a community effort! If you don't see a feature we should have, open an issue and suggest it! If you don't yet see support for your favorite platform, consider porting the existing branches to your platform, and contribute a pull request!

## Thanks
Many thanks to HCAdam and RJP5th, Rare Circuits, and the DEF CON Aerospace village for leading the charge on badgeKit\I2C and parts of the next iteration of SAO!
Thanks to everyone in our very active community over at https://discord[.]badge[.]life. Your dicussions, participation and contributions move the hobby forward!
-@ReanimationXP
