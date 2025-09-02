# PSOC&#8482; 4 HV ModusToolbox&#8482;
PSOC&#8482; 4 HV series is available with ModusToolbox&#8482;. Code example is made up of two parts: the default code examples and the additional code examples.

The additional code examples are available for PSOC&#8482; 4 HV devices in this repository.

Please refer the [ModusToolbox&#8482; software](https://github.com/Infineon/modustoolbox-software) for ModusToolbox&#8482;. It is recommended using latest ModusToolbox&#8482; software.

## Supported device and BSP
[PSOC&#8482; 4 HVMS MCU](https://www.infineon.com/products/microcontroller/32-bit-psoc-arm-cortex/psoc-4-hv-m0/hv-ms): CY8C4146LWE-HVS115X, CY8C4147LWE-HVS135X, CY8C4146LWE-HVS015X, CY8C4147LWE-HVS035X

|BSP name|KIT_PSOC4-HVMS-64K_LITE|KIT_PSOC4-HVMS-128K_LITE|KIT_PSOC4-HVMS-64K_LITE-02|KIT_PSOC4-HVMS-128K_LITE-02|
|-----------|---------------------|---------------------|-------------------|-------------------|
|Support Device|CY8C4146LWE-HVS115X  |CY8C4147LWE-HVS135X  |CY8C4146LWE-HVS015X|CY8C4147LWE-HVS035X|


[PSOC&#8482; 4 HVPA MCU](https://www.infineon.com/products/microcontroller/32-bit-psoc-arm-cortex/psoc-4-hv-m0/hv-pa): CY8C4147LCE-HV423

|BSP name|KIT_PSOC4-HVPA-144K_LITE
|-----------|---------------------
|Support Device|CY8C4147LCE-HV423

**Note:** Please select the appropriate BSP in the project creator according to device implemented on your LITE kit.

## Application note
[AN0034](https://www.infineon.com/assets/row/public/documents/10/42/infineon-an0034-getting-started-with-psoc-4-hv-ms-mcus-in-modustoolbox-applicationnotes-en.pdf) - Getting started with PSOC&#8482; 4 HV MCUs in ModusToolbox&#8482;

## Code Example
Each Code example provides a README.md file to learn more about that code example, as well as how to use it to create an application. Each README.md contains the following information:

- **Device**: The devices used by code example
- **Board**: The evaluation kit used by code example
- **Scope of work**: An abstract of code example
- **Introduction**: A generic introduction on the used module and it main features
- **Hardware setup**: The used hardware and how to configure it
- **Implementation**: A detailed explanation of how to implement the module's configuration using HAL and/or PDL and exploits their features
- **Run and Test**: The steps to follow to make sure the code is working properly and interact with it
- **References**: Related documents and web pages

## Evaluation kit
The code examples support the following types of boards: <br>
*Figure 1. KIT_PSoC4-HVMS-64K_LITE*<BR><img src="./Images/KIT_PSOC4-HVMS-64K_LITE_TOP.png" width="600" /><br>
*Figure 2. KIT_PSoC4-HVMS-128K_LITE*<BR><img src="./Images/KIT_PSOC4-HVMS-128K_LITE_TOP.png" width="600" /><br>
*Figure 3. KIT_PSoC4-HVPA-144K_LITE*<BR><img src="./Images/KIT_PSOC4-HVPA-144K_LITE_TOP.png" width="600" /><br>

|   Overview|[KIT_PSoC4-HVMS-64K_LITE](https://www.infineon.com/cms/en/product/evaluation-boards/kit_psoc4-hvms-64k_lite/)  |[KIT_PSoC4-HVMS-128K_LITE](https://www.infineon.com/cms/en/product/evaluation-boards/kit_psoc4-hvms-128k_lite/)  |[KIT_PSOC4-HVPA-144K_LITE](https://www.infineon.com/evaluation-board/KIT-PSOC4-HVPA-144K-LITE)
|-------------------------------    |-------------------------|--------------------------|-------------------------|
|MCU                                |CY8C4146LWE-HVS015X      |CY8C4147LWE-HVS035X       |CY8C4147LCE-HV423        |
|Package                            |56pin-QFN                |56pin-QFN                 | 32pin-QFN               |
|Kitprog3 programming/Debug         |✓ (USB Micro-B connector)|✓ (USB Micro-B connector)|✓ (USB Micro-B connector)|
|USER LEDs/Buttons/Potentiometer    |✓                        |✓                        |✓                        |
|Temperature sensor                 |✓                        |✓                        |✓                        |
|Pseudo load for wall adapter       |N/A                      |N/A                       |✓                        |
|Pseudo load for battery connector  |N/A                      |N/A                       |✓                        |
|LIN/CXPI connector                 |✓                        |✓                        |✓ *1                     |
|CAPSENSE&trade; Button/LED         |✓                        |✓                        |N/A                      |
|Arduino                            |✓                        |✓                        |✓                        |
|Shield2go                          |✓                        |✓                        |✓                        |
|MikroBUS                           |✓                        |✓                        |✓                        |

*1: KIT_PSOC4-HVPA-144K_LITE supports LIN slave configuration only
<BR>