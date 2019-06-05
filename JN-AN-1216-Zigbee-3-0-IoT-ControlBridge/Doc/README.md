
How to change baud rate for ControlBridge Application?

1/ Right click to project JN-AN-1216-ZigBee-3-0-IoT-ControlBridge >> click Properties
2/ In "Build Command" text box, modify baud rate:
make TRACE=1 NODE=FULL_FUNC_DEVICE BAUD=115200 JENNIC_CHIP=JN5169 JENNIC_CHIP_FAMILY=JN516x

3/ Clean project and rebuild application.
