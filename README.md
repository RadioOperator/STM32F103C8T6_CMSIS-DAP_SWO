# STM32F103C8T6_CMSIS-DAP_SWO
-----------------------------

Based x893's code on: https://github.com/x893/CMSIS-DAP

My contribution is:

1. Upgrade CMSIS-DAP version to V2.00 .
2. Enable SWO basic function, no SWO_STREAM mode, and no SWO_MANCHESTER mode.
3. CDC function improved, using USART-2.
4. Added a Soft-Reset function for Cortex-M.
5. Added BluePill board support, Remapped or unRemap (refer to Docs).
6. Added STLINK_V2A board support (refer to Docs).
7. Minor changes, like LED handling, project files re-group...

Unsolved issue:
one compile Warning on main.c (line 151), but still works fine.

Thanks.
