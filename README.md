# PSOC&#8482; 4 HV ModusToolbox&#8482;
PSOC&#8482; 4 HV series is available with ModusToolbox&#8482;.
series code example is made up of two parts: the default code examples and the additional code examples.
The additional code examples are available for PSOC&#8482; 4 HV devices in this repository.

Please refer the [ModusToolbox&#8482; software](https://github.com/Infineon/modustoolbox-software) for ModusToolbox&#8482;. It is recommended using latest ModusToolbox&#8482; software.

## Supported device and BSP
[PSOC&#8482; 4 HVMS MCU](https://www.infineon.com/cms/en/product/microcontroller/32-bit-psoc-arm-cortex-microcontroller/32-bit-psoc-4-hv-arm-cortex-m0/): CY8C4146LWE-HVS115X, CY8C4147LWE-HVS135X, CY8C4146LWE-HVS015X, CY8C4147LWE-HVS035X 

|BSP name|KIT_PSOC4-HVMS-64K_LITE|KIT_PSOC4-HVMS-128K_LITE|KIT_PSOC4-HVMS-64K_LITE-02|KIT_PSOC4-HVMS-128K_LITE-02|
|-----------|---------------------|---------------------|-------------------|-------------------|
|Support Device|CY8C4146LWE-HVS115X  |CY8C4147LWE-HVS135X  |CY8C4146LWE-HVS015X|CY8C4147LWE-HVS035X|

**Note:** Please select the appropriate BSP in the project creator according to device implemented on your LITE kit.

## Application note
[AN0034](https://www.infineon.com/assets/row/public/documents/10/42/infineon-an0034-getting-started-with-psoc-4-hv-ms-mcus-in-modustoolbox-applicationnotes-en.pdf) - Getting started with PSOC&#8482; 4 HVMS MCUs in ModusToolbox&#8482;

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
*Figure 5. KIT_PSoC4-HVMS-64K_LITE*<BR><img src="./Images/KIT_PSOC4-HVMS-64K_LITE_TOP.png" width="600" /><br>
*Figure 6. KIT_PSoC4-HVMS-128K_LITE*<BR><img src="./Images/KIT_PSOC4-HVMS-128K_LITE_TOP.png" width="600" /><br>

|   Overview|[KIT_PSoC4-HVMS-64K_LITE](https://www.infineon.com/cms/en/product/evaluation-boards/kit_psoc4-hvms-64k_lite/)  |[KIT_PSoC4-HVMS-128K_LITE](https://www.infineon.com/cms/en/product/evaluation-boards/kit_psoc4-hvms-128k_lite/)  |
|-------------------------------|------------------------|--------------------------|
|MCU                            |CY8C4146LWE-HVS015X (56pin-QFN) |CY8C4147LWE-HVS035X (56pin-QFN) |
|Kitprog3 programming/Debug     |✓ (USB Micro-B connector)|✓ (USB Micro-B connector)|
|USER LEDs/Buttons/Potentiometer|✓                       |✓                        |
|Temperature sensor             |✓                       |✓                        |
|LIN/CXPI connector             |✓                       |✓                        |
|CAPSENSE&trade; Button/LED     |✓                       |✓                        |
|Arduino                        |✓                       |✓                        |
|Shield2go                      |✓                       |✓                        |
|MikroBUS                       |✓                       |✓                        |
<BR>