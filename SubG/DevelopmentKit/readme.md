HopeRF provides both hardware and software tools for developing and testing RF communication modules. Here’s a brief overview of the key tools:

*RFPDK (Radio Frequency Parameter Development Kit)*   
A software tool for configuring HopeRF modules like RF transceivers.
Allows users to adjust parameters such as frequency, modulation, and power levels.

*RFDK (RF Development Kit) & EVB (Evaluation Boards)*   
RFDK includes hardware kits for developing RF applications using HopeRF chips.
EVBs are specific evaluation boards for testing and optimizing HopeRF RF modules.
These tools help engineers validate RF performance and integrate HopeRF solutions into their projects.

*HopeDuino*   
A development board that combines HopeRF's RF modules with Arduino-compatible functionality.
Designed for rapid prototyping and IoT applications.
Supports HopeRF’s wireless communication modules, making it easier to integrate RF capabilities into Arduino-based projects.

# 1. RFPDK
RFPDK is a software tool from HopeRF for configuring and testing RF products. It provides a user-friendly GUI to adjust key RF settings such as frequency, modulation, power, and data rate, supporting almost all of the CMT products.

<div align="center">
  <img src="/images/SubG_RFPDK.png" width="600">  
</div>  
</br>

# 2. HopeRF RFDK

The HopeRF RFDK is a development kit designed to facilitate the evaluation and testing of HopeRF's range of RF modules. It provides a straightforward platform for developers to assess module performance and expedite the development process from prototype to final product.

<div align="center">
  <img src="/images/SubG_RFDK.jpg" width="600">  
</div>  
</br>

## 2.1. Key Features of the HopeRF RFDK:

Comprehensive Kit Components: Each RFDK set includes:
2 RFDK base boards
2 converter boards
2 antennas
Pin headers

## 2.2. Module Compatibility:

The kit supports a wide range of HopeRF modules, including:
RFM01/02/12B
RFM22B/23B/31B/42B/43B
RFM24/26
RFM63/64/65/66/67/68/69/69H
RFM92/93/95/96/97/98 (LoRa)

## 2.3. User-Friendly Interface:

The RFDK features a PIC16 series microcontroller and an LCD display, enabling users to easily modify parameters and conduct transmission and reception tests. This facilitates a clear understanding of the RF module's performance.
HOPERF

Flexible Power Options: The development kit can be powered either by four 1.5V AA batteries or via a 5V USB connection, offering versatility in various testing environments.

By utilizing the HopeRF RFDK, developers can efficiently evaluate and optimize the performance of HopeRF's RF modules, streamlining the development cycle for wireless communication applications. For more information, please refer to "HopeRF_RFDK_RFMxx_DEMO_V2.1_operation_manual"

# 3. HopeRF RF-EVB (Evaluation Board)

RF-EVB is an evaluation board which is used to test the RF COB modules from HOPERF. Simple and practical way of demonstration lets users to understand the
corresponding COB module of radio frequency characteristics easily and intuitively. This board has moderate size, simple operation, easy to carry these
advantages which are suitable for R&D evaluation and out door distance evaluation

<div align="center">
  <img src="/images/SubG_RFEVB.jpg" width="600">  
</div>  
</br>

# 4. HopeDuino

HopeDuino is an Arduino-compatible development platform created by HOPERF, a leading manufacturer of wireless RF chips and sensors. This platform is designed to facilitate the evaluation and development of applications using HOPERF's RF modules.

<div align="center">
  <img src="/images/SubG_HOPEDUINO.png" width="600">  
  <img src="/images/SubG_Hopeduino_2.jpg" width="600">  
</div>  
</br>

## 4.1. Key Features of HopeDuino:

### 4.1.1. Compatibility:

HopeDuino boards are compatible with the Arduino IDE, allowing users to program them using familiar tools and libraries.

### 4.1.2. Support for HOPERF Modules:

The platform supports various HOPERF RF modules, such as the RFM69W, RFM95W and RFM219AW, enabling users to experiment with different wireless communication technologies.

### 4.1.3. Evaluation Capabilities:

HopeDuino provides a practical way to test and evaluate the performance of HOPERF's RF modules, making it suitable for both research and development purposes.

To get started with HopeDuino, you'll need to set up the development environment by installing the Arduino IDE and the necessary libraries provided by HOPERF. Detailed guidance on platform construction and module integration can be found in HOPERF's application notes AN0002 and manuals.

By leveraging the HopeDuino platform, developers can effectively prototype and implement wireless communication solutions using HOPERF's range of RF modules.
