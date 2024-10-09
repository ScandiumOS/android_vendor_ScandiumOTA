### ScandiumOS OTA
In order for a device to be officially supported by ScandiumOS, OTA (Over-The-Air) information needs to be added. Please refer to the following "Readme" to get started.

### Introduction
In order for a device to be OTA compliant, there are a few things to know.

### JSON Structure
```
{
  "response": [
    {
      "Maintainer": "Maintainer Name",
      "Devices": "Device Name",
      "Filename": "ScandiumOS-v1.0-OFFICIAL.zip",
      "Date": "199167575",
      "MD5": "41ce8869f4b",
      "Size": "716918528",
      "Version": "v1.0",
      "Build Type": "OFFICIAL"
    }
  ]
}
```

### To Get JSON After Build Completed [For OFFICIAL Devices]
You can obtain the JSON files at out/target/product/product_device/product_device.json
