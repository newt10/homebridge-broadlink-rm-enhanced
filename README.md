# Homebridge Broadlink RM Community

## Introduction
Welcome to the Broadlink RM Mini and Broadlink RM Pro plugin for [Homebridge](https://github.com/nfarina/homebridge).

This is a fork of the [original plugin by Luke Rhodes] (https://github.com/lprhodes/homebridge-broadlink-rm) that allows you to control your RM Mini and RM Pro with HomeKit using the Home app and Siri.

### About this fork
I am working on upgrades to the accessory specifications in this repository. For starters I am focused on fan, air-conditioners and heater accessories to help improve the user experience of the devices like portable ACs, Lasko tower fans and tower heaters, etc.

I eventually would like to add multiple contibuters who can review and integrate PRs hence the "community" tag here so more people can collectively extend the accessories.

If you want to use this fork, use this command:

`npm i -g homebridge-broadlink-rm-community`

## Like this plugin?

Please consider testing it and providing feedback. This project is built on top of the labor of many folks so please feel free to show your support to them as well.

Thank you!

## Documentation

### Orignial
Full documentation can be found [here](https://lprhodes.github.io/slate/).

### Enhancements

#### Fan Accessory
##### Fan speed step size property
Improves user experience of changing fan speeds to pre-defined steps in the Home app.

<img src="https://j.gifs.com/L7oJQX.gif" alt="Home app fan speed UI in action" width="150"/>


Add under the data section of the fan accessory in config.json as shown in the config-sample.json
| key | description | example | default |
|--|--|--|--|
| stepSize | Increments of fan speed. This will update Home app UI so that fan speed increases in steps. If your fan support 4 speeds and the step size should be 100/4 = 25. | 25 | 1 |

## Thanks
Thanks to @lprhodes (https://github.com/lprhodes/homebridge-broadlink-rm), @kiwi-cam (https://github.com/kiwi-cam/homebridge-broadlink-rm), @tattn (https://github.com/tattn/homebridge-rm-mini3), @PJCzx (https://github.com/PJCzx/homebridge-thermostat) @momodalo (https://github.com/momodalo/broadlinkjs) whose time and effort got me started.