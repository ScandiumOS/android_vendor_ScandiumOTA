### ScandiumOS OTA
In order for a device to be officially supported by ScandiumOS, OTA (Over-The-Air) information needs to be added. Please refer to the following "Readme" to get started.

### Introduction
In order for a device to be OTA compliant, there are a few things to know.

### JSON Structure
```
{
  "response": [
    {
      "maintainer": "Maintainer Name",
      "device": "Device Name",
      "filename": "ScandiumOS-v1.0-OFFICIAL.zip",
      "url": "https://t.me/ScandiumUIUpdates",
      "version": "v1.0",
      "romtype": "Official"
    }
  ]
}
```
