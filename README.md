# uptimestats

A script for generating uptime statistics.

## Prerequisites

To run uptimestats, you must first install the following tools:

- [python-systemd](https://github.com/systemd/python-systemd)

### Install dependencies

#### openSUSE

`$ sudo zypper install python3-systemd`

#### Ubuntu

`$ sudo apt install python3-systemd`

## Usage

```
> uptimestats
Initial Boot Timestamp: 2018-10-07 10:54:28

   Wake Timestamp    |   Sleep Timestamp   | Awake Time | Wake From
 ------------------- | ------------------- | ---------- | ---------
 2018-10-07 10:54:28 |    (Still Awake)    |   10h  8m  | S5 (boot)
 ------------------- | ------------------- | ---------- | ---------

Days Since Boot: 0.42 - Days Awake: 0.42 - Wake/Sleep Cycles: 0

```

## License

Licensed under MIT license. See [LICENSE](LICENSE) for more information.

## Authors

* Johan Gardhage
