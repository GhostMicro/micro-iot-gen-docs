# วิธีการใช้งาน (Usage Guide)

=== "ภาษาไทย"

    1. **เลือกบอร์ด**: เลือกบอร์ดที่คุณใช้ (ESP32 หรือ ESP8266)
    2. **ตั้งค่า WiFi**: กรอกชื่อ WiFi และรหัสผ่านที่ต้องการให้บอร์ดเชื่อมต่อ
    3. **เพิ่มโมดูล**:
        - กดปุ่ม `+` ในช่อง Inspector ด้านขวา
        - เลือกเซนเซอร์ที่ต้องการ (เช่น DHT22, Relay)
        - ลากวางตำแหน่ง Pin บนบอร์ด (หากต้องการเปลี่ยน default)
    4. **Generate Code**: กดปุ่ม **Generate Code** เพื่อรับ Source Code
    5. **Flash**: นำโค้ดไปวางใน Arduino IDE แล้วกด Upload ได้เลย!

=== "English"

    1. **Select Board**: Choose your target board (ESP32 or ESP8266).
    2. **Configure WiFi**: Enter the SSID and Password for the device connectivity.
    3. **Add Modules**:
        - Click the `+` button in the Inspector panel.
        - Select desired sensors (e.g., DHT22, Relay).
        - Drag & drop to reassign pins if necessary.
    4. **Generate Code**: Click **Generate Code** to get your .ino firmware.
    5. **Flash**: Copy the code into Arduino IDE and upload!
