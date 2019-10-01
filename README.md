# STM32F103C8T6_CMSIS-DAP_SWO
-----------------------------

Based x893's code on: https://github.com/x893/CMSIS-DAP

My contribution:

1. Upgrade CMSIS-DAP version to V2.0.0 (HID mode, not WinUSB) .
2. Enable SWO_UART function(USART1), no SWO_STREAM/SWO_MANCHESTER mode.
3. CDC function improved(USART2).
4. Added a Soft-Reset function for Cortex-M.
5. Added BluePill board support, Remapped or unRemap (refer to Docs).
6. Added STLINK_V2A, STLINK_V2B board support (refer to Docs).
7. Minor changes, e.g. LED handling, project files re-group......
 -

Here is the BluePill remapped SWD port in use:
![alt text](https://github.com/RadioOperator/STM32F103C8T6_CMSIS-DAP_SWO/blob/master/Doc/Bluepill/1.SWD_Remapped.jpg) 
 -
 -
 -
Check my another repository for USB2.0 High-Speed CMSIS-DAP device, incredible more:
 -
 - https://github.com/RadioOperator/CMSIS-DAP_for_STLINK-V3MINI
 -
 - 



