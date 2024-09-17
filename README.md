# Bluetooth_Breakout_Software
<!-- <img src="https://github.com/sbcshop/MusicPi_Software/blob/main/images/musicPi_banner.png"> -->

Introducing the compact Bluetooth Breakout Board, designed for enhanced audio testing and entertainment. This versatile module serves as both an audio input and output, featuring an integrated amplifier circuit with left and right channels, delivering up to 3W per channel for crisp sound. Perfect for developers, it simplifies incorporating Bluetooth wireless technology into designs, making your workflow smoother and more efficient. Ideal for audio testing, development, and various experimental purposes.


### Features:
- Bluetooth v5.1 Compliant: Qualified to Bluetooth v5.1 specifications for robust connectivity.
- Dual-Mode BLE Radio: Simultaneous Bluetooth Classic and BLE modes provide versatile connectivity, enabling high-speed data transfer and low-energy communication concurrently.
- High-Performance Audio: 24-bit stereo audio interface with support for SBC and AAC audio codecs.
- Powerful Audio Output: Dual-channel 3W audio output for rich sound quality.
- 3.5mm Headphone TRS Jack: Convenient option for private listening.
- Microphone Support: Enables Bluetooth calling facility with clear audio.
- Mode Switch: Easily switch between Aux and Bluetooth listening modes.
- Status Indicators: Power and pairing status LEDs for clear activity indications.
- Onboard Control Buttons: Hardware buttons for play, next, previous, and volume controls.

### Specifications:
- **Module**: FSC-BT1026C Dual-mode BLE radio module
- **Bluetooth Standard**: 5.1
- T**ransmit Output Power**: +9 dBm (Max.)
- **Profiles**: A2DP, AVRCP, HFP, HSP, HOGP, PBAP, SPP, GATT
- **Frequency Band**: 2.402 ~ 2.480 GHz
- **Bluetooth Low Energy**: 
   - GATT Client and peripheral
   - Simultaneous BR/EDR and BLE Support 
- **Raw Data Rates(Air)** : 3Mbps (Classic BT - BR/EDR)
- **Amplifier**: NS4150 3W Mono Class D Audio Amplifier
- **Audio Outputs**:
   - Two Channel 3W Speaker Output 
   - Headphones (3.5mm) Support 
- **Supply Voltage**: 5V Type C
- **External Supply**: 4.2V DC
- **Operating Temperature Range**: -20°C ~ +70 °C 

## Bluetooth Breakout Hardware Overview
### Pinout

<img src="">

<img src="https://github.com/sbcshop/MusicPi_Software/blob/main/images/musicpi_setup.png" width="583" height="357">

**<ins>Bluetooth Module</ins>**: FSC-BT1026C Dual-Mode Module, simulatneous connect with Bluetooth Classic for high-data streaming like music, and to low-power BLE mode for efficient performance.

**<ins>Buttons<ins>** : Onboard there are four buttons,
   - **Power/Play/Pause** :
     - To power ON bluetooth module, play and pause songs when playing song on bluetooth mode.
     - Long Press and hold switch till PAIR LED starts blinking. This confirms module is ON and searching for device to pair with. Once device paired then PAIR LED stops blinking and stays Active.
   - **Vol+/Next** : Simple press and release for Volume increase while Long press for next song play
   - **Vol-/BACK** : Simple press and release for Volume decrease while Long press for back.
   - **RESET** : This entirely reset the module for reconnection.

**<ins>Mic</ins>**: Microphone for bluetooth calling 
**<ins>Type C Interface</ins>**: Type C interface for power and USB to UART Bluetooth module access. 
**<ins>External Power</ins>**: Additional External power source option to connect battery in case type C not connected. Max allowed voltage is 4.2V

<ins>AUX IN</ins>
<ins>AUX OUT</ins>
<ins>Speaker Connector</ins>

#### Compatible speakers available Here:
* [2W 6 Ohm Mono Enclosed Speaker](https://shop.sb-components.co.uk/products/2-watt-6-ohm-mini-portable-speaker-for-small-electronic-projects-2pcs)
* [3 Watt 8 Ohm Mini Speaker](https://shop.sb-components.co.uk/products/3-watt-8-ohm-mini-speaker-full-range-portable-for-small-electronic-projects)
* [5W 8 Ohm Dual Mini Speaker](https://shop.sb-components.co.uk/products/8-ohm-5w-speaker-ic-test-board)


## Bluetooth / Aux Mode
## BLE App 
## UART Data Capture via XCTU/Terminal Software
   
## Resources
  * [Schematic]()
  * [Hardware Files]()
  * [Step File]()
  * [Module Datasheet]()

## Related Products

  * [MusicPi](https://shop.sb-components.co.uk/products/musicpi-high-quality-stereo-audio?variant=42131572293715)
  
    ![MusicPi](https://shop.sb-components.co.uk/cdn/shop/files/6_576c3640-c7f2-4909-a74f-efc9b49ac6e3.png?v=1724243010&width=300)
  
  * [TRRS 3.5mm Audio Jack Breakout](https://shop.sb-components.co.uk/products/trrs-3-5mm-audio-jack-breakout?_pos=3&_sid=dca87c6f7&_ss=r)
  
    ![TRRS 3.5mm Audio Jack Breakout](https://shop.sb-components.co.uk/cdn/shop/files/1_93fe94b5-e09f-4f4f-9b16-65348c47343d.jpg?v=1690882465&width=300)
  
  * [BoomBit - Music Player for microbit](https://shop.sb-components.co.uk/products/boombit?_pos=10&_sid=39ade3b9b&_ss=r) 
  
    ![BoomBit - Music Player for microbit](https://shop.sb-components.co.uk/cdn/shop/products/BoomBitProductImage.png?v=1622521944&width=300)

 
## Product License

This is ***open source*** product. Kindly check LICENSE.md file for more information.

Please contact support@sb-components.co.uk for technical support.
<p align="center">
  <img width="360" height="100" src="https://cdn.shopify.com/s/files/1/1217/2104/files/Logo_sb_component_3.png?v=1666086771&width=300">
</p>
