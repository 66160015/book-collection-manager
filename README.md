# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# วิธีการติดตั้ง
1. ติดตั้ง Vite และ React
npm create vite@latest book-collection-manager -- --template react 
cd book-collection-manager 
npm install 
2. ติดตั้ง dependencies
npm install react-router-dom axios 
3. ทดลองรันโปรเจค 
npm run dev 
4. เข้าหน้าเว็บ
http://localhost:5173/

# วิธีการใช้งาน
1. เพิ่มหนังสือ
- กดเข้าไปในหน้าต่าง "เพิ่มหนังสือ"
- กรอกข้อมูลต่างๆ ของหนังสือ
- กดปุ่ม "เพิ่ม"
2. ลบ หรือ แก้ไข
- กดเข้าไปในหน้าต่าง "รายการหนังสือ"
- เลือกหนังสือที่ต้องการแก้ไข
- กด ลบ เพื่อนำหนังสือออก
- กด แก้ไข เพื่อแก้ไขข้อมูลหนังสือ
3.การค้นหาหนังสือ
- กดเข้าไปในหน้าต่าง "รายการหนังสือ"
- กรอก ชื่อหนังสือ ที่ search bar
- เลือก หมวดหมู่ ของหนังสือ
- กดไอคอน ค้นหา

# การจัดเก็บข้อมูลของเว็บด้วย localstorage
เมื่อ เพิ่ม/ลบ/แก้ไข หนังสือจะเก็บข้อมูลลงใน localstorage ทำให้เมื่อมีการปิดหน้าต่างเว็บไปแล้วข้อมูลต่างๆ ก้ยังคงอยู่ใน localstorage เหมือนเดิม