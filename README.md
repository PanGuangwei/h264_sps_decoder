# h264_sps_decoder
* Set your SPS stream, edit sps.cpp 
```c
unsigned char buf[27] = {0x67,0x64,0x00,0x1e,0xac,0xd3,0x05,0xc1,0x47,0x97,0x9b,0x81,0x01,0x02,0xa0,0x00,0x00,0x03,0x00,0x20,0x00,0x00,0x06,0x11,0xe2,0xc5,0xa7};
```
* Save & compile
```
g++ sps.cpp -o sps
```
* Run
```
./sps
```
* Output
```
H.264 SPS: -> video size 368x640, 24 fps, profile(100) High(FRExt)
```