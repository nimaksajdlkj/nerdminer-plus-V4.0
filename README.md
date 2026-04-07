Online flashing tool: https://www.nerdminerplus.com/

Supported device purchase link: https://www.amazon.com/dp/B0GLGFZMRV
Delivers a hashrate of up to 740 KH/s with support for primary and failover pools.
——————————————————————————————————————————————————————————————————————————————————————————
Here is the professionally organized English version of the manual, optimized for readability and clarity.

---

## 🛠️ NerdMiner Plus Quick Start Guide

### --- Step 1: Device Boot & Hotspot Connection --- 
1.  **Power On**: Once plugged in, the miner's screen will light up, displaying "Connecting to WiFi..." and "Will switch to AP in 60s if failed." 
2.  **Enter Configuration Mode**: If it is the first boot or the network hasn't been configured, the device will automatically enter **AP (Access Point) mode** after about 60 seconds. 
3.  **Connect to Miner's Hotspot**: Open the Wi-Fi settings on your phone or computer, find the Wi-Fi signal starting with **"BTC_"**, and connect to it. 
    * **Default Wi-Fi Password**: `12345678`

### --- Step 2: Login to the Management Dashboard --- 
1.  **Access Address**: After successfully connecting, open your web browser and enter: `192.168.4.1` or `http://192.168.4.1/config`
2.  **Authentication**: In the login page, enter the default credentials: 
    * **Default Username**: `admin`
    * **Default Password**: `admin`
3.  **Change Language**: Once logged in, you can switch the language using the drop-down menu in the top right corner for easier navigation.

### --- Step 3: Important Parameter Configuration ---
> **⚠️ Note**: It is highly recommended to configure **Mining Settings** and **Display Settings** first, and update **Network Settings** last. Once the miner connects to your home Wi-Fi, the current AP configuration page will disconnect.

1.  **Mining Settings [Required]**
    * Expand the **"Mining Settings"** panel to configure Primary and Backup nodes.
    * **Mining Pool**: Defaults are set to `public-pool.io` (Primary) and `solo.ckpool.org` (Backup).
    * **Wallet Address**: **IMPORTANT!** Replace the default address with your own **Bitcoin (BTC) wallet address**. Otherwise, any rewards mined will not go to your account.
    * Click **"Update Mining Settings"** at the bottom to save. 

2.  **Display & LED Settings [Optional]**
    * **Screen Rotation**: Supports four modes (Portrait/Landscape). Default is "Landscape: Cable at right."
    * **Brightness & Inactivity**: Adjust display brightness and set a timer to turn off the screen automatically to extend its lifespan.
    * **LED Settings**: Independently adjust the brightness (0-255) for Red, Green, and Blue LEDs.

3.  **User & Advanced Settings [Optional]**
    * **Security**: It is recommended to change the default `admin` password under **User Settings** (8-32 characters required).
    * **Logs**: Enable **"Log Viewer"** in Advanced Settings if you need to troubleshoot or view system statistics.

### --- Step 4: Network Settings [Final Step] --- 
1.  Expand the **"Network Settings"** panel. 
2.  Click the **"Scan"** button to search for nearby Wi-Fi signals. 
3.  Select your home Wi-Fi from the list and enter your **Wi-Fi Password**. 
4.  (Optional) Fill in Static IP details if your network requires it.
5.  Click **"Update Network Settings"** to finalize.

---

### 🎉 Congratulations! 
The miner will now disconnect from your phone and attempt to connect to your home Wi-Fi. Once the **Wi-Fi icon** in the top-left corner stays solid and the **Hashrate** begins to update on the screen, your miner is successfully online and mining!
