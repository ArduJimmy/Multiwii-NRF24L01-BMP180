# Arduino Quadcopter with NRF24L01 + Multiwii 2.3 + BMP180 (Updated In January 13, 2025)
# Multiwii-NRF24L01-BMP180
This is about how to activate Barometer BMP180 on Multiwii 2.3 with NRF24L01

<h2>WARNING</h2>
<p>This version ONLY works for Ladybird Board Type (Config.h). You dont need to modify anything. Just upload it and done.</p>

<h3>SPECIFICATION</h3>
<u>
  <li>Multiwii 2.3</li>
  <li>NRF24L01 as Receiver & Transmitter</li>
  <li>For BMP180 ONLY</li>
  <li>Brushed DIY ESC (Using mosfet) and Brushed Motor</li>
  <li>All specification that is compatible with Ladybird board type</li>
</u>

<h3>PIN CONFIG</h3>
<ol>
  <li>SCL pin BMP180 to A5</li>
  <li>SDA pin BMP180 to A4</li>
  <li>VCC pin BMP180 to 3.3v Voltage Regulator</li>
  <li>GND pin BMP180 to GND pin of 3.3v Voltage Regulator</li>
</ol>

<p>From the PIN CONFIG above, 3.3v voltage regulator must be connected to:</p>
<ul>
  <li>MPU6050 /Gyro Module</li>
  <li>NRF24L01 module</li>
  <li>BMP180 Barometer module</li>
</ul>

<h2>FULL SCHEMATIC DIAGRAM NRF24 Quadcopter Arduino Based, Multiwii 2.3 with BMP180</h2>
<p>Each colors refers to unique wiring.</p>

<img src="https://github.com/ArduJimmy/Multiwii-NRF24L01-BMP180/blob/main/Schematic%20Diagram%20NRF24%20Drone%20with%20BMP180.jpg" alt="NRF24 Drone Schematic Diagram"/>
<br />

<p>To make a drone like that, you must make one as in this video: https://www.youtube.com/watch?v=wbK7oOLr6PM
Or Click <a href="https://www.youtube.com/watch?v=wbK7oOLr6PM" target="_blank">here</a>.</p>

<h4>PLEASE SUBSCRIBE & SHARE OUR CHANNEL</h4>
<p><a href="https://www.youtube.com/@ardujimmy" target="_blank">Subscribe</a>.</p>
