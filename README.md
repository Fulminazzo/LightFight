# LightFight

> 🇮🇹 Sei italiano? 🇮🇹 
> Clicca [qui](https://github.com/Fulminazzo/LightFight-IT) per visualizzare la pagina in Italiano!

LightFight is a combat log plugin created with the cross compatibility in mind. In fact, it can be used from 1.8 through 1.18 and more upcoming versions! In here you will find a simple list of the most important features, but I suggest you carefully read the [Wiki](https://github.com/Fulminazzo/LightFight/wiki) to better understand how the plugin works.

## Functioning

LightFight is very simple: when a player gets hit by another entity and/or a player, she/he is put in Combat Mode, meaning that some actions (executing commands, flying, changing gamemode...) are blocked. All of these can be easily modified in the [config.yml](https://github.com/Fulminazzo/LightFight/wiki/Configuration) file to adapt these behaviours to your liking.

<div align="center">
    <img src="https://github.com/Fulminazzo/LightFight/blob/main/images/timer.png" alt="Timer Preview">
    <p style="line-height: 100px"><small>A very unpractical use of the entry <b>timer</b>.</small></p>
</div>

## Config

The [Configuration File](https://github.com/Fulminazzo/LightFight/tree/main/config.yml) is crucial to modify the plugin behaviour. In there you will find many available features that can be activated:
- **auto update** of the config.yml file;
- **PvE combat**: enable Combat Mode for entities;
- **auto respawn** on death;
- **grace period** for the player that just logged protecting from PvE and PvP;
- a list of **ignored worlds**;
- a list of **events** to be **disabled**;
- **barriers**;

and [more](https://github.com/Fulminazzo/LightFight/wiki/Configuration)!
<p align="center">
    <img src="https://github.com/Fulminazzo/LightFight/blob/main/images/enable.png" alt="Enable Preview">
</p>

## Commands

The plugin supports three main commands:
- [CTag](https://github.com/Fulminazzo/LightFight/wiki/Commands#ctag)
- [CUntag](https://github.com/Fulminazzo/LightFight/wiki/Commands#cuntag)
- [LightFight](https://github.com/Fulminazzo/LightFight/wiki/Commands#lightfight)

The first two commands allow to check and remove the Combat Mode for a user. The third command is the most important for admins: it allows to control and change how the plugin works or how the players interact with the world among them. The  ```LightFight```  command allows some subcommands that are explained [here](https://github.com/Fulminazzo/LightFight/wiki/Commands#lightfight).

<p align="center">
    <img src="https://github.com/Fulminazzo/LightFight/blob/main/images/ctag.png" alt="CTag Preview">
</p>

## Messages

LightFight also has a full list of messages that can be edited in the [messages file](https://github.com/Fulminazzo/LightFight/tree/main/messages.yml).

## Integrations

Both [PlaceholderAPI](https://github.com/PlaceholderAPI/PlaceholderAPI) and [WorldGuard](https://enginehub.org/worldguard) are supported. Not only the plugin offers many [placeholders](https://github.com/Fulminazzo/LightFight/wiki/Placeholders), but WorldGuard can be used to **set barriers** where the user in combat mode cannot enter (this will only happen if the region has the flag **pvp** set to **deny**).
