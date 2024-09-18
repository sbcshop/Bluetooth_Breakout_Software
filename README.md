# Bluetooth_Breakout_Software
<img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/main%20banner.jpg">

Introducing the compact Bluetooth Breakout Board, designed for enhanced audio testing and entertainment. This versatile module serves as both an audio input and output, featuring an integrated amplifier circuit with left and right channels, delivering up to 3W per channel for crisp sound. Perfect for developers, it simplifies incorporating Bluetooth wireless technology into designs, making your workflow smoother and more efficient. Ideal for audio testing, development, and various experimental purposes.

This github page contains details and instructions for using Bluetooth Breakout.

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
<img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/pinouts.jpg">

- **<ins>Bluetooth Module</ins>**: FSC-BT1026C Dual-Mode Module, simulatneous connect with Bluetooth Classic for high-data streaming like music, and to low-power BLE mode for efficient performance. Checkout for more details [here](https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/documents/FSC-BT1026C.pdf)

- **<ins>Buttons<ins>** : Onboard there are four buttons,
   - **Power/Play/Pause** :
     - To power ON bluetooth module, play and pause songs when playing song on bluetooth mode.
     - Long Press and hold switch till PAIR LED starts blinking. This confirms module is ON and searching for device to pair with. Once device paired then PAIR LED stops blinking and stays Active.
   - **Vol+/Next** : Simple press and release for Volume increase while Long press for next song play
   - **Vol-/BACK** : Simple press and release for Volume decrease while Long press for back.
   - **RESET** : This entirely reset the module for reconnection.
   - **Mode Switch Button**: Push and closed switch to select Aux Mode. Release switch to move breakout in Bluetooth mode for wireless listening.
     
- **<ins>Mic</ins>**: Microphone for bluetooth calling or voice related operation.
- **<ins>Type C Interface</ins>**: Type C interface for power and USB to UART Bluetooth module access. 
- **<ins>External Power</ins>**: Additional External power source option to connect battery in case type C not connected. Max allowed voltage is 4.2V.
- **<ins>AUX IN</ins>**: For audio input using 3.5mm Standard Jack Aux cable. Rquired 3 Pole TRS Aux pin connector for Compatibility.
- **<ins>AUX OUT</ins>**: For audio output for standard 3.5mm Audio Jack. Rquired 3 Pole TRS Aux pin connector for Compatibility.
- **<ins>Speaker Connector</ins>**: Two options available to connect speakers (1) 2.54" four pin header and (2) 2mm JST right and left connector

#### Compatible speakers available Here:
* [2W 6 Ohm Mono Enclosed Speaker](https://shop.sb-components.co.uk/products/2-watt-6-ohm-mini-portable-speaker-for-small-electronic-projects-2pcs)
* [3 Watt 8 Ohm Mini Speaker](https://shop.sb-components.co.uk/products/3-watt-8-ohm-mini-speaker-full-range-portable-for-small-electronic-projects)
* [5W 8 Ohm Dual Mini Speaker](https://shop.sb-components.co.uk/products/8-ohm-5w-speaker-ic-test-board)

## Bluetooth / Aux Mode
<img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/mode.jpg">

### Aux Mode
- To activate Aux Mode, just push the Mode Switch button and lock it in the closed position.
  
- Now you may connect 3.5mm TRS 3 pole Aux Jack to Aux IN and play any music.

  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/aux_input_mode.png" width=440 height=346>
  
- Audio output is offered for driving a speaker with amplified music or connecting 3.5mm TRS 3 pole stereo headphones for private listening at Aux OUT.

### Bluetooth Mode
- To activate Bluetooth Mode, just push the Mode Switch button and release to open.
- Make sure Module is power ON, if not press and hold Power/Play/Pause button
  
  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/bluetooth_mode_switch_open.jpeg" width=453 height=262>

- Once module power ON, indicated by Pair LED blinking. Now use your smartphone or any device to pair with breakout. When device active meaning paired, LED will stop blinking.

  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/Pairing_device.jpg" width=676 height=370>

  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/bluetooth_headphone.jpg" width="400" height="400">
  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/bluetooth_speaker.jpg" width="400" height="400">

- Now, breakout is ready to play your favorite music. This connection is with Bluetooth Classic, but this module also supports simultaneous connections with BLE mode in addition to Classic. Follow the steps below to connect with BLE.
   
#### BLE Feature 
- Bluetooth classic is for high speed data transfer like music play. BLE meant for low power operations.
- To connect and explore BLE features, download and install Feasyblue app
   - [Andriod App](https://play.google.com/store/apps/details?id=com.feasycom.feasyblue&hl=en_IN)
   - [iOS App](https://apps.apple.com/us/app/feasyblue/id1171297423)
- Provide location permission and then run App. Then select BLE option, device will be listed as shown. Select FSC-BT1026C-LE option.

  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/ble_pair.jpg" width="439" height="444">

- With this you can experiment BLE features in more details. Follow below procedure for detail view of activity with Bluetooth module and AT command usage.
  
## UART Data Capture via XCTU/Terminal Software
- Connect bluetooth breakout to PC/laptop using Type C interface, make sure bluetooth module is power ON.
- Now you will see device listed with COM port you can checkout in device manager, If not listed meaning CH340 driver missing. To install driver check out [CH340 Driver Installation Manual Guide](https://github.com/sbcshop/NFC_Module/blob/main/documents/CH340%20Driver%20installation%20steps.pdf).
  
  <img src="https://github.com/sbcshop/L76_GPS_Breakout_Software/blob/main/images/device_manager_comport.jpg" width="583" height="426">

- To monitor device data you can use any serial console terminal. For demo we have used XCTU which you can download from [official site here](https://hub.digi.com/support/products/xctu/).

  Select Tools > Serial console > configure

  <img src="https://github.com/sbcshop/L76_GPS_Breakout_Software/blob/main/images/xctu_1.jpg" width="600" height="451">

  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/xctu_device_setting.jpg" width="600" height="451">
  
- Ongoing music status visible on terminal,

  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/music_play_monitor.jpg" width="959" height="508">

- Even you can monitor data sent over BLE, 
  
  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/ble_msg_app.jpeg" width="216" height="480">
  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/BLE_msg.jpg" width="959" height="508">

- Some AT Command operations, you can directly send AT command or create packets for ease. When creating packets make sure to add 0D and 0A after every command in HEX. Below simple demo for changing advertising name of bluetooth breakout from default FSC-BT1026C to SB_BL_Breakout.
  
  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/at_command_packets.jpg" width="" height="">
  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/AT_cmd_send.jpg" width="580" height="408">
  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/AT_name_changed.jpg" width="694" height="225">
  <img src="https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/images/modified_name.jpeg" width="324" height="387">
  
- For Details Checkout [Command and Programming Manual](https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/documents/FSC-BT1026_programming_user_guide_2.0.pdf)
  
## Resources
  * [Schematic](https://github.com/sbcshop/Bluetooth_Breakout_Hardware/blob/main/Design%20Data/SCH%20bluetooth%20bkt.pdf)
  * [Hardware Files](https://github.com/sbcshop/Bluetooth_Breakout_Hardware)
  * [Step File](https://github.com/sbcshop/Bluetooth_Breakout_Hardware/blob/main/Mechanical%20Data/BluetoothBreakout.step)
  * [Bluetooth Module Datasheet](https://github.com/sbcshop/Bluetooth_Breakout_Software/blob/main/documents/FSC-BT1026C.pdf)

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
