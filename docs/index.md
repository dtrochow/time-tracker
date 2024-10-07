# time-tracker

## Idea

The main purpose of this device is to measure the time spent working each day. It will summarize the hours worked before and after noon, as well as provide a weekly summary. Additionally, it will track the start and end times of work each day. The summary will be displayed on a 1.5-inch 128x128 OLED display.

The device will be simple to use. To start tracking work, flip a switch to the "work" position. To stop, switch it back to the original position. All calculations will be performed automatically by the device.

The device will synchronize its clock with an NTP server, updating the time every hour/day/week. This means the device must be connected to a local WiFi network with internet access. Upon startup, it will act as an access point, serving a web page where the user can input the WiFi network SSID and password.

## Future Enhancements

Potential future improvements could include:

- Tracking reading hours
- Tracking training hours
- Tracking gaming hours
- Adding a Pomodoro timer
