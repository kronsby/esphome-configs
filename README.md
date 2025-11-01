# ESPHome Configs

This is where I keep my esphome configs. Most are really simple basic configs,
but sometimes I get a little crazy with it.

## ESPHome Instructions

### Create a project

```
docker run --rm -v "${PWD}":/config -it esphome/esphome wizard livingroom.yaml
```

### Upload over USB

```
docker run --rm -v "${PWD}":/config --device=/dev/ttyUSB0 -it esphome/esphome run livingroom.yaml
```

### Upload over WiFi
docker run --rm -v "${PWD}:/config -it esphome/esphome run livingroom.yaml
