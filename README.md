# 🚀 NerdMiner Plus: Setup & Support Guide

### 🔗 Compatible Hardware & Tools
* **Online Flashing Tool:** [nerdminerplus.com](https://www.nerdminerplus.com/)
* **Compatible Device Purchase Links:** *(Devices purchased from these stores are fully compatible for flashing)*
    * **Amazon:** [Shop Here](https://www.amazon.com/dp/B0GLGFZMRV)
    * **eBay:** [Shop Here](https://www.ebay.com/itm/397656584782)
    * **AliExpress:** [Official Store](https://www.aliexpress.com/store/1105392427)
* **Performance:** Delivers a hashrate of up to **740 KH/s** with Primary & Failover pool support.

---

## 🛠️ Quick Start Guide

### --- Step 1: Device Boot & Hotspot Connection --- 
1.  **Power On**: Plug in the device. The screen will display "Connecting to WiFi..." and "Will switch to AP in 60s if failed." 
2.  **Configuration Mode**: If no Wi-Fi is configured, the device enters **AP (Access Point) mode** after 60 seconds. 
3.  **Connect to Hotspot**: On your phone/PC, connect to the Wi-Fi named **"BTC_..."**
    * **Default Password**: `12345678`

### --- Step 2: Login to Dashboard --- 
1.  **Access Address**: Open your browser and go to `192.168.4.1` or `http://192.168.4.1/config`
2.  **Authentication**: Enter the default credentials: 
    * **Username**: `admin` | **Password**: `admin`
3.  **Language**: Use the top-right drop-down menu to switch languages for easier navigation.

### --- Step 3: Important Configurations ---
> **⚠️ Note**: Complete **Mining** and **Display** settings **BEFORE** updating Network settings. Once the miner connects to your home Wi-Fi, the AP page will disconnect.

1.  **Mining Settings [Required]**
    * **Mining Pool**: Defaults are `public-pool.io` (Primary) and `solo.ckpool.org` (Backup).
    * **Wallet Address**: **IMPORTANT!** Replace the default with your own **BTC Wallet Address**.
    * Click **"Update Mining Settings"** to save. 

2.  **Display & LED [Optional]**
    * **Rotation**: Adjust screen orientation (default is Landscape with cable at right).
    * **LEDs**: Adjust RGB brightness (0-255) to customize your miner's look.

3.  **Security [Recommended]**
    * Change the default `admin` password under **User Settings** to keep your miner secure.

### --- Step 4: Network Settings [Final Step] --- 
1.  Expand **"Network Settings"**. 
2.  Click **"Scan"** and select your home Wi-Fi. 
3.  Enter your **Wi-Fi Password**. 
4.  Click **"Update Network Settings"**.

---

### 🎉 Success! 
The miner will reboot and connect to your home Wi-Fi. When the **Wi-Fi icon** stays solid and the **Hashrate (up to 740 KH/s)** starts updating, your miner is successfully online and mining!
