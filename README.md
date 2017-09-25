# ModularServer

Authors:

    Peter Polidoro <polidorop@janelia.hhmi.org>

License:

    BSD

This firmware requires at least Arduino Mega level resources, although Teensy
3.x level resources are preferred. Known to work with the Arduino Mega 2560,
Teensy 3.2, Teensy 3.5, and Teensy 3.6.

## Converting Between File Formats

```shell
pandoc -f markdown_github -t org -o README.org README.md
```

## API NAMES

```json
{
  "id":"getApi",
  "result":{
    "firmware":["ModularServer"],
    "verbosity":"NAMES",
    "functions":[
      "getDeviceId",
      "getDeviceInfo",
      "getApi",
      "getPropertyDefaultValues",
      "setPropertiesToDefaults",
      "getPropertyValues",
      "getInterruptInfo",
      "detachAllInterrupts"
    ],
    "parameters":[
      "firmware",
      "verbosity"
    ],
    "properties":[
      "serialNumber"
    ]
  }
}
```

## API GENERAL

[API GENERAL](./api/)

## More Detailed Modular Device Information

[modular-devices](https://github.com/janelia-modular-devices/modular-devices)

## Install Library Dependencies

[arduino-libraries](https://github.com/janelia-arduino/arduino-libraries)
