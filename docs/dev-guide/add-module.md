# การเพิ่มโมดูล (Adding New Modules)

=== "ภาษาไทย"

    หากต้องการเพิ่มเซนเซอร์ใหม่ลงในระบบ ให้แก้ไขไฟล์ `data/modules.ts`:

    ```typescript
    {
      id: "sensor-new",
      name: "New Sensor",
      type: "sensor",
      requires: ["VCC", "GND", "DATA"], // ขาที่ต้องใช้
      libraries: ["NewSensorLib"],      // ไลบรารีที่ต้องใช้
      code: {
        setup: "sensor.begin();",       // โค้ดส่วน Setup
        loop: "sensor.read();"          // โค้ดส่วน Loop
      }
    }
    ```

=== "English"

    To register a new sensor in the system, edit `data/modules.ts`:

    ```typescript
    {
      id: "sensor-new",
      name: "New Sensor",
      type: "sensor",
      requires: ["VCC", "GND", "DATA"], // Required pins
      libraries: ["NewSensorLib"],      // Required libraries
      code: {
        setup: "sensor.begin();",       // Setup block
        loop: "sensor.read();"          // Loop block
      }
    }
    ```
