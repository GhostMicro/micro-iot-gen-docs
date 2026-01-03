# มาตรฐาน GRIDS-IOT V1

=== "ภาษาไทย"

    **GRIDS-IOT** คือมาตรฐานโปรโตคอล MQTT ที่ใช้ภายใน GhostMicro
    
    ## Topic Structure
    รูปแบบ Topic: `grids-iot/{device_id}/{channel}`
    
    | Channel | ทิศทาง | รายละเอียด |
    | :--- | :--- | :--- |
    | `status` | Device -> Broker | ส่งสถานะการออนไลน์ (online/offline) |
    | `telemetry` | Device -> Broker | ส่งค่าเซ็นเซอร์ (JSON format) |
    | `command` | Broker -> Device | รับคำสั่งควบคุม (เช่น เปิด/ปิด ไฟ) |

=== "English"

    **GRIDS-IOT** is the internal MQTT protocol standard used by GhostMicro.
    
    ## Topic Structure
    Format: `grids-iot/{device_id}/{channel}`
    
    | Channel | Direction | Description |
    | :--- | :--- | :--- |
    | `status` | Device -> Broker | Online/Offline status presence |
    | `telemetry` | Device -> Broker | Sensor data stream (JSON format) |
    | `command` | Broker -> Device | Control commands (e.g., Turn Relay ON/OFF) |
