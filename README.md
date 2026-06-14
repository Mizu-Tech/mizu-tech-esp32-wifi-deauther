<p align="center">
  <img src="logo/mylogo.png" width="500">
</p>
<br>
<br>

<hr>
<h3 align="center">‼️WARNING‼️</h3>
<h3 align="center">Do with your own risk. Misuse of this tool is beyond our responsibility, use it wisely!</h3>
<hr>
<br>
<br>

<h1 align="left">ESP32 WIFI DEAUTHER 2.4GHz</h1>
<h4 align="left">
This firmware is quite powerful for disconnecting clients from Wi-Fi. You only need the SSID, BSSID, and Channel to perform deauthentication.
</h4>

<h1 align="left">Firmware Price List</h1>
<blockquote>
<h4 align="left">
<b>esp32-deauther-v4.0</b><br>
Price : IDR 20.000 ($1)
</h4>
</blockquote>

<br>
The firmware is paid, to access the flasher you have to buy the firmware first then you can open the web flasher. For payment, you can DM me on social media section at the bottom. If you have purchased the firmware, I consider you have donated to me. 
<br>
<br>
Thank you for your support ^_^

<h1 align="left">Web Flasher</h1>
<h4 align="left">Authentication required</h4>
<img src="assets/login.png" width="800">
<h4 align="left">Connect the ESP32 to the laptop USB then install the firmware</h4>
<img src="assets/flash.png" width="800">

Firmware : esp32-deauther-v4.0
<blockquote>
<a href="https://flasher-esp32-wifi-deauther.vercel.app/">Web flasher</a>
</blockquote>
<h4 align="left">Flasher cannot be accessed if using a github account that is not registered as a buyer.</h4>

<h1 align="left">Features</h1>
<p align="left">
<ul>
<li>Deauthentication</li>
<li>Evil Twin</li>
<li>Beacon Spam</li>
<li>Password Catcher (with Evil Twin)</li>
</ul>

<h1 align="left">Requirements Device</h1>
<ul>
  <li>ESP32 WROOM 32U</li>
  <li>2.4GHz SMA antenna U.FL connector</li>
</ul>
<blockquote>You can find the components in the marketplace.</blockquote>

<h1 align="left">Instructions</h1>
<h3 align="left">➤ STEP 1 : Wiring </h3>
<h4 align="left">ESP32 WROOM 32U</h4>
<img src="hardware/esp32_wroom-32u.jpg" width="400">
<img src="hardware/ufl_antenna.jpeg" width="400">
You can also use the ML01DP5 module, the pin configuration is exactly the same as the NRF24L01.
<h1></h1>

<h3 align="left">➤ STEP 2 : Uploading firmware </h3>
After the wiring and pin configuration process is complete, open the web flasher and select the firmware to be used. Make sure your internet connection is stable to anticipate failure of the installation process.
<br>
<br>Click here to view the <a href="https://youtu.be/nAdMXXIz-rI">TUTORIAL VIDEO</a>.

<h4 align="left">Requirements</h4>
<ul>
  <li><a href="https://sparks.gogo.co.nz/assets/_site_/downloads/CH34x_Install_Windows_v3_4.zip">CH340 driver</a></li>
  <li><a href="https://www.silabs.com/documents/public/software/CP210x_Windows_Drivers.zip">CP2102 driver</a></li>
  <li>USB data cable</li>
</ul>

<h4 align="left">Troubleshoot</h4>
<blockquote>If the installation process fails, reinstall the firmware while pressing and holding the BOOT button on the ESP32 board.</blockquote>
<blockquote>If the COM port is not detected, try using another laptop port and make sure to use a data cable (not a charging cable).</blockquote>

<h3 align="left">➤ STEP 3 : Explanation</h3>
After a successful installation, you can turn on the device. Make sure your hardware wiring is correct.

<h3 align="left">> RESULT (oled version)</h3>
<h4 align="left">Prototype</h4>
<img src="assets/tool.jpeg" width="500">
<h4 align="left">Random hopping mode</h4>
<img src="assets/hopping_mode.jpeg" width="500">
<h4 align="left">Sequential mode</h4>
<img src="assets/sequential_mode.jpeg" width="500">
<h4 align="left">Spectrum analyzer</h4>
<img src="assets/spectrum_analyzer.jpeg" width="500">
You can build your own version of the prototype. <br>
LCD version review is in the DEMO video, or click here <a href="https://www.tiktok.com/@azfamahardika__/photo/7632892815738932498?is_from_webapp=1&sender_device=pc&web_id=7642704300384585223">LCD prototype</a>.
<h1></h1>

<h3 align="left">> HOW TO USE ?</h3>

<h4 align="left">For OLED version firmware</h4>

<ul>
  <li>At the top left is the radio status indicator (N1, N2, N3)</li>
  <li>At the top right is the channel range indicator</li>
  <li>Press to change attack mode (Hopping, Cross, Hunter, Sequential)</li>
  <li>Hold to enter spectrum analyzer mode</li>
</ul>

<p><i>*You can change attack modes to find the most effective technique.</i></p>

<h4 align="left">For LCD version firmware</h4>

<ul>
  <li>After booting, the LCD displays the NRF status</li>
  <li>Press to change system mode (WIFI, BLE, DRONE, FULLBAND)</li>
  <li>Hold to change attack mode (Random Hopping or Cross Sweeping)</li>
</ul>

<p><i>*You can switch system mode according to the target.</i></p>

<h1 align="left"> !! READ THIS !!</h1>
<blockquote><h4 align="left">If the power supply voltage doesn't reach 5V, I recommend purchasing a boost converter to increase the voltage to 5V. However, if the voltage is above 5V, it's best to purchase a buck converter to lower the voltage so your ESP32 doesn't burn out.</h4></blockquote>
<blockquote><h4 align="left"> If the NRF24 or ML01DP5 is powered directly from the battery, ensure the voltage is at 3.3V (3.6V is the maximum). Anything below this limit will reduce jamming performance, including range. Too high a voltage can also cause the module to burn out.</h4></blockquote>

<h1 align="left">Social Media</h1>
<a href="https://www.tiktok.com/@azfamahardika__">TikTok</a> <br>
<a href="https://www.instagram.com/azfamahardika_">Instagram</a>
