
# Controller - Chromecast Speaker  

This accessory will discover all chromecasts on the network and create a speaker for 'Chromecast Audio', 'Google Cast Group', 'JBL Link View', 'Lenovo Smart Display', 'Google Nest Hub', 'Lenovo Smart Clock', 'Google Home', 'Google Home Mini', 'Google Nest Mini'.  
  
Apple Home app does not support speakers yet and the accessory is shown as unsupported, but can be controlled via thirs-party apps like Home+, Controller for HomeKit and others.

## Installation

```sh
npm i -g homebridge-chromecast-speaker
```
  
Add this to your config.json.
  
```json
"platforms":[
    {
      "platform": "ChromecastSpeaker",
      "name": "ChromecastSpeaker"
    }
]
```

## Credits
This project is based on [@homebridge-control-chromecast](https://github.com/yotamtal/homebridge-control-chromecast#readme)
