# Wii U Dark Mode

This is a simple plugin that makes the Wii U menu dark. It is an adaptation of [DarkU](https://github.com/vincent-coding/DarkU) that does not require external devices.

## Wii U Plugin System
This is a plugin for the [Wii U Plugin System (WUPS)](https://github.com/Maschell/WiiUPluginSystem/). To be able to use this plugin you have to place the resulting `.mod` file into the following folder:

```
sd:/wiiu/plugins
```
When the file is placed on the SDCard you can load it with [plugin loader](https://github.com/Maschell/WiiUPluginSystem/).

## Building:

For building you need: 
- [wups](https://github.com/Maschell/WiiUPluginSystem)
- [wut](https://github.com/decaf-emu/wut)
- [libutilswut](https://github.com/Maschell/libutils/tree/wut) (WUT version) 

Install them (in this order) according to their README's. Don't forget the dependencies of the libs itself.

Steps to build:
1. run `git clone https://github.com/jacquesCedric/WUPS_dark_mode_plugin`
2. `cd` into the folder
3. run `make`
4. copy `WUPS_dark_mode_plugin.mod` to `sd:/wiiu/plugins`



