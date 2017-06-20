## Visionertech VMG-PRO FPGA project
## General Description:
This is an open-source project of VMG-PRO HMD mostly written in verilog. There are two process flows contained: one is the basic ISP flow, and the other is the HDR flow.
The top-hierarchy file is also provided in the project. Developers only need to open a new project and add all of the RTL and ip files to start their own design. By the way, all of the modules included have already been simulated and tested in hardware.

## Developer tool:
Recommended PC configuration： Intel Core i5-4460/8G RAM/at least two USB3.0/Xilinx ISE 13.4 design suite
JTAG debug tool which is Xilinx compatible, narrow edge JTAG row line which is 2.0mm and 14pins.

## Module localtion:
design/top
The top file and UCF file.

design/clock
The system clock.

design/bnt_process
The input button process.

design/powerUp_sequence
The power up process and reset process.

design/auto_exposure
The auto exposure.

design/config_sensor
The image sensor controller.

design/sensor_sync_signal_regen
Regenerate image sensor synchronizing signal.

design/width_conv_12to10
Pixel depth compress.

design/frames_buffer DDR3
The interface of DDR3 controller.

design/Bayer2RGB
Bayer convert to RGB.

design/HDR
The HDR module.

design/output_mux
Strobe output ISP or HDR.

design/his_eq
The histogram equalization.

design/IMU_package
Packaging IMU data and button signal into video.

design/USB_cy3014
Packaging UVC data format of usb3.0.

design/YC_RGB_convertion
RGB convert to YC.
