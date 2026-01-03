# การติดตั้ง (Installation)

=== "ภาษาไทย"

    ## 📋 สิ่งที่ต้องเตรียม (Prerequisites)
    ก่อนเริ่มใช้งาน ท่านจำเป็นต้องติดตั้งโปรแกรมต่อไปนี้:
    
    1. **Docker Desktop** (สำหรับจำลอง Server)
    2. **Git** (สำหรับดาวน์โหลดโปรเจกต์)
    3. **Node.js** (หากต้องการรันแบบ Development)

    ## 🛠️ ขั้นตอนการติดตั้ง
    
    ### 1. Clone Project
    เปิด Terminal หรือ Command Prompt แล้วพิมพ์คำสั่ง:
    ```bash
    git clone https://github.com/GhostMicro/micro-iot-gen.git
    cd micro-iot-gen
    ```

    ### 2. รันด้วย Docker (แนะนำ)
    วิธีนี้ง่ายที่สุด ไม่ต้องลงโปรแกรมอื่นเพิ่ม
    ```bash
    docker-compose up -d
    ```

    ### 3. เข้าใช้งาน
    เปิด Browser ไปที่: [http://localhost:3000](http://localhost:3000)

=== "English"

    ## 📋 Prerequisites
    Before you begin, ensure you have the following installed:
    
    1. **Docker Desktop** (For server emulation)
    2. **Git** (For cloning the repository)
    3. **Node.js** (If running in Development mode)

    ## 🛠️ Installation Steps
    
    ### 1. Clone Project
    Open your Terminal or Command Prompt and run:
    ```bash
    git clone https://github.com/GhostMicro/micro-iot-gen.git
    cd micro-iot-gen
    ```

    ### 2. Run via Docker (Recommended)
    This is the easiest method as it handles all dependencies.
    ```bash
    docker-compose up -d
    ```

    ### 3. Access the App
    Open your browser to: [http://localhost:3000](http://localhost:3000)
