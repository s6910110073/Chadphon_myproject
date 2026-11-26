"# Chadphon_myproject"
พื้นที่เขียนอธิบายงานที่ทำ

git init
---สร้าง local repository

gir add .
---อัพทั้งโฟลเดอร์
git add ชื่อไฟล์.สกุล 
---อัพแค่ไฟล์นั้น

หลังชื่อไฟล์ ขึ้น U ก่อนใช้ git add.  --คือสถานะยังไม่ติดตาม

git commit -m "text"
การคอมเม้นว่าอัพอะไรไป

git branch -M main
---อัพแล้วใช้เป็น version หลัง

git remote add origin https://github.com/s6910110073/Chadphon_myproject.git
---ซิงค์กับ รีโมต rspository

git push -u origin main
---อัพขึ้น git

git statis
---แจ้งเตือนว่ามีการแก้ไขในไฟล์



หลังตั้งค่าก็ใช้แค่
git add .
git commit -m "text"
git push -u origin main