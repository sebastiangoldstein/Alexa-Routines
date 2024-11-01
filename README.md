# Homebridge Alexa Routines Plugin

This plugin allows you to control your Alexa routines through HomeKit.

## Installation

1. Install Homebridge: `npm install -g homebridge`
2. Install this plugin: `npm install -g homebridge-alexa-routines`
3. Update your Homebridge configuration file

## Configuration

Add this to your Homebridge `config.json`:

```json
{
  "platforms": [
    {
      "platform": "AlexaRoutines",
      "name": "Alexa Routines",
      "email": "your-amazon-email@example.com",
      "password": "your-amazon-password"
    }
  ]
}
