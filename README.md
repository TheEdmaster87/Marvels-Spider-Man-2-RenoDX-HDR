# Marvel's Spider-Man 2 RenoDX HDR

A RenoDX HDR modification/enhancement for **Spider-Man 2** that adds some HDR fixes and optimizations when using the game's native HDR.

## NOTE
This mod is designed to work with native in-game HDR enabled
This mod will not work in SDR of the game; it's not a replacement for native HDR, it's an upgrade/enhancement of native HDR of the game, which is not bad, but has some limitations, such as raised black levels, which are fixed with this mod.

## Features

- **HDR Support**: Native HDR10 from the game
- **Advanced Color Grading**: Fine-tune brightness, contrast, saturation, highlights, black level, etc...
- **Real-time Adjustments**: All settings can be adjusted in real-time via the ReShade overlay

## Requirements

- **Spider-Man 2** (Steam version recommended)
- **ReShade with Add-on Support** (Required for RenoDX functionality)
- **HDR-capable display** (for HDR features)
- **Windows 10/11** with HDR enabled in display settings

## Installation

### Step 1: Install ReShade with Add-on Support

1. Download **ReShade** with full addon support from [reshade.me](https://reshade.me/)
2. Run the ReShade installer
3. Select **Spider-Man 2**: `Spider-Man2.exe`
4. Choose **DirectX 10/11/12**
6. Skip shader selection (not needed for this mod)

### Step 2: Install RenoDX HDR Mod

1. Download `Spider-Man 2 addon` from the [Releases](../../releases) page
2. Copy the file to your Spider-Man 2 installation directory.
3. Run the game

### Step 3: Configure HDR (Optional)

For HDR displays:
1. Enable HDR in Windows Display Settings
2. Set your display to HDR mode if it needs to be manually selected; it should automatically detect HDR when you enable HDR in Windows Display Settings.
3. Launch Spider-Man 2
4. Enable in-game HDR and set brightness to the lowest possible settings, which is usually 200 nits. After that, you don't need to touch in-game HDR settings again, just use the RenoDX UI sliders instead!
5. Open ReShade overlay (Home key by default)
6. Navigate to RenoDX settings and select the appropriate HDR settings

## Usage

### Accessing RenoDX Settings

1. Launch Spider-Man 2
2. Press **Home** key to open ReShade overlay
3. Navigate to the **Add-ons** tab
4. Find **RenoDX** settings

### Key Settings

#### HDR Configuration
- **HDR Peak Brightness**: Choose based on your display peak brightness
- **Black Level Adjustment**: Adjust the game black levels, important for QD-OLED and OLED TVs/Monitors.
- **Highlights Adjustment**: Adjust the game highlights to your liking.
- **Scene Brightness**: Adjust midtones and shadows for your liking, similar to the paper-white setting.
- **UI/HUD Brightness**: Adjust UI/HUD element brightness 

#### Color Grading
- **Contrast**: Contrast enhancement
- **Saturation**: Color saturation control

## Known Issues

## Troubleshooting

### Mod Not Loading
- Ensure ReShade was installed with **Add-on Support** enabled, it only works on the Reshade with add-on support version of Reshade.
- Verify `renodx-spiderman2.addon64` is in the correct directory
- Check that the ReShade overlay shows RenoDX in the Add-ons tab

### Color Issues/brightness isuees
- Reset RenoDX settings to defaults
- Adjust tonemapping type
- Check display color profile settings
- Calibrate Windows HDR for your display


## Contributing

Found a bug or have suggestions? Please open an issue on this repository.

## Credits

- **RenoDX Framework**: [clshortfuse/renodx](https://github.com/clshortfuse/renodx)
- **ReShade**: [crosire/reshade](https://github.com/crosire/reshade)
- **Marvel's Spiderman 2**: [Game Developer]

## License

This modification is provided as-is for educational and enhancement purposes.

