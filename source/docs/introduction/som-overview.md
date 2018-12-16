# SoM Overview
SoM Overview section enumerates the SoM processing, peripherals and packaging specifications.
## Processing Specifications
<style>  
table{text-align:center;vertical-align:middle;color:black;margin:auto}  
tr{height:40px}
td{vertical-align:middle}
</style>
<table rules="all"  frame="box" bgcolor="#f0f0f0" border=2 cellpadding=10 cellspacing=0>
    <tr bgcolor="#76b700">
        <th>Feature</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>GPU</td>
        <td align="left">8 NVIDIA Carmel ARMv8.2 (64bit) CPU @ 2.26GHz / 8MB L2 + 4MB L3</td>
    </tr>
    <tr>
        <td>CPU</td>
        <td align="left">699 pin board to board connector</td>
    </tr>
     <tr>
        <td>Memory</td>
        <td align="left">16 GB, 256-bit LPDDR4x @ 2133MHz (137GB/s)</td>
    </tr>
     <tr>
        <td>Storage</td>
        <td align="left">32GB eMMC 5.1 Flash Storage @ 200MHz</td>
    </tr>
    <tr>
        <td>DLA</td>
        <td align="left">2 NVDLA engines Deep Learning Accelerator</td>
    </tr>
    <tr>
        <td>VA</td>
        <td align="left">(2x) 7-way VLIW Vision Accelerator</td>
    </tr>
    <tr>
        <td>Encoder</td>
        <td align="left">
            <ul>
                <li>H.265(HEVC) up to 2x 4Kp60</li>
                <li>H.264 up to 4x 4Kp60</li>
                <li>VP9 up to 2x 4Kp60</li>
                <li>JPEG up to 16Kx16K</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>Decoder</td>
        <td align="left">
            <ul>
                <li>H.265(HEVC) up to 2x 8Kp30</li>
                <li>H.264 up to 4x 4Kp60</li>
                <li>VP9 up to 4x 4Kp60</li>
                <li>JPEG up to 16Kx16K</li>
                <li>MPEG-4</li>
                <li>MPEG-2</li>
                <li>VC-1</li>
            </ul>
        </td>
    </tr>
</table>
  
---
## Peripherals
- xHCI host controller with integrated PHY
- 3 x USB 3.1 (10GT/s)
- 4 x USB 2.0
- SD/MMC Controller
- Display <ul><li>3x eDP/DP/HDMI at 4Kp60 | HDMI 2.0, DP HBR3</li></ul>
- Camera <ul><li>16x CSI-2 Lanes (40 Gbps in D-PHY V1.2 or 109 GBps in CPHY v1.1)</li><li>
8x SLVS-EC lanes (up to 18.4 Gbps)</li><li>
Up to 16 simultaneous cameras</li></ul>
- PCie <ul><li>5x 16GT/s gen4 controllers | 1x8, 1x4, 1x2, 2x1</li><li>
(3x) Root Port + Endpoint</li><li>
(2x) Root Port</li></ul>
- Ethernet — Gigabit Ethernet-AVB over RGMII
- 5 x UART
- 3 x SPI
- 5 x I2C
- 2 x CAN
- 4 x I2S
---
## Package
<style>  
table{text-align:center;color:black;margin:auto}  
tr{height:40px}
td{vertical-align:middle}
</style>
<table rules="all"  frame="box" bgcolor="#f0f0f0" border=2 cellpadding=10 cellspacing=0>
    <tr bgcolor="#76b700">
        <th>Feature</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Module Size</td>
        <td>100 mm x 87 mm</td>
    </tr>
    <tr>
        <td>Connector</td>
        <td>699 pin board to board connector</td>
    </tr>
     <tr>
        <td>Operating Temperature</td>
        <td>Range from -25C to 80C</td>
    </tr>
     <tr>
        <td>Power Input</td>
        <td>9V - 20V</td>
    </tr>
    <tr>
        <td>TPP</td>
        <td>Integrated Thermal Transfer Plate with Heatpipe</td>
    </tr>
</table>

---



```eval_rst

.. toctree::
   :maxdepth: 2
   
   

```
	
	
	
	
