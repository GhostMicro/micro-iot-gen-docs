# โครงสร้างโปรเจกต์ (Project Structure)

=== "ภาษาไทย"

    โปรเจกต์ถูกพัฒนาด้วย **Next.js 16** โดยมีโครงสร้างไฟล์หลักดังนี้:
    
    ```
    micro-iot-gen/
    ├── app/                    # หน้าเว็บหลัก (App Router)
    │   ├── page.tsx            # หน้า Generator
    │   └── globals.css         # ไฟล์ CSS หลัก (Tailwind)
    ├── components/             # UI Components
    │   ├── dashboard/          # ส่วนประกอบหน้าปัด (Board, Inspector)
    │   └── ui/                 # ชิ้นส่วนพื้นฐาน (Button, Modal)
    ├── data/                   # ข้อมูล Static
    │   ├── modules.ts          # นิยามโมดูล (Pinout, Code Template)
    │   └── libraries.ts        # รายชื่อไลบรารี Arduino
    └── lib/                    # Logic หลัก
        ├── generator/          # ตัวแปลง Logic เป็น C++ Code
        └── store.ts            # State Management (Zustand)
    ```

=== "English"

    The project is built on **Next.js 16** with the following directory structure:
    
    ```
    micro-iot-gen/
    ├── app/                    # Main App Router
    │   ├── page.tsx            # Generator Page
    │   └── globals.css         # Global CSS (Tailwind)
    ├── components/             # UI Components
    │   ├── dashboard/          # Dashboard Widgets (Board, Inspector)
    │   └── ui/                 # Basic UI Elements (Button, Modal)
    ├── data/                   # Static Data definitions
    │   ├── modules.ts          # Module Definitions (Pinout, Code Template)
    │   └── libraries.ts        # Arduino Library Registry
    └── lib/                    # Core Logic
        ├── generator/          # Code Generation Engine (Logic -> C++)
        └── store.ts            # State Management (Zustand)
    ```
