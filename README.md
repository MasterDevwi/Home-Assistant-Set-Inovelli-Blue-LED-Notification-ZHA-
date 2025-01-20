# Home Assistant: Set Inovelli Blue LED Notification (ZHA) script
A Home Assistant script allowing you to define custom presets for the LED notifications on the Home Assistant Blue switches using ZHA.

## Pre-requisites 
* [Inovelli Blue switches](https://inovelli.com/)
* Home Assistant
* A Zigbee network set up using use ZHA

## How to use
1. Copy the code for the script ([Set Inovell Blue LED Notification (ZHA).yaml](https://github.com/MasterDevwi/Home-Assistant-Set-Inovelli-Blue-LED-Notification-ZHA/blob/main/set_inovelli_blue_led_notification_zha.yaml)) to a new script in Home Assistant.
2. You can use the default presets, but to customize your own:
   1. Edit the list of presets in the **Define presets** variables. All properties match the standard Inovelli Blue LED properties. Set led_number to -1 to target all LEDs at once.
   2. In the preset field, expand the selector options and edit the list to match the custom presets you just configured
3. You can now call this script in any of your automations!
