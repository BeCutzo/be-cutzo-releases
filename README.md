# Be Cutzo — ดาวน์โหลด

ตัวติดตั้ง **Be Cutzo** (Public Beta) โปรแกรมตัดต่อวิดีโอด้วย AI สำหรับคลิปพูดภาษาไทย
ที่นี่มีแค่ไฟล์ติดตั้ง ซอร์สโค้ดของโปรแกรมไม่ได้อยู่ในหน้านี้

## ดาวน์โหลด

1. เปิด **[เวอร์ชันล่าสุด](https://github.com/BeCutzo/be-cutzo-releases/releases/latest)**
2. เลื่อนลงไปที่หัวข้อ **Assets** แล้วกดไฟล์ของเครื่องคุณ
   - **Windows 10/11 (64-bit):** `Be-Cutzo-Setup-….exe` (ราว 1.2 GB)
   - **Mac ชิป Apple (M1–M4):** `Be-Cutzo-…-arm64.dmg` (Mac รุ่น Intel ยังใช้ไม่ได้)
3. ไฟล์ `latest.yml`, `.blockmap` และ `.sha256` ไม่ต้องโหลด เป็นไฟล์สำหรับตรวจอัปเดตและตรวจไฟล์

## ติดตั้งบน Windows

1. เปิดไฟล์ที่โหลดมา
2. ถ้าขึ้น "Windows protected your PC" ให้กด **More info → Run anyway**
   (ตัวติดตั้งยังไม่ได้เซ็นใบรับรองของ Microsoft)
3. เปิดโปรแกรมครั้งแรก โปรแกรมจะโหลดโมเดลถอดเสียงราว 3 GB ครั้งเดียว มีแถบบอกความคืบหน้า
4. กด **สมัครสมาชิก** → กรอกชื่อ อีเมล รหัสผ่าน → กรอกรหัส 6 หลักจากอีเมล
   ช่วง Beta ได้ 300 เครดิตฟรี จำกัด 100 บัญชีแรก

## ติดตั้งบน Mac

1. เปิดไฟล์ `.dmg` → ลาก **Be Cutzo** ไปใส่โฟลเดอร์ **Applications**
2. เปิดแอป **Terminal** พิมพ์บรรทัดนี้ครั้งเดียว แล้วกด Enter
   (แอปยังไม่ได้เซ็นใบรับรองของ Apple ถ้าไม่พิมพ์ Mac จะขึ้นว่าแอป "damaged")
   ```
   xattr -cr "/Applications/Be Cutzo.app"
   ```
3. เปิด Be Cutzo จาก Applications → ครั้งแรกโหลดโมเดลถอดเสียงราว 3 GB ครั้งเดียว → สมัครสมาชิกเหมือน Windows

## อัปเดต

โปรแกรมตรวจหาเวอร์ชันใหม่จากหน้านี้ทุกครั้งที่เปิด และบอกเมื่อมีเวอร์ชันใหม่
บน Windows กดโหลดและติดตั้งในโปรแกรมได้เลย บน Mac ปุ่มจะพามาหน้านี้ให้โหลดไฟล์ใหม่
ปิดการตรวจอัตโนมัติได้ที่ ตั้งค่า → อัปเดต

## ตรวจว่าไฟล์ถูกต้อง (ไม่บังคับ)

รหัส SHA-256 ของแต่ละเวอร์ชันอยู่ในหน้ารายละเอียดของเวอร์ชันนั้น

## ติดต่อ

becutzohq@gmail.com

---

*English:* this repository only hosts Be Cutzo installers; the source code is private.
Download from the [latest release](https://github.com/BeCutzo/be-cutzo-releases/releases/latest):
the `.exe` for Windows 10/11 (64-bit), or the `-arm64.dmg` for Apple-silicon Macs (unsigned — run
`xattr -cr "/Applications/Be Cutzo.app"` once after installing). Contact: becutzohq@gmail.com
