<p align="center">
  <h1 align="center">High-Performance Low-Latency Bluetooth 5.0 Dongle</h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0ac78fd6-a2e4-4355-b1ab-97973d19146d" alt="pluggedin" width="600"/>
</p>

## Project Overview
This project aimed to design and manufacture a custom Bluetooth 5.0 dongle that exceeds the RF signal integrity and latency performance of commercial off-the-shelf solutions. 
* **Custom 4-Layer PCB:** Designed in Altium Designer with strictly routed, impedance-matched traces for optimal RF performance.
* **Low Latency:** Achieves <20ms latency for real-time input registration.
* **Extended Range:** Verified effective wireless range of up to 280 feet.
* **Precision Enclosure:** Custom-modeled magnetic enclosure (Fusion 360)

---

## Performance & RF Specifications
* **Protocol:** Bluetooth 5.0 (Classic + BLE)
* **Transmit Power:** Up to +8dBm
* **Receive Sensitivity:** -88dBm
* **Effective Latency:** < 20ms
* **Max Range:** ~280 feet (Line of sight)

---

## Hardware & Architecture

### PCB Design (Altium Designer)
![Altium Designer 4-layer PCB routing]

<table align="center">
  <tr>
    <td align="center" valign="bottom">
      <img src="https://github.com/user-attachments/assets/9cdaeb53-3378-49fc-8059-a2108db192a0" width="500" alt="Isometric View of PCB" />
      <br><b>Altium 3D Render</b>
    </td>
    <td align="center" valign="bottom">
      <img src="https://github.com/user-attachments/assets/b6846794-0515-4dd3-a436-1684514b8c97" width="300" alt="Top View of PCB" />
      <br><b>Assembled Hardware</b>
    </td>
  </tr>
</table>


The board utilizes a 4-layer stackup to ensure proper ground shielding and power delivery. The critical RF pathways were impedance-matched to 50 ohms to prevent signal reflection and detuning, which is a common failure point in compact commercial dongles.

### Mechanical Design (Fusion 360)
  <img src="https://github.com/user-attachments/assets/7db9d73e-83da-47a9-8b9f-3d2885c66a38" width="800" alt="Enclosure Top View" />
  <br><b>Enclosure Top </b><br><br>
  
  <img src="https://github.com/user-attachments/assets/bc710a2a-566e-45ba-bfa2-eb4175413ee8" width="800" alt="Enclosure Bottom View" />
  <br><b>Enclosure Bottom </b>
</p>

---

