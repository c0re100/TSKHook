# TSKHook

Twinkle Star Knights mod for DMM Game Player version

## Feature

1. Game speed (more fun if Ready Go is faster, is not?^^)
   ![3x speed](3x.gif)
2. In-game Screenshot
3. FPS setting

## Requirement

1. Windows 10 or newer
2. Twinkle Star Knights DMM Game Player version

## Installation

Download and extract [Release](https://github.com/c0re100/TSKHook/releases) zip to your Twinkle Star Knights install location `C:\Users\<username>>\Twinkle_StarKnightsX)`

## Config

You can edit config.json(`./BepInEx/plugins/config.json`) if you don't like default settings.

| Name  | Default Value | Description                                                  |
|-------|---------------|--------------------------------------------------------------|
| speed | 0.5           | Increase/Decrease game speed each step (per click)           | 
| fps   | 60            | Override FPS setting, take effects when value bigger than 60 |

## Key binding

| Key  | Type       | Description                                                                   |
|------|------------|-------------------------------------------------------------------------------|
| F5   | Freeze     | Freeze game, mean set game speed to 0x                                        |
| F6   | Reset      | Reset game speed to 1x/normal                                                 | 
| F7   | Decrease   | Decrease game speed (2-0.5 etc), depends on your `speed` config               | 
| F8   | Increase   | Increase game speed (1+0.5 etc), depends on your `speed` config               |
| F12  | Screenshot | Screenshot current frame and save to Pictures(`C:\Users\<username>\Pictures`) |
| Ctrl | Skip text  | Skip text via Ctrl button, just like Galgame control system                   |

## Contributing

You're free to contribute to TSKHook as long as the features are useful, such as battle stats log, 360 stamina alert or something else, except modifying battle data.

## Disclaimer

Using TSKHook violates Twinkle Star Knights and DMM's terms of service.

I will NOT be held responsible for any bans!
