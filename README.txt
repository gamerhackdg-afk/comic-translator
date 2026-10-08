วิธีนำขึ้นใช้งานด้วย GitHub Pages (ฟรี)
1. สมัคร/เข้าสู่ระบบ github.com แล้วสร้าง repository ใหม่ (ตั้งเป็น Public) เช่นชื่อ comic-translator
2. กด "Add file" > "Upload files" แล้วอัปโหลดไฟล์ทั้ง 4 ไฟล์: index.html, manifest.webmanifest, sw.js, icon.svg
3. ไปที่ Settings > Pages > เลือก Branch: main และโฟลเดอร์ / (root) > Save
4. รอ 1-2 นาที จะได้ลิงก์ https://ชื่อคุณ.github.io/comic-translator/
5. เปิดลิงก์ใน Chrome บนมือถือ (ใช้ Wi-Fi) กด "แปลเลย" ครั้งแรกเพื่อโหลดโมเดล รอจนเสร็จ
6. กดเมนูจุดสามจุด > "เพิ่มไปยังหน้าจอหลัก" เพื่อใช้เหมือนแอพ

หมายเหตุ
- ต้องเปิดผ่าน https (เช่น GitHub Pages) การเปิดไฟล์ตรง ๆ จากเครื่องจะใช้ไม่ได้
- ถ้าเครื่องช้าหรือหน่วยความจำไม่พอ ลองเปลี่ยนค่า MODEL ในไฟล์ index.html เป็นโมเดลที่เล็กกว่า
