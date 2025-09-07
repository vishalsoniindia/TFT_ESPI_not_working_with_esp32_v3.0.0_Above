# TFT_ESPI_not_working_with_esp32_v3.0.0_Above

The Setup302_Waveshare_ESP32S3_GC9A01 is not supported with ESP32 Board version 3.0 and above, so you need to define HSPI to make it work. ✅

Add this line to Setup File or Relace File with given file in repo.
```
#define USE_HSPI_PORT          // Force HSPI
```
