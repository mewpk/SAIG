# คู่มือ SAIG training

## โปรแกรมที่จำเป็น

### 1. Node JS

    1.1 คลิ๊กลิ้งค์ Download | Node.js (nodejs.org)

    1.2 เลือก LTS แล้วคลิ๊ก Windows Installer หรือ macOS Installer ตาม OS ที่ใช้

    1.3 เปิด Node.js Setup ที่ดาวน์โหลดมา





    1.4 กด Next ไปเรื่อยๆ แล้วกด Install


    1.5 เสร็จสิ้น ให้ลองเช็คว่าลงสำเร็จแล้ว โดยเปิด Command Prompt แล้วพิมว่า node -v ถ้าขึ้นเป็น version ที่ลงก็หมายความว่าติดตั้งสำเร็จ

### 2. Postman

    2.1 คลิ๊กลิ้งค์ Download Postman | Get Started for Free


    2.2 เลือก Window 64-bit หรือตามที่ OS ตัวเองใช้

    2.3 เปิด Postman Setup ที่ดาวน์โหลดมา หลังจากติดตั้งเสร็จสิ้นจะได้เป็นดังรูป

### 3. MongoDB

    3.1 คลิ๊กลิ้งค์ MongoDB Compass Download | MongoDB แล้วเลือก MongoDB Compass


    3.2 เลือก version และ platform ให้เรียบร้อยแล้วกด Download
    3.3 เมื่อ download เสร็จให้เปิด MongoDB Compass ถ้าขึ้นดังรูปก็เสร็จสิ้น

### 4. Git

    4.1 คลิ๊กลิ้งค์ Git - Downloads (git-scm.com)


    4.2 เลือก Download for Windows หรือตามที่ OS ตัวเองใช้
    4.3 เปิด Git ที่ดาวน์โหลดมา



    4.4 กด Next ไปเรี่อยๆ จนถึงหน้า Choosing the default editor ให้เลือก

    Use Visual Studio Code as Git’s default editor


    4.5 จากนั้นกด Next ไปเรื่อยๆ จน Install

ทดลองใช้งาน npm, npx

    *Editor ที่ใช้จะเป็น VS Code

สร้าง folder ไว้ซักที่นึง โดยในตัวอย่างจะสร้างที่ Desktop

เปิด VS Code ขึ้นมา เลือก File -> Open Folder… แล้วเลือก folder

ที่เราพึ่งสร้างไว้

ให้ดูที่ Terminal ว่า path ตรงกับ folder เราหรือไม่

    *วิธีเปิด terminal เลือก Terminal -> New Terminal

ที่ Terminal ให้พิมว่า npx create-react-app train-frontend แล้วกด enter

### 5. รอจนติดตั้งสำเร็จ จนขึ้นดังรูป และเราจะได้ folder ที่ชื่อว่า train-frontend

### 6. ตอนนี้ path เราอยู่ที่ saig เราต้องเข้าไปที่ train-frontend ด้วยคำสั่ง

cd train-frontend แล้วกด enter เราจะย้ายเข้ามาที่ train-frontend

### 7. พิม npm start แล้วกด enter

### 8. จากนั้นจะมี React App เด้งขึ้นมา

### 9. และ Terminal ที่ VS Code จะเป็นดังรูป ถ้าต้องการออกให้กด Ctrl + c แล้วมันจะถามเรา ให้พิม y แล้วกด enter
